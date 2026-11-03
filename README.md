# Simple STT

**Speech-to-text, simplified.**

A fast, local-first speech workspace for turning spoken ideas into editable text, correcting recognition mistakes, reading drafts aloud, and getting the result where it needs to go.

[Website](https://simple-stt.com) · [Source code](https://github.com/basedwon/simple-stt) · [Releases](https://github.com/basedwon/sstt/releases)

## What you can do

- **Dictate and edit in one place.** Capture speech, refine the draft, and send or copy the text without losing your working context.
- **Choose your recognition provider.** Use the on-device Whistle engine, supported browser speech recognition, or an explicitly configured local/remote transcription service.
- **Teach it your vocabulary.** Keep frequently misrecognized names, projects, and phrases in a personal correction list.
- **Listen to your writing.** Read Aloud supports pause/resume, progress and five-word jumps.
- **Keep your workspace.** Local persistence stores drafts, preferences, history and corrections on your device, subject to the capabilities of your distribution.
- **Use familiar shortcuts.** Keyboard-first controls include recording, history, insertion and sending.

## Get Simple STT

Visit **[simple-stt.com](https://simple-stt.com)** for the download page and the recommended build for your platform.

| Platform | Distribution |
| --- | --- |
| Windows | Native desktop installer |
| macOS | Native desktop application |
| Linux | Native desktop package |
| Chrome | Browser extension |
| Web | Browser application / PWA |
| Portable | Offline-capable HTML (served over localhost/HTTPS) or shell HTML |
| Android and iOS | Planned mobile distributions |

Installers and store entries are **available only after their corresponding releases are published and verified**. The download page should link to the actual release asset rather than a guessed filename.

### Download directly from GitHub

When a release is available, open [Releases](https://github.com/basedwon/sstt/releases), choose a version, then select the installer or portable asset for your device under **Assets**. You do **not** need to clone the Git repository to download an installer.

Releases can include multiple files—Windows, macOS, Linux, portable HTML, checksums, and update artifacts—under the same version tag. Download only the assets appropriate for your platform.

## Privacy and providers

Simple STT is designed around local-first workflows, but privacy depends on the provider you select.

- **Whistle** performs recognition on-device once its required assets are available.
- **Browser recognition** uses the browser's speech service, which may process audio remotely.
- **Local/remote API providers** send audio only to the endpoint you explicitly configure and select.

Microphone access requires user permission. Optional provider services and their privacy policies are separate from local workspace storage.

## Project and development

Simple STT is built by [Basedwon](https://github.com/basedwon). The product's public-facing source lives at [basedwon/simple-stt](https://github.com/basedwon/simple-stt); the shared application architecture is designed for browser, portable, extension, and native distributions.

The source is MIT-licensed. If you're interested in the project, want to report an issue, or want to collaborate, start with the [source repository](https://github.com/basedwon/simple-stt) or [simple-stt.com](https://simple-stt.com).

---

**Release delivery note:** This `sstt` repository is currently a **public release-workflow sandbox**, separate from the eventual production release channel. Its `v0.0.0-release-lab.1` prerelease contains older portable HTML artifacts used to verify direct anonymous downloads; those files may not reflect the current Simple STT source. Public production installers will be linked from the official website only after build verification and deliberate publication.
