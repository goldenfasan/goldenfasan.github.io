<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Morning Dashboard</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Mono:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0d0d0d;
    --bg2: #141414;
    --bg3: #1c1c1c;
    --border: rgba(255,255,255,0.07);
    --border2: rgba(255,255,255,0.13);
    --text: #f0ede6;
    --muted: #888880;
    --accent: #c8b97a;
    --accent2: #7ab8c8;
    --danger: #c87a7a;
    --success: #7ac891;
    --warn: #c8a07a;
    --radius: 12px;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'DM Mono', monospace;
    min-height: 100vh;
    padding: 2.5rem 3rem;
    display: grid;
    grid-template-rows: auto 1fr;
    gap: 2rem;
  }

  /* HEADER */
  header {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    border-bottom: 0.5px solid var(--border2);
    padding-bottom: 1.5rem;
  }

  .greeting {
    font-family: 'DM Serif Display', serif;
    font-size: 2.8rem;
    color: var(--text);
    letter-spacing: -0.5px;
  }

  .greeting span {
    color: var(--accent);
    font-style: italic;
  }

  .datetime {
    text-align: right;
  }

  .time-display {
    font-size: 3rem;
    font-weight: 300;
    color: var(--text);
    letter-spacing: 2px;
    line-height: 1;
  }

  .date-display {
    font-size: 0.75rem;
    color: var(--muted);
    letter-spacing: 0.15em;
    text-transform: uppercase;
    margin-top: 0.4rem;
  }

  /* MAIN GRID */
  .grid {
    display: grid;
    grid-template-columns: 1.1fr 1fr 1.2fr;
    gap: 1.5rem;
    align-items: start;
  }

  .card {
    background: var(--bg2);
    border: 0.5px solid var(--border);
    border-radius: var(--radius);
    padding: 1.5rem;
  }

  .card-title {
    font-size: 0.65rem;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 1.2rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .card-title::before {
    content: '';
    display: inline-block;
    width: 3px;
    height: 3px;
    background: var(--accent);
    border-radius: 50%;
  }

  /* TASKS */
  .task-list { list-style: none; display: flex; flex-direction: column; gap: 0.6rem; }

  .task-item {
    display: flex;
    align-items: flex-start;
    gap: 0.75rem;
    padding: 0.7rem 0.9rem;
    background: var(--bg3);
    border-radius: 8px;
    border: 0.5px solid var(--border);
    cursor: pointer;
    transition: border-color 0.2s, opacity 0.2s;
    user-select: none;
  }

  .task-item:hover { border-color: var(--border2); }

  .task-item.done { opacity: 0.4; }

  .task-check {
    width: 16px;
    height: 16px;
    border: 1.5px solid var(--border2);
    border-radius: 4px;
    flex-shrink: 0;
    margin-top: 1px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 10px;
    color: var(--accent);
    transition: background 0.15s, border-color 0.15s;
  }

  .task-item.done .task-check {
    background: var(--accent);
    border-color: var(--accent);
    color: #0d0d0d;
  }

  .task-text {
    font-size: 0.82rem;
    line-height: 1.4;
    color: var(--text);
  }

  .task-item.done .task-text { text-decoration: line-through; color: var(--muted); }

  .task-prio {
    margin-left: auto;
    font-size: 0.65rem;
    padding: 2px 6px;
    border-radius: 4px;
    flex-shrink: 0;
  }

  .prio-high { background: rgba(200,122,122,0.15); color: var(--danger); }
  .prio-mid  { background: rgba(200,160,122,0.15); color: var(--warn); }
  .prio-low  { background: rgba(122,200,145,0.15); color: var(--success); }

  .add-task {
    display: flex;
    gap: 0.5rem;
    margin-top: 1rem;
  }

  .add-task input {
    flex: 1;
    background: var(--bg3);
    border: 0.5px solid var(--border);
    border-radius: 8px;
    padding: 0.5rem 0.75rem;
    color: var(--text);
    font-family: 'DM Mono', monospace;
    font-size: 0.78rem;
    outline: none;
    transition: border-color 0.2s;
  }

  .add-task input::placeholder { color: var(--muted); }
  .add-task input:focus { border-color: var(--border2); }

  .add-task button {
    background: var(--accent);
    color: #0d0d0d;
    border: none;
    border-radius: 8px;
    padding: 0.5rem 0.9rem;
    font-family: 'DM Mono', monospace;
    font-size: 0.78rem;
    font-weight: 500;
    cursor: pointer;
    transition: opacity 0.2s;
  }

  .add-task button:hover { opacity: 0.85; }

  /* KLAUSUREN */
  .exam-list { display: flex; flex-direction: column; gap: 0.75rem; }

  .exam-item {
    padding: 0.9rem 1rem;
    background: var(--bg3);
    border-radius: 8px;
    border-left: 2px solid var(--border2);
    transition: border-color 0.2s;
  }

  .exam-item:hover { border-left-color: var(--accent); }

  .exam-name {
    font-size: 0.82rem;
    color: var(--text);
    font-weight: 500;
    margin-bottom: 0.3rem;
  }

  .exam-date {
    font-size: 0.7rem;
    color: var(--muted);
    margin-bottom: 0.5rem;
  }

  .exam-countdown {
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .days-num {
    font-size: 1.4rem;
    font-weight: 500;
    line-height: 1;
  }

  .days-label {
    font-size: 0.65rem;
    color: var(--muted);
    letter-spacing: 0.1em;
    text-transform: uppercase;
  }

  .progress-bar {
    height: 2px;
    background: var(--border);
    border-radius: 1px;
    margin-top: 0.7rem;
    overflow: hidden;
  }

  .progress-fill {
    height: 100%;
    border-radius: 1px;
    transition: width 0.5s ease;
  }

  /* SCHEDULE */
  .week-tabs {
    display: flex;
    gap: 0.3rem;
    margin-bottom: 1.2rem;
    flex-wrap: wrap;
  }

  .week-tab {
    font-family: 'DM Mono', monospace;
    font-size: 0.65rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    padding: 0.3rem 0.6rem;
    border-radius: 6px;
    border: 0.5px solid var(--border);
    background: transparent;
    color: var(--muted);
    cursor: pointer;
    transition: background 0.15s, color 0.15s, border-color 0.15s;
  }

  .week-tab.active {
    background: var(--accent);
    color: #0d0d0d;
    border-color: var(--accent);
  }

  .week-tab:hover:not(.active) {
    border-color: var(--border2);
    color: var(--text);
  }

  .lecture-list { display: flex; flex-direction: column; gap: 0.55rem; }

  .lecture-item {
    display: flex;
    gap: 0.85rem;
    align-items: flex-start;
    padding: 0.7rem 0.9rem;
    background: var(--bg3);
    border-radius: 8px;
    border: 0.5px solid var(--border);
  }

  .lecture-time {
    font-size: 0.72rem;
    color: var(--accent);
    min-width: 80px;
    line-height: 1.5;
    flex-shrink: 0;
  }

  .lecture-info { flex: 1; }

  .lecture-name {
    font-size: 0.82rem;
    color: var(--text);
    font-weight: 500;
    margin-bottom: 0.15rem;
  }

  .lecture-room {
    font-size: 0.68rem;
    color: var(--muted);
  }

  .lecture-dot {
    width: 8px;
    height: 8px;
    border-radius: 50%;
    margin-top: 5px;
    flex-shrink: 0;
  }

  .no-lecture {
    font-size: 0.78rem;
    color: var(--muted);
    text-align: center;
    padding: 2rem 0;
  }

  /* FOOTER */
  footer {
    margin-top: 2rem;
    text-align: center;
    font-size: 0.65rem;
    color: rgba(136,136,128,0.4);
    letter-spacing: 0.1em;
  }
</style>
</head>
<body>

<header>
  <div class="greeting">Guten Morgen, <span>Student.</span></div>
  <div class="datetime">
    <div class="time-display" id="clock">--:--</div>
    <div class="date-display" id="datestr">---</div>
  </div>
</header>

<main class="grid">

  <!-- TASKS -->
  <div class="card">
    <div class="card-title">Tagesaufgaben</div>
    <ul class="task-list" id="taskList"></ul>
    <div class="add-task">
      <input type="text" id="newTaskInput" placeholder="Neue Aufgabe..." maxlength="60" />
      <button onclick="addTask()">+</button>
    </div>
  </div>

  <!-- EXAMS -->
  <div class="card">
    <div class="card-title">Klausuren · Countdown</div>
    <div class="exam-list" id="examList"></div>
  </div>

  <!-- SCHEDULE -->
  <div class="card">
    <div class="card-title">Vorlesungsplan</div>
    <div class="week-tabs" id="weekTabs"></div>
    <div class="lecture-list" id="lectureList"></div>
  </div>

</main>

<footer>Aktualisiert täglich · Daten lokal gespeichert · Klicke Aufgaben zum Abhaken</footer>

<script>
// =============================================
// KONFIGURATION — hier deine Daten anpassen!
// =============================================

const EXAMS = [
  {
    name: "Mathematik II",
    date: "2025-07-15",
    color: "#c8b97a"
  },
  {
    name: "Algorithmen & Datenstrukturen",
    date: "2025-07-28",
    color: "#7ab8c8"
  },
  {
    name: "Softwareentwicklung",
    date: "2025-08-05",
    color: "#c87a7a"
  }
];

// Wochenplan: 0=So, 1=Mo, 2=Di, 3=Mi, 4=Do, 5=Fr, 6=Sa
const SCHEDULE = {
  1: [ // Montag
    { time: "08:00–09:30", name: "Mathematik II", room: "Hörsaal A · Geb. 20", color: "#c8b97a" },
    { time: "10:00–11:30", name: "Algorithmen & DS", room: "Seminarraum 3 · Geb. 11", color: "#7ab8c8" },
    { time: "14:00–15:30", name: "Softwareentwicklung", room: "PC-Pool · Geb. 05", color: "#c87a7a" },
  ],
  2: [ // Dienstag
    { time: "09:45–11:15", name: "Lineare Algebra", room: "Hörsaal B · Geb. 20", color: "#7ac891" },
    { time: "14:00–15:30", name: "Übung: Mathe II", room: "Seminarraum 1 · Geb. 11", color: "#c8b97a" },
  ],
  3: [ // Mittwoch
    { time: "08:00–09:30", name: "Algorithmen & DS", room: "Hörsaal A · Geb. 20", color: "#7ab8c8" },
    { time: "11:30–13:00", name: "Softwareentwicklung", room: "Seminarraum 4 · Geb. 06", color: "#c87a7a" },
  ],
  4: [ // Donnerstag
    { time: "10:00–11:30", name: "Lineare Algebra", room: "Hörsaal C · Geb. 20", color: "#7ac891" },
    { time: "14:00–17:00", name: "Praktikum", room: "Labor · Geb. 08", color: "#c8a07a" },
  ],
  5: [ // Freitag
    { time: "08:00–09:30", name: "Mathematik II", room: "Hörsaal A · Geb. 20", color: "#c8b97a" },
  ],
  0: [],
  6: [],
};

const DEFAULT_TASKS = [
  { text: "Vorlesungsunterlagen vorbereiten", prio: "high", done: false },
  { text: "Aufgabenblatt abgeben", prio: "high", done: false },
  { text: "Mitschrift durchlesen", prio: "mid", done: false },
  { text: "Lerngruppe organisieren", prio: "low", done: false },
];

// =============================================
// CLOCK & DATE
// =============================================
const DAYS_DE = ["Sonntag","Montag","Dienstag","Mittwoch","Donnerstag","Freitag","Samstag"];
const MONTHS_DE = ["Januar","Februar","März","April","Mai","Juni","Juli","August","September","Oktober","November","Dezember"];

function updateClock() {
  const now = new Date();
  const h = String(now.getHours()).padStart(2,'0');
  const m = String(now.getMinutes()).padStart(2,'0');
  document.getElementById('clock').textContent = h + ':' + m;
  const d = DAYS_DE[now.getDay()];
  const day = now.getDate();
  const mo = MONTHS_DE[now.getMonth()];
  const yr = now.getFullYear();
  document.getElementById('datestr').textContent = d + ', ' + day + '. ' + mo + ' ' + yr;
}

setInterval(updateClock, 1000);
updateClock();

// =============================================
// TASKS
// =============================================
const STORAGE_KEY_TASKS = 'morning_tasks_v2';
const STORAGE_KEY_DATE  = 'morning_tasks_date';

function todayStr() {
  const n = new Date();
  return n.getFullYear() + '-' + String(n.getMonth()+1).padStart(2,'0') + '-' + String(n.getDate()).padStart(2,'0');
}

function loadTasks() {
  const savedDate = localStorage.getItem(STORAGE_KEY_DATE);
  const today = todayStr();
  if (savedDate !== today) {
    // Neuer Tag → Tasks zurücksetzen
    const fresh = DEFAULT_TASKS.map(t => Object.assign({}, t, {done: false}));
    localStorage.setItem(STORAGE_KEY_TASKS, JSON.stringify(fresh));
    localStorage.setItem(STORAGE_KEY_DATE, today);
    return fresh;
  }
  const raw = localStorage.getItem(STORAGE_KEY_TASKS);
  return raw ? JSON.parse(raw) : DEFAULT_TASKS.map(t => Object.assign({}, t));
}

function saveTasks(tasks) {
  localStorage.setItem(STORAGE_KEY_TASKS, JSON.stringify(tasks));
  localStorage.setItem(STORAGE_KEY_DATE, todayStr());
}

let tasks = loadTasks();

function renderTasks() {
  const ul = document.getElementById('taskList');
  ul.innerHTML = '';
  tasks.forEach((t, i) => {
    const li = document.createElement('li');
    li.className = 'task-item' + (t.done ? ' done' : '');
    li.onclick = () => { tasks[i].done = !tasks[i].done; saveTasks(tasks); renderTasks(); };
    const prioClass = t.prio === 'high' ? 'prio-high' : t.prio === 'mid' ? 'prio-mid' : 'prio-low';
    const prioLabel = t.prio === 'high' ? 'hoch' : t.prio === 'mid' ? 'mittel' : 'niedrig';
    li.innerHTML = `
      <div class="task-check">${t.done ? '✓' : ''}</div>
      <span class="task-text">${t.text}</span>
      <span class="task-prio ${prioClass}">${prioLabel}</span>
    `;
    ul.appendChild(li);
  });
}

function addTask() {
  const input = document.getElementById('newTaskInput');
  const val = input.value.trim();
  if (!val) return;
  tasks.push({ text: val, prio: 'mid', done: false });
  saveTasks(tasks);
  renderTasks();
  input.value = '';
  input.focus();
}

document.getElementById('newTaskInput').addEventListener('keydown', e => {
  if (e.key === 'Enter') addTask();
});

renderTasks();

// =============================================
// EXAMS
// =============================================
function renderExams() {
  const container = document.getElementById('examList');
  container.innerHTML = '';
  const today = new Date();
  today.setHours(0,0,0,0);

  EXAMS.forEach(exam => {
    const examDate = new Date(exam.date);
    examDate.setHours(0,0,0,0);
    const diffMs = examDate - today;
    const diffDays = Math.ceil(diffMs / 86400000);

    const semStart = new Date(today);
    semStart.setDate(semStart.getDate() - 60);
    const totalDays = Math.ceil((examDate - semStart) / 86400000);
    const elapsed = Math.ceil((today - semStart) / 86400000);
    const pct = Math.min(100, Math.max(0, Math.round((elapsed / totalDays) * 100)));

    const urgencyColor = diffDays <= 7 ? '#c87a7a' : diffDays <= 21 ? '#c8a07a' : exam.color;

    const dateFormatted = examDate.toLocaleDateString('de-DE', { day: '2-digit', month: 'long', year: 'numeric' });

    const div = document.createElement('div');
    div.className = 'exam-item';
    div.style.borderLeftColor = urgencyColor;
    div.innerHTML = `
      <div class="exam-name">${exam.name}</div>
      <div class="exam-date">${dateFormatted}</div>
      <div class="exam-countdown">
        <span class="days-num" style="color:${urgencyColor}">${diffDays > 0 ? diffDays : '—'}</span>
        <span class="days-label">&nbsp;${diffDays === 1 ? 'Tag' : 'Tage'} noch</span>
      </div>
      <div class="progress-bar">
        <div class="progress-fill" style="width:${pct}%; background:${urgencyColor}; opacity:0.6;"></div>
      </div>
    `;
    container.appendChild(div);
  });
}

renderExams();

// =============================================
// SCHEDULE
// =============================================
const SHORT_DAYS = ['So', 'Mo', 'Di', 'Mi', 'Do', 'Fr', 'Sa'];
let selectedDay = new Date().getDay();

function renderTabs() {
  const container = document.getElementById('weekTabs');
  container.innerHTML = '';
  [1,2,3,4,5].forEach(d => {
    const btn = document.createElement('button');
    btn.className = 'week-tab' + (selectedDay === d ? ' active' : '');
    btn.textContent = SHORT_DAYS[d];
    btn.onclick = () => { selectedDay = d; renderTabs(); renderSchedule(); };
    container.appendChild(btn);
  });
}

function renderSchedule() {
  const container = document.getElementById('lectureList');
  container.innerHTML = '';
  const lectures = SCHEDULE[selectedDay] || [];
  if (!lectures.length) {
    container.innerHTML = '<div class="no-lecture">Keine Vorlesungen · freier Tag</div>';
    return;
  }
  lectures.forEach(lec => {
    const div = document.createElement('div');
    div.className = 'lecture-item';
    div.innerHTML = `
      <div class="lecture-dot" style="background:${lec.color}"></div>
      <div class="lecture-info">
        <div class="lecture-name">${lec.name}</div>
        <div class="lecture-room">${lec.room}</div>
      </div>
      <div class="lecture-time">${lec.time}</div>
    `;
    container.appendChild(div);
  });
}

renderTabs();
renderSchedule();
</script>
</body>
</html>
