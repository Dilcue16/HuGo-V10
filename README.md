# HuGo v9 PWA
## Human Rights on the Go
### Bulacan Police Provincial Human Rights Affairs Office · BULPPO, PRO 3

---

## WHAT'S NEW IN v9 — 5th INSPECTION CONDITION: CCTV CAMERAS

### All 5 Official Visual Inspection Conditions
1. 🔴 Fire Extinguisher
2. 💊 Medical Kits / Medicines
3. 📘 Log Book (Blue PUPC Logbook)
4. 🟡 Detainee Formation (Yellow shirts, organized rows)
5. 📷 CCTV Cameras ← NEW in v9

### CCTV Cameras — 3-Tier Criteria
GOOD: Cameras in designated locations · Unobstructed view · Image clear and functional
      Recording working properly · Date and time correct · Cables secured and protected

NEEDS ATTENTION: Minor obstruction in view · Camera not properly aligned
                 Dust or dirt on lens · Recording intermittent

NOT ACCEPTABLE: Camera not working · Recording not functioning
                Severely obstructed view · Damaged/loose/exposed wires
                Missing camera in critical area

Other checks: Check all cameras daily · Verify storage capacity and retention
              Ensure power backup is functional · Secure access to CCTV system
              Report and repair immediately

---

### 3-Tier Rating System (official BULPPO chart)
✅ GOOD (Acceptable) — Compliant / Meets Standard
⚠ NEEDS ATTENTION — Minor issue / Monitor
❌ NOT ACCEPTABLE — Immediate action required + flagged to super user

---

## LOGIN CREDENTIALS (for testing)

Station passcode (all stations): PHRA2025
Super user password: HUGO@ADMIN2025
Camera inspection tokens:
  - HUGO-INSPECT-01
  - PHRA-CAM-2025
  - BULPPO-SU-99

---

## DEPLOY TO GITHUB (Dilcue16)
1. Go to github.com/new → name: hugo-pwa → Public → Create repository
2. Upload ALL files from this package (keep folder structure including icons/)
3. Settings → Pages → Deploy from main branch / root → Save
4. Wait 2-3 minutes
5. Your URL: https://dilcue16.github.io/hugo-pwa/

## INSTALL ON ANDROID
1. Open Chrome → go to your URL
2. Tap ⋮ menu → "Add to Home screen"
3. Tap "Add"
4. HuGo launches fullscreen like a native app!

## INSTALL ON iPHONE
1. Open Safari → go to URL
2. Share button → "Add to Home Screen" → Add

---

## FILE STRUCTURE
hugo-v9/
├── index.html        ← Complete HuGo v9 app
├── manifest.json     ← PWA manifest
├── sw.js             ← Service worker (offline, caching)
├── offline.html      ← Offline fallback page
├── README.md         ← This file
└── icons/            ← App icons (72px to 512px)
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
