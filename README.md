# ⚗️ The Design Alchemist's Workshop — Portfolio Website

A high-craft, interactive personal portfolio website inspired by [Shreyas Vyas's viral Framer portfolio](https://shreyasvyas.framer.website/). This site reframes the creative process into a **Design Alchemist's Workshop / Crucible**—transmuting raw, chaotic user problems and engineering constraints into pure golden digital experiences.

---

## 🌟 Key Metaphors & Architecture

| Reference Section (`shreyasvyas.framer.website`) | Workshop Alchemy Adaptation (`index.html`) | Purpose / Feature |
| :--- | :--- | :--- |
| **Hero Concept** | **The Active Workshop Viewport** | Frames the website as a live window into your creation room, complete with live status badge ("Station 01: Open for Quests"). |
| **"About the Chef"** | **"The Alchemist & The Crucible"** | Displays your persona, location, current organization, and design philosophy ("Never ship lead disguised as gold"). |
| **"The Menu" (Projects)** | **"The Concoctions & Transmutations"** | Interactive category filter (`All`, `Enterprise`, `Mobile`, `AI & Spatial`) with quantifiable impact metrics (`-54% Latency`, `+49% Capacity`). |
| **"Case Study Previews"** | **"Inspect Transmutation Recipe"** | Interactive pop-up modal showing Problem, Solution, Metrics, and Process steps. |
| **"The Dessert" (Sketches)** | **"The Tactile Laboratory"** | Showcase for physical ball-point sketches, urban drawings, watercolors, and 3D passion projects. |
| **"Beyond Jira Tickets" Bento** | **"Workshop Bench Secrets"** | Quirky personal facts, keyboard hobby, and an **interactive "Chief Meme Officer" poll** with live vote tally. |
| **"What people remember"** | **"Collaborator Echoes"** | Testimonial quote cards from Engineering Leads, Product VPs, and Founders. |
| **"THE BILL" (Viral Receipt)** | **"The Workshop Bill / Transmutation Receipt"** | Perforated receipt design with itemized fun items ("Spaghetti Architecture Untangling", "Crying in Figma"), GST ("Genuine Spent Time"), one-click copy email button, and barcode stamp. |

---

## 🎨 Positive Alchemy Color Palette

Crafted specifically to evoke **curiosity, craftsmanship, and wonder** without negative/dark tones:

- **Sunstone & Warm Amber Gold (`#F59E0B`, `#D97706`)**: Symbol of creative discovery and transmutation of raw ideas into shipped gold.
- **Warm Parchment Paper (`#FAF6ED`, `#F2EBD9`)**: Tactile paper aesthetic reminiscent of real studio worktables and vintage laboratory notebooks.
- **Rich Obsidian Ink (`#14120E`)**: High-contrast, crystal-clear typography.
- **Emerald Elixir (`#10B981`)**: Positive vitality and live status indicators.
- **Mystic Celestial Indigo (`#6366F1`)**: For spatial computing, AI, and futuristic experiments.
- **Dual Realm Switcher**: Seamlessly toggle between **"Sunlight Laboratory"** (Light theme) and **"Midnight Crucible"** (Deep atmospheric Dark theme).

---

## 🚀 How to Open and Preview

1. **Direct Double-Click**: Double-click `index.html` to open it immediately in Chrome, Edge, Safari, or Firefox.
2. **Local Server (Optional)**:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
   ```
3. Open `http://localhost:8000` or the path in your browser.

---

## 📝 Customization Guide: Updating Placeholders

All personal data in `index.html` is labeled with bracketed placeholders `[...]`. Use Find & Replace (`Ctrl + F` or `Cmd + F`) in your code editor:

1. **Name & Identity**:
   - `[Your Name]` → Your full name.
   - `[Your Initials]` → Your initials (e.g. `SV` or `JD`).
   - `[Your Designation]` → e.g. `Senior Product Designer`, `Lead UX Architect`, `Founding Designer`.
   - `[X]+ Years` → Your professional experience (e.g. `3+ Years`, `5+ Years`).
   - `[Your Location]` → e.g. `Bengaluru, India` or `San Francisco, CA / Remote Worldwide`.
   - `[Current Company / Studio Name]` → Your current or most recent team.
2. **Contact & Socials**:
   - `[your.email@domain.com]` → Your contact email (used in mailto links & the receipt copy button).
3. **Projects (1 to 6)**:
   - Search for `[Project Title 1: ...]` through `[Project Title 6: ...]` in `index.html` and update the titles, descriptions, and metrics in both the grid cards and the JavaScript `projectRecipes` object.
4. **Sketches / Tactile Work**:
   - In the `#tactile-lab` section, update `[Sketch 01]` to `[Sketch 04]` with your own image URLs (`<img src="..." />`).
5. **Colleague Testimonials**:
   - In the Collaborator Echoes section, replace `[Colleague Name / VP of Product]`, `[Tech Lead]`, and `[Founder]` with actual recommendations from your LinkedIn or past managers.
