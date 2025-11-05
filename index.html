<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover" />
  <title>Financy — Budget mobile & desktop</title>

  <!-- App-like metas -->
  <meta name="theme-color" content="#0b5bff" />
  <meta name="apple-mobile-web-app-capable" content="yes" />
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
  <!-- Apple icon (PNG base64). Puoi sostituirla in futuro: 1024px PNG. -->
  <link rel="apple-touch-icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQAAAAEACAYAAABccqhmAAAACXBIWXMAAAsSAAALEgHS3X78AAAEsElEQVR4nO3awW3cQBRA0Y6iS6N1o4uA4gq2r8zR8o1C9Qn0v4O0i7w9W1o8o4wYzPp8NwAAALhJz3Cw9kqg3w9fUdqv9kNf8q8fAABwZx0N9s1g2mN6z6v3mQYkqg8V8bqgq5o9f8Vb8+zj2s3G5b8qB0v7u9m3b2x5T3vQ1v2q9s8Y3Huv1Xj8m6jXbqf8w6H0m2H2b7f2cJ8oH7Pp4v+qg0d9y5w9q6kS6h9K0f0p0s9G2b3b0r9Wc9Y7oYf3b0d9Ue8o9Qv0bNf9oQAAwKpZUI1bX5l+6gZb+QqGq9m2kqK9mWm4d6bHk9c6JrZb7Y8yJqf6b9+Wf0Z1o9r8wXx1sQ4rj2W4bqTq3pQqkqgGZpAqkqgGZpAqkqgGZpAqkqgGZpAoAAICb/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2JgAABg6y1cH2vR9m2fG1+3G6r0cYj7d5S3j6e8v7sWcQAAwKk+Zf8y8uQkXw8AAAAASUVORK5CYII=" />

  <!-- Manifest dinamico (iniettato via JS) -->
  <link id="manifestLink" rel="manifest" href="#" />

  <!-- CSS minimal, elegante e blu → niente CDN -->
  <style>
    :root { --bg:#f6f8ff; --card:#ffffff; --text:#0f172a; --muted:#5b6b8a; --line:#e3e8ff; --accent:#0b5bff; --ok:#10b981; --bad:#ef4444; }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{margin:0;font-family: ui-sans-serif, -apple-system, Segoe UI, Roboto, Helvetica, Arial; background:var(--bg); color:var(--text);}
    header{position:sticky;top:0;z-index:30;background:rgba(246,248,255,.9);backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
    .wrap{max-width:980px;margin:0 auto;padding:12px 16px}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:40px;height:40px;border-radius:12px;background:radial-gradient(120% 120% at 30% 20%, #5aa0ff 0%, #0b5bff 60%, #0731a8 100%);color:#fff;display:grid;place-items:center;font-weight:900;letter-spacing:.5px}
    /* Monogram "Fi" custom: */
    .logo svg{width:22px;height:22px;display:block}
    .chips{display:flex;gap:8px;align-items:center;margin-left:auto}
    button,input,select{font:inherit}
    .btn{padding:8px 12px;border:1px solid var(--line);border-radius:12px;background:#fff}
    .btn:active{transform:translateY(1px)}
    .btn-primary{background:var(--accent);color:#fff;border-color:var(--accent)}
    main{padding:16px}
    .grid{display:grid;gap:12px}
    .grid-2{grid-template-columns:repeat(2,1fr)}
    @media(min-width:900px){.grid-2{grid-template-columns:repeat(4,1fr)}}
    .card{background:var(--card);border:1px solid var(--line);border-radius:18px;padding:14px}
    .title{font-weight:700}
    .muted{color:var(--muted);font-size:12px}
    .kpi{font-size:22px;font-weight:800}
    .row{display:flex;gap:8px;align-items:center}
    .input{width:100%;border:1px solid var(--line);border-radius:12px;padding:10px 12px;background:#fff}
    table{width:100%;border-collapse:collapse}
    th,td{padding:10px;border-bottom:1px solid var(--line);font-size:14px;text-align:left}
    td.right{text-align:right}
    .bar{height:8px;background:#e7ebff;border-radius:999px;overflow:hidden}
    .bar>i{display:block;height:100%;background:linear-gradient(90deg,var(--accent),#22c55e)}
    nav{position:fixed;bottom:0;left:0;right:0;z-index:40;background:rgba(255,255,255,.96);backdrop-filter:blur(8px);border-top:1px solid var(--line)}
    .tabs{display:grid;grid-template-columns:repeat(4,1fr);gap:6px;padding:8px}
    .tab{padding:10px;border-radius:12px;text-align:center;color:var(--muted)}
    .tab.active{color:var(--text);font-weight:700;background:#eaf1ff}
    .safe{height:72px}
    .section{display:none}
    .section.active{display:block}
    .danger{color:var(--bad)} .success{color:var(--ok)}

    /* Splash overlay */
    #splash{position:fixed;inset:0;display:grid;place-items:center;background:radial-gradient(120% 120% at 30% 20%, #5aa0ff 0%, #0b5bff 60%, #031a66 100%);color:#fff;z-index:60}
    .splash-card{display:flex;flex-direction:column;align-items:center;gap:12px}
    .splash-logo{width:88px;height:88px;border-radius:24px;background:rgba(255,255,255,.1);display:grid;place-items:center;border:1px solid rgba(255,255,255,.2)}
    .fade-out{animation:fade .6s ease forwards}
    @keyframes fade{to{opacity:0;visibility:hidden}}

    /* Category editor pills */
    .pill{display:flex;align-items:center;gap:8px;border:1px solid var(--line);background:#fff;border-radius:12px;padding:6px 8px}
    .pill input{border:none;outline:none;width:100%}
    .icon-btn{width:28px;height:28px;border-radius:8px;border:1px solid var(--line);display:grid;place-items:center;background:#fff}
    .icon-btn:active{transform:translateY(1px)}
  </style>
</head>
<body>
  <!-- Splash screen marketing minimal -->
  <div id="splash">
    <div class="splash-card">
      <div class="splash-logo">
        <svg viewBox="0 0 64 64" width="44" height="44" fill="none">
          <circle cx="32" cy="32" r="28" stroke="white" stroke-opacity=".35" stroke-width="2"/>
          <path d="M18 36c3.5 6 10 10 17 10 7.7 0 14-6.3 14-14S42.7 18 35 18c-4.7 0-8.9 2.3-11.5 5.9" stroke="white" stroke-width="4" stroke-linecap="round"/>
          <path d="M22 28h16M22 34h12" stroke="#91c1ff" stroke-width="4" stroke-linecap="round"/>
        </svg>
      </div>
      <div style="font-weight:800;font-size:20px;letter-spacing:.3px">Financy</div>
      <div style="opacity:.9">Controllo chiaro • Scelte migliori</div>
    </div>
  </div>

  <header>
    <div class="wrap brand">
      <div class="logo" title="Financy">
        <!-- Monogramma unico: F/euro stilizzato -->
        <svg viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2.2" stroke-linecap="round">
          <path d="M6 8h9"/>
          <path d="M6 12h7"/>
          <path d="M16.5 5.5c-3-1.2-7 .8-8 4.5-1.2 4.2 2 8.5 6.4 8.5 2.4 0 4.1-1.1 5.1-2.5" stroke-opacity=".9"/>
        </svg>
      </div>
      <div>
        <div class="title">Financy</div>
        <div class="muted">Semplice • Intuitiva • Offline</div>
      </div>
      <div class="chips">
        <button id="btnExport" class="btn" title="Esporta dati">Esporta</button>
        <label class="btn" title="Importa dati"><input id="fileImport" type="file" accept="application/json" hidden>Importa</label>
      </div>
    </div>
  </header>

  <main class="wrap">
    <!-- DASHBOARD -->
    <section id="dash" class="section active">
      <div class="grid grid-2">
        <div class="card">
          <div class="muted">Mese attivo</div>
          <div class="row" style="margin-top:6px">
            <select id="activeMonth" class="input"></select>
            <select id="activeYear" class="input" style="max-width:120px"></select>
          </div>
        </div>
        <div class="card"><div class="muted">Entrate mese</div><div id="kpiIncome" class="kpi">€0</div></div>
        <div class="card"><div class="muted">Uscite mese</div><div id="kpiExpense" class="kpi">€0</div></div>
        <div class="card"><div class="muted">Saldo mese</div><div id="kpiBalance" class="kpi">€0</div></div>
      </div>
      <div class="grid" style="margin-top:12px">
        <div class="card">
          <div class="title" style="margin-bottom:8px">Spese per categoria (mese)</div>
          <div id="catList" class="grid" style="grid-template-columns:1fr;gap:10px"></div>
        </div>
      </div>
    </section>

    <!-- TRANSAZIONI -->
    <section id="tx" class="section">
      <div class="card">
        <div class="title">Aggiungi movimento</div>
        <div class="grid" style="grid-template-columns:repeat(2,1fr);gap:10px;margin-top:10px">
          <div><div class="muted">Data</div><input id="txDate" type="date" class="input"></div>
          <div><div class="muted">Tipo</div><select id="txType" class="input"><option>Entrata</option><option>Uscita</option></select></div>
          <div><div class="muted">Categoria</div><select id="txCategory" class="input"></select></div>
          <div><div class="muted">Importo</div><input id="txAmount" type="number" inputmode="decimal" min="0" step="0.01" class="input" placeholder="0,00"></div>
          <div style="grid-column:1/-1"><div class="muted">Note</div><input id="txNote" class="input" placeholder="(opzionale)"></div>
          <div class="row" style="grid-column:1/-1;gap:10px"><button id="btnAdd" class="btn btn-primary">Aggiungi</button><button id="btnClear" class="btn">Pulisci</button></div>
        </div>
      </div>
      <div class="card" style="margin-top:12px">
        <div class="row" style="justify-content:space-between">
          <div class="title">Movimenti</div>
          <div class="row"><input id="searchTx" class="input" placeholder="Cerca…" style="max-width:200px"><select id="filterType" class="input" style="max-width:140px"><option value="">Tutti</option><option>Entrata</option><option>Uscita</option></select></div>
        </div>
        <div style="overflow:auto;margin-top:6px">
          <table>
            <thead><tr class="muted"><th>Data</th><th>Tipo</th><th>Categoria</th><th class="right">Importo</th><th>Note</th><th class="right">Azioni</th></tr></thead>
            <tbody id="txTable"></tbody>
          </table>
        </div>
      </div>
    </section>

    <!-- BUDGET -->
    <section id="budget" class="section">
      <div class="card">
        <div class="row" style="justify-content:space-between">
          <div class="title">Budget — <span id="budgetMonthLabel"></span></div>
          <button id="btnResetBudget" class="btn">Azzera budget</button>
        </div>
        <div id="budgetList" class="grid" style="grid-template-columns:1fr 1fr; gap:10px; margin-top:10px"></div>
      </div>
    </section>

    <!-- IMPOSTAZIONI -->
    <section id="settings" class="section">
      <div class="card">
        <div class="title">Preferenze</div>
        <div class="grid" style="grid-template-columns:1fr 1fr;gap:10px;margin-top:10px">
          <div><div class="muted">Valuta</div><select id="currency" class="input"><option value="EUR">Euro (€)</option><option value="USD">Dollaro ($)</option><option value="GBP">Sterlina (£)</option><option value="CHF">Franco (CHF)</option></select></div>
          <div>
            <div class="muted">Categorie</div>
            <div id="categoriesEditor" class="grid" style="grid-template-columns:1fr;gap:8px"></div>
            <div class="row" style="margin-top:8px"><button id="btnAddCategory" class="btn">+ Aggiungi categoria</button></div>
          </div>
        </div>
        <div class="row" style="gap:10px;margin-top:10px"><button id="btnSaveSettings" class="btn btn-primary">Salva impostazioni</button><button id="btnResetAll" class="btn danger" style="border-color:#fecaca;color:#b91c1c">Reset totale</button></div>
      </div>
      <div class="card" style="margin-top:12px"><div class="title">Backup</div><div class="muted" style="margin-top:6px">Usa Esporta/Importa (in alto) per salvare o ripristinare tutti i dati.</div></div>
    </section>
  </main>

  <nav>
    <div class="wrap tabs">
      <button class="tab active" data-tab="dash">Dashboard</button>
      <button class="tab" data-tab="tx">Transazioni</button>
      <button class="tab" data-tab="budget">Budget</button>
      <button class="tab" data-tab="settings">Impostazioni</button>
    </div>
  </nav>
  <div class="safe"></div>

  <script>
  // ---------------------- STORAGE ----------------------
  const STORE_KEY = 'financy_state_v2';
  const defaultState = () => ({
    currency:'EUR',
    categories:['Casa','Spesa alimentare','Ristoranti','Trasporti','Auto','Salute','Abbonamenti','Tempo libero','Regali/Donazioni','Bollette/Utenze','Istruzione/Formazione','Lavoro','Vacanze/Viaggi','Figli/Famiglia','Altro'],
    transactions:[], // {id,date,type,category,amount,note}
    budgets:{},      // {'YYYY-MM': {'Categoria':number}}
    activeMonth: new Date().toLocaleString('it-IT',{month:'long'}),
    activeYear: new Date().getFullYear()
  });
  let state = load();
  function load(){ try{ return JSON.parse(localStorage.getItem(STORE_KEY)) || defaultState(); }catch(e){ return defaultState(); } }
  function save(){ localStorage.setItem(STORE_KEY, JSON.stringify(state)); }

  // ---------------------- UTIL ----------------------
  const $ = id=>document.getElementById(id);
  function monthKey(y, name){ const months=['gennaio','febbraio','marzo','aprile','maggio','giugno','luglio','agosto','settembre','ottobre','novembre','dicembre']; const i=months.indexOf((name||'').toLowerCase()); return `${y}-${String(i+1).padStart(2,'0')}`; }
  function uid(){ return Math.random().toString(36).slice(2,9); }
  function money(v){ return new Intl.NumberFormat('it-IT',{style:'currency',currency:state.currency}).format(v||0); }

  // ---------------------- INIT ----------------------
  function initSelectors(){
    const months=['Gennaio','Febbraio','Marzo','Aprile','Maggio','Giugno','Luglio','Agosto','Settembre','Ottobre','Novembre','Dicembre'];
    $('activeMonth').innerHTML = months.map(m=>`<option ${m===state.activeMonth?'selected':''}>${m}</option>`).join('');
    const y = new Date().getFullYear();
    $('activeYear').innerHTML = Array.from({length:5},(_,k)=>y-3+k).map(Y=>`<option ${Y===state.activeYear?'selected':''}>${Y}</option>`).join('');
    $('txCategory').innerHTML = state.categories.map(c=>`<option>${c}</option>`).join('');
    $('currency').value = state.currency;
    $('budgetMonthLabel').textContent = `${state.activeMonth} ${state.activeYear}`;
    renderCategoriesEditor();
  }

  // ---------------------- KPI + CATEGORY LIST ----------------------
  function monthTotals(){ const key=monthKey(state.activeYear,state.activeMonth); let inc=0,exp=0; state.transactions.forEach(t=>{ const d=new Date(t.date); const k=`${d.getFullYear()}-${String(d.getMonth()+1).padStart(2,'0')}`; if(k===key){ if(t.type==='Entrata') inc+=t.amount; else exp+=t.amount; }}); return {inc,exp,bal:inc-exp}; }
  function renderKPI(){ const {inc,exp,bal}=monthTotals(); $('kpiIncome').textContent=money(inc); $('kpiExpense').textContent=money(exp); $('kpiBalance').textContent=money(bal); }
  function spendByCategory(){ const key=monthKey(state.activeYear,state.activeMonth); const m=Object.fromEntries(state.categories.map(c=>[c,0])); state.transactions.forEach(t=>{ const d=new Date(t.date); const k=`${d.getFullYear()}-${String(d.getMonth()+1).padStart(2,'0')}`; if(k===key && t.type==='Uscita') m[t.category]=(m[t.category]||0)+t.amount; }); return m; }
  function renderCatList(){ const wrap=$('catList'); const m=spendByCategory(); wrap.innerHTML = state.categories.map(cat=>{ const v=m[cat]||0; const b=(state.budgets[monthKey(state.activeYear,state.activeMonth)]||{})[cat]||0; const p=b>0? Math.min(100, Math.round((v/b)*100)): 0; const ok=b===0? '#94a3b8': (v<=b? '#10b981':'#ef4444'); return `<div><div class="row" style="justify-content:space-between"><div>${cat}</div><div class="muted">${money(v)}${b? ' / '+money(b):''}</div></div><div class="bar" style="margin-top:6px"><i style="width:${p}%;background:${ok}"></i></div></div>`; }).join(''); }

  // ---------------------- TX TABLE ----------------------
  function renderTx(){ const q=($('searchTx').value||'').toLowerCase(); const ft=$('filterType').value; const cur = new Intl.NumberFormat('it-IT',{style:'currency',currency:state.currency}); const rows = state.transactions.filter(t=>!ft||t.type===ft).filter(t=>`${t.category} ${t.note||''}`.toLowerCase().includes(q)).sort((a,b)=>new Date(b.date)-new Date(a.date)); $('txTable').innerHTML = rows.map(t=>`<tr><td>${new Date(t.date).toLocaleDateString('it-IT')}</td><td>${t.type}</td><td>${t.category}</td><td class='right'>${cur.format(t.amount)}</td><td>${t.note||''}</td><td class='right'><button class='btn' onclick="editTx('${t.id}')">Modifica</button> <button class='btn' onclick="delTx('${t.id}')">Elimina</button></td></tr>`).join(''); }

  function addTx(){ const date=$('txDate').value; const amount=parseFloat($('txAmount').value||'0'); if(!date||!amount||amount<0) return; const tx={id:uid(),date,type:$('txType').value,category:$('txCategory').value,amount,note:$('txNote').value.trim()}; state.transactions.push(tx); save(); clearTx(); renderAll(); }
  function clearTx(){ $('txDate').value=''; $('txType').value='Entrata'; $('txCategory').selectedIndex=0; $('txAmount').value=''; $('txNote').value=''; }
  function editTx(id){ const t=state.transactions.find(x=>x.id===id); if(!t) return; $('txDate').value=t.date.slice(0,10); $('txType').value=t.type; $('txCategory').value=t.category; $('txAmount').value=t.amount; $('txNote').value=t.note||''; delTx(id); }
  function delTx(id){ state.transactions = state.transactions.filter(t=>t.id!==id); save(); renderAll(); }

  // ---------------------- BUDGET ----------------------
  function renderBudget(){ const wrap=$('budgetList'); const key=monthKey(state.activeYear,state.activeMonth); const spent=spendByCategory(); const monthBudget=state.budgets[key]||{}; wrap.innerHTML = state.categories.map(cat=>{ const b=monthBudget[cat]||0; const s=spent[cat]||0; const diff=b-s; const p=b>0? Math.min(100, Math.round((s/b)*100)):0; const col= diff>=0? 'linear-gradient(90deg,#22c55e,#0b5bff)' : '#ef4444'; return `<div class='card'><div class='row' style='justify-content:space-between'><b>${cat}</b><span class='muted'>${money(s)} / ${money(b)}</span></div><div class='bar' style='margin-top:6px'><i style='width:${p}%;background:${col}'></i></div><div class='row' style='gap:8px;margin-top:6px'><input type='number' step='0.01' min='0' class='input' value='${b}' oninput="setBudget('${cat}', this.value)"><div class='muted' style='margin-left:auto'>Diff: <b class='${diff>=0?'success':'danger'}'>${money(diff)}</b></div></div></div>`; }).join(''); }
  function setBudget(cat,val){ const key=monthKey(state.activeYear,state.activeMonth); state.budgets[key]=state.budgets[key]||{}; state.budgets[key][cat]=parseFloat(val||'0')||0; save(); renderBudget(); renderKPI(); }

  // ---------------------- SETTINGS (Categorie editor) ----------------------
  function renderCategoriesEditor(){ const box=$('categoriesEditor'); box.innerHTML = state.categories.map((c,i)=>`<div class='pill'><input value="${c}" oninput="updateCategory(${i}, this.value)"/><button class='icon-btn' title='Elimina' onclick='removeCategory(${i})'>−</button></div>`).join(''); }
  function addCategory(){ state.categories.push('Nuova categoria'); save(); renderCategoriesEditor(); initSelectors(); renderCatList(); }
  function removeCategory(i){ state.categories.splice(i,1); save(); renderCategoriesEditor(); initSelectors(); renderCatList(); }
  function updateCategory(i,val){ state.categories[i]=val.trim()||'Senza nome'; save(); initSelectors(); renderCatList(); }
  function saveSettings(){ state.currency=$('currency').value; save(); initSelectors(); renderAll(); }
  function resetAll(){ if(!confirm('Sicura/o? Cancellerai tutti i dati.')) return; state=defaultState(); save(); initSelectors(); renderAll(); }

  // ---------------------- EXPORT/IMPORT ----------------------
  function exportJSON(){ const blob=new Blob([JSON.stringify(state,null,2)],{type:'application/json'}); const url=URL.createObjectURL(blob); const a=document.createElement('a'); a.href=url; a.download='financy-data.json'; a.click(); URL.revokeObjectURL(url); }
  function importJSON(file){ const r=new FileReader(); r.onload=()=>{ try{ const data=JSON.parse(r.result); if(!data||!data.transactions) throw new Error(); state={...defaultState(),...data}; save(); initSelectors(); renderAll(); }catch(e){ alert('File non valido'); } }; r.readAsText(file); }

  // ---------------------- NAV ----------------------
  function show(tab){ ['dash','tx','budget','settings'].forEach(id=>{ document.getElementById(id).classList.toggle('active', id===tab); document.querySelector(`[data-tab="${id}"]`).classList.toggle('active', id===tab); }); if(tab==='budget') renderBudget(); if(tab==='dash') renderCatList(); }

  // ---------------------- BINDINGS ----------------------
  function bind(){
    $('btnAdd').onclick=addTx; $('btnClear').onclick=clearTx; $('searchTx').oninput=renderTx; $('filterType').onchange=renderTx;
    $('activeMonth').onchange=(e)=>{state.activeMonth=e.target.value; save(); initSelectors(); renderAll();};
    $('activeYear').onchange=(e)=>{state.activeYear=parseInt(e.target.value,10); save(); initSelectors(); renderAll();};
    $('btnResetBudget').onclick=()=>{state.budgets[monthKey(state.activeYear,state.activeMonth)] = {}; save(); renderBudget();};
    $('btnSaveSettings').onclick=saveSettings; $('btnResetAll').onclick=resetAll; $('btnExport').onclick=exportJSON; $('fileImport').onchange=(e)=> e.target.files[0] && importJSON(e.target.files[0]);
    document.querySelectorAll('[data-tab]').forEach(b=> b.onclick=()=> show(b.dataset.tab));
    $('btnAddCategory').onclick=addCategory;
  }

  // ---------------------- MANIFEST (dinamico, un solo file) ----------------------
  (function(){
    const iconPng = 'data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQAAAAEACAYAAABccqhmAAAACXBIWXMAAAsSAAALEgHS3X78AAAEsElEQVR4nO3awW3cQBRA0Y6iS6N1o4uA4gq2r8zR8o1C9Qn0v4O0i7w9W1o8o4wYzPp8NwAAALhJz3Cw9kqg3w9fUdqv9kNf8q8fAABwZx0N9s1g2mN6z6v3mQYkqg8V8bqgq5o9f8Vb8+zj2s3G5b8qB0v7u9m3b2x5T3vQ1v2q9s8Y3Huv1Xj8m6jXbqf8w6H0m2H2b7f2cJ8oH7Pp4v+qg0d9y5w9q6kS6h9K0f0p0s9G2b3b0r9Wc9Y7oYf3b0d9Ue8o9Qv0bNf9oQAAwKpZUI1bX5l+6gZb+QqGq9m2kqK9mWm4d6bHk9c6JrZb7Y8yJqf6b9+Wf0Z1o9r8wXx1sQ4rj2W4bqTq3pQqkqgGZpAqkqgGZpAqkqgGZpAqkqgGZpAoAAICb/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2Jg/2JgAABg6y1cH2vR9m2fG1+3G6r0cYj7d5S3j6e8v7sWcQAAwKk+Zf8y8uQkXw8AAAAASUVORK5CYII=';
    const manifest = {
      name: 'Financy — Budget mobile & desktop',
      short_name: 'Financy',
      start_url: './',
      display: 'standalone',
      background_color: '#0b5bff',
      theme_color: '#0b5bff',
      icons: [
        { src: iconPng, sizes: '192x192', type: 'image/png' },
        { src: iconPng, sizes: '512x512', type: 'image/png' }
      ]
    };
    const blob = new Blob([JSON.stringify(manifest)], {type:'application/manifest+json'});
    const url = URL.createObjectURL(blob);
    document.getElementById('manifestLink').setAttribute('href', url);
  })();

  // ---------------------- SERVICE WORKER (cache offline) ----------------------
  if('serviceWorker' in navigator){
    const swCode = `self.addEventListener('install',e=>{e.waitUntil((async()=>{const c=await caches.open('financy-cache-v2'); await c.addAll(['./']); self.skipWaiting();})())}); self.addEventListener('activate',e=>self.clients.claim()); self.addEventListener('fetch',e=>{e.respondWith((async()=>{const r=await caches.match(e.request); return r||fetch(e.request);} )())});`;
    const blob = new Blob([swCode], {type:'text/javascript'});
    const swUrl = URL.createObjectURL(blob);
    navigator.serviceWorker.register(swUrl);
  }

  // ---------------------- SPLASH FLOW ----------------------
  window.addEventListener('load', ()=>{
    setTimeout(()=>{ const s=document.getElementById('splash'); s.classList.add('fade-out'); setTimeout(()=> s.remove(), 600); }, 600);
  });

  // ---------------------- BOOT ----------------------
  function renderAll(){ renderKPI(); renderTx(); renderCatList(); renderBudget(); $('budgetMonthLabel').textContent = `${state.activeMonth} ${state.activeYear}`; }
  function bindGlobal(){ window.editTx = editTx; window.delTx = delTx; window.updateCategory = updateCategory; window.removeCategory = removeCategory; window.addCategory = addCategory; window.setBudget = setBudget; }
  initSelectors(); bind(); bindGlobal(); renderAll(); show('dash');
  </script>
</body>
</html>
