# Privacy policy · Politique de confidentialité

<!-- Published at this address: the apps (ProjectLinks on both platforms) and the
store listings link to it. Keep it true for the code: change it, and its date,
with any change to what the apps send. -->

[English](#english) · [Français](#français)

## English

Effective date: November 18, 2026

Encave is a wine cellar app for iPhone, iPad, Mac and Android. This policy
covers those apps. In short: **the developer of Encave collects nothing about you or your cellar.**
There is no account, no analytics, no advertising, no tracking and no
third-party SDK (except Google ML Kit on Android if you turn it on, Google
Play Integrity on Android for Encave AI's free credits, and the stores' own
purchase systems for Encave Lifetime, below). The one server
the developer runs is Encave AI's, used only if you use Encave AI: it receives
information about a wine, never your cellar, and keeps nothing personal.

### What stays on your device

Your cellar (wines, bottles, storage, the Journal, prices, places, notes), its
photos and documents, and your settings are kept in Encave's own storage on
your device. Encave does not add encryption of its own to these files; they
are protected by the device:

- **iPhone and iPad**: iOS encrypts them (data protection, available after
  the first unlock following a restart). They are part of the device backups
  you make (iCloud Backup or a computer), as for any app.
- **Mac**: they are in the app's sandboxed container, encrypted when FileVault
  is on, and part of your Time Machine backups if you use it.
- **Android**: Android encrypts the app's private storage. Encave leaves them
  out of Google's cloud backups; they move to a new phone only with a direct
  device-to-device transfer.

Keys and passwords you enter (AI and web search keys, the WebDAV login, the
sync keys) are kept in the Keychain (Apple) or encrypted with an Android
Keystore key, on that device only. The one exception is your choice: when you
add a device, or later from Devices while both are on the same Wi-Fi, you can
give it the AI connections you tick, with their keys. They are sent once,
directly and encrypted between the two devices (when adding one, only after
you confirmed the code on both), and stored in the other device's Keychain or
Keystore-protected storage; never through a relay, iCloud, WebDAV, a backup or
an export. A device that is already in the cellar asks first, showing each
connection's server, and adds them only if you say Add.

The aroma game's guesses and scores ("Guess the aromas", "My palate") stay on
the device that played: they are never synced, not even with people sharing
your cellar, and are left out of Encave's backups and exports and of Android's
backups and device transfer.

What your AI requests cost (AI Spending in Settings › AI, and in Insights on
iPhone, iPad and Mac: the date,
purpose, model, tokens and cost of each request, the last 2,000 for twelve months
at most) is recorded on the device that made them only: never synced, exported,
put in Encave's backups or in the device's backups. Reading the credit left on
an OpenRouter key sends that key to OpenRouter only, as its requests do.

The words you tap among the Cellar's "In the mood for…" words (so the ones you use
most grow a little) stay on the device too, the last 200 for six months at most:
never synced, exported or put in Encave's backups.

The camera is used inside Encave for Add's scanner (the label photo, and the
bottle's barcode and a shared wine's QR code, read on the device) and for the
pairing code; on Android, other photos (another side of the bottle, a document)
are taken with the device's camera app, which hands the photo to Encave.

