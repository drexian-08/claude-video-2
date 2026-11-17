# Run this video project with Claude Code

This folder contains the approved brief, storyboard and Malay narration. Use the `claude-video-studio` skill from this repository.

## 1. Prepare
- Use Node.js 22 or newer.
- Install ffmpeg and make sure `ffmpeg` is available in PATH.
- Install Claude Code.
- Copy this repository's skill folder into Claude Code's skills directory as described in the root README:
  `~/.claude/skills/claude-video-studio/`
- Run the skill doctor:
  `bash ~/.claude/skills/claude-video-studio/scripts/doctor.sh`

## 2. Open the project brief
Open this folder in Claude Code and give it this instruction:

> Use the claude-video-studio skill to produce the video in this folder. Read BRIEF.md, storyboard.json and NARRATION.md first. The style is blueprint. The final output must be a 75-second 16:9, 1920x1080, 30fps Malay-language educational animation. Follow the storyboard timing exactly. Use code-generated isometric 2.5D timber-house geometry, exploded construction views, a flood cross-section and an explanatory staged-lifting sequence. Do not use paid AI generation or call Higgsfield. Keep historical accuracy notes in BRIEF.md: ordinary Malay stilt houses are elevated on posts; do not claim all old houses had automatic lifting machinery. The staged jack-and-cribbing sequence is a conceptual adaptation, not a universal historical method. Make a new render folder inside this project, show three stills for approval before rendering, then render MP4 and run the pacing check. Do not claim the result is full photorealistic 3D; use convincing dimensional/isometric motion graphics.

## 3. Output
Save the approved MP4 as:
`projects/rumah-kayu-warisan-melayu/out/rumah-kayu-warisan-melayu.mp4`

No API keys or paid generation credits are needed for the code-only version.
