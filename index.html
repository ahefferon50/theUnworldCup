<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>the unworld cup</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500;700&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#0a0a0a;--bg2:#111;--bg3:#1a1a1a;--fg:#e8e8e8;--fg2:#888;--fg3:#444;--danger:#ff4444;--good:#44ff88;--warn:#ffcc44;--border:#252525;--mono:'IBM Plex Mono',monospace}
body{background:var(--bg);color:var(--fg);font-family:var(--mono);font-size:13px;min-height:100vh}
.app{max-width:960px;margin:0 auto;padding:0 16px 80px}
.header{border-bottom:1px solid var(--border);padding:24px 0 16px}
.header-sub{font-size:10px;letter-spacing:.2em;color:var(--fg3);text-transform:uppercase;margin-bottom:4px}
.header-title{font-size:28px;font-weight:700;letter-spacing:-.03em}
.header-title span{color:var(--fg3);font-weight:400}
.ticker{font-size:10px;color:var(--fg3);letter-spacing:.1em;padding:8px 0;border-bottom:1px solid var(--border);white-space:nowrap;overflow:hidden}
.tabs{display:flex;border-bottom:1px solid var(--border);flex-wrap:wrap}
.tab{padding:11px 18px;font-family:var(--mono);font-size:11px;letter-spacing:.1em;text-transform:uppercase;cursor:pointer;color:var(--fg2);border-bottom:2px solid transparent;background:none;border-top:none;border-left:none;border-right:none;transition:color .12s}
.tab.active{color:var(--fg);border-bottom-color:var(--fg)}
.tab:hover:not(.active){color:var(--fg)}
.tab.otab{margin-left:auto;color:var(--fg3);font-size:10px}
.tab.otab.active{color:var(--warn);border-bottom-color:var(--warn)}
.tc{display:none}.tc.active{display:block}
.section{padding:20px 0}
.slabel{font-size:10px;letter-spacing:.2em;text-transform:uppercase;color:var(--fg3);margin-bottom:14px}
.pgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(180px,1fr));gap:8px}
.pc{background:var(--bg2);border:1px solid var(--border);padding:12px;transition:border-color .1s;position:relative}
.pc:hover{border-color:#333}
.pn{font-size:13px;font-weight:700;margin-bottom:2px}
.pp{font-size:10px;letter-spacing:.1em;text-transform:uppercase;margin-bottom:6px}
.pst{font-size:11px;color:var(--warn);margin-bottom:6px}
.psc{position:absolute;top:12px;right:12px;font-size:16px;font-weight:700;color:var(--good)}
.sr{display:flex;justify-content:space-between;font-size:11px;color:var(--fg2);padding:1px 0}
.sv{color:var(--fg);font-weight:500}
.pos-atk{color:#ff8844}.pos-def{color:#44ccff}.pos-gk{color:#cc88ff}
input[type=text],input[type=number],input[type=password]{background:var(--bg);border:1px solid var(--border);color:var(--fg);font-family:var(--mono);font-size:12px;padding:7px 10px;width:100%;outline:none}
input:focus{border-color:#444}
input[type=range]{-webkit-appearance:none;width:100%;height:2px;background:var(--border);outline:none}
input[type=range]::-webkit-slider-thumb{-webkit-appearance:none;width:13px;height:13px;background:var(--fg);border-radius:50%;cursor:pointer}
select{background:var(--bg);border:1px solid var(--border);color:var(--fg);font-family:var(--mono);font-size:12px;padding:7px 10px;width:100%;outline:none}
button{background:none;border:1px solid var(--fg3);color:var(--fg2);font-family:var(--mono);font-size:11px;letter-spacing:.08em;padding:9px 18px;cursor:pointer;text-transform:uppercase;transition:all .12s}
button:hover{border-color:var(--fg);color:var(--fg)}
button.primary{border-color:var(--fg);color:var(--fg);font-weight:700}
button.primary:hover{background:var(--fg);color:var(--bg)}
button.good{border-color:var(--good);color:var(--good);font-weight:700}
button.good:hover{background:var(--good);color:var(--bg)}
button.danger{border-color:var(--danger);color:var(--danger)}
button.danger:hover{background:var(--danger);color:var(--bg)}
button.warn{border-color:var(--warn);color:var(--warn)}
button.warn:hover{background:var(--warn);color:var(--bg)}
button:disabled{opacity:.35;pointer-events:none}
.brow{display:flex;gap:8px;flex-wrap:wrap;margin-top:14px}
.card{background:var(--bg2);border:1px solid var(--border);padding:16px;margin-bottom:8px}
.erow{display:grid;grid-template-columns:130px 1fr;gap:8px;align-items:center;margin-bottom:8px}
.elabel{font-size:10px;color:var(--fg3);letter-spacing:.1em;text-transform:uppercase}
.wrow{display:grid;grid-template-columns:1fr 100px 36px;gap:12px;align-items:center;margin-bottom:12px}
.wnum{font-size:13px;color:var(--warn);text-align:right;font-weight:700}
.divider{border:none;border-top:1px solid var(--border);margin:22px 0}
.notice{font-size:11px;color:var(--fg3);padding:18px;border:1px dashed var(--border);text-align:center;letter-spacing:.05em}
.pill{display:inline-block;font-size:9px;letter-spacing:.15em;text-transform:uppercase;padding:3px 8px;border:1px solid var(--border);color:var(--fg3)}
.pill.live{border-color:var(--good);color:var(--good)}
.pill.w{border-color:var(--warn);color:var(--warn)}
.srow{display:grid;grid-template-columns:22px 1fr 60px 60px;gap:8px;align-items:center;padding:9px 0;border-bottom:1px solid var(--border);font-size:12px}
.srow:last-child{border-bottom:none}
.bigbtn{display:block;width:100%;padding:18px;border:1px dashed var(--fg3);background:none;color:var(--fg2);font-family:var(--mono);font-size:12px;letter-spacing:.15em;text-transform:uppercase;cursor:pointer;text-align:center;transition:all .15s}
.bigbtn:hover{border-color:var(--good);color:var(--good);border-style:solid}
.overlay{position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.88);display:flex;align-items:center;justify-content:center;z-index:100;padding:20px}
.modal{background:var(--bg2);border:1px solid #333;padding:28px;width:400px;max-width:100%;max-height:90vh;overflow-y:auto}
.modal-title{font-size:13px;font-weight:700;margin-bottom:18px;letter-spacing:.05em}
.color-picker{display:flex;gap:8px;flex-wrap:wrap;margin:8px 0}
.sw{width:26px;height:26px;border-radius:50%;cursor:pointer;border:2px solid transparent;transition:border-color .1s}
.sw.sel{border-color:var(--fg)}
.filter-bar{display:flex;gap:8px;margin-bottom:14px;flex-wrap:wrap}
.fbtn{padding:5px 12px;font-size:10px;letter-spacing:.1em}
.fbtn.active{border-color:var(--fg);color:var(--fg)}
.h2h-wrap{overflow-x:auto}
.h2h-table{border-collapse:collapse;font-size:11px}
.h2h-table td,.h2h-table th{padding:8px 10px;border:1px solid var(--border);text-align:center;white-space:nowrap}
.h2h-table th{color:var(--fg3);font-weight:400;font-size:10px;letter-spacing:.1em}
.h2h-table td.lbl{text-align:left;color:var(--fg2)}
.h2h-table td.win{background:#0a1a0a;color:var(--good)}
.h2h-table td.loss{background:#1a0a0a;color:var(--danger)}
.h2h-table td.draw{background:#1a1a0a;color:var(--warn)}
.h2h-table td.self{background:var(--bg3);color:var(--fg3)}
.fixture{padding:14px 0;border-bottom:1px solid var(--border)}
.fix-teams{display:flex;align-items:center;gap:8px;margin-bottom:8px}
.fix-score{font-size:18px;font-weight:700;min-width:60px;text-align:center}
.fix-report{font-size:11px;color:var(--fg2);line-height:1.7;font-style:italic;border-left:2px solid var(--border);padding-left:10px}
.round-hdr{font-size:11px;color:var(--warn);letter-spacing:.2em;text-transform:uppercase;padding:14px 0 8px;border-top:1px solid var(--border);margin-top:8px}
.slot-label{font-size:10px;letter-spacing:.15em;text-transform:uppercase;margin-bottom:8px;padding-bottom:4px;border-bottom:1px solid var(--border)}
.slot-label.atk{color:#ff8844}.slot-label.def{color:#44ccff}.slot-label.gk{color:#cc88ff}
.slot-grid{display:grid;grid-template-columns:1fr 1fr;gap:6px;margin-bottom:14px}
.slot-grid.one{grid-template-columns:1fr}
.slot-card{background:var(--bg3);border:1px solid var(--border);padding:10px 12px;display:flex;justify-content:space-between;align-items:center}
.slot-empty{background:var(--bg);border:1px dashed var(--border);padding:10px 12px;font-size:10px;color:var(--fg3);letter-spacing:.1em;text-transform:uppercase;text-align:center}
.team-list-card{background:var(--bg2);border:1px solid var(--border);padding:14px;margin-bottom:8px;display:flex;align-items:center;gap:12px}
.sync-note{font-size:10px;color:var(--fg3);text-align:center;padding:8px 0;letter-spacing:.08em}
</style>
</head>
<body>
<div class="app">
  <div class="header">
    <div class="header-sub">fantasy football league // season 1</div>
    <div class="header-title" id="leagueTitle">the <span>unworld</span> cup</div>
  </div>
  <div class="ticker" id="ticker">loading...</div>
  <div class="tabs">
    <button class="tab active" onclick="switchTab('players')">players</button>
    <button class="tab" onclick="switchTab('draft')">draft</button>
    <button class="tab" onclick="switchTab('teams')">teams</button>
    <button class="tab" onclick="switchTab('league')">league</button>
    <button class="tab" onclick="switchTab('standings')">standings</button>
    <button class="tab otab" onclick="switchTab('owner')">owner</button>
  </div>

  <div id="tab-players" class="tc active">
    <div class="section">
      <div class="slabel">all players</div>
      <div class="filter-bar">
        <button class="fbtn active" onclick="filterPlayers('all',this)">all</button>
        <button class="fbtn" onclick="filterPlayers('attacker',this)">attackers</button>
        <button class="fbtn" onclick="filterPlayers('defender',this)">defenders</button>
        <button class="fbtn" onclick="filterPlayers('goalie',this)">goalies</button>
      </div>
      <div class="pgrid" id="playerGrid"></div>
    </div>
  </div>

  <div id="tab-draft" class="tc">
    <div class="section">
      <div class="slabel">draft</div>
      <div id="draftTop"></div>
      <div class="filter-bar" id="draftFilterBar" style="margin-top:14px">
        <button class="fbtn active" onclick="filterDraft('all',this)">all</button>
        <button class="fbtn" onclick="filterDraft('attacker',this)">attackers</button>
        <button class="fbtn" onclick="filterDraft('defender',this)">defenders</button>
        <button class="fbtn" onclick="filterDraft('goalie',this)">goalies</button>
      </div>
      <div id="draftGrid" class="pgrid"></div>
    </div>
  </div>

  <div id="tab-teams" class="tc">
    <div class="section">
      <div class="slabel">all teams</div>
      <div id="teamsSection"></div>
    </div>
  </div>

  <div id="tab-league" class="tc">
    <div class="section">
      <div class="slabel">head-to-head results</div>
      <div class="h2h-wrap" id="h2hGrid"></div>
      <div class="divider"></div>
      <div class="slabel">match dispatches</div>
      <div id="fixtureLog"></div>
    </div>
  </div>

  <div id="tab-standings" class="tc">
    <div class="section">
      <div class="slabel">league table</div>
      <div id="standingsTable"></div>
    </div>
  </div>

  <div id="tab-owner" class="tc">
    <div class="section">
      <div class="slabel">owner controls</div>
      <div class="card">
        <div class="slabel" style="margin-bottom:12px">scoring weights</div>
        <div id="weightEditor"></div>
        <div class="brow">
          <button class="primary" onclick="saveWeights()">save weights</button>
          <button class="warn" onclick="runSim()">simulate round</button>
        </div>
      </div>
      <div class="divider"></div>
      <div class="slabel">manage teams</div>
      <div id="ownerTeams"></div>
      <div class="divider"></div>
      <div class="slabel">edit players</div>
      <div id="playerEditor"></div>
      <div class="brow">
        <button class="good" onclick="addPlayer()">+ add player</button>
        <button class="primary" onclick="savePlayers()">save all players</button>
      </div>
      <div class="divider"></div>
      <div class="slabel">league settings</div>
      <div class="card">
        <div class="erow"><div class="elabel">league name</div><input type="text" id="leagueNameInput"></div>
        <div class="brow">
          <button class="primary" onclick="saveSettings()">save settings</button>
          <button class="danger" onclick="resetLeague()">reset league</button>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="modalMount"></div>

<script>
const STORAGE_KEY = 'unworldcup_v1';
const COLORS = ['#ff4444','#ff8844','#ffcc44','#44ff88','#44ccff','#8844ff','#ff44cc','#e8e8e8','#888888'];
const ROSTER_SLOTS = {attacker:2, defender:2, goalie:1};

const WASTELAND = ["April is the cruellest month, breeding lilacs out of the dead land.","I will show you fear in a handful of dust.","The river's tent is broken; the last fingers of leaf clutch and sink into the wet bank.","What are the roots that clutch, what branches grow out of this stony rubbish?","Here is no water but only rock, rock and no water and the sandy road.","I think we are in rats' alley where the dead men lost their bones.","The awful daring of a moment's surrender.","These fragments I have shored against my ruins.","Who is the third who walks always beside you?","Unreal city, under the brown fog of a winter dawn.","The wind crosses the brown land, unheard.","At the violet hour, when the eyes and back turn upward from the desk.","The nymphs are departed.","Son of man, you cannot say, or guess, for you know only a heap of broken images.","I had not thought death had undone so many.","There I saw one I knew, and stopped him, crying: you who were with me in the ships at Mylae.","What have we given? My friend, blood shaking my heart.","Sweet Thames, run softly, till I end my song.","By the waters of Leman I sat down and wept.","O the moon shone bright on Mrs. Porter and on her daughter."];
const OMINOUS = ["The scoreboard does not lie, though the scoreboard itself has lied before.","Witnesses report the grass did not grow back for three days.","Officials declined to comment on what the linesperson saw.","The stadium clocks ran backwards for approximately eleven minutes.","All post-match interviews were conducted in a room that had no door.","The referee has not been seen since.","The ball, when recovered, was warm.","Meteorologists are not returning calls.","Something was decided here today. What, exactly, remains contested.","Players from both sides later agreed: the shadows had been wrong.","Three spectators in row G reported briefly forgetting their own names.","The away team bus arrived. The away team had not been on it.","One corner flag remained upright. No one touched it.","The goal was given. The goal was also not given. Both are true.","Investigators later confirmed the pitch was exactly one metre longer than it had been before kickoff."];
const VERBS_ATK = ['struck','dispatched','detonated','manifested','willed into existence','deposited','conjured','forced through the membrane of possibility','launched into the void','inscribed upon the net'];
const VERBS_GK = ['refused entry to','dissolved','returned to the nothing from which it came','unmade','held at the threshold','consumed','quietly reclassified as not having occurred','denied passage to'];

function rnd(arr){ return arr[Math.floor(Math.random()*arr.length)]; }

function generateReport(game) {
  const hR = Object.entries(state.draftedBy).filter(([pid,tid])=>tid===game.homeId).map(([pid])=>state.players.find(p=>p.id===pid)).filter(Boolean);
  const aR = Object.entries(state.draftedBy).filter(([pid,tid])=>tid===game.awayId).map(([pid])=>state.players.find(p=>p.id===pid)).filter(Boolean);
  const scorer = hR.filter(p=>p.pos==='attacker')[0] || hR[0] || null;
  const keeper = aR.filter(p=>p.pos==='goalie')[0] || null;
  let s1 = '';
  if (scorer && keeper) s1 = `${scorer.name} ${rnd(VERBS_ATK)} a goal in the ${Math.floor(Math.random()*85+5)}th minute; ${keeper.name} ${rnd(VERBS_GK)} two subsequent attempts before the ground shifted.`;
  else if (scorer) s1 = `${scorer.name} ${rnd(VERBS_ATK)} the only goal of the half, which officials later described as "probable".`;
  else s1 = `The match proceeded. Causality was maintained, more or less.`;
  return `${s1} "${rnd(WASTELAND)}" ${rnd(OMINOUS)}`;
}

const RAW = [
  ['Vex Holloway','attacker',82,90,44,75,80],['Ember Cross','attacker',88,85,40,78,72],
  ['Kael Dusk','attacker',91,87,35,72,68],['Oryn Fell','attacker',79,84,42,77,74],
  ['Morwenna Ux','attacker',84,89,37,81,69],['Ash Pendry','attacker',80,86,41,76,73],
  ['Solene Drax','attacker',83,88,39,79,71],['Wren Hallow','attacker',78,83,43,74,75],
  ['Aldric Vane','attacker',86,91,36,78,67],['Cleo Bask','attacker',81,85,40,80,72],
  ['Edda Lorn','attacker',87,90,38,77,70],['Zenn Pallor','attacker',83,87,41,78,73],
  ['Tavia Seld','attacker',80,84,44,76,76],['Lux Pallid','attacker',85,89,37,79,69],
  ['Corvus Fell','attacker',82,86,42,77,74],['Sera Pell','attacker',79,83,44,75,77],
  ['Calix Drake','attacker',84,88,38,80,71],['Pip Mallow','attacker',77,82,45,73,78],
  ['Flax Oner','attacker',86,90,36,78,68],['Rook Pyre','attacker',83,87,40,77,72],
  ['Solen Ark','attacker',81,85,41,76,73],['Cade Fell','attacker',85,89,37,79,70],
  ['Lore Vaunt','attacker',80,84,43,75,75],['Idris Nox','attacker',84,88,39,78,71],
  ['Orin Veck','attacker',82,86,41,77,73],['Bray Noll','attacker',79,83,44,76,76],
  ['Caer Vult','attacker',86,91,36,80,67],['Mave Thorn','attacker',81,85,42,75,74],
  ['Lynd Brae','attacker',83,87,40,77,72],['Ren Vosk','attacker',85,89,38,79,69],
  ['Tarn Orle','attacker',80,84,43,76,75],['Cren Flax','attacker',84,88,39,78,71],
  ['Yore Fell','attacker',82,86,42,77,73],['Drift Mako','attacker',95,72,55,66,65],
  ['Soot Harrow','attacker',93,61,48,68,63],['Cleft Rue','attacker',87,66,51,73,67],
  ['Iris Nox','attacker',91,63,53,69,64],['Caspian Fell','attacker',89,67,50,75,66],
  ['Finch Morrow','attacker',92,64,49,71,62],['Seren Moth','attacker',86,69,54,76,69],
  ['Mast Orwen','attacker',90,62,51,70,65],['Briar Nex','attacker',94,65,47,67,61],
  ['Sage Drift','attacker',88,68,52,72,68],['Gorse Wray','attacker',91,63,50,69,64],
  ['Elke Trave','attacker',87,66,53,74,67],['Nym Silt','attacker',93,62,49,68,63],
  ['Lorn Hawse','attacker',89,67,51,73,66],['Vesper Nole','attacker',90,64,50,71,65],
  ['Cord Vestige','attacker',92,61,48,67,62],['Bael Sorn','attacker',88,68,53,72,69],
  ['Thrice Weld','attacker',91,65,51,70,64],['Drex Callow','attacker',89,66,52,74,67],
  ['Wick Sable','attacker',93,63,49,68,63],['Skell Rime','attacker',87,67,53,73,68],
  ['Frome Celd','attacker',90,62,50,70,65],['Tule Sorrel','attacker',88,66,52,75,68],
  ['Pelk Reeve','attacker',92,64,50,68,63],['Seld Riven','attacker',89,65,51,72,66],
  ['Coll Wend','attacker',91,63,48,69,62],['Fael Hern','attacker',90,67,53,74,67],
  ['Cord Lode','attacker',88,65,51,71,65],['Brae Seld','attacker',93,62,49,68,63],
  ['Vore Nept','attacker',87,68,54,75,69],['Silt Morven','attacker',91,64,50,70,64],
  ['Calla Rune','defender',70,65,80,88,77],['Sable Piers','defender',55,60,94,72,85],
  ['Crest Vane','defender',60,55,91,65,88],['Pale Wren','defender',51,48,90,69,86],
  ['Vael Croft','defender',58,52,88,71,89],['Thorn Massy','defender',52,50,93,70,87],
  ['Bram Vole','defender',56,54,89,72,88],['Dun Carraway','defender',53,51,92,68,90],
  ['Leven Quay','defender',59,53,87,73,85],['Pyke Null','defender',54,49,95,67,91],
  ['Rowan Grex','defender',57,55,90,74,86],['Hal Voss','defender',50,47,93,66,89],
  ['Kern Ashfall','defender',55,52,91,71,87],['Mira Cull','defender',60,56,88,73,84],
  ['Dray Morne','defender',52,50,94,69,90],['Breck Wold','defender',58,53,89,72,88],
  ['Oast Miren','defender',54,51,92,70,89],['Thane Corr','defender',56,54,90,74,85],
  ['Arda Peil','defender',59,55,87,75,83],['Cess Dray','defender',53,50,93,68,91],
  ['Maeve Null','defender',57,53,90,73,86],['Yael Morn','defender',55,52,91,71,88],
  ['Penn Orris','defender',51,48,94,67,90],['Donn Wrace','defender',58,54,88,72,87],
  ['Asen Mire','defender',53,51,92,69,89],['Hasp Drove','defender',56,53,90,73,85],
  ['Foss Amble','defender',59,56,87,74,84],['Drex Pell','defender',54,50,93,68,90],
  ['Ness Croft','defender',57,54,89,73,86],['Gale Dross','defender',55,52,91,70,88],
  ['Pax Aven','defender',52,49,94,67,91],['Wael Mist','defender',58,55,88,73,85],
  ['Eld Sorn','defender',53,51,92,70,89],['Drex Hale','defender',56,53,90,72,87],
  ['Riven Shore','defender',62,58,89,70,86],['Trace Linden','defender',65,62,85,76,82],
  ['Nox Quill','goalie',45,40,98,70,90],['Cinder Page','goalie',42,38,96,68,92],
  ['Moth Drelk','goalie',48,42,97,66,91],['Vess Hollow','goalie',44,39,99,65,93],
  ['Pale Gate','goalie',40,36,98,63,94],['Orm Sunder','goalie',43,41,96,67,90],
  ['Threl Void','goalie',46,38,97,64,92],['Sorn Kassel','goalie',41,37,99,66,93],
  ['Brynn Dusk','goalie',47,43,95,69,89],['Vel Arren','goalie',44,40,98,65,91],
];

function makePlayers() {
  return RAW.map((r,i) => ({id:'p'+(i+1), name:r[0], pos:r[1], spd:r[2], str:r[3], def:r[4], vis:r[5], stm:r[6]}));
}

const DEFAULT_STATE = {
  leagueName: 'the unworld cup',
  stats: [
    {id:'spd',name:'speed',weight:3},
    {id:'str',name:'strike force',weight:4},
    {id:'def',name:'defense',weight:2},
    {id:'vis',name:'vision',weight:3},
    {id:'stm',name:'stamina',weight:2},
  ],
  players: makePlayers(),
  teams: [],
  games: [],
  draftedBy: {},
  roundNum: 0,
};

let state = {};
let playerFilter = 'all';
let draftFilter = 'all';

function loadState() {
  try {
    const raw = localStorage.getItem(STORAGE_KEY);
    if (raw) {
      state = JSON.parse(raw);
      if (!state.players || state.players.length < 50) state.players = makePlayers();
      if (!state.draftedBy) state.draftedBy = {};
      if (!state.games) state.games = [];
      if (!state.teams) state.teams = [];
      if (!state.stats) state.stats = DEFAULT_STATE.stats;
      if (!state.roundNum) state.roundNum = 0;
    } else {
      state = JSON.parse(JSON.stringify(DEFAULT_STATE));
    }
  } catch(e) {
    state = JSON.parse(JSON.stringify(DEFAULT_STATE));
  }
}

function saveState() {
  try { localStorage.setItem(STORAGE_KEY, JSON.stringify(state)); } catch(e) {}
}

// Poll for changes from other tabs every 3 seconds
setInterval(() => {
  try {
    const raw = localStorage.getItem(STORAGE_KEY);
    if (raw) {
      const fresh = JSON.parse(raw);
      state = fresh;
      render();
    }
  } catch(e) {}
}, 3000);

function calcScore(p) {
  const total = state.stats.reduce((a,b)=>a+b.weight,0) || 1;
  return Math.round(state.stats.reduce((a,s)=>a+(p[s.id]||0)*s.weight,0) / total);
}
function stars(sc) { const n=Math.round((sc/100)*5); return '★'.repeat(Math.max(1,n))+'☆'.repeat(5-Math.max(1,n)); }
function posClass(pos) { return pos==='attacker'?'pos-atk':pos==='defender'?'pos-def':'pos-gk'; }

function rosterCountsFor(teamId) {
  const c = {attacker:0, defender:0, goalie:0};
  Object.entries(state.draftedBy).filter(([pid,tid])=>tid===teamId).forEach(([pid]) => {
    const p = state.players.find(pl=>pl.id===pid);
    if (p && c[p.pos] !== undefined) c[p.pos]++;
  });
  return c;
}
function canDraft(teamId, pos) {
  return rosterCountsFor(teamId)[pos] < (ROSTER_SLOTS[pos]||0);
}

function render() {
  updateTicker();
  renderPlayers();
  renderDraft();
  renderTeams();
  renderLeague();
  renderStandings();
  renderOwner();
  const t = document.getElementById('leagueTitle');
  if (t) {
    const p = (state.leagueName||'the unworld cup').split(' ');
    t.innerHTML = p[0] + ' <span>' + p.slice(1).join(' ') + '</span>';
  }
}

function updateTicker() {
  const el = document.getElementById('ticker'); if (!el) return;
  const atk = state.players.filter(p=>p.pos==='attacker').length;
  const def = state.players.filter(p=>p.pos==='defender').length;
  const gk = state.players.filter(p=>p.pos==='goalie').length;
  el.textContent = `// ${state.players.length} players (${atk} atk / ${def} def / ${gk} gk) // ${state.teams.length} teams // ${state.leagueName||'unworld cup'} // last sync: ${new Date().toLocaleTimeString()}`;
}

function filterPlayers(f, btn) {
  playerFilter = f;
  document.querySelectorAll('#tab-players .fbtn').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  renderPlayers();
}

function filterDraft(f, btn) {
  draftFilter = f;
  document.querySelectorAll('#draftFilterBar .fbtn').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  renderDraft();
}

function renderPlayers() {
  const g = document.getElementById('playerGrid'); if (!g) return;
  g.innerHTML = '';
  const list = playerFilter==='all' ? state.players : state.players.filter(p=>p.pos===playerFilter);
  list.forEach(p => {
    const sc = calcScore(p);
    const tid = state.draftedBy[p.id];
    const tm = tid ? state.teams.find(t=>t.id===tid) : null;
    const el = document.createElement('div');
    el.className = 'pc';
    el.innerHTML = `<div class="psc">${sc}</div><div class="pn">${p.name}</div><div class="pp"><span class="${posClass(p.pos)}">${p.pos}</span>${tm ? ' // <span style="color:var(--fg3)">'+tm.name+'</span>' : ''}</div><div class="pst">${stars(sc)}</div>${state.stats.map(s=>`<div class="sr"><span>${s.name}</span><span class="sv">${p[s.id]||0}</span></div>`).join('')}`;
    g.appendChild(el);
  });
}

function renderDraft() {
  const top = document.getElementById('draftTop');
  const g = document.getElementById('draftGrid');
  if (!top || !g) return;

  // Check if user has a team stored in sessionStorage
  const myTeamId = sessionStorage.getItem('uwc_myteam');
  const myTeam = myTeamId ? state.teams.find(t=>t.id===myTeamId) : null;

  if (!myTeam) {
    top.innerHTML = `<div class="notice" style="margin-bottom:12px">select your team to draft players</div>
      <div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:8px;margin-bottom:14px">
        ${state.teams.length ? state.teams.map(t=>{
          const counts = rosterCountsFor(t.id);
          const total = Object.values(counts).reduce((a,b)=>a+b,0);
          return `<div class="team-list-card" style="cursor:pointer;flex-direction:column;align-items:flex-start" onclick="claimTeam('${t.id}')">
            <div style="display:flex;align-items:center;gap:6px;margin-bottom:4px">
              ${(t.colors||['#888']).map(c=>`<span style="display:inline-block;width:9px;height:9px;border-radius:50%;background:${c}"></span>`).join('')}
              <span style="font-weight:700">${t.name}</span>
            </div>
            <div style="font-size:10px;color:var(--fg3)">${total}/5 players drafted</div>
          </div>`;
        }).join('') : '<div class="notice" style="grid-column:1/-1">no teams yet — create one in the teams tab</div>'}
      </div>`;
    g.innerHTML = '';
    return;
  }

  const counts = rosterCountsFor(myTeam.id);
  const total = Object.values(counts).reduce((a,b)=>a+b,0);
  top.innerHTML = `<div style="display:flex;align-items:center;gap:10px;flex-wrap:wrap;margin-bottom:6px">
    <span class="pill live">managing: ${myTeam.name}</span>
    <span style="color:var(--fg2);font-size:11px">roster: ${total}/5 &nbsp;|&nbsp; <span class="pos-atk">atk ${counts.attacker}/2</span> &nbsp;<span class="pos-def">def ${counts.defender}/2</span> &nbsp;<span class="pos-gk">gk ${counts.goalie}/1</span></span>
    <button style="margin-left:auto;padding:4px 10px;font-size:10px" onclick="sessionStorage.removeItem('uwc_myteam');renderDraft()">switch team</button>
  </div>`;

  g.innerHTML = '';
  const drafted = new Set(Object.keys(state.draftedBy));
  const list = draftFilter==='all' ? state.players : state.players.filter(p=>p.pos===draftFilter);

  // Only show undrafted players, or players on this team
  list.filter(p => !drafted.has(p.id) || state.draftedBy[p.id]===myTeam.id).forEach(p => {
    const mine = state.draftedBy[p.id] === myTeam.id;
    const sc = calcScore(p);
    const slotFull = !canDraft(myTeam.id, p.pos);
    const el = document.createElement('div');
    el.className = 'pc' + (mine ? ' sel' : '');
    let btn = '';
    if (mine) btn = `<button class="danger" style="margin-top:8px;width:100%" onclick="undraft('${p.id}')">release</button>`;
    else if (!slotFull) btn = `<button class="good" style="margin-top:8px;width:100%" onclick="draft('${p.id}')">draft</button>`;
    else btn = `<div class="pill w" style="margin-top:8px">${p.pos} full</div>`;
    el.innerHTML = `<div class="psc">${sc}</div><div class="pn">${p.name}</div><div class="pp"><span class="${posClass(p.pos)}">${p.pos}</span></div><div class="pst">${stars(sc)}</div>${state.stats.map(s=>`<div class="sr"><span>${s.name}</span><span class="sv">${p[s.id]||0}</span></div>`).join('')}${btn}`;
    g.appendChild(el);
  });
  if (!g.children.length) g.innerHTML = '<div class="notice" style="grid-column:1/-1">all available players drafted</div>';
}

function claimTeam(id) {
  sessionStorage.setItem('uwc_myteam', id);
  renderDraft();
}

function draft(pid) {
  const myTeamId = sessionStorage.getItem('uwc_myteam');
  const myTeam = myTeamId ? state.teams.find(t=>t.id===myTeamId) : null;
  if (!myTeam) return;
  const p = state.players.find(pl=>pl.id===pid); if (!p) return;
  if (!canDraft(myTeam.id, p.pos)) return;
  state.draftedBy[pid] = myTeam.id;
  saveState(); renderDraft(); renderPlayers();
}

function undraft(pid) {
  delete state.draftedBy[pid];
  saveState(); renderDraft(); renderPlayers();
}

function renderTeams() {
  const sec = document.getElementById('teamsSection'); if (!sec) return;
  const myTeamId = sessionStorage.getItem('uwc_myteam');

  let html = `<button class="bigbtn" style="margin-bottom:16px" onclick="showCreateTeam()">+ create new team</button>`;

  if (!state.teams.length) {
    html += '<div class="notice">no teams yet — be the first</div>';
  } else {
    state.teams.forEach(t => {
      const roster = Object.entries(state.draftedBy).filter(([pid,tid])=>tid===t.id).map(([pid])=>state.players.find(p=>p.id===pid)).filter(Boolean);
      const atk = roster.filter(p=>p.pos==='attacker');
      const def = roster.filter(p=>p.pos==='defender');
      const gk = roster.filter(p=>p.pos==='goalie');
      const total = roster.reduce((a,p)=>a+calcScore(p),0);
      const dots = (t.colors||['#888']).map(c=>`<span style="display:inline-block;width:10px;height:10px;border-radius:50%;background:${c};margin-right:3px"></span>`).join('');
      const isMine = myTeamId === t.id;

      function rosterSection(players, max, label, cls) {
        let out = `<div style="margin-bottom:10px"><div class="slot-label ${cls}">${label} (${players.length}/${max})</div><div class="slot-grid${max===1?' one':''}">`;
        for (let i=0;i<max;i++) {
          if (players[i]) {
            out += `<div class="slot-card"><div><div style="font-size:12px;font-weight:700">${players[i].name}</div><div style="font-size:10px;color:var(--warn)">${stars(calcScore(players[i]))}</div></div><div style="color:var(--good);font-size:14px;font-weight:700">${calcScore(players[i])}</div></div>`;
          } else {
            out += `<div class="slot-empty">empty</div>`;
          }
        }
        out += '</div></div>';
        return out;
      }

      html += `<div class="card" style="border-color:${isMine?'#555':''}" >
        <div style="display:flex;align-items:center;gap:8px;margin-bottom:8px">
          ${dots}<div style="font-size:16px;font-weight:700">${t.name}</div>
          <div style="color:var(--good);font-size:12px;margin-left:auto">${total} pts</div>
          ${isMine ? '<span class="pill live">your team</span>' : ''}
        </div>
        ${t.motto ? `<div style="font-size:11px;color:var(--fg3);margin-bottom:12px;font-style:italic">"${t.motto}"</div>` : ''}
        ${rosterSection(atk,2,'attackers','atk')}
        ${rosterSection(def,2,'defenders','def')}
        ${rosterSection(gk,1,'goalie','gk')}
        <div class="brow">
          ${isMine ? `<button class="primary" onclick="showEditTeam('${t.id}')">edit team</button>` : `<button onclick="claimTeamAndGoDraft('${t.id}')">manage roster</button>`}
        </div>
      </div>`;
    });
  }
  sec.innerHTML = html;
}

function claimTeamAndGoDraft(id) {
  sessionStorage.setItem('uwc_myteam', id);
  switchTab('draft');
}

function renderLeague() {
  const h2h = document.getElementById('h2hGrid');
  const fl = document.getElementById('fixtureLog');
  if (!h2h || !fl) return;
  const teams = state.teams;
  if (teams.length < 2) { h2h.innerHTML='<div class="notice">need 2+ teams</div>'; fl.innerHTML=''; return; }

  const results = {};
  teams.forEach(t => results[t.id] = {});
  (state.games||[]).forEach(g => {
    if (!results[g.homeId] || !results[g.awayId]) return;
    if (!results[g.homeId][g.awayId]) results[g.homeId][g.awayId] = {w:0,l:0,d:0,last:null};
    if (!results[g.awayId][g.homeId]) results[g.awayId][g.homeId] = {w:0,l:0,d:0,last:null};
    const hW = g.homeScore > g.awayScore, aW = g.awayScore > g.homeScore;
    if (hW) { results[g.homeId][g.awayId].w++; results[g.awayId][g.homeId].l++; }
    else if (aW) { results[g.homeId][g.awayId].l++; results[g.awayId][g.homeId].w++; }
    else { results[g.homeId][g.awayId].d++; results[g.awayId][g.homeId].d++; }
    results[g.homeId][g.awayId].last = `${g.homeScore}-${g.awayScore}`;
    results[g.awayId][g.homeId].last = `${g.awayScore}-${g.homeScore}`;
  });

  let tbl = `<table class="h2h-table"><tr><th></th>${teams.map(t=>`<th title="${t.name}">${t.name.length>10?t.name.slice(0,9)+'…':t.name}</th>`).join('')}</tr>`;
  teams.forEach(home => {
    tbl += `<tr><td class="lbl">${home.name.length>12?home.name.slice(0,11)+'…':home.name}</td>`;
    teams.forEach(away => {
      if (home.id===away.id) { tbl+='<td class="self">—</td>'; return; }
      const r = results[home.id] && results[home.id][away.id];
      if (!r || (!r.w&&!r.l&&!r.d)) { tbl+='<td style="color:var(--fg3)">—</td>'; return; }
      const cls = r.w>r.l?'win':r.l>r.w?'loss':'draw';
      tbl += `<td class="${cls}" title="W:${r.w} L:${r.l} D:${r.d}">${r.last||'—'}</td>`;
    });
    tbl += '</tr>';
  });
  tbl += '</table>';
  h2h.innerHTML = tbl;

  const games = [...(state.games||[])].reverse();
  if (!games.length) { fl.innerHTML = '<div class="notice">no matches played yet</div>'; return; }
  const byRound = {};
  games.forEach(g => { const r=g.round||1; if(!byRound[r])byRound[r]=[]; byRound[r].push(g); });
  const rounds = Object.keys(byRound).sort((a,b)=>b-a);
  fl.innerHTML = rounds.map(r => `<div class="round-hdr">round ${r}</div>${byRound[r].map(g=>`<div class="fixture"><div class="fix-teams"><div style="flex:1;font-size:13px;font-weight:700">${g.home}</div><div class="fix-score">${g.homeScore} – ${g.awayScore}</div><div style="flex:1;text-align:right;font-size:13px;font-weight:700">${g.away}</div></div><div class="fix-report">${g.report||''}</div></div>`).join('')}`).join('');
}

function renderStandings() {
  const tbl = document.getElementById('standingsTable'); if (!tbl) return;
  const ts = state.teams.map(t => {
    const games = (state.games||[]).filter(g=>g.homeId===t.id||g.awayId===t.id);
    let w=0,l=0,d=0,gf=0,ga=0;
    games.forEach(g => { const home=g.homeId===t.id; const tf=home?g.homeScore:g.awayScore; const ta=home?g.awayScore:g.homeScore; gf+=tf; ga+=ta; if(tf>ta)w++; else if(ta>tf)l++; else d++; });
    return {...t, w, l, d, gf, ga, pts: w*3+d};
  }).sort((a,b) => b.pts-a.pts || (b.gf-b.ga)-(a.gf-a.ga));
  if (!ts.length) { tbl.innerHTML = '<div class="notice">no teams registered</div>'; return; }
  tbl.innerHTML = `<div class="srow" style="color:var(--fg3);font-size:10px"><div>#</div><div>team</div><div>W-D-L</div><div>pts</div></div>${ts.map((t,i)=>`<div class="srow"><div style="color:var(--fg3)">${i+1}</div><div><span style="display:inline-block;width:8px;height:8px;border-radius:50%;background:${(t.colors||['#888'])[0]};margin-right:5px"></span>${t.name}</div><div style="color:var(--fg2)">${t.w}-${t.d}-${t.l}</div><div style="color:var(--good)">${t.pts}</div></div>`).join('')}`;
}

function renderOwner() {
  const li = document.getElementById('leagueNameInput'); if (li) li.value = state.leagueName||'';
  renderWeightEditor();
  renderOwnerTeams();
  renderPlayerEditor();
}

function renderWeightEditor() {
  const ed = document.getElementById('weightEditor'); if (!ed) return;
  ed.innerHTML = state.stats.map((s,i) => `<div class="wrow"><input type="text" value="${s.name}" onchange="state.stats[${i}].name=this.value" style="width:100%"><input type="range" min="0" max="10" step="1" value="${s.weight}" oninput="state.stats[${i}].weight=+this.value;document.getElementById('wv${i}').textContent=this.value"><div class="wnum" id="wv${i}">${s.weight}</div></div>`).join('');
}

function saveWeights() { saveState(); render(); flash('weights saved'); }

function renderOwnerTeams() {
  const el = document.getElementById('ownerTeams'); if (!el) return;
  if (!state.teams.length) { el.innerHTML = '<div class="notice">no teams to manage</div>'; return; }
  el.innerHTML = state.teams.map(t => {
    const roster = Object.entries(state.draftedBy).filter(([pid,tid])=>tid===t.id).length;
    const dots = (t.colors||['#888']).map(c=>`<span style="display:inline-block;width:8px;height:8px;border-radius:50%;background:${c};margin-right:3px"></span>`).join('');
    return `<div class="team-list-card">
      ${dots}
      <div style="flex:1"><div style="font-weight:700">${t.name}</div><div style="font-size:10px;color:var(--fg3)">${roster}/5 players drafted</div></div>
      <button class="danger" style="padding:5px 12px;font-size:10px" onclick="ownerDeleteTeam('${t.id}')">delete</button>
    </div>`;
  }).join('');
}

function ownerDeleteTeam(id) {
  const t = state.teams.find(t=>t.id===id);
  if (!t || !confirm(`delete team "${t.name}"? their drafted players will be released.`)) return;
  Object.keys(state.draftedBy).forEach(pid => { if (state.draftedBy[pid]===id) delete state.draftedBy[pid]; });
  state.teams = state.teams.filter(t=>t.id!==id);
  state.games = state.games.filter(g=>g.homeId!==id&&g.awayId!==id);
  if (sessionStorage.getItem('uwc_myteam')===id) sessionStorage.removeItem('uwc_myteam');
  saveState(); render(); flash('team deleted');
}

function renderPlayerEditor() {
  const ed = document.getElementById('playerEditor'); if (!ed) return;
  ed.innerHTML = state.players.map((p,pi) => `<div class="card" style="margin-bottom:8px">
    <div class="erow"><div class="elabel">name</div><input type="text" value="${p.name}" onchange="state.players[${pi}].name=this.value"></div>
    <div class="erow"><div class="elabel">position</div><select onchange="state.players[${pi}].pos=this.value"><option value="attacker"${p.pos==='attacker'?' selected':''}>attacker</option><option value="defender"${p.pos==='defender'?' selected':''}>defender</option><option value="goalie"${p.pos==='goalie'?' selected':''}>goalie</option></select></div>
    ${state.stats.map(s=>`<div class="erow"><div class="elabel">${s.name}</div><input type="number" min="0" max="100" value="${p[s.id]||0}" onchange="state.players[${pi}]['${s.id}']=+this.value"></div>`).join('')}
    <div class="brow"><button class="danger" onclick="removePlayer(${pi})">remove</button></div>
  </div>`).join('');
}

function addPlayer() {
  const id = 'p'+Date.now(); const blank = {};
  state.stats.forEach(s=>blank[s.id]=50);
  state.players.push({id, name:'New Player', pos:'attacker', ...blank});
  renderPlayerEditor();
}
function removePlayer(i) {
  const pid = state.players[i].id;
  state.players.splice(i, 1);
  delete state.draftedBy[pid];
  renderPlayerEditor();
}
function savePlayers() { saveState(); render(); flash('players saved'); }

function saveSettings() {
  state.leagueName = document.getElementById('leagueNameInput').value.trim() || 'the unworld cup';
  saveState(); render(); flash('settings saved');
}

function resetLeague() {
  if (!confirm('reset all teams, drafts, and games? players and settings remain.')) return;
  state.teams = []; state.draftedBy = {}; state.games = []; state.roundNum = 0;
  sessionStorage.removeItem('uwc_myteam');
  saveState(); render(); flash('league reset');
}

function runSim() {
  if (state.teams.length < 2) { flash('need 2+ teams'); return; }
  state.roundNum = (state.roundNum||0) + 1;
  const teams = [...state.teams];
  for (let i=0; i<teams.length-1; i++) {
    for (let j=i+1; j<teams.length; j++) {
      const h=teams[i], a=teams[j];
      const hR = Object.entries(state.draftedBy).filter(([pid,tid])=>tid===h.id).map(([pid])=>state.players.find(p=>p.id===pid)).filter(Boolean);
      const aR = Object.entries(state.draftedBy).filter(([pid,tid])=>tid===a.id).map(([pid])=>state.players.find(p=>p.id===pid)).filter(Boolean);
      const hAtk = hR.filter(p=>p.pos==='attacker').reduce((s,p)=>s+calcScore(p),0);
      const aDef = aR.filter(p=>p.pos==='defender').reduce((s,p)=>s+calcScore(p),0);
      const aGk = aR.filter(p=>p.pos==='goalie').reduce((s,p)=>s+calcScore(p),0);
      const aAtk = aR.filter(p=>p.pos==='attacker').reduce((s,p)=>s+calcScore(p),0);
      const hDef = hR.filter(p=>p.pos==='defender').reduce((s,p)=>s+calcScore(p),0);
      const hGk = hR.filter(p=>p.pos==='goalie').reduce((s,p)=>s+calcScore(p),0);
      const hPow = hAtk*2 - (aDef+aGk) + Math.floor(Math.random()*80) + 20;
      const aPow = aAtk*2 - (hDef+hGk) + Math.floor(Math.random()*80) + 20;
      const g = {home:h.name, away:a.name, homeId:h.id, awayId:a.id, homeScore:Math.max(0,Math.round(hPow/55)), awayScore:Math.max(0,Math.round(aPow/55)), round:state.roundNum};
      g.report = generateReport(g);
      state.games.push(g);
    }
  }
  saveState(); renderLeague(); renderStandings(); flash(`round ${state.roundNum} simulated — ${state.teams.length*(state.teams.length-1)/2} matches played`);
}

function showCreateTeam() { showTeamModal(null); }
function showEditTeam(id) { showTeamModal(state.teams.find(t=>t.id===id)); }

function showTeamModal(existing) {
  const isNew = !existing;
  const sel = existing ? (existing.colors||[]) : ['#e8e8e8'];
  const mount = document.getElementById('modalMount');
  mount.innerHTML = `<div class="overlay" onclick="if(event.target===this)closeModal()"><div class="modal">
    <div class="modal-title">${isNew?'create a new team':'edit team'}</div>
    <div style="margin-bottom:10px"><div class="elabel" style="margin-bottom:5px">team name</div><input type="text" id="tname" value="${existing?existing.name:''}" placeholder="the void walkers" maxlength="32"></div>
    <div style="margin-bottom:10px"><div class="elabel" style="margin-bottom:5px">motto</div><input type="text" id="tmotto" value="${existing?existing.motto||'':''}" placeholder="from nothing, everything" maxlength="60"></div>
    <div style="margin-bottom:18px"><div class="elabel" style="margin-bottom:6px">team colors (pick up to 3)</div>
    <div class="color-picker">${COLORS.map(c=>`<div class="sw${sel.includes(c)?' sel':''}" style="background:${c}" data-c="${c}" onclick="toggleSw(this)"></div>`).join('')}</div></div>
    <div class="brow">
      <button class="good" onclick="saveTeam(${isNew},'${existing?existing.id:''}')">${isNew?'create team':'save changes'}</button>
      <button onclick="closeModal()">cancel</button>
    </div>
  </div></div>`;
}

function toggleSw(el) {
  const s = document.querySelectorAll('.sw.sel');
  if (el.classList.contains('sel')) el.classList.remove('sel');
  else { if (s.length>=3) s[0].classList.remove('sel'); el.classList.add('sel'); }
}

function saveTeam(isNew, existingId) {
  const name = document.getElementById('tname').value.trim();
  if (!name) { flash('team needs a name'); return; }
  const motto = document.getElementById('tmotto').value.trim();
  const colors = [...document.querySelectorAll('.sw.sel')].map(el=>el.dataset.c);
  if (isNew) {
    const id = 't'+Date.now();
    state.teams.push({id, name, motto, colors: colors.length?colors:['#e8e8e8']});
    sessionStorage.setItem('uwc_myteam', id);
  } else {
    const idx = state.teams.findIndex(t=>t.id===existingId);
    if (idx>=0) state.teams[idx] = {id:existingId, name, motto, colors: colors.length?colors:['#e8e8e8']};
  }
  saveState(); closeModal(); render();
}

function closeModal() { document.getElementById('modalMount').innerHTML = ''; }

function switchTab(name) {
  document.querySelectorAll('.tc').forEach(el=>el.classList.remove('active'));
  document.querySelectorAll('.tab').forEach(el=>el.classList.remove('active'));
  document.getElementById('tab-'+name).classList.add('active');
  const map = {players:0, draft:1, teams:2, league:3, standings:4, owner:5};
  document.querySelectorAll('.tab')[map[name]].classList.add('active');
  if (name==='draft') renderDraft();
  if (name==='owner') renderOwner();
  if (name==='league') renderLeague();
  if (name==='teams') renderTeams();
}

let ft;
function flash(msg) {
  const t = document.getElementById('ticker');
  t.textContent = '// ' + msg;
  t.style.color = 'var(--good)';
  clearTimeout(ft);
  ft = setTimeout(() => { updateTicker(); t.style.color = ''; }, 2400);
}

loadState();
render();
</script>
</body>
</html>
