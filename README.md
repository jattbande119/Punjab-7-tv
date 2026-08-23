# Punjab 7 TV — GitHub + Firebase + OBS

1. Create Firebase project and enable Realtime Database.
2. Create a Web App and paste its config into `config.js`.
3. For first testing, use `firebase-rules.json` rules.
4. Upload this entire folder to a GitHub repository.
5. GitHub Settings → Pages → Deploy from branch → main/root.
6. Controller URL: `https://USERNAME.github.io/REPO/controller.html`
7. OBS Browser Source URL: `https://USERNAME.github.io/REPO/overlay.html`
8. OBS Browser Source size: 1920×1080.

Flow: Phone Controller → Firebase Realtime Database → OBS Overlay.

Score: 0 → 1.5 → 2.5 → 3.5 ... and minus reverses it.

The controller edits Team Names, Main, Title, Subtitle, Last Line, Phone, Show/Hide and Opposite View.

The included Firebase rules are for testing only. Add Firebase Authentication and restrict writes before public use.
