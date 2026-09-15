# Lesvos Basket — Android / Google Play

Έτοιμο Android Studio project για το live app:
https://lesvos-basket.netlify.app/

## Στοιχεία εφαρμογής
- Όνομα: Lesvos Basket
- Application ID: gr.lesvosbasket.app
- Version: 1.0.0
- minSdk: 24
- targetSdk: 35
- HTTPS only
- Εξωτερικά links ανοίγουν στον browser

## Παραγωγή AAB
1. Άνοιξε αυτόν τον φάκελο στο Android Studio.
2. Περίμενε να ολοκληρωθεί το Gradle Sync.
3. Build > Generate Signed App Bundle or APK.
4. Επίλεξε Android App Bundle.
5. Δημιούργησε/επέλεξε keystore και φύλαξέ το με ασφάλεια.
6. Επίλεξε release και Generate.
7. Ανέβασε το παραγόμενο .aab στο Google Play Console.

## Πριν από δημοσίευση
Χρειάζονται τελικό launcher icon, screenshots/feature graphic,
privacy policy URL, store listing και οι σωστές δηλώσεις Data Safety.

Σημείωση: Το project φορτώνει το production site μέσα σε Android WebView.
Η αποδοχή στο Google Play εξαρτάται από τις ισχύουσες πολιτικές και τον
τελικό έλεγχο της Google. Το package ID καλό είναι να θεωρηθεί μόνιμο
μόλις γίνει η πρώτη δημοσίευση.
