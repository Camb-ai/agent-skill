# CAMB AI Agent Skill

Agent skill for [CAMB AI](https://camb.ai) voice and translation APIs — text-to-speech, voice cloning, dubbing, and transcription.

## Install

### Claude Code

```bash
/skill add Camb-ai/agent-skill
```

### Manual

Clone into your Claude skills directory:

```bash
git clone https://github.com/Camb-ai/agent-skill.git ~/.claude/skills/camb-ai-agent-skill
```

## What's included

| Capability | Description |
|------------|-------------|
| **Text-to-Speech** | Streaming TTS with MARS models (mars-flash, mars-pro, mars-instruct) |
| **Voice Cloning** | Clone voices from 10-30s reference audio |
| **Translation** | Translate text and generate speech in 50+ languages |
| **Transcription** | Speech-to-text from audio/video files |
| **Dubbing** | Dub videos/audio into other languages |
| **Integrations** | Pipecat and LiveKit real-time voice agent examples |

## Setup

1. Get an API key from [CAMB AI Studio](https://studio.camb.ai)
2. Set your environment variable:

```bash
export CAMB_API_KEY=your_api_key
```

3. Install the SDK:

```bash
# Python
pip install camb-sdk

# Node.js
npm install @camb-ai/sdk
```

## Links

- [CAMB AI Documentation](https://docs.camb.ai)
- [CAMB AI Studio](https://studio.camb.ai)
- [Python SDK](https://pypi.org/project/camb-sdk/)
- [Node.js SDK](https://www.npmjs.com/package/@camb-ai/sdk)
