# Encave relay

A small HTTP service that lets Encave devices sync when they are not on the same
network. It stores encrypted files and nothing else: devices encrypt everything
before sending it, and the relay never has a key.

**You do not need a relay** to sync your own devices on the same Wi-Fi. A relay
is for devices that are apart, or for households with both iPhones and Android
phones. Use one run by someone you trust: enter its address in **Devices › Sync away from home**.

## What the relay sees

- Mailbox IDs, which look random. The cellar's mailbox ID changes when a device
  is removed; each device's inbox ID stays the same.
- Encrypted files: their number, sizes and when they are written, and their
  names: random device IDs and change counters, and hashes of photos.
- The IP addresses of the devices that connect. Whether they are logged
  depends on who runs the relay and where.

It never sees cellar contents, device names, photos or keys.

## How long files are kept

Mailboxes not written to for a year are deleted, so a relay is a mailbox, not a
backup. Keep backups with **Back Up Now** in **Settings › Your data**.
