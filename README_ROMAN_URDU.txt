PHARMA NET SURVEY - ANDROID APP PROJECT

Ye Android Studio/GitHub Actions project hai, compiled APK abhi nahi hai.

APK nikalne ka sab se seedha tareeqa:
1. Is ZIP ko GitHub par new repository mein upload karein.
2. Repository ke Actions tab mein Build Pharma Net Survey APK workflow select karein.
3. Run workflow dabayein.
4. Build complete hone par run ke Artifacts mein PharmaNet-Survey-APK download karein.
5. ZIP extract karke app-debug.apk supervisor ko WhatsApp se bhej dein.
6. Supervisor Android mein APK tap kare, zarurat par “Install unknown apps” allow kare, phir Install.

Important:
- Survey entries app ke local WebView storage mein rehti hain; devices ke darmiyan auto-sync nahi hota.
- PDF/download/share features Android WebView mein browser se mukhtalif behave kar sakte hain; actual phone testing zaroori hai.
- Ye debug APK hogi. Agar production/distribution signing chahiye to release keystore se sign karna hoga.
- APK banane ke liye GitHub account/repository par project upload karna zaroori hai; is environment mein Android SDK/Gradle installed nahi, is liye yahan direct compile nahi ho saka.
