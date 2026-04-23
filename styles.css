/* ===========================
   RoboPrep – Main Stylesheet
   =========================== */

:root {
  --bg: #f8fafc;
  --bg2: #f1f5f9;
  --surface: #ffffff;
  --border: #e2e8f0;
  --text: #0f172a;
  --text-muted: #64748b;
  --text-light: #94a3b8;
  --accent: #2563eb;
  --accent-light: #eff6ff;
  --accent2: #7c3aed;
  --success: #10b981;
  --warning: #f59e0b;
  --danger: #ef4444;
  --sidebar-w: 260px;
  --radius: 14px;
  --radius-sm: 8px;
  --shadow: 0 1px 3px rgba(0,0,0,.08), 0 4px 16px rgba(0,0,0,.06);
  --shadow-lg: 0 8px 32px rgba(0,0,0,.1);
  --font-display: 'Syne', sans-serif;
  --font-body: 'DM Sans', sans-serif;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
html { scroll-behavior: smooth; }

body {
  font-family: var(--font-body);
  background: var(--bg);
  color: var(--text);
  display: flex;
  min-height: 100vh;
  font-size: 15px;
  line-height: 1.65;
}

/* ===== SIDEBAR ===== */
.sidebar {
  width: var(--sidebar-w);
  background: var(--surface);
  border-right: 1px solid var(--border);
  display: flex;
  flex-direction: column;
  position: fixed;
  top: 0; left: 0; bottom: 0;
  z-index: 100;
  overflow-y: auto;
  transition: transform .3s ease;
}

.sidebar-logo {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 24px 20px 20px;
  font-family: var(--font-display);
  font-size: 1.3rem;
  font-weight: 800;
  border-bottom: 1px solid var(--border);
}
.logo-icon { font-size: 1.5rem; }

.sidebar-nav {
  padding: 16px 12px;
  display: flex;
  flex-direction: column;
  gap: 3px;
  flex: 1;
}

.nav-item {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 10px 12px;
  border-radius: var(--radius-sm);
  color: var(--text-muted);
  text-decoration: none;
  font-size: 0.88rem;
  font-weight: 500;
  transition: all .18s;
}
.nav-item i { width: 16px; text-align: center; }
.nav-item:hover { background: var(--bg2); color: var(--text); }
.nav-item.active { background: var(--accent-light); color: var(--accent); font-weight: 600; }

.nav-divider { height: 1px; background: var(--border); margin: 10px 0; }

.sidebar-footer {
  padding: 16px 20px;
  font-size: 0.78rem;
  color: var(--text-light);
  border-top: 1px solid var(--border);
}

/* ===== MOBILE HEADER ===== */
.mobile-header {
  display: none;
  position: fixed;
  top: 0; left: 0; right: 0;
  height: 56px;
  background: var(--surface);
  border-bottom: 1px solid var(--border);
  align-items: center;
  padding: 0 16px;
  gap: 14px;
  z-index: 200;
}
.hamburger {
  background: none; border: none; cursor: pointer;
  font-size: 1.2rem; color: var(--text);
}
.mobile-logo { font-family: var(--font-display); font-weight: 800; font-size: 1.1rem; }

.sidebar-overlay {
  display: none;
  position: fixed; inset: 0;
  background: rgba(0,0,0,.4);
  z-index: 99;
}

/* ===== MAIN CONTENT ===== */
.main-content {
  margin-left: var(--sidebar-w);
  flex: 1;
  padding: 48px 48px 80px;
  max-width: 1100px;
}

/* ===== HERO ===== */
.hero {
  margin-bottom: 48px;
}
.hero-badge {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--accent-light);
  color: var(--accent);
  border: 1px solid #bfdbfe;
  border-radius: 999px;
  padding: 5px 14px;
  font-size: 0.8rem;
  font-weight: 600;
  margin-bottom: 18px;
}
.hero-title {
  font-family: var(--font-display);
  font-size: 3rem;
  font-weight: 800;
  line-height: 1.1;
  margin-bottom: 12px;
  color: var(--text);
}
.hero-title .accent {
  background: linear-gradient(135deg, var(--accent) 0%, var(--accent2) 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}
.hero-sub { color: var(--text-muted); font-size: 1.05rem; margin-bottom: 32px; }

/* ===== SEARCH ===== */
.search-wrap {
  position: relative;
  max-width: 560px;
}
.search-icon {
  position: absolute; left: 16px; top: 50%;
  transform: translateY(-50%);
  color: var(--text-muted); font-size: 0.9rem;
}
.search-input {
  width: 100%;
  padding: 14px 16px 14px 44px;
  border: 2px solid var(--border);
  border-radius: 12px;
  font-family: var(--font-body);
  font-size: 0.95rem;
  background: var(--surface);
  color: var(--text);
  outline: none;
  transition: border-color .2s;
  box-shadow: var(--shadow);
}
.search-input:focus { border-color: var(--accent); }

.search-results {
  position: absolute; top: calc(100% + 6px); left: 0; right: 0;
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 12px;
  box-shadow: var(--shadow-lg);
  z-index: 50;
  max-height: 320px; overflow-y: auto;
  display: none;
}
.search-results.open { display: block; }
.search-result-item {
  padding: 12px 16px;
  cursor: pointer;
  border-bottom: 1px solid var(--border);
  font-size: 0.88rem;
}
.search-result-item:last-child { border-bottom: none; }
.search-result-item:hover { background: var(--bg2); }
.search-result-item .sr-module { font-weight: 600; color: var(--accent); font-size: 0.75rem; }
.search-result-item .sr-text { color: var(--text); margin-top: 2px; }

/* ===== STATS ROW ===== */
.stats-row {
  display: flex;
  gap: 14px;
  flex-wrap: wrap;
  margin-bottom: 48px;
}
.stat-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 12px;
  padding: 16px 24px;
  display: flex;
  flex-direction: column;
  align-items: center;
  box-shadow: var(--shadow);
  flex: 1;
  min-width: 90px;
}
.stat-num {
  font-family: var(--font-display);
  font-size: 1.8rem;
  font-weight: 800;
  color: var(--accent);
}
.stat-label { font-size: 0.75rem; color: var(--text-muted); font-weight: 500; }

