# Zetboo pour Android

Application Android de [Zetboo](https://zetboo.com), plateforme de chat en direct gratuite et multilingue
(salons publics, messages privés, appels audio et vidéo).

L'application ouvre `https://zetboo.com/app/` en plein écran grâce à une
[Trusted Web Activity](https://developer.chrome.com/docs/android/trusted-web-activity) (TWA),
générée avec [Bubblewrap](https://github.com/GoogleChromeLabs/bubblewrap). Le service Zetboo lui-même
tourne sur le serveur zetboo.com ; ce dépôt ne contient que l'application Android.

## Construire

    ./gradlew assembleRelease

Réglages de l'application : `twa-manifest.json` (régénérer le projet avec `bubblewrap update`).

## Licence

Apache License 2.0, voir [LICENSE](LICENSE).

---

# Zetboo for Android

Android app for [Zetboo](https://zetboo.com), a free multilingual live chat platform (public rooms,
private messages, audio and video calls). It opens `https://zetboo.com/app/` full screen as a
Trusted Web Activity built with Bubblewrap. Build with `./gradlew assembleRelease`.
Licensed under the Apache License 2.0.
