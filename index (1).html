<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Python Project Log</title>
<style>
  :root{
    --bg: #0f1613;
    --panel: #161f1b;
    --panel-2: #1c2622;
    --line: #2a3630;
    --line-strong: #3a4a42;
    --ink: #e8ede9;
    --ink-dim: #9caaa2;
    --ink-faint: #647169;
    --amber: #e0a94a;
    --amber-dim: #7a5f2c;
    --teal: #5fb89c;
    --teal-dim: #2c4a3f;
    --mono: 'JetBrains Mono', 'SF Mono', Consolas, monospace;
    --sans: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  }
  *{box-sizing:border-box;}
  body{
    margin:0; background:var(--bg); color:var(--ink);
    font-family:var(--sans); line-height:1.5;
  }
  .wrap{max-width:980px; margin:0 auto; padding:48px 24px 100px;}

  /* header / terminal bar */
  .termbar{
    display:flex; align-items:center; gap:8px;
    background:var(--panel-2); border:1px solid var(--line);
    border-radius:8px 8px 0 0; padding:10px 14px;
  }
  .dot{width:10px;height:10px;border-radius:50%;}
  .dot.r{background:#e0665a;} .dot.y{background:#e0b85a;} .dot.g{background:#5ac97a;}
  .termbar span{font-family:var(--mono); font-size:12px; color:var(--ink-faint); margin-left:8px;}
  .terminal{
    background:var(--panel); border:1px solid var(--line); border-top:none;
    border-radius:0 0 8px 8px; padding:28px 32px; margin-bottom:36px;
  }
  .terminal .prompt{font-family:var(--mono); color:var(--teal); font-size:14px;}
  h1{
    font-family:var(--mono); font-size:28px; font-weight:500; margin:10px 0 6px;
    color:var(--ink);
  }
  .sub{color:var(--ink-dim); font-size:15px; margin:0 0 18px; max-width:560px;}

  /* stats row */
  .stats{display:flex; gap:12px; flex-wrap:wrap;}
  .stat{
    background:var(--panel-2); border:1px solid var(--line); border-radius:6px;
    padding:10px 16px; min-width:110px;
  }
  .stat .n{font-family:var(--mono); font-size:22px; color:var(--amber);}
  .stat .l{font-size:11px; color:var(--ink-faint); text-transform:uppercase; letter-spacing:.06em;}

  /* controls */
  .controls{display:flex; gap:10px; flex-wrap:wrap; margin:32px 0 20px; align-items:center;}
  input[type=text]{
    flex:1; min-width:200px; background:var(--panel-2); border:1px solid var(--line);
    color:var(--ink); font-family:var(--mono); font-size:13px; padding:9px 12px; border-radius:6px;
  }
  input[type=text]:focus{outline:none; border-color:var(--teal);}
  select{
    background:var(--panel-2); border:1px solid var(--line); color:var(--ink);
    font-family:var(--mono); font-size:13px; padding:9px 10px; border-radius:6px;
  }
  .chip{
    font-family:var(--mono); font-size:12px; padding:7px 12px; border-radius:20px;
    border:1px solid var(--line); color:var(--ink-dim); cursor:pointer; background:transparent;
    white-space:nowrap;
  }
  .chip.active{border-color:var(--teal); color:var(--teal); background:var(--teal-dim);}

  /* category groups */
  .category{margin-bottom:8px;}
  .cat-head{
    display:flex; align-items:center; gap:10px; padding:14px 4px 10px;
    border-bottom:1px solid var(--line); cursor:pointer; user-select:none;
  }
  .cat-head h2{font-size:15px; font-weight:500; margin:0; font-family:var(--mono); color:var(--ink);}
  .cat-head .count{font-size:12px; color:var(--ink-faint); font-family:var(--mono);}
  .cat-head .chev{margin-left:auto; color:var(--ink-faint); font-family:var(--mono); font-size:12px;}
  .card-list{display:grid; grid-template-columns:1fr 1fr; gap:10px; padding:14px 4px 24px;}
  @media (max-width:640px){.card-list{grid-template-columns:1fr;}}

  .card{
    background:var(--panel-2); border:1px solid var(--line); border-radius:8px;
    padding:12px 14px; display:flex; gap:10px; align-items:flex-start;
  }
  .card.done{border-color:var(--teal-dim); background:rgba(95,184,156,0.06);}
  .card input[type=checkbox]{
    margin-top:3px; width:15px; height:15px; accent-color:var(--teal); cursor:pointer; flex-shrink:0;
  }
  .card .name{font-size:13.5px; color:var(--ink); font-weight:500;}
  .card.done .name{color:var(--teal); text-decoration:line-through; text-decoration-color:var(--teal-dim);}
  .card .diff{
    font-family:var(--mono); font-size:10px; padding:2px 6px; border-radius:4px;
    text-transform:uppercase; letter-spacing:.04em; margin-left:8px; display:inline-block;
  }
  .diff.beg{background:var(--teal-dim); color:var(--teal);}
  .diff.int{background:var(--amber-dim); color:var(--amber);}
  .diff.adv{background:#4a2c2c; color:#e08a7a;}

  /* showcase */
  .showcase-head{margin:56px 0 16px; padding-top:24px; border-top:1px solid var(--line);}
  .showcase-head h2{font-family:var(--mono); font-size:18px; margin:0 0 6px;}
  .showcase-head p{color:var(--ink-dim); font-size:13.5px; margin:0;}
  .showcase-empty{
    color:var(--ink-faint); font-size:13.5px; font-family:var(--mono);
    padding:24px; text-align:center; border:1px dashed var(--line); border-radius:8px; margin-top:14px;
  }
  .showcase-list{display:flex; flex-direction:column; gap:10px; margin-top:14px;}
  .show-item{
    background:var(--panel-2); border:1px solid var(--line); border-radius:8px;
    padding:12px 16px; display:flex; align-items:center; gap:12px;
  }
  .show-item .name{flex:1; font-size:14px; color:var(--ink);}
  .show-item input[type=url]{
    flex:1.4; background:var(--panel); border:1px solid var(--line); color:var(--teal);
    font-family:var(--mono); font-size:12px; padding:7px 10px; border-radius:5px;
  }
  .empty-list{color:var(--ink-faint); font-family:var(--mono); font-size:13px; padding:30px 4px; text-align:center;}
  .hidden{display:none !important;}
</style>
</head>
<body>
<div class="wrap">

  <div class="termbar">
    <div class="dot r"></div><div class="dot y"></div><div class="dot g"></div>
    <span>~/projects/python — log.py</span>
  </div>
  <div class="terminal">
    <div class="prompt">&gt;&gt;&gt; import portfolio</div>
    <h1>Python project log</h1>
    <p class="sub">A running list of Python projects to build. Check them off as you finish, then drop your GitHub link in the showcase below to build your portfolio piece by piece.</p>
    <div class="stats">
      <div class="stat"><div class="n" id="stat-done">0</div><div class="l">completed</div></div>
      <div class="stat"><div class="n" id="stat-total">0</div><div class="l">total ideas</div></div>
      <div class="stat"><div class="n" id="stat-pct">0%</div><div class="l">progress</div></div>
    </div>
  </div>

  <div class="controls">
    <input type="text" id="search" placeholder="search projects...">
    <select id="diff-filter">
      <option value="all">all levels</option>
      <option value="beg">beginner</option>
      <option value="int">intermediate</option>
      <option value="adv">advanced</option>
    </select>
    <button class="chip" id="show-toggle" data-mode="all">showing: all</button>
  </div>

  <div id="categories"></div>

  <div class="showcase-head">
    <h2>&gt;&gt;&gt; portfolio.showcase()</h2>
    <p>Finished projects with a link land here automatically — this is what you show recruiters.</p>
  </div>
  <div id="showcase"></div>

</div>

<script>
const DATA = [
{cat:"Automation & scripts", items:[
["File renamer (bulk rename by pattern)","beg"],
["Duplicate file finder","beg"],
["Folder organizer (sort files by type)","beg"],
["Auto image resizer / compressor","beg"],
["PDF merger and splitter","beg"],
["Password generator","beg"],
["Email sender bot (SMTP)","int"],
["Screenshot scheduler","int"],
["Auto-backup script to cloud folder","int"],
["Clipboard manager","int"],
["Desktop notification reminder app","int"],
["Web form auto-filler (Selenium)","int"],
["File watcher that triggers scripts on change","adv"],
["Automated report generator (PDF from data)","adv"],
["Cron-style task scheduler from scratch","adv"],
]},
{cat:"Games", items:[
["Number guessing game","beg"],
["Rock paper scissors","beg"],
["Hangman","beg"],
["Tic-tac-toe (2 player)","beg"],
["Text adventure / choose your own story","beg"],
["Memory matching game","beg"],
["Snake game (pygame)","int"],
["Tic-tac-toe with unbeatable AI (minimax)","int"],
["Connect 4","int"],
["2048 clone","int"],
["Simple platformer (pygame)","int"],
["Blackjack with betting","int"],
["Chess move validator","adv"],
["Multiplayer tic-tac-toe over sockets","adv"],
["Roguelike dungeon crawler","adv"],
["Physics-based pool/billiards sim","adv"],
]},
{cat:"Simulations", items:[
["Dice roll probability simulator","beg"],
["Coin flip streak simulator","beg"],
["Bouncing ball physics (turtle)","beg"],
["Traffic light controller sim","beg"],
["Elevator simulation","int"],
["Robot maze-solver simulation","int"],
["Conway's Game of Life","int"],
["Ecosystem predator-prey simulation","int"],
["Solar system orbit simulator","int"],
["Self-driving car in a 2D grid (rule-based)","int"],
["Traffic flow simulator (multi-lane)","adv"],
["Ant colony pathfinding simulation","adv"],
["Epidemic spread model (SIR)","adv"],
["Robot arm inverse kinematics sim","adv"],
["Warehouse robot pathing simulation","adv"],
]},
{cat:"Calendars & productivity", items:[
["Command-line calendar viewer","beg"],
["To-do list (terminal)","beg"],
["Countdown timer to a date","beg"],
["Pomodoro timer","beg"],
["Habit tracker (CLI)","beg"],
["Calendar app with GUI (tkinter)","int"],
["Event reminder with recurring events","int"],
["Meeting scheduler that finds free slots","int"],
["Shared calendar sync with Google Calendar API","adv"],
["Smart scheduler that auto-resolves conflicts","adv"],
]},
{cat:"Data & visualization", items:[
["Weather data fetcher + chart","beg"],
["CSV cleaner and summarizer","beg"],
["Personal expense tracker","beg"],
["Word frequency counter for a text file","beg"],
["COVID/stock data line chart (matplotlib)","beg"],
["Interactive dashboard (Streamlit)","int"],
["Sports stats scraper + visualizer","int"],
["Reddit/Twitter sentiment tracker","int"],
["Budget forecaster with charts","int"],
["Real-time stock price dashboard","adv"],
["Geospatial map of local data (folium)","adv"],
["Data pipeline: scrape, clean, store, visualize","adv"],
]},
{cat:"AI & machine learning", items:[
["Rock-paper-scissors AI that learns your patterns","beg"],
["Spam email classifier","beg"],
["Digit recognizer (MNIST)","beg"],
["Movie recommender (basic)","beg"],
["Sentiment analyzer for reviews","int"],
["Chatbot with rule-based responses","int"],
["Chatbot using an LLM API","int"],
["Image classifier (cats vs dogs)","int"],
["Handwriting-to-text OCR tool","int"],
["Music genre classifier","adv"],
["Face detection with webcam (OpenCV)","adv"],
["Self-driving car in a simulator (RL)","adv"],
["Custom neural net from scratch (no libraries)","adv"],
["Style transfer image generator","adv"],
]},
{cat:"Web & APIs", items:[
["Personal portfolio site (Flask)","beg"],
["Weather app using an API","beg"],
["URL shortener","beg"],
["Simple blog with Flask","int"],
["REST API for a to-do list","int"],
["Web scraper for price tracking","int"],
["Discord bot","int"],
["Twitter/X bot that posts on schedule","int"],
["Job listing aggregator","adv"],
["Full-stack app with auth (Flask/Django + DB)","adv"],
["Real-time chat app (websockets)","adv"],
]},
{cat:"CLI tools & utilities", items:[
["Unit converter","beg"],
["BMI / calorie calculator","beg"],
["Quiz game from a question file","beg"],
["Text-based encryption/decryption tool (Caesar cipher)","beg"],
["Markdown to HTML converter","int"],
["Command-line password manager","int"],
["Log file analyzer","int"],
["Custom shell (mini command interpreter)","adv"],
["Static site generator","adv"],
["Package dependency resolver","adv"],
]},
{cat:"Math & algorithms", items:[
["Prime number generator","beg"],
["Fibonacci sequence visualizer","beg"],
["Sorting algorithm visualizer","int"],
["Pathfinding visualizer (A*, Dijkstra)","int"],
["Sudoku solver","int"],
["Maze generator + solver","int"],
["N-queens solver","int"],
["Fractal generator (Mandelbrot set)","adv"],
["Genetic algorithm to solve a puzzle","adv"],
["Neural network trained on custom data","adv"],
]},
];

let idCounter = 0;
DATA.forEach(cat => cat.items.forEach(item => { item.push('p'+(idCounter++)); }));

const state = { done:{}, links:{}, search:'', diff:'all', mode:'all' };

async function loadState(){
  try{
    const r = await window.storage.get('py-portfolio-state', false);
    if(r && r.value){ const parsed = JSON.parse(r.value); state.done = parsed.done||{}; state.links = parsed.links||{}; }
  }catch(e){}
  render();
  renderShowcase();
}
async function saveState(){
  try{ await window.storage.set('py-portfolio-state', JSON.stringify({done:state.done, links:state.links}), false); }catch(e){}
}

function totalCount(){ return DATA.reduce((a,c)=>a+c.items.length,0); }
function doneCount(){ return Object.values(state.done).filter(Boolean).length; }

function matches(name, diff){
  if(state.diff!=='all' && diff!==state.diff) return false;
  if(state.search && !name.toLowerCase().includes(state.search.toLowerCase())) return false;
  if(state.mode==='done' && !state.done[nameToId(name)]) return false;
  if(state.mode==='todo' && state.done[nameToId(name)]) return false;
  return true;
}
const idMap = {};
function nameToId(name){ return idMap[name]; }

function render(){
  const wrap = document.getElementById('categories');
  wrap.innerHTML = '';
  DATA.forEach(cat=>{
    const visible = cat.items.filter(([name,diff,id])=>{ idMap[name]=id; return matches(name,diff); });
    if(visible.length===0) return;
    const catDiv = document.createElement('div');
    catDiv.className='category';
    const doneInCat = cat.items.filter(([n,d,id])=>state.done[id]).length;
    catDiv.innerHTML = `<div class="cat-head"><h2>${cat.cat}</h2><span class="count">${doneInCat}/${cat.items.length}</span></div>`;
    const list = document.createElement('div');
    list.className='card-list';
    visible.forEach(([name,diff,id])=>{
      const card = document.createElement('div');
      card.className = 'card'+(state.done[id]?' done':'');
      const diffLabel = diff==='beg'?'beginner':diff==='int'?'intermediate':'advanced';
      card.innerHTML = `<input type="checkbox" data-id="${id}" ${state.done[id]?'checked':''}>
        <div><span class="name">${name}</span><span class="diff ${diff}">${diffLabel}</span></div>`;
      list.appendChild(card);
    });
    catDiv.appendChild(list);
    wrap.appendChild(catDiv);
  });

  wrap.querySelectorAll('input[type=checkbox]').forEach(cb=>{
    cb.addEventListener('change', e=>{
      const id = e.target.dataset.id;
      state.done[id] = e.target.checked;
      saveState();
      render();
      renderShowcase();
    });
  });

  document.getElementById('stat-done').textContent = doneCount();
  document.getElementById('stat-total').textContent = totalCount();
  document.getElementById('stat-pct').textContent = Math.round(100*doneCount()/totalCount())+'%';

  if(wrap.children.length===0){
    wrap.innerHTML = '<div class="empty-list">no projects match your filters</div>';
  }
}

function renderShowcase(){
  const box = document.getElementById('showcase');
  box.innerHTML='';
  const doneItems = [];
  DATA.forEach(cat=>cat.items.forEach(([name,diff,id])=>{ if(state.done[id]) doneItems.push({name,id}); }));
  if(doneItems.length===0){
    box.innerHTML = '<div class="showcase-empty">Nothing checked off yet. Finish a project above and it will show up here.</div>';
    return;
  }
  const list = document.createElement('div');
  list.className='showcase-list';
  doneItems.forEach(({name,id})=>{
    const row = document.createElement('div');
    row.className='show-item';
    row.innerHTML = `<span class="name">${name}</span>
      <input type="url" placeholder="github.com/you/project-repo" data-link="${id}" value="${state.links[id]||''}">`;
    list.appendChild(row);
  });
  box.appendChild(list);

  box.querySelectorAll('input[type=url]').forEach(inp=>{
    inp.addEventListener('input', e=>{
      state.links[e.target.dataset.link] = e.target.value;
      saveState();
    });
  });
}

document.getElementById('search').addEventListener('input', e=>{ state.search=e.target.value; render(); });
document.getElementById('diff-filter').addEventListener('change', e=>{ state.diff=e.target.value; render(); });
document.getElementById('show-toggle').addEventListener('click', e=>{
  const modes=['all','todo','done'];
  const next = modes[(modes.indexOf(state.mode)+1)%modes.length];
  state.mode = next;
  e.target.textContent = 'showing: '+next;
  render();
});

loadState();
</script>
</body>
</html>
