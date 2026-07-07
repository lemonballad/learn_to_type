# ⭐ Star Typer

A friendly, colorful typing game for young kids — inspired by the classic 1980s
"defend the ship in the middle of the screen" typing games (MasterType / Type Attack).

Letters drift in from all sides toward a cute rocket in the center. Press the
matching key to zap them before they reach the ship!

## How to play

**Just double‑click `index.html`.** It opens in your web browser (Chrome, Edge,
Firefox, or Safari). No installation, no internet needed — it runs entirely offline.

### 📱 On a tablet or phone

The game works on touch devices too. When it detects a touchscreen it shows a big,
kid‑friendly **on‑screen keyboard** at the bottom that changes with the world:
letters for the letter worlds, a **number pad** for Numbers & Math, symbols for the
Symbol world, and a space bar for words and sentences. You can force the on‑screen
keyboard on or off in the Grown‑ups Corner.

To play on a tablet you can either open the `index.html` file in the tablet's browser,
or (easiest) put the file somewhere both devices can reach and open it there. It's a
single file, so it's easy to copy over.

- Type the letter/number/symbol shown in each bubble to blast it.
- **Levels rise automatically** as you zap targets — the game never stops to ask
  "keep going?" It just gets a little faster and busier as your child gets better.
- Earn ⭐ for every target. 3 hearts — very forgiving. No scary "game over,"
  just "Good try!" with a one‑tap Play again.

## Worlds (unlock as you go)

1. 🔤 **Little Letters** — lowercase a–z
2. 🔢 **Numbers & Math** — see below ⬇️
3. 🅰️ **BIG Letters** — capitals *(press the lowercase key — no Shift needed!)*
4. ❓ **Symbols** — `. , ! ?` etc. *(press `1` for `!`, `/` for `?` — no Shift needed)*
5. 🐱 **Little Words** — cat, dog, sun…
6. 📖 **Sentences** — the cat ran…

A world keeps leveling up forever — every level adds a bit of speed and a few
more targets. Reaching Level 3 in a world unlocks the next one.

### 🔢 Numbers & Math grows with your child

The Numbers world starts with counting and climbs through real arithmetic —
always **small whole numbers, never negative**:

| Levels | Skill | Example |
|--------|-------|---------|
| 1–2 | Recognize digits | `7` |
| 3–6 | ➕ Adding | `6 + 3 = ?` |
| 7–10 | ➖ Taking away | `8 − 3 = ?` |
| 11–14 | ✖️ Times | `4 × 2` |
| 15–16 | ➗ Sharing (division) | `6 ÷ 2` |
| 17–19 | 🔀 Mix: add & take away | |
| 20–22 | 🔀 Mix: add, take away, times | |
| 23+ | 🌟 Mixed math (all four) | |

Once a skill is introduced it comes back in the mixed levels, so your child keeps
practicing everything — not just the newest operation. The bubble shows just the
problem (e.g. `6 ÷ 2`). Your child types the **answer**; the moment it's right, the
**full solved equation pops up** on screen (`6 ÷ 2 = 3`).

## 🗣️ Read aloud

Turn **Read aloud** on in the Grown-ups Corner and every **word or sentence** is
spoken out loud the instant it's typed correctly — a nice way to connect the letters
to the sound of the word. It uses your computer's built-in voices (no files, works
offline). Toggle it off any time.

### Getting a more natural voice 🎙️

The Grown-ups Corner has a **Voice picker** and a **▶ Test** button. The game
automatically selects the most natural voice it can find (marked ⭐ / "auto"), but you
can choose any installed voice and set the speaking speed. The naturalness depends on
which voices your computer has:

- **Chrome / Edge:** usually includes **"Google US English"** and Microsoft
  **"…Online (Natural)"** neural voices — pick one of those for the most human sound.
- **Windows:** install extra natural voices free via **Settings → Time & Language →
  Speech → Manage voices → Add voices** (look for *Natural* voices like Aria or Jenny).
  They then appear in the picker after you restart the browser.
- **macOS:** **System Settings → Accessibility → Spoken Content → System Voice → Manage
  Voices**, and download an **Enhanced/Premium** English voice (e.g. Ava, Samantha).
- **Most natural of all** would be a cloud voice service (ElevenLabs, Google, Azure),
  but that needs an internet connection, an API key, and has a cost — so it's left out
  of this offline, kid-friendly build. It's noted on the roadmap as an optional add-on.

## Grown‑ups Corner ⚙️

Tap the **⚙️ Grown‑ups** button on the title screen to:

- Toggle **Dark mode** 🌙 (dims the bright menus, keyboard, and background for
  night-time play; follows your device's light/dark setting by default)
- Adjust **game speed** (Slow 🐢 / Normal / Fast 🐇)
- Turn **sound effects** on/off
- Turn **Read aloud** (spoken words & sentences) on/off and pick the **voice**
- Turn the **on‑screen keyboard** on/off (for tablets & phones)
- Turn on **Hints** 💡 — the on‑screen keyboard flashes the exact key to press next
  for the closest target, a perfect training wheel for a brand‑new typer
- **Jump to any world** or **unlock everything** for practice
- **Reset progress** to start fresh

Progress and settings are saved on this computer automatically.

## Notes

- **Uppercase accepts the lowercase key** so little hands don't need to fight the
  Shift key. (This was a deliberate choice for early typers.)
- **No two targets on screen ever start with the same key**, so a keypress is never
  ambiguous. And if your child starts one word then presses the first letter of a
  different target, the game **fluidly switches** to that one instead of getting stuck.
- Sound effects are generated in code (Web Audio) — there are no sound files to manage.
- Everything lives in a single file (`index.html`), so it's easy to back up or copy
  to another computer.

## Roadmap / ideas

This is built to grow into a broader learning tool. The worlds are data-driven, so
these are natural next steps:

- **Alternative languages** (letters, words, and spoken audio in other languages)
- **Algebra** (`3 + □ = 7`, simple equations) as higher math worlds
- **Compound & longer sentences**, punctuation, and capitalization practice
- **Relaxed mode** where math targets wait for an answer instead of drifting
- Per-child profiles, and a "practice just these keys/facts" picker
