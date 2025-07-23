# BeatOS: Interactive CPU Scheduling Practice Tool

Welcome to **BeatOS** — a playful, paint-bucket-style interface for practicing CPU scheduling algorithms. This tool combines music-inspired visuals, accessibility awareness, and compact layout design to help you prepare for your final exam (and have some fun while doing it 🐞🎶).

##  1. Theming: BeatOS + CPU Scheduling

- New text and labels reflect the **BeatOS theme**, inspired by music and beetles.
- Messages like `"🐞 Beetle missed a beat at time X!"` add personality and tie in with the paint-bucket interaction and the Gantt chart scheduler.
- Visual metaphors (beat, rhythm, beetles, scheduling) reinforce the idea of processes keeping time like a band.



## 2. Color Accessibility Testing

- While original colors are retained, **extensive testing** was done using the [DaltonLens colorblindness simulator](https://daltonlens.org/colorblindness-simulator).
- Goal: ensure **all users, including those with color vision deficiencies**, can distinguish the 3 process colors clearly.
- **Red, blue, and yellow** (used as pink, lightblue, and khaki) work well for most cases, including:
  - Protanopia (red-blind)
  - Deuteranopia (green-blind)
  - Tritanopia (blue-blind)

**If you need to adjust color:**
- Open the project in an IDE or text editor.
- Search for `khaki` and replace with a higher-contrast yellow or another accessible hue.



## 3. Compact Layout for 1366×768 and Retina Screens

- The layout has been **tightened and condensed** to comfortably fit on a **1366×768 display**, which is common for:
  - Classic 13" laptops
  - School and office environments
- This improves usability by ensuring all interactive elements stay on-screen without scrolling.

Tested on:
- Standard 13" Windows laptops (1366×768)
- **MacBook Air default scaling** (1440×900 logical resolution on a 2560×1600 panel)

**Responsive note:**
- Attempts to make the layout fluid using pure CSS responsiveness led to visual imbalance or content overflow.
- If you're using a large or high-DPI screen, like a 2K monitor or MacBook Retina, try **zooming in with `Ctrl +`** to scale the interface for better readability.



## 4. All-In-One Offline File

This tool is built as a **single self-contained `.html` file**:
- No external CSS or JavaScript links
- Easy to use offline
- No setup required — just open in any modern browser

This is **not an example of best practice** for production or learning modern frontend architecture.



## 5. AI-Generated Code & Notes

- Parts of this code and README were generated or co-written with AI assistance.
- While useful and fun, there **may be bugs or odd behavior**.

If you find issues — don't panic!  
This tool is made for **practice**, not perfection. Use it to:
- Test your own understanding of CPU scheduling
- Help describe your questions on **Piazza**
- Discuss with **classmates, tutors, or the lecturer**


Enjoy using BeatOS, and maybe you’ll take it to the next level someday!  
Happy scheduling! 🐞🎶



