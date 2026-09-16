# Build the DiDi Max APK in the cloud

This project includes a GitHub Actions workflow that builds a debug APK without requiring Android Studio on your phone.

## Exact steps

1. Create or sign in to a GitHub account.
2. Create a new repository, for example `didimax`.
3. Upload **all files and folders inside this project** to the repository. Keep the `.github/workflows/android-apk.yml` file in exactly that location.
4. Open the repository's **Actions** tab.
5. Select **Build DiDi Max APK**.
6. Press **Run workflow**.
7. Wait for the build to finish.
8. Open the completed workflow run and download the artifact named **DiDi-Max-debug-apk**.
9. Inside the downloaded artifact is `app-debug.apk`, which can be installed on a compatible Android phone for testing.

## Release APK

The workflow intentionally builds a debug APK so no signing key or secret is required. A Play Store release needs a private signing key and release configuration. Do not put a private keystore or passwords directly into the repository.

## Current app scope

The source includes the DiDi Max luxury UI, welcome/home navigation, photo import/filter UI, video import and encoded cut/trim export, starter games, settings/about screens, and Android project configuration.

Production services such as cloud accounts, online sync, advertising networks, payments, and large game/content catalogues still need their own provider accounts, credentials, backend services, and implementation.
