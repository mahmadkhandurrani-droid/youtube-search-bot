# youtube-search-bot
YouTube Search Bot - Python automation that opens YouTube with any search query. Works on PC (auto-opens browser) &amp; Android (Alif IDE). Built at 14. My first project: turns "How to be a business woman at 14" into a direct YouTube search link instantly. No API needed.
# 🎥 YouTube Search Bot - By Ziggy

A beginner-friendly Python automation bot that opens YouTube with custom search queries instantly.

### ✨ What it does
- Takes any search topic (like "How to be a business woman at 14")
- Creates a smart YouTube search link
- Auto-opens it in your browser (PC) or tap-to-open (Android)

### 💻 How to use

**On Computer:**
1. Save as `youtube_bot.py`
2. Double-click -> Opens YouTube automatically

**On Android (Alif IDE):**
1. Paste code
2. Tap the link in output

### 🛠️ Code
```python
import webbrowser
import urllib.parse

search_query = "How to be a business woman at 14"
query = urllib.parse.quote(search_query)
link = f"https://www.youtube.com/results?search_query={query}"

webbrowser.open(link)
