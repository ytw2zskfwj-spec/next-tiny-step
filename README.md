# Next Tiny Step

A free web app that beats procrastination. Tell it the task you're
avoiding and it gives you one first step so small it takes under two
minutes, then the next one, one at a time.

**Live app:** https://ytw2zskfwj-spec.github.io/next-tiny-step/

On iPhone, open the link in Safari, tap Share, then Add to Home Screen.

## Why it exists
Big tasks feel impossible because the first move is unclear. Next Tiny
Step removes that. Instead of a to-do list, you get one concrete action
at a time.

## How it works
1. Type the thing you're putting off.
2. Optionally pick how you feel (tired, anxious, overwhelmed, low on time).
3. Get one tiny first step.
4. Use the optional 2-minute timer, then tap "I did it" for the next step.
5. If a step is still too big, tap "Still too big" and it shrinks.

## Features
- One step at a time, never a long list
- Steps shrink when you are tired, anxious, or short on time
- 2-minute timer with a gentle chime
- Daily tiny-step count and streak
- Works with no setup using built-in steps
- Optional AI mode for steps written for your exact task
- Light and dark mode
- Free to use, no account, no tracking

## Optional: turn on AI steps
1. Get a free key at https://aistudio.google.com/apikey
2. Open the app, tap Settings, paste the key, and tap Save.

The key is stored only in your browser and sent only to Google. It is
never part of this repository.

## Privacy
Everything runs in your browser. Your tasks and progress are saved only
on your device. In AI mode, your task text is sent to Google's Gemini
API to generate the next step.

## Built with
Plain HTML, CSS, and JavaScript in a single file, hosted on GitHub Pages.
AI steps use the Google Gemini API.

## Limitations
The free Gemini tier has usage limits. When it runs out or fails, the
app switches to its built-in steps automatically.
