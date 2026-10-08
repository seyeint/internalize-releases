<div align="center">

<img src="icon.png" width="128" alt="Internalize icon" />

# Internalize

**A native Mac PDF reader where you converse with what you're reading, on the ChatGPT or Claude plan you already have.**

Ask anything about the document, or select a passage first. The AI reads (and looks at) the pages your question needs, and cites the exact words: a click lands on them.
No API key needed, no subscription, no servers. Free.

### [⬇ Download the latest version](https://github.com/seyeint/internalize-releases/releases/latest) · [getinternalize.com](https://getinternalize.com)

</div>

---

## Requirements

- **macOS 15** or newer (Apple Silicon and Intel)
- The **[ChatGPT app for Mac](https://learn.chatgpt.com/codex/app)**. Codex ships inside it, and Internalize runs its AI through Codex on *your* plan, which is why it's free and needs no API key. If Codex isn't signed in on your Mac yet, Internalize signs you in with one click, on OpenAI's own page
- Or **Claude Code**, with a paid Claude plan (Pro, Max, Team, or Enterprise) or an Anthropic API key (billed to you by Anthropic). Open the Code tab in the Claude app once, or install it with [Anthropic's installer](https://code.claude.com/docs/en/setup). You sign in once: Claude Code opens Anthropic's sign-in page in your browser. That sign-in is separate from the Claude app's and stays in Internalize's own private Claude Code profile

## Install

1. Download the DMG above and open it
2. Drag **Internalize** into **Applications**
3. Launch, drop a PDF on the welcome screen, and start asking

The app is signed and notarized by Apple, so it opens without warnings. Updates are automatic: when a new version ships, Internalize offers to install it in one click (or check manually via **Internalize ▸ Check for Updates…**).

## Features

- 🤖 The AI reads the document itself: it has the table of contents and three tools (search the text, read pages, look at a page as it's printed, figures and tables included), looks up what your question needs, and cites the exact words. A short document travels in full; a long book is read on demand. Every step shows in the conversation
- 🔀 ChatGPT or Claude, or both: the reply menu lists each one's models, any conversation can switch between them, and each conversation remembers its model. The document tools, citations, and web search work the same either way
- 💬 Replies keep going: hide the chat, open the hub or switch conversations, and the answer keeps coming in; two conversations can be answered at once
- 🎯 Citations land on the words they quote, and light them for a moment; ⌘[ and ⌘] go back and forward through every jump
- 📖 Printed page numbers, as the book numbers them ("Page xii (14 of 400)"), and Go to Page (⌥⌘G) takes them
- 👁️ Force click a link inside the PDF (a reference, a figure, a chapter) to peek at where it goes without losing your place
- 🖍️ Highlights that stay on the page in the color you chose, with notes, exported as Markdown
- 📑 The PDF's own contents in the sidebar, with the chapter you're in marked
- 🔍 Scanned PDFs get their text recognized on your Mac, once; ⌘F search works on them too
- ✍️ Area capture for diagrams and equations (vision): switch to it in the toolbar, or hold Option over the page
- 🗂️ A project hub where every project wears its document's title page; Open With ▸ Internalize from the Finder
- 🗺️ Document map: every highlight anchored to its exact place, plus reading progress
- ⏱️ Focus timer with a reading activity dashboard: heatmap, streaks, time by project
- 📊 Your ChatGPT or Claude plan usage, in the reply menu and beside it when it's running low (for Claude, the limits Claude Code reports)
- 🔊 Hear answers read aloud
- 📤 Export conversations and highlights to Markdown

## Privacy and security model

Internalize is built local-first and is honest about what it touches:

- **Your documents and conversations never leave your Mac** except as AI requests through your own Codex installation or Claude Code, the same path as chatting in the ChatGPT app or using Claude Code itself
- **No telemetry, no analytics, no accounts, no servers operated by us**
- Codex runs in an **isolated, read-only profile** with the shell, browser, computer, app, plugin, and multi-agent capabilities switched off: the model can read your document and search the web, and nothing else. Your personal Codex configuration is never loaded
- Claude Code runs in **Internalize's own isolated profile**, never your `~/.claude`, so none of your settings, hooks, plugins, MCP servers, or `CLAUDE.md` files load: the model can read the open document through Internalize's tools and search the web, and every other tool and permission is refused
- Your ChatGPT and Claude credentials are **never handled by Internalize**. ChatGPT sign-in happens on OpenAI's own page (Internalize opens it for you) or in the ChatGPT app; Claude Code signs you in on Anthropic's own page and keeps the sign-in in the macOS keychain. Verify all of this with any network monitor

## Support

Internalize is free and built by one person. If it makes your reading life better, you can [**buy me a coffee on Ko-fi** ☕](https://ko-fi.com/internalize). Tips keep the app free for everyone.

---

*Issues and feature requests: open one [here](https://github.com/seyeint/internalize-releases/issues).*
