# StyleClear — HCI Final Project

**Reducing Cognitive Overload in Fast-Fashion Mobile Shopping Apps**  
Antariksha Dhanure  UBID 50676220  University at Buffalo 

---

## 🌐 Live Site

**[styleclear](https://potatant.github.io/Style-clear/)**

---

## What This Is

StyleClear is a research-backed HCI project that redesigns the SHEIN-style fast-fashion shopping interface to reduce cognitive overload — without removing the features that make these platforms commercially useful.

The project includes:
- A **mixed-methods user study** (survey n=42 + heuristic audit)
- A **fully interactive desktop web prototype** built in vanilla HTML/CSS/JS
- A **comparative evaluation** of the redesign vs. the original interface

---

## Key Findings

| Metric | Result |
|--------|--------|
| Users overwhelmed by pop-ups & flash sales | **87%** |
| Cart abandonment due to overload | **71%** |
| Preferred the redesign after 5 min exposure | **64%** |
| Faster product discovery (redesign vs. original) | **3.2×** |
| Reduction in perceived interface clutter | **−69%** |

---

## Theoretical Grounding

- **Cognitive Load Theory** (Sweller, 1988) — reducing extraneous interface load frees working memory for decision-making
- **Choice Overload** (Iyengar & Lepper, 2000) — excess options create stress, not satisfaction  
- **Information Overload** (Eppler & Mengis, 2004) — when input exceeds capacity, users disengage

---

## Design Principles Applied

| Principle | Implementation |
|-----------|---------------|
| Progressive Disclosure | Product cards show 5 elements max; detail hidden in modal accordions |
| Gestalt Proximity | Related attributes grouped; whitespace separates unrelated content |
| Persistent Filters | Sidebar always visible — never interrupts browsing |
| Zero Urgency Design | No countdown timers, "Limited stock" warnings, or floating badges |
| Pagination | Replaces infinite scroll — defined browsing unit per session |

---

## Files

```
styleclear/
├── index.html        ← Portfolio landing page (this is the homepage)
├── prototype.html    ← Fully interactive StyleClear prototype
└── README.md
```

---

## Tech Stack

- Vanilla HTML, CSS, JavaScript — zero dependencies, zero frameworks
- Google Fonts (Cormorant Garamond, Figtree, DM Mono, DM Sans)
- CSS custom properties throughout
- Fully offline-capable (fonts are the only external resource)

---

## References

- Eppler, M. J., & Mengis, J. (2004). The concept of information overload. *The Information Society, 20*(5), 325–344.
- Iyengar, S. S., & Lepper, M. R. (2000). When choice is demotivating. *Journal of Personality and Social Psychology, 79*(6), 995–1006.
- Nielsen, J. (1994). Heuristic evaluation. In *Usability Inspection Methods* (pp. 25–62). Wiley.
- Sweller, J. (1988). Cognitive load during problem solving. *Cognitive Science, 12*(2), 257–285.

---