/* ===== SECTION ===== */
.section { margin-bottom: 56px; }
.section-title {
  font-family: var(--font-display);
  font-size: 1.25rem;
  font-weight: 700;
  margin-bottom: 20px;
  color: var(--text);
}

/* ===== MODULE GRID ===== */
.module-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 18px;
}
.module-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 28px;
  text-decoration: none;
  color: inherit;
  position: relative;
  overflow: hidden;
  transition: transform .2s, box-shadow .2s;
  box-shadow: var(--shadow);
}
.module-card::before {
  content: '';
  position: absolute; top: 0; left: 0; right: 0;
  height: 4px;
  background: var(--accent, #2563eb);
}
.module-card:hover { transform: translateY(-3px); box-shadow: var(--shadow-lg); }
.module-number {
  font-family: var(--font-display);
  font-size: 0.7rem; font-weight: 800;
  color: var(--text-light); letter-spacing: 2px;
  margin-bottom: 10px;
}
.module-icon { font-size: 2rem; margin-bottom: 12px; display: block; }
.module-card h3 {
  font-family: var(--font-display);
  font-size: 1rem; font-weight: 700;
  margin-bottom: 8px; color: var(--text);
}
.module-card p { font-size: 0.83rem; color: var(--text-muted); margin-bottom: 14px; }
.module-tags { display: flex; gap: 6px; flex-wrap: wrap; margin-bottom: 16px; }
.module-tags span {
  background: var(--bg2); color: var(--text-muted);
  border-radius: 99px; padding: 2px 10px; font-size: 0.72rem; font-weight: 500;
}
.module-arrow {
  color: var(--accent);
  font-size: 1rem; font-weight: 700;
  position: absolute; bottom: 20px; right: 22px;
}

/* ===== QUICK GRID ===== */
.quick-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  gap: 16px;
}
.quick-card {
  border-radius: var(--radius);
  padding: 28px 24px;
  text-decoration: none;
  color: white;
  transition: transform .2s, box-shadow .2s;
}
.quick-card:hover { transform: translateY(-3px); box-shadow: var(--shadow-lg); }
.quick-card i { font-size: 1.6rem; margin-bottom: 12px; display: block; }
.quick-card h3 { font-family: var(--font-display); font-size: 1rem; font-weight: 700; margin-bottom: 6px; }
.quick-card p { font-size: 0.82rem; opacity: .85; }
.qr { background: linear-gradient(135deg, #f59e0b, #ef4444); }
.qz { background: linear-gradient(135deg, #8b5cf6, #2563eb); }
.iq { background: linear-gradient(135deg, #10b981, #059669); }

/* ===== IMPORTANT QUESTIONS LIST ===== */
.iq-list { display: flex; flex-direction: column; gap: 8px; }
.iq-item {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 14px 18px;
  display: flex;
  align-items: center;
  gap: 12px;
  cursor: pointer;
  transition: background .15s;
  font-size: 0.9rem;
}
.iq-item:hover { background: var(--bg2); }
.iq-badge {
  border-radius: 6px;
  padding: 3px 8px;
  font-size: 0.7rem;
  font-weight: 700;
  white-space: nowrap;
  color: white;
}
.m1 { background: #3b82f6; }
.m2 { background: #10b981; }
.m3 { background: #f59e0b; }
.m4 { background: #ef4444; }
.m5 { background: #8b5cf6; }

.iq-item > span:nth-child(2) { flex: 1; }
.iq-type {
  font-size: 0.7rem;
  font-weight: 600;
  border-radius: 6px;
  padding: 2px 8px;
  white-space: nowrap;
}
.iq-type.long { background: #fef3c7; color: #b45309; }
.iq-type.short { background: #dcfce7; color: #15803d; }

/* ===== MODULE PAGE LAYOUT ===== */
.module-page-header {
  margin-bottom: 36px;
  padding-bottom: 28px;
  border-bottom: 2px solid var(--border);
}
.module-page-header .badge {
  display: inline-block;
  background: var(--accent-light); color: var(--accent);
  border-radius: 999px; padding: 4px 14px;
  font-size: 0.78rem; font-weight: 600;
  margin-bottom: 12px;
}
.module-page-header h1 {
  font-family: var(--font-display);
  font-size: 2.2rem; font-weight: 800;
  margin-bottom: 8px;
}
.module-page-header p { color: var(--text-muted); max-width: 600px; }

/* ===== CONTENT CARDS ===== */
.content-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 28px 32px;
  margin-bottom: 20px;
  box-shadow: var(--shadow);
}
.content-card h2 {
  font-family: var(--font-display);
  font-size: 1.15rem; font-weight: 700;
  margin-bottom: 18px;
  color: var(--text);
  display: flex; align-items: center; gap: 8px;
}

/* ===== DEFINITION BOX ===== */
.def-box {
  background: var(--accent-light);
  border-left: 4px solid var(--accent);
  border-radius: 0 10px 10px 0;
  padding: 16px 20px;
  margin-bottom: 14px;
}
.def-box strong { color: var(--accent); font-weight: 700; }

/* ===== KEY TERM ===== */
.key-term {
  background: #fef3c7;
  color: #92400e;
  padding: 1px 6px;
  border-radius: 4px;
  font-weight: 600;
  font-size: 0.92em;
}

/* ===== QUESTION ACCORDION ===== */
.q-block {
  border: 1px solid var(--border);
  border-radius: 10px;
  margin-bottom: 10px;
  overflow: hidden;
}
.q-header {
  padding: 14px 18px;
  background: var(--surface);
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  font-weight: 600;
  font-size: 0.9rem;
  user-select: none;
  transition: background .15s;
}
.q-header:hover { background: var(--bg2); }
.q-label {
  font-size: 0.68rem; font-weight: 700;
  border-radius: 5px; padding: 2px 8px;
  white-space: nowrap;
}
.q-label.short { background: #dcfce7; color: #15803d; }
.q-label.long { background: #fef3c7; color: #b45309; }
.q-label.note { background: #ede9fe; color: #5b21b6; }
.q-toggle { color: var(--accent); font-size: 0.8rem; transition: transform .2s; }
.q-header.open .q-toggle { transform: rotate(180deg); }
.q-body {
  display: none;
  padding: 18px 20px;
  background: var(--bg2);
  border-top: 1px solid var(--border);
  font-size: 0.88rem;
  line-height: 1.7;
}
.q-body.open { display: block; }
.q-body p { margin-bottom: 10px; }
.q-body ul, .q-body ol { padding-left: 20px; margin-bottom: 10px; }
.q-body li { margin-bottom: 5px; }
.q-body strong { color: var(--text); }

/* ===== DIAGRAM ===== */
.diagram-box {
  background: var(--bg2);
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 20px;
  text-align: center;
  margin: 16px 0;
  overflow-x: auto;
}
.diagram-box svg { max-width: 100%; height: auto; }
.diagram-caption { font-size: 0.8rem; color: var(--text-muted); margin-top: 10px; }

/* ===== KEY POINTS ===== */
.key-points {
  background: linear-gradient(135deg, #f0fdf4, #dcfce7);
  border: 1px solid #86efac;
  border-radius: 10px;
  padding: 18px 22px;
}
.key-points h4 { color: #15803d; font-weight: 700; margin-bottom: 10px; }
.key-points ul { padding-left: 18px; }
.key-points li { color: #166534; font-size: 0.88rem; margin-bottom: 6px; }

/* ===== TABLE ===== */
.diff-table {
  width: 100%; border-collapse: collapse;
  font-size: 0.87rem; margin: 12px 0;
  border-radius: 8px; overflow: hidden;
}
.diff-table th {
  background: var(--accent);
  color: white;
  padding: 10px 14px;
  text-align: left;
  font-weight: 600;
}
.diff-table td { padding: 9px 14px; border-bottom: 1px solid var(--border); }
.diff-table tr:nth-child(even) td { background: var(--bg2); }
.diff-table tr:last-child td { border-bottom: none; }

/* ===== QUICK REVISION PAGE ===== */
.rev-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 16px; }
.rev-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 22px;
  box-shadow: var(--shadow);
}
.rev-card h4 {
  font-family: var(--font-display);
  font-size: 0.95rem; font-weight: 700;
  margin-bottom: 10px; color: var(--accent);
}
.rev-card ul { padding-left: 18px; }
.rev-card li { font-size: 0.84rem; color: var(--text-muted); margin-bottom: 5px; }

/* ===== QUIZ PAGE ===== */
.quiz-wrap { max-width: 700px; }
.quiz-score-bar {
  background: var(--bg2); border-radius: 99px; height: 8px;
  margin-bottom: 8px; overflow: hidden;
}
.quiz-score-fill { height: 100%; background: linear-gradient(90deg, var(--accent), var(--accent2)); border-radius: 99px; transition: width .4s; }
.quiz-meta { font-size: 0.82rem; color: var(--text-muted); margin-bottom: 32px; }

.quiz-q-card {
  background: var(--surface); border: 1px solid var(--border);
  border-radius: var(--radius); padding: 28px;
  box-shadow: var(--shadow); margin-bottom: 20px;
}
.quiz-q-num { font-size: 0.75rem; font-weight: 700; color: var(--text-light); margin-bottom: 8px; }
.quiz-q-text { font-size: 0.98rem; font-weight: 600; margin-bottom: 18px; }
.quiz-options { display: flex; flex-direction: column; gap: 8px; }
.quiz-option {
  padding: 12px 16px;
  border: 2px solid var(--border);
  border-radius: 9px;
  cursor: pointer;
  font-size: 0.88rem;
  transition: all .15s;
  background: var(--bg2);
}
.quiz-option:hover { border-color: var(--accent); background: var(--accent-light); }
.quiz-option.correct { border-color: var(--success); background: #f0fdf4; color: #166534; font-weight: 600; }
.quiz-option.wrong { border-color: var(--danger); background: #fef2f2; color: #991b1b; }
.quiz-option.disabled { pointer-events: none; opacity: .6; }

.quiz-feedback {
  margin-top: 14px; padding: 12px 16px;
  border-radius: 9px; font-size: 0.87rem; font-weight: 500;
  display: none;
}
.quiz-feedback.correct { background: #f0fdf4; color: #15803d; border: 1px solid #86efac; }
.quiz-feedback.wrong { background: #fef2f2; color: #991b1b; border: 1px solid #fca5a5; }

.quiz-nav { display: flex; gap: 12px; margin-top: 20px; }
.btn {
  padding: 11px 24px;
  border-radius: 9px;
  border: none; cursor: pointer;
  font-family: var(--font-body);
  font-size: 0.9rem; font-weight: 600;
  transition: all .15s;
}
.btn-primary { background: var(--accent); color: white; }
.btn-primary:hover { background: #1d4ed8; }
.btn-secondary { background: var(--bg2); color: var(--text); border: 1px solid var(--border); }
.btn-secondary:hover { background: var(--border); }

.quiz-result {
  text-align: center; padding: 48px 32px;
  background: var(--surface); border: 1px solid var(--border);
  border-radius: var(--radius); box-shadow: var(--shadow);
}
.quiz-result .score-big { font-family: var(--font-display); font-size: 4rem; font-weight: 800; color: var(--accent); }
.quiz-result p { color: var(--text-muted); margin: 10px 0 24px; }

/* ===== NOTE HIGHLIGHT ===== */
.note-highlight {
  background: #fff7ed;
  border-left: 4px solid #f59e0b;
  border-radius: 0 8px 8px 0;
  padding: 14px 18px;
  font-size: 0.88rem;
  color: #92400e;
  margin: 12px 0;
}
.note-highlight strong { font-weight: 700; }

/* ===== BREADCRUMB ===== */
.breadcrumb {
  display: flex; align-items: center; gap: 6px;
  font-size: 0.8rem; color: var(--text-muted);
  margin-bottom: 24px;
}
.breadcrumb a { color: var(--accent); text-decoration: none; }
.breadcrumb a:hover { text-decoration: underline; }

/* ===== SCROLL TO TOP ===== */
.scroll-top {
  position: fixed; bottom: 28px; right: 28px;
  background: var(--accent); color: white;
  border: none; border-radius: 50%;
  width: 44px; height: 44px;
  font-size: 1rem; cursor: pointer;
  box-shadow: var(--shadow-lg);
  display: flex; align-items: center; justify-content: center;
  z-index: 50;
  opacity: 0; pointer-events: none;
  transition: opacity .25s;
}
.scroll-top.visible { opacity: 1; pointer-events: auto; }

/* ===== RESPONSIVE ===== */
@media (max-width: 900px) {
  .sidebar { transform: translateX(-100%); }
  .sidebar.open { transform: translateX(0); }
  .sidebar-overlay.open { display: block; }
  .mobile-header { display: flex; }
  .main-content { margin-left: 0; padding: 72px 20px 60px; }
  .hero-title { font-size: 2rem; }
  .module-grid { grid-template-columns: 1fr; }
  .quick-grid { grid-template-columns: 1fr; }
  .stats-row { gap: 8px; }
  .stat-card { min-width: 70px; padding: 12px 14px; }
  .stat-num { font-size: 1.4rem; }
}