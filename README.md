# Monami's apps

Installers for [Monami](https://monami.narikia.com): meetings, webinars and courses. Download them at **https://monami.narikia.com/download**.

Each release is built by this repository's Release workflow from Monami's private source, tested on macOS and on Windows against monami.narikia.com, and published here with its SHA-256 checksums (`SHA256SUMS.txt`).

The app is a window onto monami.narikia.com and opens nothing else. It is not yet signed with Apple's or Microsoft's certificates, so both systems warn on the first start; the download page says what to choose.

The iPhone, iPad and Android apps are built and tested here too, by the Mobile workflow. The TestFlight and Google Play workflows send them to testers; nothing is in the App Store or on Google Play for the public yet. The source of all the apps stays private; this repository holds only its workflows and the releases.

The Uptime workflow checks monami.narikia.com every two hours.
