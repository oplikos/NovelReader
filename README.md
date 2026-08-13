# 📖 Novel Reader https://oplikos.github.io/NovelReader/

### A modern, browser-based text-to-speech reader for novels, books, and long-form content.

Turn your books into an immersive listening experience — directly in your browser.

**No installation. No account. No backend. Just open, load, and read.**

---

<p align="center">

🎧 **Listen** · 📖 **Read** · ⚡ **Control** · 💾 **Resume**

</p>

---

## ✨ What is Novel Reader?

**Novel Reader** is a lightweight web-based reading assistant designed for people who prefer listening to their books while following along with the text.

Load a `.TXT` or `.PDF` book and the reader automatically turns the content into a navigable, speech-enabled reading experience.

It combines:

* 🔊 Text-to-Speech
* 📖 Chapter detection
* 📝 Sentence highlighting
* ⏯️ Play / Pause / Resume
* ⚡ Adjustable reading speed
* 🎙️ Multiple system voices
* 🔍 Search
* 📚 Reading library
* 💾 Automatic progress saving
* 🌙 Dark / Light mode
* 🔠 Adjustable font size
* ⏭️ Chapter navigation
* ⌨️ Keyboard shortcuts
* 🎧 Media / Bluetooth controls

All inside a single web application.

---

# 🚀 Features

## 🔊 Text-to-Speech

Let your browser read your book aloud using the voices available on your computer.

Choose from the voices installed on your system and adjust the reading speed.

**Supported controls:**

```text
0.5x ──────────────── 4x
```

Perfect for:

* Relaxed reading
* Studying
* Listening while working
* Accessibility
* Long novels
* Hands-free reading

---

## 📖 Automatic Chapter Detection

Novel Reader scans the loaded document and attempts to identify chapters automatically.

For example:

```text
Chapter 1
Chapter 2
Chapter 3
Chapter 4
...
Chapter 100
```

Detected chapters are automatically added to the chapter selector.

You can jump directly to any chapter without manually scrolling through the entire book.

---

## 🟨 Sentence Highlighting

While the book is being read aloud, the current sentence is highlighted.

The reader automatically scrolls to keep the current sentence visible.

```text
The door slowly opened.

The hallway was completely dark.

🟨 He stepped inside and looked around.

Nothing moved.
```

This creates a **read-along experience** instead of simply playing audio.

---

# ⏯️ Smart Playback

The reader supports:

### ▶ Play

Start reading from the current sentence.

### ⏸ Pause

Stop reading while keeping your position.

### ▶ Resume

Continue reading from where you stopped.

### ⏭ Next Chapter

Move directly to the next chapter.

### ⏮ Previous Chapter

Return to the previous chapter.

### ↻ Restart

Restart the current chapter.

---

# 🎧 Media & Bluetooth Controls

Novel Reader is designed to work with modern browser media controls.

Compatible devices may include:

* 🎧 Bluetooth headphones
* 🎧 Bluetooth earbuds
* ⌨️ Keyboard media keys
* 🖥️ Windows media controls
* 🎮 Devices exposing standard media commands

The goal is simple:

> **You shouldn't need to touch the screen every time you want to pause or continue reading.**

---

# ⚡ Reading Speed

Choose your preferred speed.

### Presets

```text
1x
1.5x
2x
3x
4x
```

Or adjust the speed manually.

This makes the reader useful for both slow immersive reading and rapid consumption.

---

# 🎙️ Voice Selection

Novel Reader uses the browser's built-in Speech Synthesis API.

Choose from the voices available on your operating system.

Example:

```text
Microsoft David
Microsoft Zira
Google US English
Google UK English
...
```

A built-in voice test lets you quickly check the selected voice before starting your book.

---

# 📚 Personal Library

Novel Reader automatically remembers books you've opened.

The browser stores reading information locally.

Saved information can include:

```text
Book
 ├── Chapter
 ├── Sentence
 ├── Reading Speed
 └── Last Read Date
```

This allows the reader to remember where you were.

---

# 💾 Automatic Progress Saving

Progress is automatically saved while reading.

The reader periodically stores your current position and can ask whether you want to resume when you reopen the book.

Example:

```text
Resume MyNovel.txt?

Chapter: 36
Sentence: 124

[ Cancel ]   [ OK ]
```

No account is required.

---

# 📄 File Support

Currently supported:

| Format    | Support |
| --------- | ------- |
| `.TXT`    | ✅       |
| `.PDF`    | ✅       |
| `.EPUB`   | 🔜      |
| Web Pages | 🔜      |
| URLs      | 🔜      |

PDF files are processed directly in the browser using **PDF.js**.

---

# 🔍 Search

Search through your loaded book to quickly find words or phrases.

Useful for:

* Character names
* Locations
* Events
* Specific conversations
* Important passages

---

# 🔠 Reading Customization

Make the reader comfortable for long reading sessions.

### Font Size

```text
A−     A+
```

Font size is saved automatically.

### Theme

Switch between:

🌙 **Dark Mode**

and

☀️ **Light Mode**

---

# ⌨️ Keyboard Shortcuts

