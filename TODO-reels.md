# TODO: S-Chat Reels (TikTok Style)

✅ **Current:** Login/Dashboard/Chat/Logout/Profile full functional di single `schat-login.html`

**Information Gathered:**
- Bottom nav index 1 (`fa-video`) ready trigger reels
- currentUser w/ faul verified badge logic siap reuse
- CSS/JS structure futuristik glassmorphism ada

**Plan (Single File Edit):**
1. [ ] **CSS Reels:** `.reels-page` fullvh video container, dynamic gradient BG scroll, right-side like/comment/share overlay, upload modal
2. [ ] **HTML Reels:** `<div id="reelsPage">` hidden in #dashboard, video stack w/ poster MP4 simulasi, overlay UI (like counter anim, caption musik), upload UI (+ button)
3. [ ] **JS Integration:** nav-item[1] onclick=showReels(), scroll detect video active → BG color change (gradient array), like anim hati burst, share modal, upload simulasi
4. [ ] **Dynamic Features:** Verified badge jika username faul, fake reels data (5 videos w/ captions/users), smooth snap scroll, branding footer subtle
5. [ ] **Performance:** IntersectionObserver video change, GPU accelerated transitions

**Dependent:** None (vanilla)

**Followup:** Edit schat-login.html step-by-step, test `start schat-login.html` login→Reels nav.

1. [x] **CSS Reels:** Fullvh layout, dynamic gradient BG scroll, right overlays, upload modal, heart anim
1. [x] **CSS Reels:** Fullvh layout, dynamic gradient BG scroll, right overlays, upload modal, heart anim
2. [x] **HTML Reels:** reelsSection + uploadModal complete w/ 3+ fake reels (faul badge, captions, musik, public BigBuckBunny test video), nav onclicks
3. [ ] **JS:** nav showReels(), IntersectionObserver BG change, toggleLike heart burst, upload handler, share/comment
4. [ ] **Polish:** Full 5 reels, + nav upload, test mobile scroll/smooth
5. [ ] Test + attempt_completion

**Next:** Step 3 - Add JS Reels functionality



