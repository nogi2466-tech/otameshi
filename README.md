<!doctype html>
<html lang="ja"><head><script>window["__codeletBootstrap__"]=JSON.parse('{"A":"A","B":"20260814-05-a1b2e7b","C":{"Abril Fatface":"YACgEZbkUVE,0","Alfa Slab One":"YACgEYS9sJU,0","Anton":"YACgEcYqQ-A,0","Archivo":"YAHO2-t-jNE,0","Arial":"YAGyDvJ_4Ts,0","Bebas Neue":"YACgESME5ew,0","Bricolage Grotesque":"YAFyMcdwzpc,0","Canva Sans":"YAFLd8sKbwc,2","Caveat":"YALBs2ploWQ,0","Comic Sans MS":"YAHO2VMiyZo,0","Cormorant Garamond":"YAFdJhX-538,0","Courier New":"YAGzXiGs0_8,0","DM Sans":"YAD1aU3sLnI,0","DM Serif Display":"YAD1aYG82rc,0","Forum":"YACgEcnnqB4,0","Fraunces":"YAEul-FRQw4,0","Georgia":"YAGzXkO0pEM,0","Helvetica Neue":"YAFcf6CtJfI,0","Impact":"YAFcfnjI7Vk,0","Inter":"YAFdJvSyp_k,3","Iowan Old Style":"YAGNIFa8j9o,0","Jacques Francois":"YAHO2a5g66Q,0","JetBrains Mono":"YAFdJksXcAk,0","Libre Baskerville":"YACgEUFdPdA,0","Manrope":"YAHO2b2feC4,0","Merriweather":"YACgEXvHxxs,0","Montserrat":"YADLjI9qxTA,0","Nunito":"YACgEX8C5Gg,0","Oleo Script":"YACgEQQ14jI,0","Phantom Sans":"YAHO2E8Pb88,0","Playfair Display":"YACgEYmuCJE,0","Poppins":"YAFdJjbTu24,1","Press Start 2P":"YAFyGr-8pmQ,0","Quicksand":"YADWjpfPmdk,0","Raleway":"YACgEVg3xZg,0","Segoe UI":"YAHNdRD1Klw,0","Source Sans 3":"YAG4lO1Mj10,0","Spectral":"YAHO2rVUHIM,0","Times New Roman":"YAGzXW3gftg,0","Times":"YAGzXW3gftg,0","Ubuntu":"YACgERDU--Q,0","Work Sans":"YAGXhLOKv44,0","Yellowtail":"YACgEYG4kG4,0","ui-monospace":"YADlN8CFZ8Q,0","ui-sans-serif":"YACkoN-xg4g,0"}}');</script><script src="/_sdk/7949ff62d67710d5.telemetry_sdk.js" integrity="sha512-KIvXA82Di44YY/RH9/63A9MuTuavYgDFG8PfErJn7Wli4K0LAOk+coo/aPXk3+ZNL96nHh9VYD4PE+fLes+laQ=="></script>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>京王線デジタル時刻表</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.263.0/dist/umd/lucide.min.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&amp;display=swap" rel="stylesheet">
  <script>
tailwind.config={theme:{extend:{colors:{navy:'#0a1628','navy-light':'#132040','navy-card':'#1a2d50',accent:'#38bdf8'}}}}
</script>
  <style>
