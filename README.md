# PageGrab 🧩

**A free Chrome extension for capturing webpage content with its context.**

PageGrab helps you capture page elements and export them as screenshots, Markdown, CSV, or links. It also includes full-page capture, an annotation editor, offline OCR, and a check for potentially exposed keys and tokens.

## ✨ Features

- 🎯 Capture webpage elements with surrounding context
- 📸 Export captures as screenshots, Markdown, CSV, or links
- 📄 Capture full pages
- ✍️ Annotate captures in the built-in editor
- 🔎 Run OCR offline
- 🔐 Check captured content for potentially exposed keys and tokens
- 💻 Work locally without an account or PageGrab server

## 👥 Who is PageGrab for?

PageGrab may be useful for:

- 🐞 Bug hunters documenting findings on websites they are authorized to test
- 👩‍💻 Developers collecting webpage content and context while debugging
- 🧪 QA testers recording interface issues
- 📝 Researchers organizing information from webpages

## 📥 Installation

PageGrab is free to download from this repository. It is installed manually in Chrome and is not currently listed in the Chrome Web Store.

1. On this GitHub page, select **Code → Download ZIP**.
2. Extract the ZIP file to a folder on your computer.
3. In Chrome, open `chrome://extensions`.
4. Turn on **Developer mode**.
5. Select **Load unpacked**.
6. Choose the extracted PageGrab folder containing `manifest.json`.
7. Pin PageGrab from Chrome’s Extensions menu for quick access.

Keep the extracted folder in place while using the extension.

## 🚀 Usage

1. Open a webpage in Chrome.
2. Open PageGrab and choose a capture option.
3. Select the page content you want to capture.
4. Review or annotate the capture.
5. Export it in your preferred format.

##  ⌨️ Keyboard shortcuts

Capture content quickly with these shortcuts:

- **Grab an element:** `Alt + Shift + G`
- **Grab a region:** `Alt + Shift + R`
- **Grab the full page:** `Alt + Shift + F`

You can also customize Chrome shortcuts by opening `chrome://extensions/shortcuts`.

## 🛡️ Privacy and security

PageGrab is designed to process content locally on your device. It does not require an account or a PageGrab server.

The key and token check is a detection aid, not a complete security audit. It may miss findings or produce results that need review. Check results before sharing a capture, and use security checks only on pages or systems you own or are authorized to assess.

Review the browser permissions listed in `manifest.json` before installation.

## 🤖 Built with AI-assisted vibe coding

PageGrab began as an idea and was developed through AI-assisted vibe coding. AI tools helped me write and refine code and work through bugs, while I shaped the project and its workflow.

## 🔄 Updating

1. Download and extract the latest ZIP from this repository.
2. Replace the files in the folder you originally loaded with the updated files.
3. Open `chrome://extensions` and select **Reload** for PageGrab.

If you extracted the update to a different folder, remove the previous extension and select **Load unpacked** to load the new folder.

## 🧰 Troubleshooting

- If Chrome cannot load the extension, check that Developer mode is on.
- Make sure you selected the extracted folder containing `manifest.json`, not the ZIP file itself.
- If PageGrab does not appear in the toolbar, open Chrome’s Extensions menu and pin it.

## ⚠️ Disclaimer

PageGrab is an educational project for learning, research, and authorized testing. Use it responsibly and follow applicable laws, website terms, and authorization requirements.

PageGrab is not a professional security-auditing tool. Its OCR and key/token checks may be incomplete or inaccurate. Review results yourself before acting on them or sharing them.

## 💬 Feedback

Found a bug or have an idea? Open an issue in this repository.

## 📄 License

PageGrab is free to download and use. A software license has not been specified yet, so the reuse and modification rights for the source code are not defined here.
