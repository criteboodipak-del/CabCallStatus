# Cab & Call Status — one-click APK build

## Phone-only build
1. Create a GitHub account at github.com if needed.
2. Create a new repository, e.g. `CabCallStatus`.
3. Upload ALL files/folders from this project to the repository. Keep `.github/workflows/build-apk.yml` exactly in that path.
4. Open the repository's **Actions** tab.
5. Select **Build APK**.
6. Tap **Run workflow** (after the first push, the workflow also runs automatically).
7. Wait for the green check.
8. Open the completed workflow run, scroll to **Artifacts**, and download `CabCallStatus-debug-apk`.
9. Extract the downloaded artifact and install `app-debug.apk` on your Vivo T4 Pro.

This is a local demo. It does not secretly detect another person's calls or status. A future multi-user version should use explicit user consent and a backend such as Firebase.