**Reading the label's text on Android** (off by default). If you turn on **Read
label text on this phone** (Settings › AI label recognition), Google ML Kit, a
library from Google built into Encave for Android, reads the text of a label photo
on the phone to fill in the name, producer, vintage and appellation. The photo and
its text never leave the phone for this. While it is on, ML Kit sends Google, over
HTTPS, for its diagnostics and usage statistics: the device's manufacturer, model,
Android version and build and its machine learning hardware; the app's package name
and version; an identifier of this installation of Encave (not meant to identify you
or the phone); and how ML Kit is used (when it starts and reads, how long it takes,
the images' size and format, its version, error codes). Google says it does not pass
this on to third parties ([ML Kit's data disclosure](https://developers.google.com/ml-kit/android-data-disclosure));
Google's privacy policy applies to it. Statistics recorded while it was on may still
be sent shortly after you turn it off. When the setting is off, ML Kit does not run.
The setting is kept on that phone only: never synced, backed up or moved to a new phone.

Reminders, notifications of changes from your other devices, widgets, Siri,
Shortcuts and Spotlight, and the on-device features of Apple Intelligence
(asking your cellar, suggesting details, estimating a price) are worked out on
the device. So are the AI requests sent to the **Apple Intelligence** connection's
model on this device, if you add it in Settings › AI (iPhone, iPad and Mac with
iOS 27 or macOS 27): nothing about them leaves the device.

Prepare an Evening Request (Shortcuts) and Share an Evening Request (Android,
in Tonight) only hand a text to you: a request for an evening's selection with
your bottles and their positions, without prices, notes or places of purchase.
Encave sends nothing; if you pass it to an assistant app such as Claude, it
leaves the device through that app, under its privacy policy, by your choice.

Share This Wine (iPhone, iPad, Mac and Android) makes a QR code and a link on the
device with the wines you chose: their name, producer, vintage and other
identity details, and only the details you turn on (your rating and note, the
price paid, where you bought it, the drinking window, what to expect, critics'
scores, a small picture). Nothing goes through a server: the code and the link
hold it all, and they reach only the people you show the code to or send the
link to, through the app you pick. Opening such a link adds nothing until you
choose where the wine goes.

The iPhone and iPad widgets read a short summary the app keeps on the device,
in a folder shared only with its widgets: counts of bottles, and the names,
vintages, producers and positions of tonight's bottle and of the first wines to
drink soon. They never read the cellar, keys or notes, and use no network. The
lock screen widgets show what you choose to place there, the wine's name
included; Encave marks names and positions as private, so iOS hides them while
the device is locked when your settings ask for it.

The device also keeps earlier versions of your cellar (one for each of the
last 7 days it changed, then one a week for 4 weeks), in the same storage.

**Backups are not encrypted.** The weekly backup is **on by default**: once a
week, Encave makes a ZIP file of your whole cellar, its photos and documents,
by itself, and keeps the last two on the device. It runs when you open Encave,
and in the background: on iPhone and iPad only while sync away from home is on
(iOS decides when), on Android once a day. You can turn it off in Settings.

- **iPhone, iPad and Mac**: the weekly backups are in Encave's own Documents
  folder (on iPhone and iPad, the Files app shows it under On My iPhone or On
  My iPad › Encave). They are left out of the device's backups and Time
  Machine. On iPhone and iPad, removing the app deletes them.
- **Android**: the weekly backups are in the shared **Download/Encave**
  folder. The Files app, apps you allow to access all files, and a computer
  connected by USB can read them. They stay there when you remove the app.

A backup you make yourself (**Back Up Now**, or an export) is a standard file,
not encrypted either: it goes where you choose to save or share it.

### What can leave your device, and only if you turn it on

1. **Sync between your devices.** Paired devices exchange your cellar, its
   photos and documents, encrypted from end to end. On the same network they
   connect directly. Away from home, if you turn it on, they go through a
   storage you choose: iCloud (on Apple devices, when offered), a WebDAV
   folder, or a relay (run by you or someone you trust). It stores only
   encrypted files that it cannot read; it sees when your devices sync, how
   much they send and, for a WebDAV server or a relay, their IP addresses. The
   device names and models and the cellar stay encrypted. A WebDAV folder on your local
   network may use plain http: the files stay encrypted, but the WebDAV
   username and password then travel unencrypted on that network, and Encave
   warns about it.
   In a shared cellar, the name you give in **Devices › Your Name** syncs with
   the cellar: every device of the cellar shows it with your tastings and
   notes, and so do backups of it. It is encrypted like the rest.
2. **AI** (nothing is sent until you set up a model). If you set up AI models
   with your own keys (or a server of your own), Encave sends them
   **information about a wine**, directly from your device, whenever it helps
   fill in or check that wine: the label photo when you scan a label or ask to
   complete a wine; the photos of a restaurant's wine list when you ask your AI
   to read one (Wine List is read on your device first, sending nothing; Read with
   AI sends the photos: the AI lists the wines printed, with their prices, and the wine
   you pick, the restaurant and the price stay on your device, like any wine
   tasted elsewhere); and the wine's details (such as its name as you typed it,
   producer, appellation, region, country, classification, vintage, colour,
   grapes, alcohol and bottle size),
   with the current year (and, for a price estimate, your cellar's currency),
   for what to expect, its drinking window, a price estimate or a completion;
   and, when you tap Suggest Details on a device without Apple Intelligence,
   the search terms and the results of your search. It goes to the first model of your list, and to
   the next one only if the previous one fails or when you ask for another
   reading; never to two at once. What the AI estimates is marked as
   estimated. If a connection allows **web search** (on by default for
   Claude, ChatGPT, Grok and OpenRouter; you can turn it off), the model may
   search the web with these details through its provider's own search
   (through OpenRouter, possibly its search partner, such as Exa), for a
   completion and for what to expect from that vintage; the pages it used are
   listed. After you add a wine (unless turned off in Settings › AI) and when
   you tap Search with AI, such a model also looks up its drinking window,
   sent only the wine's name, producer, vintage and appellation; the wine's
   page names the model and the pages. Through OpenRouter, by default Encave asks it to use
   only providers that do not keep or train on the data, unless you turn that
   off. Each service's own privacy policy applies to what it receives. Your
   keys stay on your device: they are never synced, exported or backed up
   (unless you give them to another of your devices, as above).
   The **Apple Intelligence** connection (Apple devices, if you add it) needs no
   key: its model on the device sends nothing; with Apple's server model, the
   same information about a wine goes to Apple's Private Cloud Compute, which,
   as Apple describes it, uses it only to answer and does not keep it. Neither
   searches the web.

   **Studio** (on at first, used only once AI is set up). After you scan a
   wine, in the background, Encave makes a presentation image of it. If you
   allow **Image Generated by AI** and one of your connections has a model
   that makes images (OpenRouter, Google or OpenAI), the label photo (without
   its metadata) goes to the image model you chose, with a reference picture
   bundled with Encave, to make that image; your key pays for it. If you
   allow **Official Image from the Web** and a connection may search the web,
   the model that completes the wine also looks for the official picture of
   the cuvée on producers' and merchants' sites; Encave downloads it from
   that site, from your device (the site sees the request, as for any
   picture), and asks a model that reads images whether it shows the same
   wine as your label photo, sending both. The image kept becomes part of
   your cellar (synced with its photos); pictures from producers and
   merchants are kept for your private use. Nothing else is sent for it.
3. **Web search** (nothing is sent until you choose a service). If you choose
   a search service, Encave sends it search terms made from a wine's details
   (producer, name, appellation, vintage, and for a price the bottle size)
   when you search online, look for a price or a picture; you can change the
   terms and search again. The results are read on the device. When you look
   for a price, Encave then opens the first five result pages from your
   device and reads the bottle's price on them, on the device. Those sites
   see your IP address, the page asked for and the app's name and version (on
   Apple devices, also the system version and your preferred languages, which
   the system sends); no cookies, stored passwords or referring page are
   sent. Each search opens its own connections, closed after it. Encave
   refuses pages whose name leads to your device or your local network. When
   you search pictures, the thumbnails and the picture you pick are
   downloaded from the sites that host them, which see the request (pictures
   from your device or local network are refused too); the picture becomes
   the wine's cover and never replaces your label photo.

**Never sent to an AI, search or web service:** your cellar as a whole or as
a list, who owns it, your storage places and the positions of your bottles,
the prices you paid, where and when you bought, your notes, tastings, ratings
and aroma game, occasions and reservations, names and contacts, accounts,
device and sync identifiers, and your location. Photos lose their metadata
(such as location or camera) before they are sent. Requests carry no cookies
and no identifier of you or your device; like any connection, the service
sees your IP address.

Plain HTTP is used only for a server on your local network, including a name
on your home network (such as a `.local` name): Encave then connects only to a
local address of that name, never to an address outside your network, and
refuses a name that has none. Such a connection never goes through a proxy set
up on the device. Everything else uses HTTPS. Links (the website, this
policy, a search result) open in your browser.

### Encave AI, the developer's server

Encave AI is the AI that works without keys of your own, paid with credits. It
is used only while its switch is on in **Settings › AI** (until you touch that
switch, only when no AI of your own can answer). With your own keys on, they
are asked first and Encave AI only when they cannot answer.

- **What is sent**: the same information about a wine as for your own AI
  (above): the label photo, wine list photos you scan, and the wine's details,
  sent over HTTPS (TLS 1.3) to Encave's server. The server passes the request on
  to the AI provider through OpenRouter, asking it to use only providers that
  keep nothing and train on nothing. Your cellar, prices paid, places, notes,
  names and contacts are never sent.
- **Your wallet**: no account. Your device makes a key; the server stores a
  random wallet number and the public half of that key, never your name, email,
  or a device, Apple or Google identifier. Each request is signed with the key,
  so only your devices can use your credits. On Apple devices the key is in your
  iCloud Keychain (your other Apple devices share the wallet); on Android it
  stays on the phone.
- **What the server keeps**: per wallet, the balance, the credits given or
  used, the bottles opened (a random number for each, valid 30 days), costs and
  counters for limits, and, for about ten minutes, the random number of each
  signed request (so it cannot be replayed). Outside the beta (below), it keeps **no request content**
  (no photo, no wine, no answer) and **writes no IP address**: addresses are
  only held in memory for a short time to limit abuse. A wallet never used is
  deleted after 30 days. The server's data is backed up daily on the server.
- **Troubleshooting, anonymous**: for each request, the server notes its kind
  (label, details…), the AI model and provider, whether it worked or the error,
  how long it took and its size in tokens. Never the wallet, an address or the
  content. These notes are deleted after 7 days (30 days while Encave is in beta).
- **During the beta (TestFlight only)**: to reproduce problems and choose the best
  AI models, the server also keeps the requests of TestFlight installs and the AI's
  answers: the label photos (with their metadata, such as location, removed), the
  wine's details as sent, and the answer. When a TestFlight install with an Encave AI
  wallet reads a wine list on the device, it also sends the list's photos (without
  their metadata), the text the device recognised and the wines it read, kept the
  same way to improve the reading. They are not tied to your wallet and are
  deleted after 30 days. App Store installs are never kept.
- **The free credits, once per device**: to give them only once, the app asks
  the system to vouch for it, only when your wallet is made:
  - **Apple**: Apple's DeviceCheck (Apple keeps two bits per device for Encave;
    the server sets one to say "free credits given") and the App Store's signed
    proof that the app was installed from the App Store or TestFlight.
  - **Android**: Google Play Integrity. Google Play checks that the app and the
    phone are genuine and gives a signed verdict, which the server has Google
    decode and then forgets. To do this, Google collects information about the
    phone and the app under its own policy (see
    [Play Integrity's data disclosure](https://developer.android.com/google/play/integrity/overview)).
    If it fails, you get no free credits; nothing else changes.

  Neither check involves your cellar.

### Encave Lifetime and the free trial

Encave can be tried for free for 14 days; Encave Lifetime is then bought once,
in the app, with no subscription. The trial and the purchase go through the
App Store (Apple's in-app purchase) or Google Play (Google Play Billing), under
their policies: Apple or Google take the payment and tell the app what your
store account owns. The app reads this on the device. It is never sent to the
developer or to Encave AI's server, and never synced: each device asks its own
store. On Android, the date the trial started is kept on the device only. From
Apple and Google, the developer receives only sales reports (how many, how
much, by country), never who bought.

### What the stores may provide

Apple and Google may give developers crash reports and usage statistics from
users who allowed it in the system settings (for example "Share with App
Developers"). Those are collected by Apple or Google under their policies, not
by Encave, and hold no cellar data.

### Children

Encave is about wine and is not meant for children.

### Your rights

The developer holds no data about you: there is nothing to access, correct or
delete on the developer's side. You can export, delete and restore your data at
any time in the app. **Erase all data** empties the cellar (on your other
devices too, if they sync with this one) and, unless you turn off **Also erase
previous versions and backups**, the earlier versions and the weekly backups
Encave made on the device (on Android, the files it wrote itself in
Download/Encave); files you exported or saved elsewhere are never touched. On iPhone, iPad and
Android, removing the app deletes what Encave keeps in its own storage, but not
the weekly backups in Android's Download/Encave folder: delete them in the
Files app. On a Mac, the app's container stays until you delete it. Backups you
saved elsewhere stay where you put them. For the storage, AI or search service you choose, their
own policies apply.

### Changes and contact

Changes to this policy are published here, with the date above. Questions: write to
<encave@clearboxhq.com>.

## Français

Date d'effet : 18 novembre 2026

Encave est une app de cave à vin pour iPhone, iPad, Mac et Android. Cette
politique couvre ces apps. En bref : **le développeur d'Encave ne collecte rien sur vous ni sur
votre cave.** Pas de compte, pas de mesure d'audience, pas de publicité, pas de
pistage ni de SDK tiers (sauf Google ML Kit sur Android si vous l'activez, et
Google Play Integrity sur Android pour les crédits offerts d'Encave AI, et le
système d'achat des stores pour Encave à vie, ci-dessous). Le seul serveur exploité par le développeur est celui d'Encave AI,
utilisé seulement si vous utilisez Encave AI : il reçoit des informations sur un
vin, jamais votre cave, et ne garde rien de personnel.

### Ce qui reste sur votre appareil

Votre cave (vins, bouteilles, rangements, le Journal, prix, lieux, notes), ses
photos et ses documents, ainsi que vos réglages, sont gardés dans le stockage
propre à Encave sur votre appareil. Encave n'ajoute pas de chiffrement à ces
fichiers ; ils sont protégés par l'appareil :

- **iPhone et iPad** : iOS les chiffre (protection des données, accessibles
  après le premier déverrouillage suivant un redémarrage). Ils font partie des
  sauvegardes de l'appareil que vous faites (sauvegarde iCloud ou ordinateur),
  comme pour toute app.
- **Mac** : ils sont dans le conteneur isolé de l'app, chiffrés quand FileVault
  est activé, et font partie de vos sauvegardes Time Machine si vous l'utilisez.
- **Android** : Android chiffre le stockage privé de l'app. Encave les exclut
  des sauvegardes Google dans le cloud ; ils ne passent sur un nouveau
  téléphone que par un transfert direct d'appareil à appareil.

Les clés et mots de passe que vous saisissez (clés d'IA et de recherche web,
identifiants WebDAV, clés de synchronisation) sont gardés dans le trousseau
(Apple) ou chiffrés avec une clé du Keystore Android, sur cet appareil
seulement. Seule exception, à votre choix : quand vous ajoutez un appareil,
ou plus tard depuis Appareils quand les deux sont sur le même Wi-Fi, vous
pouvez lui donner les connexions d'IA que vous cochez, avec leurs clés. Elles
sont envoyées une seule fois, directement et chiffrées entre les deux
appareils (à l'ajout d'un appareil, seulement après la confirmation du code
sur les deux), et gardées dans le trousseau de l'autre appareil ou dans son
stockage protégé par le Keystore ; jamais par un relais, iCloud, WebDAV, une
sauvegarde ou un export. Un appareil qui fait déjà partie de la cave demande
d'abord, en montrant le serveur de chaque connexion, et ne les ajoute que si
vous choisissez Ajouter.

Les réponses et les scores du jeu des arômes (« Devinez les arômes », « Mon
palais ») restent sur l’appareil qui a joué : ils ne sont jamais synchronisés,
même avec les personnes qui partagent votre cave, et sont exclus des
sauvegardes et des exports d’Encave ainsi que des sauvegardes et du transfert
d’appareil d’Android.

Ce que coûtent vos requêtes d’IA (Dépenses IA dans Réglages › IA, et dans les
Statistiques sur iPhone, iPad et Mac : la date, l’usage, le modèle, les jetons et le coût de chaque
requête, les 2 000 dernières sur douze mois au plus) est enregistré sur
l’appareil qui les a faites seulement : jamais synchronisé, exporté, ni mis dans
les sauvegardes d’Encave ou de l’appareil. Lire le crédit restant sur une clé
OpenRouter n’envoie cette clé qu’à OpenRouter, comme ses requêtes.

L'appareil photo est utilisé dans Encave pour le scanner d'Ajouter (la photo de
l'étiquette, et le code-barres de la bouteille et le code QR d'un vin partagé,
lus sur l'appareil) et pour le code d'appairage ; sur Android, les autres photos
(une autre face de la bouteille, un document) sont prises avec l'app appareil
photo de l'appareil, qui remet la photo à Encave.

**Lecture du texte de l'étiquette sur Android** (désactivée par défaut). Si vous
activez **Lire le texte de l'étiquette sur ce téléphone** (Réglages › Reconnaissance
des étiquettes par IA), Google ML Kit, une bibliothèque de Google intégrée à Encave
pour Android, lit sur le téléphone le texte d'une photo d'étiquette pour remplir le
nom, le producteur, le millésime et l'appellation. Pour cela, ni la photo ni son
texte ne quittent le téléphone. Tant que ce réglage est activé, ML Kit envoie à
Google, en HTTPS, pour ses diagnostics et ses statistiques d'utilisation : le
fabricant, le modèle, la version et le build d'Android de l'appareil et son matériel
d'apprentissage automatique ; le nom du paquet et la version de l'app ; un
identifiant de cette installation d'Encave (qui n'est pas destiné à vous identifier,
ni le téléphone) ; et l'usage de ML Kit (ses démarrages et lectures, leur durée, la
taille et le format des images, sa version, ses codes d'erreur). Selon Google, ces
données ne sont pas transmises à des tiers ([déclaration de ML Kit](https://developers.google.com/ml-kit/android-data-disclosure)) ;
la politique de confidentialité de Google s'y applique. Des statistiques enregistrées
pendant qu'il était activé peuvent encore partir peu après sa désactivation. Réglage
désactivé, ML Kit ne s'exécute pas. Le réglage reste propre à ce téléphone : jamais
synchronisé, sauvegardé ni transféré vers un nouveau téléphone.

Les rappels, les notifications de modifications venant de vos autres
appareils, les widgets, Siri, Raccourcis et Spotlight, ainsi que les fonctions
d'Apple Intelligence sur l'appareil (interroger votre cave, suggérer des
détails, estimer un prix) sont calculés sur l'appareil. Il en va de même des
demandes d'IA envoyées au modèle sur l'appareil de la connexion **Apple
Intelligence**, si vous l'ajoutez dans Réglages › IA (iPhone, iPad et Mac avec
iOS 27 ou macOS 27) : rien de ces demandes ne quitte l'appareil.

Préparer une demande de soirée (Raccourcis) et Partager une demande de soirée
(Android, dans Ce soir) ne font que vous remettre un texte : une demande de
sélection pour une soirée avec vos bouteilles et leur position, sans prix,
notes ni lieux d'achat. Encave n'envoie rien ; si vous le transmettez à une app
d'assistant comme Claude, il quitte l'appareil par cette app, selon sa
politique de confidentialité, par votre choix.

Partager ce vin (iPhone, iPad, Mac et Android) crée sur l'appareil un code QR et un
lien avec les vins choisis : leur nom, producteur, millésime et autres
éléments d'identité, et seulement les détails que vous activez (votre note et
votre commentaire, le prix payé, le lieu d'achat, la période de dégustation, ce
qu'on peut attendre, les notes des critiques, une petite image). Rien ne passe
par un serveur : le code et le lien contiennent tout, et ne parviennent qu'aux
personnes à qui vous montrez le code ou envoyez le lien, par l'app que vous
choisissez. Ouvrir un tel lien n'ajoute rien tant que vous n'avez pas choisi
où va le vin.

Les widgets de l'iPhone et de l'iPad lisent un court résumé que l'app garde sur
l'appareil, dans un dossier partagé seulement avec ses widgets : le nombre de
bouteilles, et les noms, millésimes, producteurs et positions de la bouteille
de ce soir et des premiers vins à boire bientôt. Ils ne lisent jamais la cave,
les clés ni les notes, et n'utilisent pas le réseau. Les widgets de l'écran
verrouillé montrent ce que vous choisissez d'y placer, nom du vin compris ;
Encave indique les noms et les positions comme privés, pour qu'iOS les masque
tant que l'appareil est verrouillé si vos réglages le demandent.

L'appareil garde aussi des versions précédentes de votre cave (une pour
chacun des 7 derniers jours où elle a changé, puis une par semaine pendant
4 semaines), dans le même stockage.

**Les sauvegardes ne sont pas chiffrées.** La sauvegarde hebdomadaire est
**activée par défaut** : une fois par semaine, Encave fait de lui-même un
fichier ZIP de toute votre cave, de ses photos et de ses documents, et garde les
deux derniers sur l'appareil. Elle a lieu quand vous ouvrez Encave, et en
arrière-plan : sur iPhone et iPad seulement tant que la synchronisation loin
de la maison est activée (iOS décide quand), sur Android une fois par jour.
Vous pouvez la désactiver dans les réglages.

- **iPhone, iPad et Mac** : les sauvegardes hebdomadaires sont dans le dossier
  Documents propre à Encave (sur iPhone et iPad, l'app Fichiers l'affiche sous
  Sur mon iPhone ou Sur mon iPad › Encave). Elles sont exclues des sauvegardes
  de l'appareil et de Time Machine. Sur iPhone et iPad, supprimer l'app les
  supprime.
- **Android** : les sauvegardes hebdomadaires sont dans le dossier partagé
  **Download/Encave**. L'app Fichiers, les apps que vous autorisez à accéder à
  tous les fichiers et un ordinateur branché en USB peuvent les lire. Elles y
  restent quand vous supprimez l'app.

Une sauvegarde que vous faites vous-même (**Sauvegarder maintenant** ou un
export) est un fichier standard, non chiffré lui non plus : il va là où vous
choisissez de l'enregistrer ou de le partager.

### Ce qui peut quitter votre appareil, et seulement si vous l'activez

1. **La synchronisation entre vos appareils.** Les appareils appairés
   s'échangent votre cave, ses photos et ses documents, chiffrés de bout en
   bout. Sur le même réseau, ils se connectent directement. À distance, si vous
   l'activez, ils passent par un stockage que vous choisissez : iCloud (sur les
   appareils Apple, quand il est proposé), un dossier WebDAV ou un relais
   (exploité par vous ou par quelqu'un de confiance). Il ne stocke que des
   fichiers chiffrés qu'il ne peut pas lire ; il voit quand vos appareils se
   synchronisent, combien ils envoient et, pour un serveur WebDAV ou un relais,
   leurs adresses IP. Les noms et modèles des appareils et la cave restent chiffrés. Un
   dossier WebDAV de votre réseau local peut utiliser http simple : les
   fichiers restent chiffrés, mais le nom d'utilisateur et le mot de passe
   WebDAV circulent alors en clair sur ce réseau, et Encave le signale.
   Dans une cave partagée, le nom donné dans **Appareils › Votre nom** se
   synchronise avec la cave : chaque appareil de la cave l'affiche avec vos
   dégustations et vos notes, tout comme les sauvegardes. Il est chiffré
   comme le reste.
2. **L’IA** (rien n’est envoyé tant que vous n’avez pas configuré de modèle).
   Si vous configurez des modèles d’IA avec vos propres clés (ou un serveur à
   vous), Encave leur envoie des **informations sur un vin**, directement
   depuis votre appareil, chaque fois que cela aide à renseigner ou à
   vérifier ce vin : la photo de l’étiquette quand vous scannez une étiquette
   ou demandez de compléter un vin ; les photos de la carte des vins d’un
   restaurant quand vous demandez à votre IA de la lire (la Carte des vins est
   d’abord lue sur votre appareil, sans rien envoyer ; Lire avec l’IA envoie les
   photos : l’IA liste les vins
   imprimés, avec leurs prix, et le vin que vous choisissez, le restaurant et
   le prix restent sur votre appareil, comme tout vin goûté ailleurs) ; et les
   détails du vin (comme son nom tel
   que vous l’avez saisi, le producteur, l’appellation, la région, le
   pays, la classification, le millésime, la couleur, les cépages, l’alcool
   et le format de la bouteille), avec l’année en cours (et, pour une
   estimation de prix, la devise de votre cave), pour ce à quoi s’attendre, sa
   fenêtre de dégustation, une estimation de prix ou la complétion de la
   fiche ; et, quand vous touchez Suggérer des détails sur un appareil sans
   Apple Intelligence, les termes de recherche et les résultats de votre
   recherche. Ils vont au premier modèle de votre liste, et au suivant
   seulement si le précédent échoue ou si vous demandez une autre lecture ;
   jamais à deux à la fois. Ce que l’IA
   estime est signalé comme estimé. Si une connexion permet la **recherche
   web** (activée par défaut pour Claude, ChatGPT, Grok et OpenRouter ; vous
   pouvez la désactiver), le modèle peut chercher sur le web avec ces détails
   grâce à la recherche propre à son fournisseur (par OpenRouter,
   éventuellement son partenaire de recherche, comme Exa), pour compléter la
   fiche et pour ce qui est attendu de ce millésime ; les pages utilisées
   sont listées. Après l’ajout d’un vin (sauf si vous le désactivez dans
   Réglages › IA) et quand vous touchez Chercher avec l’IA, un tel modèle
   cherche aussi sa fenêtre de dégustation, en ne recevant que le nom du vin,
   le producteur, le millésime et l’appellation ; la fiche du vin nomme le
   modèle et les pages. Par OpenRouter, par défaut, Encave demande de
   n’utiliser que des fournisseurs qui ne gardent pas les données et ne s’en
   servent pas pour l’entraînement, sauf si vous le désactivez. La politique
   de confidentialité de chaque service s’applique à ce qu’il reçoit. Vos clés
   restent sur votre appareil : elles ne sont jamais synchronisées, exportées
   ni sauvegardées (sauf si vous les donnez à un autre de vos appareils, voir
   plus haut).
   La connexion **Apple Intelligence** (appareils Apple, si vous l’ajoutez)
   n’a pas de clé : son modèle sur l’appareil n’envoie rien ; avec le modèle
   serveur d’Apple, les mêmes informations sur un vin vont au Private Cloud
   Compute d’Apple, qui, selon Apple, ne s’en sert que pour répondre et ne
   les conserve pas. Aucun des deux ne cherche sur le web.

   **Studio** (activé au départ, utilisé seulement une fois l’IA configurée).
   Après le scan d’un vin, en arrière-plan, Encave crée une image de
   présentation de ce vin. Si vous autorisez **Image générée par l’IA** et
   qu’une de vos connexions a un modèle qui crée des images (OpenRouter,
   Google ou OpenAI), la photo de l’étiquette (sans ses métadonnées) est
   envoyée au modèle d’image que vous avez choisi, avec une image de
   référence fournie avec Encave, pour créer cette image ; votre clé la paie.
   Si vous autorisez **Image officielle du web** et qu’une connexion peut
   chercher sur le web, le modèle qui complète le vin cherche aussi l’image
   officielle de la cuvée sur les sites des producteurs et des cavistes ;
   Encave la télécharge depuis ce site, depuis votre appareil (le site voit
   la demande, comme pour toute image), puis demande à un modèle qui lit les
   images si elle montre le même vin que votre photo d’étiquette, en
   envoyant les deux. L’image gardée fait partie de votre cave (synchronisée
   avec ses photos) ; les images des producteurs et des cavistes sont
   gardées pour votre usage privé. Rien d’autre n’est envoyé pour cela.
3. **La recherche web** (rien n’est envoyé tant que vous n’avez pas choisi de
   service). Si vous choisissez un service de recherche, Encave lui envoie des
   termes de recherche faits des détails d’un vin (producteur, nom,
   appellation, millésime, et pour un prix la contenance) quand vous cherchez
   en ligne, un prix ou une image ; vous pouvez modifier les termes et
   chercher de nouveau. Les résultats sont lus sur l’appareil. Quand vous
   cherchez un prix, Encave ouvre ensuite les cinq premières pages de
   résultats depuis votre appareil et y lit le prix de la bouteille, sur
   l’appareil. Ces sites voient votre adresse IP, la page demandée et le nom
   et la version de l’app (sur les appareils Apple, aussi la version du
   système et vos langues préférées, que le système envoie) ; aucun cookie,
   mot de passe enregistré ni page de provenance n’est envoyé. Chaque
   recherche ouvre ses propres connexions, fermées ensuite. Encave refuse les
   pages dont le nom mène à votre appareil ou à votre réseau local. Quand vous
   cherchez des images, les miniatures et l’image choisie sont téléchargées
   depuis les sites qui les hébergent, qui voient la demande (les images de
   votre appareil ou de votre réseau local sont refusées aussi) ; l’image
   devient la couverture du vin et ne remplace jamais votre photo d’étiquette.

**Jamais envoyé à un service d’IA, de recherche ou du web :** votre cave dans
son ensemble ou sous forme de liste, à qui elle appartient, vos lieux de
rangement et la position de vos bouteilles, les prix que vous avez payés, où
et quand vous avez acheté, vos notes, dégustations, évaluations et le jeu des
arômes, les occasions et les réservations, les noms et les contacts, les
comptes, les identifiants d’appareil et de synchronisation, et votre position.
Les photos perdent leurs métadonnées (comme la position ou l’appareil photo)
avant l’envoi. Les requêtes ne portent ni cookie ni identifiant de vous ou de
votre appareil ; comme toute connexion, le service voit votre adresse IP.

Le HTTP non chiffré n'est utilisé que pour un serveur de votre réseau local, y
compris un nom de votre réseau domestique (comme un nom en `.local`) : Encave ne
se connecte alors qu'à une adresse locale de ce nom, jamais à une adresse hors
de votre réseau, et refuse un nom qui n'en a aucune. Une telle connexion ne
passe jamais par un proxy configuré sur l'appareil. Tout le reste passe en
HTTPS. Les liens (le site, cette politique, un
résultat de recherche) s'ouvrent dans votre navigateur.

### Encave AI, le serveur du développeur

Encave AI est l'IA qui fonctionne sans clés à vous, payée avec des crédits.
Elle n'est utilisée que si son interrupteur est activé dans **Réglages › IA**
(tant que vous n'y avez pas touché, seulement quand aucune IA à vous ne peut
répondre). Si vos propres clés sont activées, elles sont demandées d'abord, et
Encave AI seulement quand elles ne peuvent pas répondre.

- **Ce qui est envoyé** : les mêmes informations sur un vin que pour votre
  propre IA (ci-dessus) : la photo de l'étiquette, les photos d'une carte des
  vins que vous scannez et les détails du vin, envoyés en HTTPS (TLS 1.3) au
  serveur d'Encave. Le serveur transmet la requête au fournisseur d'IA par
  OpenRouter, en lui demandant de n'utiliser que des fournisseurs qui ne gardent
  rien et n'entraînent rien. Votre cave, vos prix payés, vos lieux, vos notes,
  noms et contacts ne sont jamais envoyés.
- **Votre portefeuille** : pas de compte. Votre appareil crée une clé ; le
  serveur garde un numéro de portefeuille au hasard et la moitié publique de
  cette clé, jamais votre nom, votre e-mail, ni un identifiant d'appareil,
  Apple ou Google. Chaque requête est signée avec la clé : seuls vos appareils
  peuvent utiliser vos crédits. Sur les appareils Apple, la clé est dans votre
  trousseau iCloud (vos autres appareils Apple partagent le portefeuille) ; sur
  Android, elle reste sur le téléphone.
- **Ce que le serveur garde** : pour chaque portefeuille, le solde, les crédits
  donnés ou utilisés, les bouteilles ouvertes (un numéro au hasard pour
  chacune, valable 30 jours), des coûts et des compteurs pour les limites et,
  pendant une dizaine de minutes, le numéro au hasard de chaque requête signée
  (pour qu'elle ne puisse pas être rejouée). Hors bêta (ci-dessous), il ne garde **aucun contenu de
  requête** (ni photo, ni vin, ni réponse) et **n'écrit aucune adresse IP** :
  les adresses ne sont gardées qu'en mémoire, peu de temps, pour limiter les
  abus. Un portefeuille jamais utilisé est effacé après 30 jours. Les données
  du serveur sont sauvegardées chaque jour sur le serveur.
- **Dépannage, anonyme** : pour chaque requête, le serveur note son type
  (étiquette, détails…), le modèle et le fournisseur d'IA, si elle a réussi ou
  l'erreur, sa durée et sa taille en tokens. Jamais le portefeuille, une adresse
  ni le contenu. Ces notes sont effacées après 7 jours (30 jours tant qu'Encave
  est en bêta).
- **Pendant la bêta (TestFlight seulement)** : pour reproduire les problèmes et
  choisir les meilleurs modèles d'IA, le serveur garde aussi les requêtes des
  installations TestFlight et les réponses de l'IA : les photos d'étiquette (sans
  leurs métadonnées, comme le lieu), les détails du vin envoyés et la réponse.
  Quand une installation TestFlight avec un portefeuille Encave AI lit une carte
  des vins sur l'appareil, elle envoie aussi les photos de la carte (sans leurs
  métadonnées), le texte reconnu par l'appareil et les vins lus, gardés de la même
  façon pour améliorer la lecture.
  Elles ne sont pas liées à votre portefeuille et sont effacées après 30 jours.
  Les installations depuis l'App Store ne sont jamais gardées.
- **Les crédits offerts, une fois par appareil** : pour ne les offrir
  qu'une fois, l'app demande au système de se porter garant, seulement quand
  votre portefeuille est créé :
  - **Apple** : DeviceCheck d'Apple (Apple garde deux bits par appareil pour
    Encave ; le serveur en met un pour dire « crédits offerts ») et la
    preuve signée par l'App Store que l'app a été installée depuis l'App Store
    ou TestFlight.
  - **Android** : Google Play Integrity. Google Play vérifie que l'app et le
    téléphone sont authentiques et donne un verdict signé, que le serveur fait
    décoder par Google puis oublie. Pour cela, Google collecte des informations
    sur le téléphone et l'app, selon sa propre politique (voir
    [la page de Play Integrity sur les données](https://developer.android.com/google/play/integrity/overview)).
    En cas d'échec, vous n'avez pas de crédits offerts ; rien d'autre ne
    change.

  Aucune de ces vérifications ne concerne votre cave.

### Encave à vie et l'essai gratuit

Encave s'essaie gratuitement pendant 14 jours ; Encave à vie s'achète ensuite
une seule fois, dans l'app, sans abonnement. L'essai et l'achat passent par
l'App Store (l'achat intégré d'Apple) ou Google Play (Google Play Billing),
selon leurs politiques : Apple ou Google encaissent le paiement et disent à
l'app ce que votre compte du store possède. L'app le lit sur l'appareil. Ce
n'est jamais envoyé au développeur ni au serveur d'Encave AI, ni synchronisé :
chaque appareil interroge son propre store. Sur Android, la date de début de
l'essai reste sur l'appareil. D'Apple et de Google, le développeur ne reçoit
que des rapports de ventes (combien, quel montant, par pays), jamais qui a
acheté.

### Ce que les stores peuvent fournir

Apple et Google peuvent transmettre aux développeurs des rapports de plantage
et des statistiques d'utilisation des utilisateurs qui l'ont autorisé dans les
réglages du système (par exemple « Partager avec les développeurs d'apps »).
Ils sont collectés par Apple ou Google selon leurs politiques, pas par Encave,
et ne contiennent aucune donnée de la cave.

### Enfants

Encave parle de vin et ne s'adresse pas aux enfants.

### Vos droits

Le développeur ne détient aucune donnée sur vous : il n'y a rien à consulter,
corriger ou supprimer de son côté. Vous pouvez à tout moment exporter, supprimer
et restaurer vos données dans l'app. **Effacer toutes les données** vide la
cave (sur vos autres appareils aussi, s’ils se synchronisent avec celui-ci) et,
sauf si vous désactivez **Effacer aussi les versions précédentes et les
sauvegardes**, les versions précédentes et les sauvegardes hebdomadaires
qu’Encave a faites sur l’appareil (sur Android, les fichiers qu’il a écrits
lui-même dans Download/Encave) ; les fichiers que vous avez exportés ou
enregistrés ailleurs ne sont jamais touchés. Sur iPhone, iPad et Android,
supprimer l’app efface ce qu’Encave garde dans son propre stockage, mais pas
les sauvegardes hebdomadaires du dossier Download/Encave d’Android :
supprimez-les dans l’app Fichiers. Sur Mac, le conteneur de l'app reste jusqu'à ce que vous le supprimiez. Les sauvegardes enregistrées
ailleurs restent là où vous les avez mises. Pour le stockage, le service d'IA ou
de recherche que vous choisissez, leurs propres politiques s'appliquent.

### Modifications et contact

Les modifications de cette politique sont publiées ici, avec la date
ci-dessus. Questions : écrivez à
<encave@clearboxhq.com>.
