# Aeva's Enhanced OpenClaw Railway Template

This is a fork of [openclaw-railway-template](https://github.com/codetitlan/openclaw-railway-template) with additional binaries for full OpenClaw skill support.

## Additional Binaries Installed

### CLI Tools
- **GitHub CLI (`gh`)** - Full GitHub operations (issues, PRs, repos, CI/CD)
- **jq** - JSON processing and manipulation
- **wget** - Additional file download tool

### Utilities
- **vim** - Text editor
- **nano** - Lightweight text editor
- **htop** - Interactive process viewer
- **tree** - Directory structure visualization
- **zip/unzip** - Archive management
- **ffmpeg** - Audio/video processing (for voice/media skills)

## Why These Tools?

With these binaries, OpenClaw can now run ALL skills that require shell access:
- ✅ GitHub skill (gh CLI)
- ✅ Notion skill (curl - already included)
- ✅ OpenAI Whisper API (curl - already included)
- ✅ Google Workspace (gog - if installed as skill)
- ✅ Web search (Brave API - no binary needed)
- ✅ Media processing (ffmpeg for audio/video)

## Deployment

Same as original template:
1. Fork this repo
2. Deploy to Railway
3. Set environment variables
4. Visit `/setup` to configure

## Credits

Based on [codetitlan/openclaw-railway-template](https://github.com/codetitlan/openclaw-railway-template)

Enhanced for [Aeva](https://github.com/AdamOhayon) - Adam's digital twin assistant.
