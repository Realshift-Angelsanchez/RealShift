<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>REALSHIFT · Mi Entrenamiento</title>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#0a0a0a;--surf:#111;--panel:#181818;--brd:#252525;
  --red:#e63946;--green:#2dc653;--amber:#f4a261;--blue:#457b9d;
  --text:#f0f0f0;--muted:#777;--subtle:#333;
}
body{background:var(--bg);color:var(--text);font-family:'Courier New',monospace;min-height:100vh}
input,select,textarea,button{font-family:inherit}
input:focus,select:focus,textarea:focus{outline:none;border-color:var(--red)!important}
::-webkit-scrollbar{width:5px;height:5px}
::-webkit-scrollbar-track{background:#111}
::-webkit-scrollbar-thumb{background:#333;border-radius:3px}
textarea{resize:vertical}
button{cursor:pointer}

/* ── HEADER ── */
#header{
  background:var(--surf);border-bottom:1px solid var(--brd);
  padding:0 24px;position:sticky;top:0;z-index:100;
  display:flex;align-items:center;justify-content:space-between;height:52px;
}
.logo{display:flex;align-items:center;gap:10px}
.logo-box{width:26px;height:26px;background:var(--red);display:flex;align-items:center;justify-content:center;font-weight:900;font-size:13px}
.logo-text{font-weight:900;font-size:13px;letter-spacing:.1em}
.logo-sub{color:var(--muted);font-size:9px;letter-spacing:.08em;margin-left:6px}
.client-badge{background:var(--red)18;border:1px solid var(--red)44;color:var(--red);
  padding:3px 12px;border-radius:3px;font-size:9px;font-weight:700;letter-spacing:.1em;text-transform:uppercase}

/* ── TABS ── */
#tabs{display:flex;gap:2px;background:var(--surf);border-bottom:1px solid var(--brd);padding:0 24px}
.tab-btn{
  background:transparent;border:none;color:var(--muted);padding:11px 18px;
  font-size:9px;font-weight:700;letter-spacing:.1em;text-transform:uppercase;
  border-bottom:2px solid transparent;transition:all .15s;
}
.tab-btn.active{color:var(--text);border-bottom-color:var(--red)}

/* ── MAIN ── */
#main{max-width:900px;margin:0 auto;padding:20px 24px}

/* ── CARDS ── */
.card{background:var(--surf);border:1px solid var(--brd);border-radius:4px;padding:16px;margin-bottom:14px}
.card-title{color:var(--muted);font-size:9px;letter-spacing:.12em;text-transform:uppercase;margin-bottom:12px}

/* ── DAY PILLS ── */
.day-pills{display:flex;gap:6px;margin-bottom:18px;flex-wrap:wrap}
.day-pill{
  padding:6px 14px;border-radius:3px;font-size:10px;font-weight:700;letter-spacing:.08em;
  border:1px solid var(--brd);background:var(--panel);color:var(--muted);
  transition:all .15s;
}
.day-pill.active{background:var(--red)18;border-color:var(--red);color:var(--red)}
.day-pill.rest{opacity:.3;cursor:default}

/* ── EXERCISE CARD ── */
.ex-card{
  background:var(--panel);border:1px solid var(--brd);border-radius:3px;
  padding:14px;margin-bottom:10px;border-left:3px solid var(--red);
}
.ex-name{font-size:13px;font-weight:700;margin-bottom:4px}
.ex-meta{font-size:9px;color:var(--muted);margin-bottom:10px;letter-spacing:.06em}
.ex-method{display:inline-block;padding:2px 8px;border-radius:2px;font-size:9px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;margin-bottom:10px}

.ex-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-bottom:10px}
.ex-field label{display:block;color:var(--muted);font-size:8px;text-transform:uppercase;letter-spacing:.08em;margin-bottom:3px}
.ex-field input{
  width:100%;background:var(--bg);border:1px solid var(--brd);
  color:var(--text);border-radius:2px;padding:5px 7px;font-size:12px;font-weight:700;
  text-align:center;
}
.ex-field input.kg-input{border-color:var(--amber)44;color:var(--amber)}
.ex-field input.rpe-input{border-color:var(--blue)44;color:var(--blue)}

.ex-notes textarea{
  width:100%;background:var(--bg);border:1px solid var(--brd);
  color:var(--muted);border-radius:2px;padding:7px 9px;font-size:11px;
}
.ex-hint{font-size:9px;color:var(--muted);font-style:italic;padding-top:6px;border-top:1px solid var(--brd);margin-top:8px}

