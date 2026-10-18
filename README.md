# Remove Internet Distraction

uBlock Origin filters to remove distractions from YouTube, Instagram, Reddit, and Google Search.

**Make the web less distracting.**

## Browser Extension

**Want an easier way to block distractions?**

Try **[Remove Internet Distraction for Firefox](https://addons.mozilla.org/en-US/firefox/addon/remove-internet-distraction/)** — a dedicated browser extension for a less distracting browsing experience.

- **[Install from Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/remove-internet-distraction/)** — available on the official Firefox Add-ons store.
- **[View Source Code on GitHub](https://github.com/Trazer09/Remove-Internet-Distraction)** — open source.
- **Feedback welcome!** Try the extension and report bugs or suggest features through [GitHub Issues](https://github.com/Trazer09/Remove-Internet-Distraction/issues).

## Installation

1. Install [uBlock Origin](https://github.com/gorhill/uBlock).
2. Open your chosen filter list, copy its contents into **My Filters**, and click **Apply Changes**.

### YouTube
- [`youtube.txt`](./youtube.txt) — Recommended
- [`youtube-strict.txt`](./youtube-strict.txt) — More aggressive filtering

### Instagram
- [`instagram.txt`](./instagram.txt) — Remove distractions

### Reddit
- [`reddit.txt`](./reddit.txt) — Remove distractions

### Google Search — Remove AI Mode
- Visit [Ten Blue Links](https://tenbluelinks.org/) to use Google Web as your default search.
- Enable **EasyList – Annoyances** in uBlock Origin to hide the Google AI Mode section.
- Add this filter to **My Filters** to remove the "All" section:

```text
www.google.com##div:nth-of-type(2) > .C6AK7c > .mXwfNd
```

*Google may change its layout, causing filters to stop working.*

---

Found a broken filter? Open an Issue or submit a pull request. If you find this project useful, consider starring the repository.