body{font-family:'DM Sans',sans-serif}
.tab-active{border-bottom:3px solid #38bdf8;color:#38bdf8}
.type-express{color:#ef4444}.bg-type-express{background:#ef4444;color:#fff}
.type-rapid-green{color:#22c55e}.bg-type-rapid-green{background:#22c55e;color:#fff}
.type-section-rapid{color:#eab308}.bg-type-section-rapid{background:#eab308;color:#000}
.type-kaisoku{color:#3b82f6}.bg-type-kaisoku{background:#3b82f6;color:#fff}
.type-local{color:#9ca3af}.bg-type-local{background:#6b7280;color:#fff}
.type-kaiso{color:#a0522d}.bg-type-kaiso{background:#8b4513;color:#fff}
.tt-grid{border-collapse:collapse;font-size:11px}
.tt-grid th,.tt-grid td{border:1px solid #1e3a5f;padding:2px 4px;text-align:center;min-width:44px}
.tt-grid th{background:#132040;position:sticky;top:0;z-index:2}
.tt-grid td.station-cell{text-align:left;position:sticky;left:0;background:#1a2d50;z-index:1;white-space:nowrap;min-width:70px}
.sub-tab-active{background:#38bdf8;color:#0a1628}
.stop-toggle{cursor:pointer;user-select:none;font-size:10px;padding:2px 6px;border-radius:4px}
.stop-toggle.active{background:#38bdf8;color:#0a1628}
.stop-toggle.inactive{background:#374151;color:#9ca3af}
::-webkit-scrollbar{width:6px;height:6px}
::-webkit-scrollbar-thumb{background:#38bdf8;border-radius:3px}
.pos-line{position:relative;margin-left:80px;border-left:3px solid #38bdf8}
.pos-station{position:relative;padding:8px 0 8px 20px}
.pos-station::before{content:'';position:absolute;left:-7px;top:50%;transform:translateY(-50%);width:11px;height:11px;border-radius:50%;background:#38bdf8;border:2px solid #0a1628}
.pos-station-name{position:absolute;left:-90px;top:50%;transform:translateY(-50%);width:75px;text-align:right;font-size:11px;color:#cbd5e1}
.pos-train-card{display:inline-flex;align-items:center;gap:4px;padding:2px 6px;border-radius:4px;font-size:10px;font-weight:700;margin:1px 0}
</style>
  <script src="/_sdk/eba18683f23e5798.resizing_sdk.js" type="text/javascript" integrity="sha512-E0UWUllhwPXaNJtjyTKXWKrIE+FruPfFpO4mRmMDP2LI+U9bOizy5npCq6xx/JyWcvSK7D3TFf2wFR2Mha9kbA=="></script>
 <script src="/_sdk/0e8d3a91e1c6f495.data_sdk.js" integrity="sha512-c00oDoGjsMgluCLLEyVl3suwEkgjOGGplVFbsilUoBg4aMKNmsL3mwsc9r0dPn95qiSZyjBousQXgROkAW7p/w=="></script></head>
 <body data-template-id="__page-root" class="min-h-screen text-gray-100" style="background: rgb(10, 22, 40);">
  <header data-template-id="header-section" class="canva-header sticky top-0 z-50 border-b border-navy-light" style="background: rgb(15, 29, 53);">
   <div class="max-w-7xl mx-auto px-4 py-3 flex items-center justify-between flex-wrap gap-2">
    <h1 data-template-id="app-title" class="canva-text text-xl font-bold" style="color: rgb(56, 189, 248); font-weight: 700; font-style: normal; font-size: 22px;">🚃 京王線デジタル時刻表</h1>
    <nav class="flex gap-1 overflow-x-auto" id="tab-nav"><button class="tab-btn tab-active px-3 py-2 text-sm font-medium whitespace-nowrap" data-tab="timetable">時刻表</button> <button class="tab-btn px-3 py-2 text-sm font-medium whitespace-nowrap text-gray-400" data-tab="train-info">列車情報</button> <button class="tab-btn px-3 py-2 text-sm font-medium whitespace-nowrap text-gray-400" data-tab="position">走行位置</button> <button class="tab-btn px-3 py-2 text-sm font-medium whitespace-nowrap text-gray-400" data-tab="settings">設定</button>
    </nav>
   </div>
  </header>
  <main class="max-w-7xl mx-auto px-4 py-4"><!-- 時刻表タブ -->
   <section id="panel-timetable" class="tab-panel">
    <p data-template-id="timetable-desc" class="canva-text text-sm mb-4" style="color: rgb(148, 163, 184); font-weight: 400; font-style: normal; font-size: 15px;">駅名を検索して時刻表を表示します。デフォルトは新宿・調布・稲城・東府中。現在時刻の前後1時間を表示します。</p>
    <div class="flex flex-wrap gap-2 mb-4"><input id="station-search" type="text" placeholder="駅名検索" class="bg-navy-card border border-navy-light rounded px-3 py-2 text-sm text-white placeholder-gray-500 w-40">
     <div class="flex rounded overflow-hidden border border-navy-light"><button id="btn-down" class="px-3 py-2 text-sm bg-accent text-navy font-medium">下り</button> <button id="btn-up" class="px-3 py-2 text-sm bg-navy-card text-gray-400">上り</button>
     </div>
     <div class="flex rounded overflow-hidden border border-navy-light"><button id="btn-weekday" class="px-3 py-2 text-sm bg-accent text-navy font-medium">平日</button> <button id="btn-holiday" class="px-3 py-2 text-sm bg-navy-card text-gray-400">土休日</button>
     </div>
    </div>
    <div id="timetable-content" class="overflow-auto" style="max-height:calc(70 * min(var(--vh,1vh),1vh))"></div>
   </section><!-- 列車情報タブ -->
   <section id="panel-train-info" class="tab-panel hidden">
    <p data-template-id="traininfo-desc" class="canva-text text-sm mb-4" style="color: rgb(148, 163, 184); font-weight: 400; font-style: normal; font-size: 15px;">列車番号を入力して停車駅・時刻・番線などの詳細情報を確認できます。</p>
    <div class="flex gap-2 mb-4"><input id="train-search" type="text" placeholder="列車番号を入力 (例: 1001K)" class="bg-navy-card border border-navy-light rounded px-3 py-2 text-sm text-white placeholder-gray-500 flex-1 max-w-xs"> <button id="btn-train-search" class="bg-accent text-navy px-4 py-2 rounded text-sm font-medium">検索</button>
    </div>
    <div id="train-info-result" class="mb-6"></div>
   </section><!-- 走行位置タブ -->
   <section id="panel-position" class="tab-panel hidden">
    <p data-template-id="position-desc" class="canva-text text-sm mb-4" style="color: rgb(148, 163, 184); font-weight: 400; font-style: normal; font-size: 15px;">登録した列車の走行位置をリアルタイム風に表示します。更新ボタンで再計算。</p>
    <div class="flex items-center gap-3 mb-4"><span id="current-time" class="text-accent font-mono text-lg"></span> <button id="btn-refresh" class="bg-accent text-navy px-3 py-2 rounded text-sm font-medium flex items-center gap-1"><i data-lucide="refresh-cw" style="width:14px;height:14px"></i> 更新</button>
    </div>
    <div id="position-content" class="overflow-y-auto" style="max-height:calc(68 * min(var(--vh,1vh),1vh))"></div>
   </section><!-- 設定タブ -->
   <section id="panel-settings" class="tab-panel hidden">
    <p data-template-id="settings-desc" class="canva-text text-sm mb-4" style="color: rgb(148, 163, 184); font-weight: 400; font-style: normal; font-size: 15px;">列車の追加・編集・削除、ダイヤ表の確認ができます。</p>
    <div class="flex gap-1 mb-4 border-b border-navy-light"><button class="sub-tab px-3 py-2 text-xs font-medium sub-tab-active rounded-t" data-sub="dia">ダイヤ表</button> <button class="sub-tab px-3 py-2 text-xs font-medium text-gray-400 rounded-t" data-sub="add">列車追加・編集</button> <button class="sub-tab px-3 py-2 text-xs font-medium text-gray-400 rounded-t" data-sub="list">列車一覧</button>
    </div>
    <div id="sub-dia" class="sub-panel">
     <div class="flex gap-2 mb-3"><button id="dia-down" class="px-2 py-1 text-xs bg-accent text-navy rounded font-medium">下り</button> <button id="dia-up" class="px-2 py-1 text-xs bg-navy-card text-gray-400 rounded">上り</button>
     </div>
     <div id="dia-table" class="overflow-auto" style="max-height:calc(60 * min(var(--vh,1vh),1vh))"></div>
    </div>
    <div id="sub-add" class="sub-panel hidden">
     <form id="add-train-form" class="space-y-3">
      <div class="grid grid-cols-1 sm:grid-cols-2 gap-2"><input id="new-train-num" type="text" placeholder="列車番号" class="bg-navy border border-navy-light rounded px-3 py-2 text-sm text-white placeholder-gray-500"> <input id="new-train-dest" type="text" placeholder="行先" class="bg-navy border border-navy-light rounded px-3 py-2 text-sm text-white placeholder-gray-500">
      </div>
      <div class="grid grid-cols-1 sm:grid-cols-3 gap-2"><select id="new-train-type" class="bg-navy border border-navy-light rounded px-3 py-2 text-sm text-white"> <option value="各駅停車">各駅停車</option><option value="快速">快速</option><option value="区間急行">区間急行</option><option value="急行">急行</option><option value="特急">特急</option><option value="回送">回送</option> </select> <select id="new-train-line" class="bg-navy border border-navy-light rounded px-3 py-2 text-sm text-white"> <option value="京王線">京王線</option><option value="高尾線">高尾線</option><option value="相模原線">相模原線</option> </select> <select id="new-train-dir" class="bg-navy border border-navy-light rounded px-3 py-2 text-sm text-white"> <option value="下り">下り</option><option value="上り">上り</option> </select>
      </div>
      <div>
       <button type="button" id="btn-gen-stops" class="text-accent text-xs underline">停車パターン自動生成</button>
      </div>
      <div id="stops-editor" class="space-y-1 max-h-64 overflow-y-auto"></div>
      <div class="flex gap-2 items-center"><button type="submit" class="bg-accent text-navy px-4 py-2 rounded text-sm font-bold ml-auto">登録</button>
      </div><input type="hidden" id="edit-id" value="">
     </form>
    </div>
    <div id="sub-list" class="sub-panel hidden">
     <div id="train-list-panel" class="space-y-2"></div>
    </div>
   </section>
  </main>
  <script src="/_sdk/a051f9537983733d.editing_sdk.js" integrity="sha512-IWn3eBHnVt7zQ0Rp79J72qSgJoLbskCA9lcfY4retf+5km4LjuhSHpvx+182KCHmEZ6EbJtWqVsybpV8Sd8PQQ=="></script>
  <script src="/_sdk/0e8d3a91e1c6f495.data_sdk.js" integrity="sha512-c00oDoGjsMgluCLLEyVl3suwEkgjOGGplVFbsilUoBg4aMKNmsL3mwsc9r0dPn95qiSZyjBousQXgROkAW7p/w=="></script>
  <script>
// === STATION DATA ===
const LINES={
'京王線':['新宿','初台','幡ヶ谷','笹塚','代田橋','明大前','下高井戸','桜上水','上北沢','八幡山','芦花公園','千歳烏山','仙川','つつじヶ丘','柴崎','国領','布田','調布','西調布','飛田給','武蔵野台','多磨霊園','東府中','府中','分倍河原','中河原','聖蹟桜ヶ丘','百草園','高幡不動','南平','平山城址公園','長沼','北野','京王八王子'],
'高尾線':['北野','京王片倉','山田','めじろ台','狭間','高尾','高尾山口'],
'相模原線':['調布','京王多摩川','京王稲田堤','京王よみうりランド','稲城','若葉台','京王永山','京王多摩センター','京王堀之内','南大沢','多摩境','橋本']
};

const PRESETS={
'特急_京王線':['新宿','明大前','調布','府中','分倍河原','聖蹟桜ヶ丘','高幡不動','北野','京王八王子'],
'特急_高尾線':['北野','高尾','高尾山口'],
'特急_相模原線':['調布','京王永山','京王多摩センター','南大沢','橋本'],
'急行_京王線':['新宿','明大前','桜上水','千歳烏山','つつじヶ丘','調布','東府中','府中','分倍河原','聖蹟桜ヶ丘','高幡不動','北野','京王八王子'],
'急行_高尾線':['北野','京王片倉','山田','めじろ台','狭間','高尾','高尾山口'],
'急行_相模原線':['調布','京王稲田堤','京王永山','京王多摩センター','南大沢','橋本'],
'区間急行_京王線':['新宿','笹塚','明大前','桜上水','千歳烏山','仙川','つつじヶ丘','調布','西調布','飛田給','武蔵野台','多磨霊園','東府中','府中','分倍河原','中河原','聖蹟桜ヶ丘','百草園','高幡不動','南平','平山城址公園','長沼','北野','京王八王子'],
'区間急行_高尾線':['北野','京王片倉','山田','めじろ台','狭間','高尾','高尾山口'],
'区間急行_相模原線':['調布','京王多摩川','京王稲田堤','京王よみうりランド','稲城','若葉台','京王永山','京王多摩センター','京王堀之内','南大沢','多摩境','橋本'],
'快速_京王線':['新宿','笹塚','明大前','下高井戸','桜上水','八幡山','千歳烏山','仙川','つつじヶ丘','調布','東府中','府中','分倍河原','中河原','聖蹟桜ヶ丘','百草園','高幡不動','南平','平山城址公園','長沼','北野','京王八王子'],
'快速_高尾線':['北野','京王片倉','山田','めじろ台','狭間','高尾','高尾山口'],
'快速_相模原線':['調布','京王多摩川','京王稲田堤','京王よみうりランド','稲城','若葉台','京王永山','京王多摩センター','京王堀之内','南大沢','多摩境','橋本'],
};

function getAllStationsForLine(line){
  if(line==='京王線')return LINES['京王線'];
  if(line==='高尾線')return LINES['高尾線'];
  if(line==='相模原線')return LINES['相模原線'];
  return LINES['京王線'];
}

function getFullRoute(line){
  if(line==='京王線')return LINES['京王線'];
  if(line==='高尾線')return[...LINES['京王線'].slice(0,LINES['京王線'].indexOf('北野')+1),...LINES['高尾線'].slice(1)];
  if(line==='相模原線')return[...LINES['京王線'].slice(0,LINES['京王線'].indexOf('調布')+1),...LINES['相模原線'].slice(1)];
  return LINES['京王線'];
}

function getPresetStops(type,line){
  const key=type+'_'+line;
  if(PRESETS[key])return PRESETS[key];
  if(type==='各駅停車'||type==='回送')return getFullRoute(line);
  return getFullRoute(line);
}

function typeColorClass(t){
  if(t==='特急')return'type-express';
  if(t==='急行')return'type-rapid-green';
  if(t==='区間急行')return'type-section-rapid';
  if(t==='快速')return'type-kaisoku';
  if(t==='回送')return'type-kaiso';
  return'type-local';
}
function typeBgClass(t){
  if(t==='特急')return'bg-type-express';
  if(t==='急行')return'bg-type-rapid-green';
  if(t==='区間急行')return'bg-type-section-rapid';
  if(t==='快速')return'bg-type-kaisoku';
  if(t==='回送')return'bg-type-kaiso';
  return'bg-type-local';
}
function typeColor(t){
  if(t==='特急')return'#ef4444';
  if(t==='急行')return'#22c55e';
  if(t==='区間急行')return'#eab308';
  if(t==='快速')return'#3b82f6';
  if(t==='回送')return'#8b4513';
  return'#9ca3af';
}

// === STATE ===
let trains=[];
let dayType='weekday';
let direction='下り';
let diaDir='下り';
const DEFAULT_STATIONS=['新宿','調布','稲城','東府中'];
let selectedStation='';

// === TIMETABLE ===
function getCurrentHourRange(){
  const now=new Date();
  const h=now.getHours();
  return[h-1<0?0:h-1,h+1>23?23:h+1];
}

function genSampleForStation(station,dir){
  const types=['各駅停車','快速','区間急行','急行','特急'];
  const rows=[];
  const allSt=[];
  for(const[ln,sts]of Object.entries(LINES)){if(sts.includes(station))allSt.push(ln);}
  const idx=LINES['京王線'].indexOf(station);
  const off=idx>=0?idx*2:5;
  for(let h=0;h<24;h++){
    for(let m=0;m<60;m+=10){
      const t=types[(h*6+m/10)%5];
      let stops=false;
      for(const ln of allSt){const ps=getPresetStops(t,ln);if(ps.includes(station)){stops=true;break;}}
      if(!stops)continue;
      const mm=(m+off)%60;
      const dep=`${String(h).padStart(2,'0')}:${String(mm).padStart(2,'0')}`;
      let dest='京王八王子';
      if(allSt.includes('相模原線')&&!allSt.includes('京王線'))dest='橋本';
      if(allSt.includes('高尾線')&&!allSt.includes('京王線'))dest='高尾山口';
      if(dir==='上り')dest='新宿';
      rows.push({time:dep,type:t,dest,num:`${1000+h*10+m/10}K`});
    }
  }
  // Add user trains
  trains.forEach(tr=>{
    if(tr.direction!==dir)return;
    const stops=JSON.parse(tr.stops_json||'[]');
    const f=stops.find(s=>s.station===station);
    if(f)rows.push({time:f.depart||f.arrive||'??:??',type:tr.train_type,dest:tr.destination||'',num:tr.train_number});
  });
  rows.sort((a,b)=>a.time.localeCompare(b.time));
  return rows;
}

function renderTimetable(){
  const search=document.getElementById('station-search').value.trim();
  const container=document.getElementById('timetable-content');
  let stations=DEFAULT_STATIONS;
  if(search){
    const all=new Set();
    for(const sts of Object.values(LINES))for(const s of sts)all.add(s);
    stations=[...all].filter(s=>s.includes(search));
  }
  if(!stations.length){container.innerHTML='<p class="text-gray-500 text-center py-8">該当する駅がありません</p>';return;}

  const[hStart,hEnd]=getCurrentHourRange();

  let html='';
  stations.forEach(st=>{
    let rows=genSampleForStation(st,direction);
    rows=rows.filter(r=>{const h=parseInt(r.time.split(':')[0]);return h>=hStart&&h<=hEnd;});
    if(!rows.length){html+=`<div class="bg-navy-card rounded-lg p-3 mb-3"><h4 class="font-medium text-accent text-sm">${st}</h4><p class="text-gray-500 text-xs mt-1">この時間帯の列車はありません</p></div>`;return;}

    // Build spreadsheet-style grid: rows=stations concept but here we show per-station so columns=trains
    // Show as time grid: columns are trains, single row shows times
    // Actually for single station view: show as hour-grouped table with train details
    const byHour={};
    rows.forEach(r=>{const h=r.time.split(':')[0];if(!byHour[h])byHour[h]=[];byHour[h].push(r);});

    html+=`<div class="bg-navy-card rounded-lg p-3 mb-3">
      <h4 class="font-medium text-accent text-sm mb-2">${st}</h4>
      <table class="tt-grid w-full"><thead><tr><th class="!text-left !min-w-[30px]">時</th>`;
    // For spreadsheet look, list each train in the hour as a column... but variable count
    // Better: classic timetable format - hour | minutes with type colors
    html+=`<th class="!text-left">列車</th></tr></thead><tbody>`;
    Object.keys(byHour).sort().forEach(h=>{
      html+=`<tr><td class="station-cell font-mono text-gray-400">${h}</td><td class="!text-left"><div class="flex flex-wrap gap-1">`;
      byHour[h].forEach(r=>{
        const destChar=r.dest?r.dest[0]:'';
        html+=`<span class="relative inline-block text-center" style="min-width:28px"><span class="absolute -top-2 left-0 right-0 text-[8px] ${typeColorClass(r.type)}">${destChar}</span><span class="font-mono text-xs" style="color:${typeColor(r.type)}">${r.time.split(':')[1]}</span></span>`;
      });
      html+=`</div></td></tr>`;
    });
    html+=`</tbody></table></div>`;
  });
  container.innerHTML=html;
}

// === TRAIN INFO ===
function searchTrain(){
  const q=document.getElementById('train-search').value.trim();
  const result=document.getElementById('train-info-result');
  if(!q){result.innerHTML='<p class="text-gray-500">列車番号を入力してください</p>';return;}
  const found=trains.find(t=>t.train_number===q);
  if(!found){result.innerHTML='<p class="text-gray-500">該当する列車が見つかりません</p>';return;}
  const stops=JSON.parse(found.stops_json||'[]');
  result.innerHTML=`<div class="bg-navy-card rounded-lg p-4"><div class="flex items-center gap-3 mb-3 flex-wrap"><span class="px-2 py-1 rounded text-xs font-bold ${typeBgClass(found.train_type)}">${found.train_type}</span><span class="font-mono font-bold">${found.train_number}</span><span class="text-gray-400">→ ${found.destination||'未設定'}</span><span class="text-[10px] px-1.5 py-0.5 rounded bg-navy-light text-gray-300">${found.line||''} ${found.direction||''}</span></div><table class="w-full text-sm"><thead><tr class="text-gray-500 text-xs border-b border-navy-light"><th class="text-left py-1">駅</th><th class="text-center">着</th><th class="text-center">発</th><th class="text-center">番線</th></tr></thead><tbody>${stops.map(s=>`<tr class="border-b border-navy-light/50"><td class="py-1">${s.station}</td><td class="text-center font-mono text-xs">${s.arrive||'―'}</td><td class="text-center font-mono text-xs">${s.depart||'―'}</td><td class="text-center text-xs">${s.track||'―'}</td></tr>`).join('')}</tbody></table></div>`;
}

// === POSITION ===
function timeToMin(t){const p=(t||'0:0').split(':').map(Number);return p[0]*60+(p[1]||0);}
function timeToSec(t){const p=(t||'0:0:0').split(':').map(Number);return p[0]*3600+(p[1]||0)*60+(p[2]||0);}

function renderPosition(){
  const now=new Date();
  const nowSec=now.getHours()*3600+now.getMinutes()*60+now.getSeconds();
  document.getElementById('current-time').textContent=now.toLocaleTimeString('ja-JP');
  const container=document.getElementById('position-content');

  // Build combined station list for display
  const keioMain=LINES['京王線'];
  const sagami=LINES['相模原線'].slice(1);
  const takao=LINES['高尾線'].slice(1);

  // Vertical line layout
  let html='<div class="relative" style="padding-left:100px">';

  // Main line
  html+='<div class="text-[10px] text-gray-500 mb-1 ml-5">京王線</div>';
  html+='<div class="pos-line" id="pos-keio">';
  keioMain.forEach((st,i)=>{
    html+=`<div class="pos-station" data-station="${st}" data-line="京王線" data-idx="${i}"><span class="pos-station-name">${st}</span><div class="trains-here" data-st="${st}"></div>`;
    // Branch indicators
    if(st==='調布')html+=`<span class="text-[9px] text-gray-500 ml-2">↘ 相模原線</span>`;
    if(st==='北野')html+=`<span class="text-[9px] text-gray-500 ml-2">↘ 高尾線</span>`;
    html+=`</div>`;
  });
  html+='</div>';

  // Sagamihara line
  html+='<div class="text-[10px] text-gray-500 mb-1 ml-5 mt-4">相模原線</div>';
  html+='<div class="pos-line" id="pos-sagami">';
  sagami.forEach((st,i)=>{
    html+=`<div class="pos-station" data-station="${st}" data-line="相模原線" data-idx="${i}"><span class="pos-station-name">${st}</span><div class="trains-here" data-st="${st}"></div></div>`;
  });
  html+='</div>';

  // Takao line
  html+='<div class="text-[10px] text-gray-500 mb-1 ml-5 mt-4">高尾線</div>';
  html+='<div class="pos-line" id="pos-takao">';
  takao.forEach((st,i)=>{
    html+=`<div class="pos-station" data-station="${st}" data-line="高尾線" data-idx="${i}"><span class="pos-station-name">${st}</span><div class="trains-here" data-st="${st}"></div></div>`;
  });
  html+='</div></div>';

  container.innerHTML=html;

  // Place trains
  trains.forEach(tr=>{
    const stops=JSON.parse(tr.stops_json||'[]');
    if(stops.length<2)return;
    const firstSec=timeToSec(stops[0].depart||stops[0].arrive||'');
    const lastSec=timeToSec(stops[stops.length-1].arrive||stops[stops.length-1].depart||'');
    if(!firstSec&&!lastSec)return;
    if(nowSec<firstSec-30||nowSec>lastSec+30)return;

    // Find current position
    let currentSt='';
    let status='';
    for(let i=0;i<stops.length;i++){
      const arr=timeToSec(stops[i].arrive||stops[i].depart||'');
      const dep=timeToSec(stops[i].depart||stops[i].arrive||'');
      const nextArr=i<stops.length-1?timeToSec(stops[i+1].arrive||stops[i+1].depart||''):dep;
      if(nowSec>=arr-30&&nowSec<=dep){currentSt=stops[i].station;status='停車中';break;}
      if(nowSec>dep&&nowSec<nextArr-30){currentSt=stops[i].station;status='→';break;}
      if(i<stops.length-1&&nowSec>=nextArr-30&&nowSec<nextArr){currentSt=stops[i+1].station;status='到着';break;}
    }
    if(!currentSt&&nowSec>=lastSec&&nowSec<=lastSec+30){currentSt=stops[stops.length-1].station;status='終着';}
    if(!currentSt)return;

    const arrow=tr.direction==='下り'?'▼':'▲';
    const card=`<div class="pos-train-card" style="background:${typeColor(tr.train_type)}20;border:1px solid ${typeColor(tr.train_type)}"><span style="color:${typeColor(tr.train_type)}">${arrow}</span><span style="color:${typeColor(tr.train_type)}">${tr.train_number}</span><span class="text-gray-300 text-[9px]">${tr.destination||''}</span></div>`;

    const el=container.querySelector(`[data-st="${currentSt}"]`);
    if(el)el.insertAdjacentHTML('beforeend',card);
  });
}

// === SETTINGS: DIA TABLE ===
function renderDiaTable(){
  const c=document.getElementById('dia-table');
  const filtered=trains.filter(t=>(t.direction||'下り')===diaDir);
  if(!filtered.length){c.innerHTML='<p class="text-gray-500 text-sm py-4">登録された列車がありません</p>';return;}
  const sorted=[...filtered].sort((a,b)=>{
    const sa=JSON.parse(a.stops_json||'[]');const sb=JSON.parse(b.stops_json||'[]');
    return(sa[0]?.depart||sa[0]?.arrive||'99:99').localeCompare(sb[0]?.depart||sb[0]?.arrive||'99:99');
  });

  // Collect all stations
  const allStations=new Set();
  sorted.forEach(tr=>{JSON.parse(tr.stops_json||'[]').forEach(s=>allStations.add(s.station));});
  let stList=[...allStations];
  // Order by line
  const order=[];const seen=new Set();
  [...LINES['京王線'],...LINES['高尾線'],...LINES['相模原線']].forEach(s=>{if(!seen.has(s)){seen.add(s);if(allStations.has(s))order.push(s);}});
  stList=diaDir==='上り'?[...order].reverse():order;

  let html=`<table class="tt-grid"><thead><tr><th class="!text-left">駅</th>`;
  sorted.forEach(tr=>{html+=`<th><span class="text-[9px] ${typeBgClass(tr.train_type)} px-1 rounded">${tr.train_type[0]}</span><br><span class="text-[9px] font-mono">${tr.train_number}</span></th>`;});
  html+=`</tr></thead><tbody>`;
  stList.forEach(st=>{
    html+=`<tr><td class="station-cell">${st}</td>`;
    sorted.forEach(tr=>{
      const stops=JSON.parse(tr.stops_json||'[]');
      const f=stops.find(s=>s.station===st);
      if(f){
        const t=f.depart||f.arrive||'';
        html+=`<td class="font-mono" style="color:${typeColor(tr.train_type)}">${t?t.slice(-5):''}</td>`;
      }else{html+=`<td></td>`;}
    });
    html+=`</tr>`;
  });
  html+=`</tbody></table>`;
  c.innerHTML=html;
}

// === TRAIN LIST ===
function renderTrainList(){
  const c=document.getElementById('train-list-panel');
  if(!trains.length){c.innerHTML='<p class="text-gray-500 text-sm py-4">登録されている列車はありません</p>';return;}
  c.innerHTML=trains.map(tr=>`<div class="bg-navy-card rounded p-2 flex items-center justify-between gap-2 flex-wrap"><div class="flex items-center gap-2"><span class="px-1.5 py-0.5 rounded text-[10px] font-bold ${typeBgClass(tr.train_type)}">${tr.train_type}</span><span class="font-mono text-sm">${tr.train_number}</span><span class="text-gray-400 text-xs">→ ${tr.destination||'未設定'}</span><span class="text-[10px] text-gray-500">${tr.line||''} ${tr.direction||''}</span></div><div class="flex gap-2"><button class="text-accent text-xs hover:underline" onclick="editTrain('${tr.__backendId}')">編集</button><button class="text-red-400 text-xs hover:underline" onclick="deleteTrain('${tr.__backendId}')">削除</button></div></div>`).join('');
}

// === STOPS EDITOR ===
let currentStops=[];

function renderStopsEditor(){
  const c=document.getElementById('stops-editor');
  const dir=document.getElementById('new-train-dir').value;
  const display=dir==='上り'?[...currentStops].reverse():currentStops;
  c.innerHTML=display.map((s,i)=>{
    const realIdx=dir==='上り'?currentStops.length-1-i:i;
    return`<div class="grid grid-cols-5 gap-1 items-center"><span class="text-xs truncate ${s.active?'text-white':'text-gray-500'}">${s.station}</span><button type="button" class="stop-toggle ${s.active?'active':'inactive'}" onclick="toggleStop(${realIdx})">${s.active?'停車':'通過'}</button><input type="text" value="${s.arrive||''}" placeholder="着" class="bg-navy border border-navy-light rounded px-1 py-0.5 text-[11px] text-white placeholder-gray-500 ${s.active?'':'opacity-30'}" data-ridx="${realIdx}" data-field="arrive" ${s.active?'':'disabled'}><input type="text" value="${s.depart||''}" placeholder="発" class="bg-navy border border-navy-light rounded px-1 py-0.5 text-[11px] text-white placeholder-gray-500 ${s.active?'':'opacity-30'}" data-ridx="${realIdx}" data-field="depart" ${s.active?'':'disabled'}><input type="text" value="${s.track||''}" placeholder="番線" class="bg-navy border border-navy-light rounded px-1 py-0.5 text-[11px] text-white placeholder-gray-500 ${s.active?'':'opacity-30'}" data-ridx="${realIdx}" data-field="track" ${s.active?'':'disabled'}></div>`;
  }).join('');
}

window.toggleStop=function(idx){currentStops[idx].active=!currentStops[idx].active;renderStopsEditor();};

function generateStops(){
  const type=document.getElementById('new-train-type').value;
  const line=document.getElementById('new-train-line').value;
  const allStations=getFullRoute(line);
  const preset=getPresetStops(type,line);
  currentStops=allStations.map(st=>({station:st,active:preset.includes(st),arrive:'',depart:'',track:''}));
  renderStopsEditor();
}

document.getElementById('btn-gen-stops').addEventListener('click',generateStops);
document.getElementById('new-train-type').addEventListener('change',generateStops);
document.getElementById('new-train-line').addEventListener('change',generateStops);
document.getElementById('new-train-dir').addEventListener('change',renderStopsEditor);

function collectStops(){
  const rows=document.querySelectorAll('#stops-editor input[data-ridx]');
  const map={};
  rows.forEach(inp=>{
    const idx=parseInt(inp.dataset.ridx);
    if(!map[idx])map[idx]={};
    map[idx][inp.dataset.field]=inp.value.trim();
  });
  return currentStops.filter(s=>s.active).map((s,_,__)=>{
    const idx=currentStops.indexOf(s);
    return{station:s.station,arrive:map[idx]?.arrive||'',depart:map[idx]?.depart||'',track:map[idx]?.track||''};
  });
}

// === FORM ===
document.getElementById('add-train-form').addEventListener('submit',async(e)=>{
  e.preventDefault();
  const num=document.getElementById('new-train-num').value.trim();
  const dest=document.getElementById('new-train-dest').value.trim();
  const type=document.getElementById('new-train-type').value;
  const line=document.getElementById('new-train-line').value;
  const dir=document.getElementById('new-train-dir').value;
  const editId=document.getElementById('edit-id').value;
  if(!num)return;
  const stops=collectStops();
  const btn=e.target.querySelector('[type="submit"]');
  btn.disabled=true;btn.textContent='保存中...';
  const record={train_number:num,train_type:type,destination:dest,direction:dir,line:line,stops_json:JSON.stringify(stops)};
  let r;
  if(editId){
    const existing=trains.find(t=>t.__backendId===editId);
    if(existing)r=await window.dataSdk.update({...existing,...record});
    else r=await window.dataSdk.create(record);
  }else{
    if(trains.length>=999){btn.disabled=false;btn.textContent='登録';return;}
    r=await window.dataSdk.create(record);
  }
  btn.disabled=false;btn.textContent='登録';
  if(r.isOk){e.target.reset();document.getElementById('edit-id').value='';currentStops=[];document.getElementById('stops-editor').innerHTML='';}
});

window.editTrain=function(id){
  const tr=trains.find(t=>t.__backendId===id);
  if(!tr)return;
  // Switch to add sub-tab
  document.querySelectorAll('.sub-tab').forEach(b=>{b.classList.remove('sub-tab-active');b.classList.add('text-gray-400');});
  document.querySelectorAll('.sub-panel').forEach(p=>p.classList.add('hidden'));
  document.querySelector('[data-sub="add"]').classList.add('sub-tab-active');
  document.querySelector('[data-sub="add"]').classList.remove('text-gray-400');
  document.getElementById('sub-add').classList.remove('hidden');

  document.getElementById('new-train-num').value=tr.train_number;
  document.getElementById('new-train-dest').value=tr.destination||'';
  document.getElementById('new-train-type').value=tr.train_type;
  document.getElementById('new-train-line').value=tr.line||'京王線';
  document.getElementById('new-train-dir').value=tr.direction||'下り';
  document.getElementById('edit-id').value=tr.__backendId;
  const stops=JSON.parse(tr.stops_json||'[]');
  const allStations=getFullRoute(tr.line||'京王線');
  currentStops=allStations.map(st=>{
    const found=stops.find(s=>s.station===st);
    return{station:st,active:!!found,arrive:found?.arrive||'',depart:found?.depart||'',track:found?.track||''};
  });
  renderStopsEditor();
};

window.deleteTrain=async function(id){
  const tr=trains.find(t=>t.__backendId===id);
  if(tr)await window.dataSdk.delete(tr);
};

// === TABS ===
document.querySelectorAll('.tab-btn').forEach(btn=>{
  btn.addEventListener('click',()=>{
    document.querySelectorAll('.tab-btn').forEach(b=>{b.classList.remove('tab-active');b.classList.add('text-gray-400');});
    btn.classList.add('tab-active');btn.classList.remove('text-gray-400');
    document.querySelectorAll('.tab-panel').forEach(p=>p.classList.add('hidden'));
    document.getElementById('panel-'+btn.dataset.tab).classList.remove('hidden');
    if(btn.dataset.tab==='position')renderPosition();
    if(btn.dataset.tab==='settings')renderDiaTable();
    if(btn.dataset.tab==='timetable')renderTimetable();
  });
});

// Sub-tabs
document.querySelectorAll('.sub-tab').forEach(btn=>{
  btn.addEventListener('click',()=>{
    document.querySelectorAll('.sub-tab').forEach(b=>{b.classList.remove('sub-tab-active');b.classList.add('text-gray-400');});
    btn.classList.add('sub-tab-active');btn.classList.remove('text-gray-400');
    document.querySelectorAll('.sub-panel').forEach(p=>p.classList.add('hidden'));
    document.getElementById('sub-'+btn.dataset.sub).classList.remove('hidden');
    if(btn.dataset.sub==='dia')renderDiaTable();
    if(btn.dataset.sub==='list')renderTrainList();
  });
});

// === FILTERS ===
document.getElementById('station-search').addEventListener('input',renderTimetable);
document.getElementById('btn-down').addEventListener('click',()=>{direction='下り';document.getElementById('btn-down').className='px-3 py-2 text-sm bg-accent text-navy font-medium';document.getElementById('btn-up').className='px-3 py-2 text-sm bg-navy-card text-gray-400';renderTimetable();});
document.getElementById('btn-up').addEventListener('click',()=>{direction='上り';document.getElementById('btn-up').className='px-3 py-2 text-sm bg-accent text-navy font-medium';document.getElementById('btn-down').className='px-3 py-2 text-sm bg-navy-card text-gray-400';renderTimetable();});
document.getElementById('btn-weekday').addEventListener('click',()=>{dayType='weekday';document.getElementById('btn-weekday').className='px-3 py-2 text-sm bg-accent text-navy font-medium';document.getElementById('btn-holiday').className='px-3 py-2 text-sm bg-navy-card text-gray-400';renderTimetable();});
document.getElementById('btn-holiday').addEventListener('click',()=>{dayType='holiday';document.getElementById('btn-holiday').className='px-3 py-2 text-sm bg-accent text-navy font-medium';document.getElementById('btn-weekday').className='px-3 py-2 text-sm bg-navy-card text-gray-400';renderTimetable();});
document.getElementById('btn-train-search').addEventListener('click',searchTrain);
document.getElementById('train-search').addEventListener('keydown',e=>{if(e.key==='Enter'){e.preventDefault();searchTrain();}});
document.getElementById('btn-refresh').addEventListener('click',renderPosition);
document.getElementById('dia-down').addEventListener('click',()=>{diaDir='下り';document.getElementById('dia-down').className='px-2 py-1 text-xs bg-accent text-navy rounded font-medium';document.getElementById('dia-up').className='px-2 py-1 text-xs bg-navy-card text-gray-400 rounded';renderDiaTable();});
document.getElementById('dia-up').addEventListener('click',()=>{diaDir='上り';document.getElementById('dia-up').className='px-2 py-1 text-xs bg-accent text-navy rounded font-medium';document.getElementById('dia-down').className='px-2 py-1 text-xs bg-navy-card text-gray-400 rounded';renderDiaTable();});

// Auto-refresh timetable every minute
setInterval(renderTimetable,60000);
setInterval(renderPosition,30000);

// === DATA SDK ===
const handler={
  onDataChanged(data){
    trains=data;
    renderTrainList();
    renderDiaTable();
    renderPosition();
    renderTimetable();
  }
};

(async()=>{
  const r=await window.dataSdk.init(handler);
  if(!r.isOk){}
  renderTimetable();
  renderPosition();
  lucide.createIcons();
})();
</script>
 
</body></html>
