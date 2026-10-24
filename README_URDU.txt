PHARMA NET SHOP SURVEY - ANDROID APK CLOUD BUILD PROJECT

Yeh Android Studio ke baghair GitHub Actions se APK compile karne ke liye project hai.

Ahm baat:
- Is ZIP mein APK pehle se compiled nahin hai.
- Central office online sync abhi configured nahin hai. Is ke liye Google Apps Script/Sheets ya doosra backend deploy karna hoga.
- Yeh WebView wrapper maujooda survey HTML ko Android app mein kholta hai aur location permission handle karta hai.
- Real Android phone par install/test zaroor karein; is build ko abhi device-tested na samjhein.

APK banane ke basic steps:
1. GitHub.com par sign in karein aur New repository banayein.
2. Is ZIP ko extract karke project ki tamam files repository mein upload karein (hidden .github folder bhi zaroor upload ho).
3. GitHub repository mein Actions tab kholein. Workflow run/build complete hone dein.
4. Build successful ho to workflow run ke neeche Artifacts mein PharmaNet-Shop-Survey-APK.zip download karein.
5. ZIP extract karke app-debug.apk Android phone par bhejein aur install karein. Android unknown-app installation permission pooch sakta hai.

Agar build fail ho to error log share karein; bina successful build ke APK ready nahin mana jayega.
