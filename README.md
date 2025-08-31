CNC Simulator - Android project (ready to build)

What I included:
- Minimal Android Studio project (Jetpack Compose, Kotlin)
- MainActivity with the CNC simulator UI and parser (educational)
- GitHub Actions workflow that builds the debug APK automatically (no gradle wrapper required)

How to get the APK without a PC:
1. Create a new GitHub repository (empty).
2. Upload the files from this zip to the repo (you can use GitHub mobile app / web).
3. Push to the `main` branch. GitHub Actions will run the workflow and produce `app-debug.apk` as an artifact.
4. Open the Actions tab in GitHub web or mobile, open the workflow run, and download the artifact `app-debug-apk`.
5. Install the APK on your Android phone (enable install from unknown sources).

If you want, I can also:
- produce a WebApp version (HTML/JS) you can run directly in the phone browser (no install needed)
- try to produce the binary APK for you (I can't compile binaries from this environment, but I can help you or someone you trust to get the APK using the steps above)