# FreeStream Hub — GitHub-ready project

This archive preserves the required Android folder structure, including:
- app/src/main/...
- .github/workflows/build-apk.yml

## Build on GitHub from Android
1. Create an empty GitHub repository.
2. Upload the project files **with their folder paths preserved**.
3. Confirm the repository contains `app/` and `.github/`.
4. Open **Actions** → **Build APK** → **Run workflow**.
5. After the run succeeds, open the run and download the `FreeStream-Hub-debug` artifact.
6. Extract the artifact and install `app-debug.apk`.

Do not upload the outer ZIP as a repository file; GitHub does not automatically extract ZIP archives.
