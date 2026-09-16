# DiDi Max — full starter build

This version starts the complete product flow from the supplied design.

## Included now
- Luxury black/gold UI
- Welcome and home dashboard
- Video section and video editor entry
- Android file picker for videos
- Photo section and photo editor
- Android file picker for photos
- Original / Warm / Mono photo filters
- Save/export UI placeholders
- Games catalogue
- Playable Tap Challenge
- Playable starter Memory Match
- Playable Tic Tac Toe
- Bottom navigation
- App icon
- Portrait Android configuration

## Build APK
Open this folder in Android Studio.
Allow Gradle to sync, then:
Build > Build Bundle(s) / APK(s) > Build APK(s)

Application ID: com.didimax.app
Version: 1.0.0

## Production work still required
The UI and app flow are implemented, but a production release still needs:
- additional video rendering features (effects, filters, music, text) beyond the working Cut/Trim pipeline
- full non-destructive photo editing and export
- original game art/game engines/content
- user accounts and backend
- cloud media storage
- subscriptions/payments
- privacy policy, terms, analytics/crash reporting
- Play Store signing and release configuration


## Cut / Trim feature
The Video Editor now supports:
- selecting a video from the Android file picker
- choosing start and end positions with trim sliders
- showing the selected duration
- cutting the selected range without re-encoding the original tracks
- saving the result to `Movies/DiDi Max` on Android 10+

## Cloud APK build

See `docs/CLOUD_APK_BUILD.md`. A GitHub Actions workflow is included at `.github/workflows/android-apk.yml` and produces a testable `app-debug.apk` artifact in the cloud.