/* ── RPE SCALE ── */
.rpe-scale{display:flex;gap:4px;margin-top:4px}
.rpe-btn{
  flex:1;padding:5px 2px;border:1px solid var(--brd);border-radius:2px;
  background:transparent;color:var(--muted);font-size:10px;font-weight:700;
  transition:all .1s;
}
.rpe-btn:hover{border-color:var(--blue);color:var(--blue)}
.rpe-btn.sel{background:var(--blue)22;border-color:var(--blue);color:var(--blue)}
.rpe-btn.high{border-color:var(--red)44;color:var(--red)88}
.rpe-btn.sel.high{background:var(--red)22;border-color:var(--red);color:var(--red)}

/* ── PROGRESS WEEK ── */
.week-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:4px;margin-top:16px}
.week-cell{
  background:var(--panel);border:1px solid var(--brd);border-radius:3px;
  padding:8px 4px;text-align:center;
}
.week-cell.active{border-color:var(--red)44}
.week-cell.selected{background:var(--red)12;border-color:var(--red)}
.week-cell .wday{font-size:8px;color:var(--muted);letter-spacing:.06em;margin-bottom:3px}
.week-cell .wcount{font-size:14px;font-weight:900;color:var(--subtle)}
.week-cell.has-data .wcount{color:var(--green)}
.week-cell .wlabel{font-size:7px;color:var(--muted)}

/* ── TRACKER ── */
.log-row{
  display:grid;grid-template-columns:60px 90px 80px 80px 1fr 30px;
  gap:8px;align-items:center;padding:8px 10px;
  border-bottom:1px solid var(--brd);font-size:11px;
}
.log-row:nth-child(odd){background:var(--panel)}
.log-head{color:var(--muted);font-size:8px;font-weight:700;letter-spacing:.1em;text-transform:uppercase}

/* ── MACRO BARS ── */
.macro-bar-wrap{margin-bottom:10px}
.macro-bar-head{display:flex;justify-content:space-between;margin-bottom:4px;font-size:10px}
.macro-bar-track{height:4px;background:var(--brd);border-radius:2px}
.macro-bar-fill{height:100%;border-radius:2px;transition:width .4s}

/* ── BUTTONS ── */
.btn{
  border:none;padding:8px 18px;border-radius:3px;font-size:10px;
  font-weight:700;letter-spacing:.08em;text-transform:uppercase;transition:all .15s;
}
.btn-red{background:var(--red);color:#fff}
.btn-ghost{background:transparent;border:1px solid var(--brd);color:var(--muted)}
.btn-green{background:var(--green);color:#000}

/* ── SAVE BAR ── */
#save-bar{
  position:fixed;bottom:16px;right:20px;display:flex;gap:8px;z-index:200;
}
.save-btn{
  border:none;border-radius:3px;padding:8px 16px;font-size:9px;
  font-weight:700;letter-spacing:.1em;text-transform:uppercase;
  display:flex;align-items:center;gap:6px;transition:all .2s;
}
#btn-export{background:var(--red);color:#fff}
#btn-import-label{background:var(--panel);border:1px solid var(--brd);color:var(--muted)}
#autosave-dot{
  width:7px;height:7px;border-radius:50%;background:var(--green);
  box-shadow:0 0 6px var(--green);
}

/* ── FOOTER ── */
#footer{
  max-width:900px;margin:0 auto;padding:14px 24px;
  display:flex;justify-content:space-between;align-items:center;
  border-top:1px solid var(--brd);margin-top:24px;
}
#footer span{font-size:8px;color:var(--subtle);letter-spacing:.1em}

/* ── MISC ── */
.tag{display:inline-block;padding:2px 8px;border-radius:2px;font-size:9px;font-weight:700;letter-spacing:.08em;text-transform:uppercase}
.empty-state{text-align:center;padding:48px 0;color:var(--subtle)}
.empty-state .icon{font-size:30px;margin-bottom:8px}
.empty-state p{font-size:10px;letter-spacing:.08em}
.section-label{color:var(--muted);font-size:9px;letter-spacing:.15em;text-transform:uppercase;margin-bottom:8px}
.divider{height:1px;background:var(--brd);margin:16px 0}
input[type=range]{width:100%;accent-color:var(--amber)}
.alert{padding:10px 14px;border-radius:3px;font-size:10px;margin-bottom:12px;border-left:3px solid var(--red);background:var(--red)10;color:var(--muted)}

