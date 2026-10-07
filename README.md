# Amerikano Segnapunti: canale aggiornamenti

Qui ci sono solo l'APK firmata e il manifest `latest.json` che l'app legge all'avvio. I sorgenti stanno in un repo privato.
L'app scarica l'APK solo se `versionCode` è più alto di quello installato, e la installa solo se il suo SHA-256 coincide con quello del manifest.
