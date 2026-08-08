# Build FreeStream Hub using only your phone

## Recommended: GitHub Actions (no PC required)

1. On your Android phone, open github.com in Chrome and sign in.
2. Create a new repository. Example name: `FreeStreamHub`.
3. Upload ALL files/folders from this project to the repository.
   - Upload the project contents, not the outer ZIP.
   - Make sure `.github/workflows/build-apk.yml` is uploaded.
4. Open the repository's **Actions** tab.
5. Select **Build APK**.
6. Tap **Run workflow** (or push to `main`, which also starts a build).
7. Wait for the green check.
8. Open the completed workflow run.
9. Under **Artifacts**, download `FreeStream-Hub-debug`.
10. Extract the downloaded artifact and install `app-debug.apk`.

If GitHub asks whether workflows are allowed, allow/enable Actions for the repository.

## Important
This app is a legal streaming-discovery app. It does not bypass subscriptions, DRM, geo-restrictions, or paid access.
