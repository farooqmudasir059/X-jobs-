# X-jobs-# Job Finder - Flutter App (Sample Project)

This is a ready-to-run Flutter sample project for a **Job Finder** app.
It uses **local sample data** (no Firebase required) so you can run and test the app immediately.

## Quick start

1. Install Flutter on your computer (or use an online editor that supports Flutter).
2. From project root, run:

flutter pub get flutter run

3. To connect to Firebase later, generate `lib/firebase_options.dart` using `flutterfire configure`
and replace the file.

## What is included
- `lib/` - Flutter source code with job feed, detail view, search and filters.
- `.github/workflows/flutter_build.yml` - GitHub Actions workflow to build APK on push to `main`.
- `assets/sample_jobs.json` - sample jobs used by the app.

You can upload this repository to GitHub and the workflow will automatically build an APK.

