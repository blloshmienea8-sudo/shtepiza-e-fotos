# Shtepiza e Fotos — iOS

Native iOS WebView wrapper for:
https://sht-piza-e-fotos.ai.studio/

## What it includes
- Native Swift + WKWebView
- Full-screen app
- Camera, microphone and photo-library permission descriptions
- Web file uploads
- In-app navigation
- App icon generated from the supplied Shtepiza e Fotos logo
- Codemagic workflow for IPA

## Codemagic
1. Upload this project to a GitHub repository.
2. Connect the repository in Codemagic.
3. Connect Apple Developer / App Store Connect signing credentials.
4. Start the `ios-release` workflow.

Bundle ID:
`com.shtepizaefotos.app`

Important: an Apple Developer account and valid signing credentials are required to produce an installable App Store IPA.
