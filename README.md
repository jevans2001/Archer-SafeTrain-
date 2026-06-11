# Archer SafeTrain

HV Safety Training Portal — demo build for Archer Aviation.

**Live site:** https://jevans2001.github.io/Archer-safeTrain-

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | Login/landing page — entry point |
| `portal.html` | 3-role dashboard (Employee, Manager, Head of Safety) |
| `courses.html` | Full HV Safety course viewer (Level 1, 2, 3) |
| `scenarios.html` | Interactive hazard identification scenario trainer |

---

## Deploy to GitHub Pages

### First time setup

```bash
# 1. Create repo at github.com/new named: archer-safetrain

# 2. Clone it
git clone https://github.com/jevans2001/archer-safeTrain.git
cd archer-safetrain

# 3. Add the 4 HTML files + this README into the folder

# 4. Push
git add .
git commit -m "Initial SafeTrain demo"
git push origin main
```

### Enable GitHub Pages

1. Go to your repo on GitHub
2. **Settings → Pages**
3. Source: **Deploy from a branch**
4. Branch: **main** / folder: **/ (root)**
5. Click **Save**
6. Wait ~60 seconds, then visit: `https://jevans2001.github.io/Archer-safeTrain-`

### Update later

```bash
# After changing any files:
git add .
git commit -m "Update"
git push origin main
```

---

## Demo roles

| Role | Name | What you can do |
|------|------|----------------|
| Employee | Alex Reyes | View training progress, launch courses, take quiz, see certificate |
| Manager | Sarah Chen | Approve qualifications, view team compliance, send reminders |
| Head of Safety | Dr. Jamie Torres | Org-wide dashboard, department breakdown, reports, manage courses |

---

## Notes

- All 4 files must be in the same directory
- No backend or database required — fully static
- Works in Chrome, Edge, Firefox, Safari
- All training content derived from Archer's actual HV safety curriculum (NFPA 70E)