/* ── PHASE BADGE ── */
.phase-badge{
  display:flex;gap:6px;margin-bottom:18px;
}
.phase-chip{
  padding:6px 14px;border-radius:3px;font-size:9px;font-weight:700;
  letter-spacing:.1em;border:1px solid var(--brd);color:var(--muted);background:transparent;
}
.phase-chip.current-reset{border-color:var(--blue);color:var(--blue);background:var(--blue)12}
.phase-chip.current-build{border-color:var(--green);color:var(--green);background:var(--green)12}
.phase-chip.current-perform{border-color:var(--red);color:var(--red);background:var(--red)12}

@media(max-width:600px){
  .ex-grid{grid-template-columns:repeat(2,1fr)}
  .log-row{grid-template-columns:50px 80px 70px 1fr 24px;font-size:10px}
  .log-row .log-waist{display:none}
  #save-bar{bottom:10px;right:10px}
}
</style>
</head>
<body>

<!-- HEADER -->
<div id="header">
  <div class="logo">
    <div class="logo-box">R</div>
    <div>
      <span class="logo-text">REALSHIFT</span>
      <span class="logo-sub">MI ENTRENAMIENTO</span>
    </div>
  </div>
  <div id="client-badge-wrap"></div>
</div>

<!-- TABS -->
<div id="tabs">
  <button class="tab-btn active" onclick="switchTab('routine')">RUTINA</button>
  <button class="tab-btn" onclick="switchTab('tracker')">SEGUIMIENTO</button>
  <button class="tab-btn" onclick="switchTab('nutrition')">NUTRICIÓN</button>
</div>

<!-- MAIN -->
<div id="main">
  <div id="tab-routine"></div>
  <div id="tab-tracker" style="display:none"></div>
  <div id="tab-nutrition" style="display:none"></div>
</div>

<!-- FOOTER -->
<div id="footer">
  <span>REALSHIFT · SISTEMA DE ENTRENAMIENTO PROFESIONAL</span>
  <div style="display:flex;align-items:center;gap:8px">
    <div id="autosave-dot" title="Autoguardado activo"></div>
    <span id="footer-phase"></span>
  </div>
</div>

<!-- SAVE BAR -->
<div id="save-bar">
  <label id="btn-import-label" class="save-btn" title="Cargar rutina">
    ↑ CARGAR
    <input type="file" accept=".json" id="import-input" style="display:none" onchange="handleImport(event)"/>
  </label>
  <button id="btn-export" class="save-btn" onclick="handleExport()">↓ EXPORTAR</button>
</div>

<script>
// ═══════════════════════════════════════════════════════════════════════════
// STATE
// ═══════════════════════════════════════════════════════════════════════════
const LS_KEY = "realshift_client_v1";

let STATE = {
  clientName: "Cliente",
  phase: "build",
  activeDays: ["LUN","MIÉ","VIE"],
  splitLabel: "Fullbody",
  exercises: {},   // { "LUN": [{name,method,sets,reps,rpe_target,kg,rpe_real,comment,methodColor,hint}] }
  logs: [],        // [{week,date,bodyWeight,waist,notes}]
  meals: [
    {name:"Desayuno",items:""},{name:"Comida",items:""},
    {name:"Merienda",items:""},{name:"Cena",items:""}
  ],
  macros: {protein:160,carbs:200,fat:70,kcal:2090},
  goal: "maintain"
};

let currentTab = "routine";
let currentDay = null;

// ═══════════════════════════════════════════════════════════════════════════
// PERSISTENCE
// ═══════════════════════════════════════════════════════════════════════════
function saveLS() {
  try { localStorage.setItem(LS_KEY, JSON.stringify(STATE)); } catch(e){}
  flashDot();
}

function loadLS() {
  try {
    const raw = localStorage.getItem(LS_KEY);
    if (raw) { STATE = JSON.parse(raw); return true; }
  } catch(e){}
  return false;
}

function handleExport() {
  const name = (STATE.clientName||"cliente").replace(/\s+/g,"_").toLowerCase();
  const date = new Date().toISOString().slice(0,10);
  const blob = new Blob([JSON.stringify(STATE,null,2)],{type:"application/json"});
  const url = URL.createObjectURL(blob);
  const a = document.createElement("a");
  a.href=url; a.download=`realshift_${name}_${date}.json`; a.click();
  URL.revokeObjectURL(url);
}

