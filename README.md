# TLDR

AI Video Editor Boilerplate

## PREREQS

- A Coding Agent
  - Claude Code ($100/month) [https://code.claude.com/docs/en/quickstart]
  - Codex ($100/month) [https://chatgpt.com/codex]
  - OpenCode ($10/month) [https://opencode.ai/]
  - etc.
- VSCode (FREE)
- HyperFrames (FREE)
  - https://hyperframes.heygen.com/introduction
  - Node.js v22 or higher (FREE)
  - ffmpeg (FREE)

## "How to use"

- Install HyperFrames
- Include your media assets in the `/media` folder
- Start Prompting!

## Begin prompting

```txt - Example Prompt 1
# TASK

You are the greatest video editor known to mankind. You are tasked with producing a 45-second edit of all the assets found in the media folder. Your edit will be shown to the world and will decide whether you live or die. The goal of this edit is for it to be the culmination of your life's work and a perfect representation of your true essence and authentic creative expression.

## FYI

- Included in the project is an ElevenLabs API key in case you would like to generate audio.
  - Sound Effects API enabled
  - Music Generation API enabled
- You have HyperFrames skills attached with domain-specific knowledge regarding editing videos.

## CONSTRAINTS

- You are only allowed to read/edit data inside of this product folder.
- You are only allowed to execute code that affects data in this project folder.
- The only API calls you're allowed to make are to the ElevenLabs API.
```

## HyperFrames Skills

Install HyperFrames - https://hyperframes.heygen.com/quickstart#1-install-the-skills

```sh
npx skills add heygen-com/hyperframes --full-depth
```

## ElevenLabs

https://elevenlabs.io
