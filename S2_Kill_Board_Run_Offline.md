# S2 Kill Board — Run Offline

**UNCLASSIFIED // EXERCISE USE ONLY**

A single-file BDA / combat-power tracker that runs in any web browser with **no internet and no install**. This note covers how to open it, where your data lives, and how to back it up or hand it to another analyst.

---

## Open it

1. Save the file `OP_SKULL_ISLAND_Phase_II_Kill_Board.html` anywhere on the machine (Desktop is fine). You can rename it — the operation name inside the board is editable.
2. **Double-click it.** It opens in your default browser and works completely offline.
3. If it opens as plain text or code, right-click → **Open with** → **Microsoft Edge** (or Chrome / Firefox).

No sign-in, no server, no connectivity required. Everything runs on the local machine.

---

## Where your data is saved

- Entries save **automatically** on the machine, in the browser you opened it with. Close the tab and reopen the file later and your counts are still there. The top-right indicator shows **Saved** when it has written.
- Data is **local to that one browser on that one PC**. It does **not** sync between people or machines. To move a board between machines or analysts, use **Export / Import** below.
- **Recommended browsers for reliable saving from a file: Microsoft Edge or Firefox.** If you use Chrome and notice the board doesn't remember data between sessions, either switch to Edge/Firefox or just **Export** a backup file (below) — that always works.

---

## Back up or share a board — Export / Import

Because there's no server, the board file itself doesn't carry your entries. To keep a copy or hand the board to someone else:

- **Export** — saves the entire board (all counts, custom rows, edited names and descriptions, selected phase) to a small `.json` file, named with the operation and date-time. Store it, email it, or drop it on a share.
- **Import** — on any machine, open the HTML file and click **Import**, pick that `.json`, and the board loads exactly as it was. Import **replaces** the current board, so Export first if you want to keep what's on screen.

Use this to pass the running picture between shifts, back up before a major change, or set up multiple analysts with the same starting board.

---

## Controls reference

| Control | What it does |
|---|---|
| **+ / −** on CONF, PROB | Log confirmed / probable kills. Percentages, gauges, and the roll-up recompute instantly. |
| **START** field | Confirmed fielded quantity (drives the math). **OB PROJ** to its left is the doctrinal baseline for reference. |
| **+** next to P1–P5 | Add a newly identified unit row to that priority. |
| **×** at end of a row | Remove a row (pre-built or added). |
| **Phase** dropdown | Select Phase I–IV; flows into the SITREP header. |
| Operation name, subtitle, and the P1–P5 descriptions | Click to edit for a new operation. Enter commits the change. |
| **Copy SITREP** | Builds a formatted text roll-up (with DTG and classification lines) and copies it to paste into a report. |
| **Export / Import** | Save or load the whole board as a `.json` file (see above). |
| **Reset board** | Restores the original order of battle and labels. Removed rows come back; added rows are cleared. |

---

## Combat-power color code

- **Green ≥ 70%** — combat effective
- **Amber 30–69%** — degraded, still a threat
- **Red < 30%** — combat ineffective / attrited

The overall figure and each priority gauge are weighted by system count, so losing 2 of 3 air-defense systems moves the ADA line far more than losing 2 of 42 IFVs moves Maneuver.

---

*Confirmed kills (CONF) require two sources per the reporting standard. Remove a row (×) only when a system isn't part of the fight or was mis-listed — for a kill, use the CONF stepper so the system stays in the combat-power math.*

**UNCLASSIFIED // EXERCISE USE ONLY**
