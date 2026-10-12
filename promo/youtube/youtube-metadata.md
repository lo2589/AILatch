# YouTube upload pack — AILatch (English video)

Upload: `promo/final/ailatch-en-v5-cover.mp4`  ·  Thumbnail: `promo/covers/ailatch-cover-youtube-1280x720-v5.png`  ·  Captions: `ailatch-en.srt`

## Before anything else
- Visibility must be **Public** (Unlisted/Private never show up in search).
- Audience: **No, it's not made for kids**. Age restriction: leave default.
- Studio → Subtitles → Upload file → `ailatch-en.srt` (captions are indexed text).

## Title (pick one, keep the first words searchable)
1. How to Hide Your Python Code from AI Coding Agents (Cursor, Claude Code) — It Still Runs
2. Stop AI Agents Reading Your Source Code: Encrypt Python in Place with AILatch

## Description (paste as-is; first two lines show in search results)
AILatch encrypts your Python files in place, so AI coding agents like Cursor, Claude Code and Copilot only see ciphertext. Your code still runs normally with `ailatch run`.

Same app, two ways to run it: `python app.py` and `ailatch run app.py` give identical results. An LLM that reads the locked file sees only noise.

Install: pip install ailatch
Source: github.com/lo2589/AILatch
Requires Python 3.11+. Locking works on any file; running and importing encrypted code is supported for Python today.

Chapters
0:00 Your AI reads everything
0:15 Lock it with one command
0:29 Same result, but the LLM can't read it
0:45 Install

How it works: files are encrypted on disk with ChaCha20-Poly1305 (keys from Argon2id). `ailatch run` decrypts only in memory, so no plaintext copy is written back to your working tree. It targets filesystem-level AI access (read_file, grep, cat, indexing); it does not claim to stop a fully informed local attacker.

#AILatch #Python #AIAgents

## Tags (comma separated, ~450 chars)
AILatch, hide code from AI, protect source code from AI, AI coding agent security, Cursor, Claude Code, GitHub Copilot, encrypt python code, python source code protection, stop AI reading my code, keep secrets from AI, ai agent leaks secrets, memory only decryption, ailatch run, python encryption tool, open source

## Pinned comment
Repo + install: github.com/lo2589/AILatch  (pip install ailatch)
Question for you: which files would you never want your AI agent to read? Reply and I'll show how to lock that case.

## Chapters (already in the description; each is 10 s or longer)
0:00 · 0:15 · 0:29 · 0:45

## Where to post the link (a new channel gets no search traffic by itself)
1. X: post the 1600x900 cover + the video, text: "AI agents read your whole repo. AILatch locks it, your code still runs."
2. Reddit: r/Python, r/cursor, r/ClaudeAI, r/LocalLLaMA (read each sub's self-promo rule; lead with the problem, not the product).
3. Hacker News: "Show HN: AILatch – lock files from AI agents, run them in memory".
4. 中文: 小红书(1080x1440 中文封面)、V2EX、掘金、即刻。
5. Put the YouTube URL in the GitHub repo "About" website field and in the PyPI project links.
6. Add the video to a playlist named "AI agent security" (YouTube groups it with related content).