function handleImport(e) {
  const file = e.target.files[0]; if(!file) return;
  const reader = new FileReader();
  reader.onload = ev => {
    try {
      STATE = JSON.parse(ev.target.result);
      if(!currentDay || !STATE.activeDays.includes(currentDay))
        currentDay = STATE.activeDays[0] || null;
      renderAll();
      saveLS();
    } catch { alert("Archivo JSON inválido."); }
  };
  reader.readAsText(file);
  e.target.value="";
}

let dotTimer;
function flashDot() {
  const dot = document.getElementById("autosave-dot");
  if(!dot) return;
  dot.style.background="#fff";
  clearTimeout(dotTimer);
  dotTimer = setTimeout(()=>{ dot.style.background="var(--green)"; },400);
}

// ═══════════════════════════════════════════════════════════════════════════
// TABS
// ═══════════════════════════════════════════════════════════════════════════
function switchTab(tab) {
  currentTab = tab;
  document.querySelectorAll(".tab-btn").forEach((b,i)=>{
    b.classList.toggle("active", ["routine","tracker","nutrition"][i]===tab);
  });
  document.getElementById("tab-routine").style.display   = tab==="routine"   ? "" : "none";
  document.getElementById("tab-tracker").style.display   = tab==="tracker"   ? "" : "none";
  document.getElementById("tab-nutrition").style.display = tab==="nutrition" ? "" : "none";
  if(tab==="routine")   renderRoutine();
  if(tab==="tracker")   renderTracker();
  if(tab==="nutrition") renderNutrition();
}

// ═══════════════════════════════════════════════════════════════════════════
// HELPERS
// ═══════════════════════════════════════════════════════════════════════════
const DAYS_ALL = ["LUN","MAR","MIÉ","JUE","VIE","SÁB","DOM"];

const METHOD_COLORS = {
  reset:"#457b9d", build_max:"#e63946", build_res:"#2dc653", perform:"#f4a261"
};
const METHOD_LABELS = {
  reset:"Técnica", build_max:"F.Máxima", build_res:"F.Resistencia", perform:"Potencia"
};

function el(id){ return document.getElementById(id); }

