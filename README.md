# 🛡️ Incident Response Mini-Drill

An interactive staff training simulation for cybersecurity incident response — built as a single, self-contained HTML file with no dependencies or install required.

**[▶ Launch the drill](https://xpenzin.github.io/Workplace_challange_sim/)**

---

## What is this?

This is a short, scenario-based drill designed to help non-technical and mixed staff teams practice the right instincts when a security incident happens. It is based on a standard Incident Response SOP and takes roughly 5 minutes to complete.

Staff are shown a realistic situation and a mix of **correct and wrong response options**. Picking the wrong answer costs points and shows an instant explanation of why it was wrong — reinforcing learning in the moment.

---

## Scenarios covered

| # | Scenario | Category |
|---|----------|----------|
| 1 | Suspicious login alert | Account security |
| 2 | Phishing link clicked | Email threat |
| 3 | Lost or stolen device | Physical security |

---

## How it works

1. **Pick a scenario** from the home screen
2. **Read the situation** — a realistic prompt sets the scene
3. **Choose your response** from a mix of correct and decoy options
4. **Get instant feedback** — wrong picks are explained immediately and cost −5 pts
5. **See your results** — score, full review, and a key takeaway at the end

### Scoring
- ✅ Correct answer → **+10 points**
- ❌ Wrong answer → **−5 points**
- Maximum score per drill: **30 points**

---

## Core principles drilled

Every scenario reinforces the same five fundamentals:

- **Isolate** the device if there is any risk of spread
- **Report** through the correct channel immediately
- **Document** everything you observed
- **Preserve** all evidence — delete nothing
- **Follow** organizational policy and wait for IT/security guidance

---

## Running it locally

No install, no server, no build step needed. Just open the file:

```bash
git clone https://github.com/Xpenzin/Workplace_challange_sim.git
cd Workplace_challange_sim
open index.html        # macOS
xdg-open index.html   # Linux
# or just double-click index.html in your file explorer
```

---

## Tech stack

| Layer | Details |
|-------|---------|
| Structure | Plain HTML5 |
| Styling | CSS custom properties, no framework |
| Logic | Vanilla JavaScript, no libraries |
| Fonts | Google Fonts — DM Serif Display + DM Sans |
| Icons | None (emoji only) |
| Dependencies | Zero — fully self-contained |

---

## Framework reference

This simulation is built around the **Incident Response Mini-Drill SOP** which covers:

1. Scenario presentation
2. Staff immediate response
3. Correct response review
4. Policy alignment
5. Post-drill documentation

---

## License

For educational and internal training use.
