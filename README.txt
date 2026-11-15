GOOD BOY POINTS — ANDROID STUDIO STARTER

This is an Android Studio project wrapping the supplied V5 website in a WebView.
The original HTML is included at app/src/main/assets/index.html.

BUILD
1. Install Android Studio on a computer.
2. Open this folder as an existing project.
3. Let Gradle sync (Android Studio may install the requested SDK/build tools).
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Find the APK under app/build/outputs/apk/debug/app-debug.apk.
6. Transfer it to your Android phone and install it. Android may ask you to allow installs from that file manager/browser.

IMPORTANT CURRENT LIMITATIONS
- This is a starter project, not a finished/verified APK. It has not been compiled or tested on a device here.
- Supabase URL and publishable/anon key must be entered in the app's setup screen, just as in the website.
- The points widget shows the last balance reported while the app is open; it is not yet a background live-sync widget.
- The appreciation widget rotates a daily message.
- A native quick-add widget action is not implemented yet. The widget currently opens the app; point changes continue to go through the existing authenticated Supabase app logic and permissions.
- Do not put a Supabase service-role key in the app.
