<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Please Rate Our Toilet</title>
<style>
  :root {
    --blue: #0b4f8a;
    --yellow: #fcd535;
    --card: #ffffff;
    --text: #111;
  }
  * { box-sizing: border-box; -webkit-tap-highlight-color: transparent; }
  body {
    margin: 0;
    font-family: Roboto, "Segoe UI", Arial, sans-serif;
    color: var(--text);
    min-height: 100vh;
    background: linear-gradient(#ffffff 0%, #c5dcf3 100%) fixed;
    padding-bottom: 24px;
  }
  .location { text-align: center; font-size: 15px; padding: 8px 0 4px; }
  .wrap { max-width: 720px; margin: 0 auto; padding: 0 12px; }

  /* Rating card */
  .rate-card {
    background: var(--card);
    border-radius: 28px;
    box-shadow: 0 6px 16px rgba(0,0,0,.15);
    padding: 16px 12px 14px;
  }
  .head {
    display: flex; align-items: center; justify-content: space-between; gap: 8px;
  }
  .head h1 { font-size: clamp(20px, 5vw, 34px); margin: 0; text-align: center; flex: 1; }
  .logo { width: 64px; height: 64px; display:flex; align-items:center; justify-content:center;
          font-weight:700; color: var(--blue); border:2px solid var(--blue); border-radius:10px; font-size:12px; text-align:center; }
  .logo img { max-width: 100%; max-height: 100%; }

  .faces { display: flex; justify-content: space-around; margin-top: 14px; }
  .face { background: none; border: 0; cursor: pointer; text-align: center; font-weight: 700;
          font-size: 14px; letter-spacing: .3px; padding: 4px; transition: transform .15s, opacity .15s; }
  .face svg { width: clamp(80px, 24vw, 140px); height: auto; display:block; margin: 0 auto 6px; }
  .face.dim { opacity: .35; }
  .face.active { transform: scale(1.1); }
  .face.active svg circle.bg { stroke: var(--blue); stroke-width: 5; }

  /* Feedback grid */
  h2 { text-align: center; font-size: 22px; margin: 20px 0 12px; }
  .grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; }
  .tile {
    background: var(--card); border: 3px solid transparent; border-radius: 18px;
    box-shadow: 0 3px 8px rgba(0,0,0,.12);
    padding: 12px 4px 10px; cursor: pointer; text-align: center;
    display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 6px;
    min-height: 100px; font-size: clamp(12px, 3.2vw, 17px); font-family: inherit;
    transition: border-color .15s, background .15s, transform .1s;
  }
  .tile:active { transform: scale(.97); }
  .tile .ico { font-size: clamp(28px, 8vw, 42px); line-height: 1; }
  .tile.selected { border-color: var(--blue); background: #e8f2fc; }

  /* Submit */
  .submit-row { text-align: center; margin-top: 18px; }
  #submit {
    background: var(--blue); color: #fff; font-weight: 700; font-size: 22px; letter-spacing: 1px;
    border: 0; border-radius: 12px; padding: 14px 48px; cursor: pointer; font-family: inherit;
  }
  #submit:disabled { background: #a9b6c6; color: #d9e1ea; cursor: not-allowed; }

  .footer { text-align: center; margin-top: 26px; font-size: 24px; font-weight: 700; }
  .footer small { display:block; font-size: 11px; font-weight: 400; margin-top: 2px; }

  /* Thank you overlay */
  .thanks {
    position: fixed; inset: 0; background: rgba(255,255,255,.97);
    display: none; flex-direction: column; align-items: center; justify-content: center; text-align: center; padding: 24px;
    z-index: 10;
  }
  .thanks.show { display: flex; }
  .thanks .big { font-size: 80px; }
  .thanks h3 { font-size: 28px; margin: 10px 0 6px; }
  .thanks p { color: #444; margin: 0; }
  .toast { color:#b00020; text-align:center; margin-top:10px; min-height:20px; font-size:14px; }
</style>
</head>
<body>

<div class="location" id="location">Loading…</div>

<div class="wrap">
  <div class="rate-card">
    <div class="head">
      <div class="logo" id="logoLeft"><!-- replace with <img src="logo-left.png"> -->LOGO</div>
      <h1>Please Rate Our Toilet</h1>
      <div class="logo" id="logoRight"><!-- replace with <img src="smart-toilet.png"> -->Smart Toilet</div>
    </div>

    <div class="faces" role="radiogroup" aria-label="Rating">
      <button class="face" data-rating="Good" role="radio" aria-checked="false">
        <svg viewBox="0 0 140 140"><circle class="bg" cx="70" cy="70" r="68" fill="#fcd535"/>
          <ellipse cx="48" cy="55" rx="7" ry="10" fill="#111"/><ellipse cx="92" cy="55" rx="7" ry="10" fill="#111"/>
          <path d="M35 80 Q70 112 105 80" stroke="#111" stroke-width="7" fill="none" stroke-linecap="round"/></svg>
        GOOD
      </button>
      <button class="face" data-rating="Neutral" role="radio" aria-checked="false">
        <svg viewBox="0 0 140 140"><circle class="bg" cx="70" cy="70" r="68" fill="#fcd535"/>
          <ellipse cx="48" cy="55" rx="7" ry="10" fill="#111"/><ellipse cx="92" cy="55" rx="7" ry="10" fill="#111"/>
          <path d="M48 92 H92" stroke="#111" stroke-width="7" stroke-linecap="round"/></svg>
        NEUTRAL
      </button>
      <button class="face" data-rating="Poor" role="radio" aria-checked="false">
        <svg viewBox="0 0 140 140"><circle class="bg" cx="70" cy="70" r="68" fill="#fcd535"/>
          <ellipse cx="48" cy="55" rx="7" ry="10" fill="#111"/><ellipse cx="92" cy="55" rx="7" ry="10" fill="#111"/>
          <path d="M38 100 Q70 68 102 100" stroke="#111" stroke-width="7" fill="none" stroke-linecap="round"/></svg>
        POOR
      </button>
    </div>
  </div>

  <h2>Feedback</h2>
  <div class="grid" id="grid"></div>

  <div class="toast" id="toast"></div>
  <div class="submit-row"><button id="submit" disabled>SUBMIT</button></div>

  <div class="footer">
    Smart Toilet® System by smarttech.sg
    <small>Copyright © 2025 Convergent Smart Technologies. All rights reserved.</small>
  </div>
</div>

<div class="thanks" id="thanks">
  <div class="big">🙏</div>
  <h3>Thank you for your feedback!</h3>
  <p>Your response helps us keep this toilet clean.</p>
</div>

<script>
/* ================= CONFIG — EDIT THESE ================= */
const CONFIG = {
  // Google Form "formResponse" URL (see setup notes)
  FORM_URL: "https://docs.google.com/forms/d/e/1FAIpQLSea0CJts_kFSEZ0bne0nLLGzizjLQOGNq1kYTDOdoPQDuk-qw/formResponse",
  // Google Form field IDs (entry.XXXXXXXXXX)
  ENTRY_LOCATION: "entry.2112153671",
  ENTRY_RATING:   "entry.1265919894",
  ENTRY_ISSUES:   "entry.1600273334",
  DEFAULT_LOCATION: "3RD Floor Male Toilet",
  COOLDOWN_SECONDS: 30,       // stops repeat/spam submissions from the same device
  REQUIRE_ISSUE_IF_NOT_GOOD: false // true = Neutral/Poor must pick at least one issue
};

const ISSUES = [
  { label: "Wet/Dirty Floor",         ico: "⚠️" },
  { label: "Dirty Mirror",            ico: "🪞" },
  { label: "No Hand Towel",           ico: "🧻" },
  { label: "Dirty/Choke Basin",       ico: "🚰" },
  { label: "Dirty Toilet Bowl/Urinal",ico: "🚽" },
  { label: "Faulty Hand Dryer",       ico: "💨" },
  { label: "Litter Bin Full",         ico: "🗑️" },
  { label: "No Hand Soap",            ico: "🧴" },
  { label: "Faulty/Blinking Light",   ico: "💡" },
  { label: "No Toilet Paper",         ico: "🧷" },
  { label: "Faulty Tap/Flush",        ico: "🚿" },
  { label: "Bad Smell",               ico: "👃" }
];

/* ================= LOGIC ================= */
const params   = new URLSearchParams(location.search);
// Per-toilet QR code: index.html?loc=27%20Mandai%20Estate%20L4%20Male
const LOCATION = params.get("loc") || CONFIG.DEFAULT_LOCATION;
document.getElementById("location").textContent = LOCATION;
document.title = "Rate: " + LOCATION;

const grid = document.getElementById("grid");
const submitBtn = document.getElementById("submit");
const toast = document.getElementById("toast");
let rating = null;
const selected = new Set();

ISSUES.forEach(i => {
  const b = document.createElement("button");
  b.className = "tile";
  b.type = "button";
  b.innerHTML = `<span class="ico">${i.ico}</span><span>${i.label}</span>`;
  b.onclick = () => {
    selected.has(i.label) ? selected.delete(i.label) : selected.add(i.label);
    b.classList.toggle("selected");
    refresh();
  };
  grid.appendChild(b);
});

document.querySelectorAll(".face").forEach(f => {
  f.onclick = () => {
    rating = f.dataset.rating;
    document.querySelectorAll(".face").forEach(x => {
      const on = x === f;
      x.classList.toggle("active", on);
      x.classList.toggle("dim", !on);
      x.setAttribute("aria-checked", on);
    });
    refresh();
  };
});

function refresh() {
  const needIssue = CONFIG.REQUIRE_ISSUE_IF_NOT_GOOD && rating && rating !== "Good";
  submitBtn.disabled = !rating || (needIssue && selected.size === 0);
}

function cooldownLeft() {
  try {
    const last = +localStorage.getItem("toiletFbLast:" + LOCATION) || 0;
    return Math.max(0, CONFIG.COOLDOWN_SECONDS - (Date.now() - last) / 1000);
  } catch { return 0; }
}

submitBtn.onclick = async () => {
  const wait = Math.ceil(cooldownLeft());
  if (wait > 0) { toast.textContent = `Please wait ${wait}s before submitting again.`; return; }

  submitBtn.disabled = true;
  submitBtn.textContent = "SENDING…";
  toast.textContent = "";

  const body = new URLSearchParams();
  body.append(CONFIG.ENTRY_LOCATION, LOCATION);
  body.append(CONFIG.ENTRY_RATING, rating);
  body.append(CONFIG.ENTRY_ISSUES, [...selected].join(", "));

  try {
    // no-cors: Google Forms doesn't send CORS headers; the response is opaque but the data is saved
    await fetch(CONFIG.FORM_URL, {
      method: "POST", mode: "no-cors",
      headers: { "Content-Type": "application/x-www-form-urlencoded" },
      body
    });
    try { localStorage.setItem("toiletFbLast:" + LOCATION, Date.now()); } catch {}
    showThanks();
  } catch (e) {
    toast.textContent = "Network error. Please try again.";
    submitBtn.textContent = "SUBMIT";
    submitBtn.disabled = false;
  }
};

function showThanks() {
  document.getElementById("thanks").classList.add("show");
  setTimeout(() => {
    document.getElementById("thanks").classList.remove("show");
    rating = null; selected.clear();
    document.querySelectorAll(".tile").forEach(t => t.classList.remove("selected"));
    document.querySelectorAll(".face").forEach(f => f.classList.remove("active", "dim"));
    submitBtn.textContent = "SUBMIT";
    refresh();
  }, 3000);
}
</script>
</body>
</html>
