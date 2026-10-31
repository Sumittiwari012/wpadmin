# GripStyle-Admin (single app)

Opens only: https://gripstylepos.netlify.app/adminwp

1. Create a **private** GitHub repo and push everything in this folder (keep the `.github` folder).
2. Actions tab -> "Build APK" (runs on every push, or "Run workflow").
3. Download **GripStyle-Admin-apk** from the run's Artifacts, unzip, install the .apk.

Install new builds OVER the old app (don't uninstall first) or the saved login is lost.
To change the link, edit START_URL in app/build.gradle.
