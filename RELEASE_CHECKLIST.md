# DiDi Max release checklist

## Implemented in this starter
- Luxury black/gold UI
- Welcome flow
- Home dashboard
- Video import
- Cut/Trim export to Movies/DiDi Max (Android 10+)
- Photo import
- Original/Warm/Mono filters
- Starter games
- Settings/About screens
- Portrait orientation
- App icon

## Required before public production release
1. Add a backend (authentication, profile, cloud media metadata).
2. Configure secure cloud media storage.
3. Replace placeholder game content with licensed/original assets.
4. Add a real video preview/player and non-destructive editing pipeline.
5. Add complete photo editing/export.
6. Add an ad provider SDK and real ad-unit IDs if ads are wanted.
7. Add billing/subscriptions if Premium is wanted.
8. Add privacy policy, terms, consent flows and data deletion.
9. Configure crash reporting and analytics.
10. Create a release keystore and Play App Signing setup.
11. Test on multiple Android devices and screen sizes.
12. Build a signed AAB for Google Play and a signed APK for direct installation.

## Important
The project does not contain third-party service credentials. Those must belong to the app owner and should never be hard-coded into source control.