function esc(str){ return String(str||"").replace(/&/g,"&amp;").replace(/</g,"&lt;").replace(/>/g,"&gt;").replace(/"/g,"&quot;"); }

// ═══════════════════════════════════════════════════════════════════════════
// ROUTINE TAB
// ═══════════════════════════════════════════════════════════════════════════
function renderRoutine() {
  const wrap = el("tab-routine");
  if(!currentDay || !STATE.activeDays.includes(currentDay))
    currentDay = STATE.activeDays[0] || null;

  const phaseColor = STATE.phase==="reset" ? "var(--blue)" : STATE.phase==="build" ? "var(--green)" : "var(--red)";
  const phaseClass = "current-"+STATE.phase;

  // Day pills HTML
  let pillsHTML = DAYS_ALL.map(d => {
    const isActive = STATE.activeDays.includes(d);
    const isSel    = d === currentDay;
    const cls      = isSel ? "day-pill active" : isActive ? "day-pill" : "day-pill rest";
    const click    = isActive ? `onclick="selectDay('${d}')"` : "";
    const label    = isActive ? "" : "<span style='font-size:7px;display:block;color:var(--subtle)'>descanso</span>";
    return `<div class="${cls}" ${click}>${d}${label}</div>`;
  }).join("");

  // Exercises for selected day
  const exs = (currentDay && STATE.exercises[currentDay]) || [];
  let exHTML = "";

  if(!currentDay || exs.length === 0) {
    exHTML = `<div class="empty-state"><div class="icon">▢</div><p>Sin ejercicios asignados para este día.</p><p style="margin-top:6px;font-size:9px;color:var(--subtle)">Tu entrenador completará esta rutina.</p></div>`;
  } else {
    exs.forEach((ex, i) => {
      const mc = ex.methodColor || METHOD_COLORS[ex.method] || "var(--red)";
      const ml = METHOD_LABELS[ex.method] || ex.method || "";

      // RPE buttons 1-10
      const rpeReal = parseInt(ex.rpe_real) || 0;
      let rpeBtns = "";
      for(let r=1;r<=10;r++){
        const isSel = rpeReal===r;
        const isHigh = r>=9;
        const cls = `rpe-btn${isSel?" sel":""}${isHigh?" high":""}`;
        rpeBtns += `<button class="${cls}" onclick="setRPE(${i},${r})">${r}</button>`;
      }

      exHTML += `
      <div class="ex-card" style="border-left-color:${mc}" id="ex-${i}">
        <div style="display:flex;justify-content:space-between;align-items:flex-start">
          <div>
            <div class="ex-name">${esc(ex.name)}</div>
            <span class="ex-method" style="background:${mc}22;color:${mc};border:1px solid ${mc}44">${ml}</span>
          </div>
          <div style="text-align:right">
            <div style="font-size:9px;color:var(--muted)">Prescrip.</div>
            <div style="font-size:11px;color:${mc};font-weight:700">${esc(ex.sets)} × ${esc(ex.reps)}</div>
            <div style="font-size:9px;color:var(--muted)">RPE obj: ${esc(ex.rpe_target||ex.rpe||"—")}</div>
          </div>
        </div>

        <div class="divider" style="margin:10px 0 10px"></div>

        <div class="ex-grid">
          <div class="ex-field">
            <label>Carga real (kg)</label>
            <input class="kg-input" type="number" min="0" step="0.5"
              value="${esc(ex.kg)}" placeholder="0"
              onchange="updateEx(${i},'kg',this.value)"
              oninput="updateEx(${i},'kg',this.value)"/>
          </div>
          <div class="ex-field">
            <label>Series hechas</label>
            <input type="number" min="0" max="10"
              value="${esc(ex.sets_done||ex.sets)}" placeholder="${esc(ex.sets)}"
              onchange="updateEx(${i},'sets_done',this.value)"/>
          </div>
          <div class="ex-field">
            <label>Reps reales</label>
            <input type="number" min="0"
              value="${esc(ex.reps_done||"")}" placeholder="${esc(ex.reps)}"
              onchange="updateEx(${i},'reps_done',this.value)"/>
          </div>
          <div class="ex-field">
            <label>RPE real</label>
            <input class="rpe-input" type="number" min="1" max="10"
              value="${esc(ex.rpe_real||"")}" placeholder="—"
              onchange="updateEx(${i},'rpe_real',this.value); renderRPEBtns(${i})"/>
          </div>
        </div>

        <div class="section-label" style="margin-top:6px">Percepción de esfuerzo</div>
        <div class="rpe-scale" id="rpe-btns-${i}">${rpeBtns}</div>

        <div class="section-label" style="margin-top:12px">Comentarios / sensaciones</div>
        <div class="ex-notes">
          <textarea rows="2" placeholder="Ej: carga bien, fallo técnico en rep 5, dolor en hombro derecho..."
            onchange="updateEx(${i},'comment',this.value)">${esc(ex.comment||"")}</textarea>
        </div>

        ${ex.hint ? `<div class="ex-hint">📌 ${esc(ex.hint)}</div>` : ""}
      </div>`;
    });
  }

  // Weekly summary
  let weekCells = DAYS_ALL.map(d => {
    const isActive = STATE.activeDays.includes(d);
    const exCount  = (STATE.exercises[d]||[]).length;
    const filled   = (STATE.exercises[d]||[]).filter(e=>e.kg||e.comment).length;
    const isSel    = d===currentDay;
    const cls      = `week-cell${isActive?" active":""}${isSel?" selected":""}${filled>0?" has-data":""}`;
    const click    = isActive ? `onclick="selectDay('${d}')"` : "";
    return `<div class="${cls}" style="cursor:${isActive?"pointer":"default"}" ${click}>
      <div class="wday">${d}</div>
      <div class="wcount">${isActive ? (exCount||"—") : "—"}</div>
      <div class="wlabel">${isActive ? (filled>0?"registrado":"vacío") : "desc"}</div>
    </div>`;
  }).join("");

  wrap.innerHTML = `
    <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:14px">
      <div>
        <span style="font-size:11px;font-weight:700;color:${phaseColor};letter-spacing:.06em;text-transform:uppercase">FASE ${STATE.phase.toUpperCase()}</span>
        <span style="color:var(--muted);font-size:9px;margin-left:10px">${esc(STATE.splitLabel||"")}</span>
      </div>
      <span class="tag" style="background:${phaseColor}18;color:${phaseColor};border:1px solid ${phaseColor}44">${esc(STATE.clientName)}</span>
    </div>

    <div class="day-pills">${pillsHTML}</div>

    ${currentDay ? `<div style="display:flex;align-items:center;gap:10px;margin-bottom:14px">
      <span style="font-size:16px;font-weight:900;letter-spacing:.06em">${currentDay}</span>
      <span style="color:var(--muted);font-size:10px">${exs.length} ejercicio(s)</span>
      ${exs.filter(e=>e.kg).length > 0 ? `<span class="tag" style="background:var(--green)18;color:var(--green);border:1px solid var(--green)44">✓ ${exs.filter(e=>e.kg).length} registrado(s)</span>` : ""}
    </div>` : ""}

    ${exHTML}

    <div class="divider"></div>
    <div class="section-label">Vista semanal</div>
    <div class="week-grid">${weekCells}</div>
  `;
}

function selectDay(d) {
  currentDay = d;
  renderRoutine();
}

function updateEx(idx, field, val) {
  if(!currentDay) return;
  const exs = STATE.exercises[currentDay];
  if(!exs || !exs[idx]) return;
  exs[idx][field] = val;
  saveLS();
  // Partial re-render: just update weekly summary
  const cells = document.querySelectorAll(".week-cell");
  // Full re-render only when needed (comment/kg change doesn't need full re-render)
}

function setRPE(idx, val) {
  if(!currentDay) return;
  const exs = STATE.exercises[currentDay];
  if(!exs || !exs[idx]) return;
  exs[idx].rpe_real = val;
  // Update the input field
  const card = el("ex-"+idx);
  if(card) {
    const input = card.querySelector(".rpe-input");
    if(input) input.value = val;
  }
  renderRPEBtns(idx);
  saveLS();
}

function renderRPEBtns(idx) {
  const container = el(`rpe-btns-${idx}`);
  if(!container || !currentDay) return;
  const ex = (STATE.exercises[currentDay]||[])[idx];
  const rpeReal = parseInt(ex?.rpe_real) || 0;
  let html = "";
  for(let r=1;r<=10;r++){
    const isSel = rpeReal===r;
    const isHigh = r>=9;
    const cls = `rpe-btn${isSel?" sel":""}${isHigh?" high":""}`;
    html += `<button class="${cls}" onclick="setRPE(${idx},${r})">${r}</button>`;
  }
  container.innerHTML = html;
}

// ═══════════════════════════════════════════════════════════════════════════
// TRACKER TAB
// ═══════════════════════════════════════════════════════════════════════════
function renderTracker() {
  const wrap = el("tab-tracker");
  const logs = STATE.logs;

  // Chart
  let chartHTML = "";
  if(logs.length > 1) {
    const vals = logs.map(l=>parseFloat(l.bodyWeight)).filter(Boolean);
    const min=Math.min(...vals), max=Math.max(...vals), range=max-min||1;
    const bars = logs.map((l,i)=>{
      const h = ((parseFloat(l.bodyWeight)-min)/range)*50+10;
      return `<div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:2px">
        <div style="font-size:7px;color:var(--muted)">${l.bodyWeight}</div>
        <div style="width:100%;height:${h}px;background:var(--red);border-radius:2px 2px 0 0"></div>
        <div style="font-size:7px;color:var(--muted)">S${l.week}</div>
      </div>`;
    }).join("");
    chartHTML = `<div class="card" style="margin-bottom:14px">
      <div class="card-title">Progresión — Peso Corporal</div>
      <div style="display:flex;align-items:flex-end;gap:6px;height:80px">${bars}</div>
    </div>`;

    const diff = (parseFloat(logs[logs.length-1].bodyWeight) - parseFloat(logs[0].bodyWeight)).toFixed(1);
    const isPos = diff > 0;
    const goodColor = STATE.goal==="bulk" ? (isPos?"var(--green)":"var(--red)") : (!isPos?"var(--green)":"var(--red)");
    chartHTML += `<div style="display:flex;gap:10px;margin-bottom:14px">
      <div class="card" style="flex:1;text-align:center;margin-bottom:0">
        <div class="card-title">Variación total</div>
        <div style="font-size:24px;font-weight:900;color:${goodColor}">${isPos?"+":""}${diff} kg</div>
      </div>
      <div class="card" style="flex:1;text-align:center;margin-bottom:0">
        <div class="card-title">Semanas registradas</div>
        <div style="font-size:24px;font-weight:900;color:var(--blue)">${logs.length}</div>
      </div>
    </div>`;
  }

  // Log form
  const formHTML = `<div class="card">
    <div class="card-title">Nuevo registro semanal</div>
    <div style="display:grid;grid-template-columns:repeat(2,1fr);gap:10px;margin-bottom:10px">
      <div>
        <div class="section-label">Semana</div>
        <input type="number" id="log-week" value="${logs.length+1}" min="1"
          style="width:100%;background:var(--bg);border:1px solid var(--brd);color:var(--text);border-radius:3px;padding:7px 10px;font-size:12px"/>
      </div>
      <div>
        <div class="section-label">Fecha</div>
        <input type="date" id="log-date"
          style="width:100%;background:var(--bg);border:1px solid var(--brd);color:var(--text);border-radius:3px;padding:7px 10px;font-size:12px"/>
      </div>
      <div>
        <div class="section-label">Peso corporal (kg)</div>
        <input type="number" id="log-weight" step="0.1" placeholder="75.5"
          style="width:100%;background:var(--bg);border:1px solid var(--brd);color:var(--amber);border-radius:3px;padding:7px 10px;font-size:14px;font-weight:700"/>
      </div>
      <div>
        <div class="section-label">Cintura (cm)</div>
        <input type="number" id="log-waist" step="0.5" placeholder="82"
          style="width:100%;background:var(--bg);border:1px solid var(--brd);color:var(--text);border-radius:3px;padding:7px 10px;font-size:12px"/>
      </div>
    </div>
    <div style="margin-bottom:10px">
      <div class="section-label">Notas / sensaciones de la semana</div>
      <textarea id="log-notes" rows="2" placeholder="Ej: semana con buenas sensaciones, energía alta, recuperación ok..."
        style="width:100%;background:var(--bg);border:1px solid var(--brd);color:var(--text);border-radius:3px;padding:8px 10px;font-size:11px"></textarea>
    </div>
    <button class="btn btn-red" onclick="addLog()">+ Registrar semana</button>
    <div class="alert" style="margin-top:12px;margin-bottom:0">
      ▸ Mídete siempre en ayunas · misma hora · mismo método cada semana
    </div>
  </div>`;

  // Table
  let tableHTML = "";
  if(logs.length > 0) {
    const rows = logs.map((l,i) => `
      <div class="log-row">
        <div style="color:var(--red);font-weight:700">S${esc(l.week)}</div>
        <div style="color:var(--muted)">${esc(l.date)}</div>
        <div style="font-weight:700;color:var(--amber)">${esc(l.bodyWeight)} kg</div>
        <div class="log-waist" style="color:var(--muted)">${l.waist?esc(l.waist)+" cm":"—"}</div>
        <div style="color:var(--muted);font-size:10px">${esc(l.notes||"—")}</div>
        <div><button onclick="removeLog(${i})" style="background:none;border:none;color:var(--muted);font-size:14px;cursor:pointer">×</button></div>
      </div>`).join("");
    tableHTML = `<div class="card" style="margin-top:14px">
      <div class="card-title">Historial</div>
      <div class="log-row log-head" style="background:var(--panel)">
        <div>SEM</div><div>FECHA</div><div>PESO</div><div class="log-waist">CINTURA</div><div>NOTAS</div><div></div>
      </div>
      ${rows}
    </div>`;
  } else {
    tableHTML = `<div class="empty-state" style="margin-top:20px"><div class="icon">◈</div><p>Sin registros aún.</p></div>`;
  }

  wrap.innerHTML = chartHTML + formHTML + tableHTML;
}

function addLog() {
  const week   = el("log-week")?.value;
  const date   = el("log-date")?.value;
  const bw     = el("log-weight")?.value;
  const waist  = el("log-waist")?.value;
  const notes  = el("log-notes")?.value;
  if(!date || !bw){ alert("Introduce al menos la fecha y el peso."); return; }
  STATE.logs.push({ week, date, bodyWeight:bw, waist, notes });
  saveLS();
  renderTracker();
}

function removeLog(i) {
  STATE.logs.splice(i,1);
  saveLS();
  renderTracker();
}

// ═══════════════════════════════════════════════════════════════════════════
// NUTRITION TAB
// ═══════════════════════════════════════════════════════════════════════════
function renderNutrition() {
  const wrap = el("tab-nutrition");
  const m = STATE.macros || {protein:160,carbs:200,fat:70,kcal:2090};

  const macroBar = (label, val, max, color) => `
    <div class="macro-bar-wrap">
      <div class="macro-bar-head">
        <span style="color:var(--muted);text-transform:uppercase;letter-spacing:.08em">${label}</span>
        <span style="color:${color};font-weight:700">${val}g</span>
      </div>
      <div class="macro-bar-track">
        <div class="macro-bar-fill" style="width:${Math.min(val/max*100,100)}%;background:${color}"></div>
      </div>
    </div>`;

  const mealsHTML = STATE.meals.map((meal,i) => `
    <div class="card">
      <div style="display:flex;align-items:center;gap:8px;margin-bottom:8px">
        <div style="width:6px;height:6px;background:var(--red);border-radius:50%"></div>
        <span style="font-size:11px;font-weight:700">${esc(meal.name)}</span>
      </div>
      <textarea rows="3" placeholder="Ej: 200g pechuga · 120g arroz integral · brócoli · AOVE..."
        onchange="updateMeal(${i},this.value)"
        style="width:100%;background:var(--bg);border:1px solid var(--brd);color:var(--text);border-radius:2px;padding:8px 10px;font-size:11px">${esc(meal.items)}</textarea>
    </div>`).join("");

  wrap.innerHTML = `
    <div style="display:grid;grid-template-columns:260px 1fr;gap:16px">
      <div>
        <div class="card">
          <div class="card-title">Macros prescritos</div>
          <div style="text-align:center;margin-bottom:14px">
            <span class="tag" style="background:var(--amber)18;color:var(--amber);border:1px solid var(--amber)44;font-size:13px;padding:5px 16px">${m.kcal} kcal</span>
          </div>
          ${macroBar("Proteína", m.protein, 300, "var(--red)")}
          ${macroBar("Carbohidratos", m.carbs, 400, "var(--green)")}
          ${macroBar("Grasa", m.fat, 150, "var(--amber)")}
          <div style="margin-top:12px;padding:10px;background:var(--panel);border-radius:3px;font-size:9px;color:var(--muted);line-height:1.9">
            <div><span style="color:var(--red)">Proteína:</span> prioridad absoluta · en todas las ingestas</div>
            <div><span style="color:var(--green)">CHO:</span> concentrar en peri-entrenamiento</div>
            <div><span style="color:var(--amber)">Grasa:</span> alejada del entrenamiento</div>
          </div>
        </div>
      </div>
      <div>
        <div style="color:var(--muted);font-size:9px;letter-spacing:.12em;text-transform:uppercase;margin-bottom:10px">Plan de comidas — edita libremente</div>
        ${mealsHTML}
        <div style="padding:10px 14px;background:var(--panel);border:1px solid var(--red)33;border-radius:3px;font-size:9px;color:var(--muted);line-height:1.8;margin-top:4px">
          <span style="color:var(--red);font-weight:700">Protocolo REALSHIFT · </span>
          Proteína en todas las ingestas · CHO peri-entreno · Grasas alejadas del entrenamiento
        </div>
      </div>
    </div>`;
}

function updateMeal(i, val) {
  STATE.meals[i].items = val;
  saveLS();
}

// ═══════════════════════════════════════════════════════════════════════════
// HEADER & FOOTER
// ═══════════════════════════════════════════════════════════════════════════
function renderHeader() {
  const badge = el("client-badge-wrap");
  if(badge) badge.innerHTML = `<span class="client-badge">${esc(STATE.clientName)}</span>`;
  const fp = el("footer-phase");
  if(fp) {
    const c = STATE.phase==="reset"?"var(--blue)":STATE.phase==="build"?"var(--green)":"var(--red)";
    fp.innerHTML = `<span style="color:${c};font-weight:700;letter-spacing:.08em">▸ FASE ${STATE.phase.toUpperCase()}</span>`;
  }
}

// ═══════════════════════════════════════════════════════════════════════════
// INIT
// ═══════════════════════════════════════════════════════════════════════════
function renderAll() {
  renderHeader();
  renderRoutine();
  if(currentTab==="tracker")   renderTracker();
  if(currentTab==="nutrition") renderNutrition();
}

// Boot
loadLS();
currentDay = STATE.activeDays[0] || null;
renderAll();
</script>
</body>
</html>
