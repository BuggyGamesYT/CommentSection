# Comment Section

A platformer you play "live" by **Buggy Games YT**. A chat full of made-up viewers runs polls while you play, and whatever wins happens to your level right away: gravity flips, reversed controls, surprise enemies, speed up, lights out, "make it harder". Donations help you out with shields, extra lives and slow-mo. Keep the viewers happy, hit END STREAM, and survive 4 streams.

The chat is 100% offline and simulated. No real viewers, accounts or platforms.

▶ **Play in your browser:** https://buggygamesyt.github.io/commentsection/
📱 **Android:** grab the APK from [Releases](https://github.com/BuggyGamesYT/CommentSection/releases).

## Controls
- Keyboard: ← → or A/D move, Space/W/↑ jump (hold for higher), Esc/P pause, M mute
- Touch: hold ◀ ▶ to move, tap JUMP, ⏸ to pause (play sideways)

## Project layout
- `web/` – the game (plain HTML + JavaScript, no libraries). `core.js` is levels, physics, chat and polls; `index.html` is drawing, controls and menus.
- `android/` – a tiny WebView wrapper that bundles `web/` into an APK. It's built, signed and released by GitHub Actions when a `v*` tag is pushed.

Made by Buggy · [YouTube](https://www.youtube.com/@BuggyGamesYT)
