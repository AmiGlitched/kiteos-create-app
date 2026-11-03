# KiteOS Create

A video editor for Mac and Windows that edits from a sentence. Drop in your clips and photos, say what you want ("a 30-second reel of our holiday with upbeat music"), and it cuts, captions, scores and grades the video on a real timeline. Every change the AI makes is a setting you can see and move: the crop, the colour wheels, the keyframes, the captions.

This repository holds the installers and release notes. The source code is private.

**[Download the latest version](https://github.com/AmiGlitched/kiteos-create-app/releases/latest)** · [Website](https://creativedesk.online/create) · [Report a problem](https://github.com/AmiGlitched/kiteos-create-app/issues)

## Free, with your own AI

KiteOS Create is free. It has no AI of its own, so you connect one:

| Connect | What it costs you |
|---|---|
| Claude Code, OpenAI Codex or Google Antigravity | Nothing extra: it uses the plan you're signed in to |
| An API key (Anthropic, OpenAI or Google) | What the provider charges for the requests |
| A local model (Ollama or LM Studio) | Nothing, and nothing leaves your computer |

Without an AI you still get the full timeline, pause removal, transcription and captions, rule-based reels from your clips, and every export format. Kite AI, a paid plan with editing, video and voice in one subscription, comes later.

You sign in with a free KiteOS account.

## Requirements

- **Mac:** Apple Silicon (M1 or newer). macOS 15 or newer recommended.
- **Windows:** Windows 10 or 11, 64-bit.
- Intel Macs and Linux are not supported yet.

## Opening it the first time

The app isn't signed with an Apple or Microsoft certificate yet, so your computer warns you once.

**Mac.** Open the `.dmg` and drag KiteOS Create to Applications. If macOS says it can't be opened, go to System Settings > Privacy & Security and click **Open Anyway** next to KiteOS Create. Or run this once in Terminal:

```
xattr -dr com.apple.quarantine "/Applications/KiteOS Create.app"
```

**Windows.** If SmartScreen shows "Windows protected your PC", click **More info**, then **Run anyway**.

Each release lists the SHA-256 of its files, so you can check a download matches.

## Your footage

Your videos stay on your computer. When you ask the AI for an edit, your words, the transcript and frames from the video go to the AI you connected, under that provider's terms. With a local model they go nowhere.

## Problems and ideas

Open an [issue](https://github.com/AmiGlitched/kiteos-create-app/issues) with what you did, what you expected, and your Mac or Windows version. A screenshot helps.

KiteOS Create is made by Almure Pressery Private Limited.
