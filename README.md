# Quiz Foot Penalty — Play Store build

This project contains the mobile game web build and a GitHub Actions workflow that generates an Android App Bundle (AAB).

## Fast path from a phone
1. Create a GitHub repository and upload these files.
2. GitHub Actions will generate the Android project and build a release bundle.
3. For Google Play, the release must be signed. Configure an upload keystore as GitHub Actions secrets before the signed build step.

App ID: com.quizfootpenalty.app
App name: Quiz Foot Penalty
