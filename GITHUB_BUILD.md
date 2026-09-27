# GitHub build instructions

1. Create a new GitHub repository, for example `my-meeting`.
2. Upload all files from this folder to the repository.
3. Open the repository's **Actions** tab.
4. Select **Build My Meeting APK**.
5. Click **Run workflow**.
6. When the workflow completes, open the workflow run and download the artifact named:
   `my-meeting-release-apk`

The workflow generates Android platform files, installs dependencies, builds the release APK, and uploads the APK as a downloadable artifact.

For production publishing, configure an Android signing key and keep signing secrets in GitHub Actions Secrets. Do not commit passwords or private keys.
