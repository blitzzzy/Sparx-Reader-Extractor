An elegant, secure, and responsive JavaScript bookmarklet utility tool designed to streamline reading comprehension workflows. This tool extracts lesson text and quiz contents directly from the DOM using strict client-side evaluation, removing the need for external network extensions.
Built with vanilla JavaScript, it features a fully draggable, minimisable glassmorphism UI with smooth animations (requestAnimationFrame), touch support, and robust clipboard integration.

⚡ Core Features

• Visual Overlay UI: A sleek, self-contained HUD featuring glassmorphism blurring, custom red glowing themes, and high-DPI scaling overrides (z-index: 999999).
• Instant Text Extraction: Targets specific dynamic reader components (#book-scroll) to grab reading sections and cleanly strip unwanted formatting.
• Intelligent Quiz Scraping: Scans the active screen dynamically for underlying question containers (PanelPaperQuestionContainer) or structured regular text indicators (Q1.) to fetch active evaluation questions.
• Fail-Safe Clipboard Engines: Leverages modern navigator.clipboard.writeText async engines with an automatic programmatic fallback (textarea + execCommand) for old browsers or strict security sandbox setups.
• Fully Responsive Controls: Features smooth desktop drag tracking and native multi-touch configurations (touchstart/touchmove) without breaking scrolling layouts.
• Keyboard Hotkeys: Speed up operations using custom interceptors built right into your keyboard controls.

🛠️ Step-by-Step Installation

Because this tool runs as a bookmarklet, you do not need to install complex extensions or extensions that risk your privacy.

Method 1: The Bookmark Bar (Recommended)

1. Ensure your browser's Bookmarks Bar is visible.
	• Shortcut: Ctrl + Shift + B (Windows) or Cmd + Shift + B (Mac).
2. Right-click any empty space on your bookmarks bar and select Add Page or Add Bookmark.
3. Name the bookmark something clear, like 🔥 Sparx Extractor.
4. Copy the complete JavaScript code block from the section below.
5. Paste that exact code directly into the URL or Location field of the new bookmark and save it.

Method 2: Browser Developer Console

1. Navigate to your target webpage.
2. Press F12 or right-click and select Inspect, then switch to the Console tab.
3. Paste the entire code payload below into the command prompt line and press Enter.

   
📖 How to Use

1. Navigate to the reading or assessment screen on your portal.
2. Click the saved bookmark from your bar. The menu HUD will instantly slide into view on the bottom-right corner.
3. Copy Text: Press to copy the entire reading passage block to your clipboard.
4. Copy Quiz: Press to scrape the current page for operational multiple-choice or short-answer prompt trees.
5. Draggable Manipulation: Click and hold the horizontal bar at the bottom of the interface panel to drag the UI window anywhere on your screen.
6. Minimise: Click the ✕ button to instantly collapse the tool into a subtle orb icon. Click the orb to restore it instantly.

🔒 Security & Verification

This utility is built with safety as a top priority:
• Zero Dependencies: It does not fetch background script elements or use hidden tracking pixels.
• No Network Traffic: All data extraction stays completely inside your local browser memory space.
• No Data Collection: The program has no cloud databases or external connection tunnels. Your textual records are never sent out or harvested.