| Key     | Action               |
| ------- | -------------------- |
| `Space` | Play / Pause         |
| `←`     | Previous 5 sentences |
| `→`     | Next 5 sentences     |
| `B`     | Back 50 sentences    |
| `N`     | Forward 50 sentences |
| `+`     | Increase speed       |
| `-`     | Decrease speed       |
| `Esc`   | Close open windows   |

---

# ↔️ Word Jump

Need to move forward quickly?

Enter the number of words:

```text
100
```

and press:

```text
↔
```

Negative values move backward:

```text
-100
```

This makes it easy to jump around a long chapter without dragging a scrollbar.

---

# 🖱️ Click-to-Read

You can click a sentence directly.

For example:

```text
Sentence 1
Sentence 2
Sentence 3  ← click
Sentence 4
Sentence 5
```

The reader immediately moves to that sentence.

---

# 🧠 Designed for Long Novels

Novel Reader was built around a simple problem:

> **Reading thousands of pages shouldn't require fighting with a complicated application.**

The interface is intentionally simple.

```text
┌─────────────────────────────────────────────┐
│ ▶  ⏮  ⌂  ⏭  Chapter 36  ⚡ 1x  🎙️  🔍     │
├─────────────────────────────────────────────┤
│                                             │
│  Chapter 36                                 │
│                                             │
│  The hallway stretched endlessly before     │
│  him.                                       │
│                                             │
│  🟨 He slowly stepped forward.              │
│                                             │
│  Something moved in the darkness.           │
│                                             │
└─────────────────────────────────────────────┘
```

Everything important is available from the top control bar.

---

# 🛠️ Technology

Novel Reader is intentionally lightweight.

### Frontend

* HTML
* CSS
* JavaScript

### Browser APIs

* `SpeechSynthesis API`
* `MediaSession API`
* `LocalStorage`
* `FileReader API`

### PDF

* PDF.js

No server is required for the basic reader.

---

# 🔒 Privacy

Novel Reader is designed around **local processing**.

Your books and reading progress do not need to be uploaded to a server.

Reading data is stored using your browser's:

```text
localStorage
```

Your files remain on your computer unless you intentionally send them somewhere else.

---

# 🌐 Run It

The simplest way to use Novel Reader is to open the HTML file in a modern browser.

Recommended:

* Google Chrome
* Microsoft Edge

Then:

```text
📂 Load Book
      ↓
📖 Select TXT / PDF
      ↓
🧠 Detect Chapters
      ↓
▶ Start Reading
```

---

# 💻 Development

Clone the repository:

```bash
git clone https://github.com/oplikos/reader.git
```

Open the project:

```bash
cd reader
```

Then open the HTML reader in your browser.

For development, using a local web server is recommended:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

---

# 🗺️ Roadmap

Novel Reader is still evolving.

### 📚 Reading

* [x] TXT support
* [x] PDF support
* [x] Chapter detection
* [x] Sentence highlighting
* [x] Chapter navigation
* [x] Reading progress
* [x] Font controls
* [x] Search
* [x] Library

### 🎧 Audio

* [x] Text-to-Speech
* [x] Voice selection
* [x] Voice testing
* [x] Speed control
* [x] Play / Pause
* [x] Keyboard controls
* [ ] Better resume handling
* [ ] MediaSession improvements
* [ ] Bluetooth controls

### 🌐 Future

* [ ] EPUB support
* [ ] Website reading mode
* [ ] Chrome extension
* [ ] Select text → Read
* [ ] Read from cursor
* [ ] Automatic chapter detection from websites
* [ ] URL-based reading
* [ ] Book metadata
* [ ] Cloud synchronization
* [ ] Mobile version
* [ ] AI-assisted chapter detection

---

# 🌎 The Bigger Idea

Novel Reader is evolving beyond a simple TXT reader.

The long-term goal is to make it possible to turn **almost any readable content into an interactive listening experience.**

Imagine:

```text
                    ┌───────────────┐
                    │   ANY TEXT    │
                    └───────┬───────┘
                            │
             ┌──────────────┼──────────────┐
             ▼              ▼              ▼
           📄 TXT          📕 PDF        🌐 WEB
             │              │              │
             └──────────────┼──────────────┘
                            ▼
                    ┌───────────────┐
                    │ NOVEL READER  │
                    └───────┬───────┘
                            │
             ┌──────────────┼──────────────┐
             ▼              ▼              ▼
          📖 TEXT        🔊 VOICE       🎧 MEDIA
             │              │              │
             └──────────────┼──────────────┘
                            ▼
                     IMMERSIVE READING
```

The eventual vision is a browser extension that can sit on top of websites and intelligently identify:

* chapters
* paragraphs
* sentences
* selected text
* cursor position
* reading location

Then it can turn the website itself into a **hands-free audiobook-like experience**.

---

# 🤝 Contributing

Ideas, improvements, bug fixes, and feature requests are welcome.

If you find a problem or have an idea for improving the reader, open an issue or submit a pull request.

---

# ⭐ Support the Project

If you find Novel Reader useful, consider giving the repository a ⭐ on GitHub.

It helps the project grow and motivates future development.

---

<p align="center">

### 📖 Read More. Listen Better. Stay in the Story.

**Novel Reader**

Made by **Sarkis Bozikian**

</p>
