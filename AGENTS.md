# Codex instructions

Project: VeroDate TrueMatch Verify, a demonstration gesture challenge, NOT an identity-verification system.

Goals: make camera and MediaPipe work reliably on Android Chrome; three automatic challenges (smile, peace sign, head turn), capture each frame locally, and display a clearly DEMO-only badge. Preserve user consent, no backend uploads of camera frames. Model assets must be served locally by Vite; no runtime CDN imports. Run npm test and npm run build before deployment. Never claim anti-spoofing or biometric identity assurance. Do not commit secrets, face photos or biometric data.
