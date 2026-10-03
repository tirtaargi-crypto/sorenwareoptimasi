# SorenWare

Ready-to-upload Android project with GitHub Actions.

1. Extract this ZIP.
2. Upload the extracted files/folders to the root of your GitHub repository.
3. Commit.
4. Open Actions > Build SorenWare APK.
5. Run the workflow.
6. Download `SorenWare-debug-apk` from Artifacts.

Important: `.github/workflows/build-apk.yml` is a YAML workflow. `app/build.gradle.kts` is the Android Gradle file. They must not be swapped.

Java and Kotlin are both configured for JVM 17 to avoid the previous 1.8 vs 17 error.
