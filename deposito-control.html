<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>Control Depósito</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@400;600;700;800;900&family=Barlow:wght@300;400;500;600&display=swap');
:root {
  --bg:#0d0d0d;--bg2:#161616;--bg3:#1f1f1f;--card:#1a1a1a;
  --border:#2a2a2a;--border2:#383838;
  --text:#f0ece4;--muted:#555;--muted2:#888;
  --red:#e03a2f;--red-d:rgba(224,58,47,0.13);
  --green:#2ea84e;--green-d:rgba(46,168,78,0.13);
  --yellow:#d4a017;--yell-d:rgba(212,160,23,0.13);
  --blue:#2e7de0;--blue-d:rgba(46,125,224,0.13);
  --orange:#e07a2e;--purple:#9b59b6;
  --cond:'Barlow Condensed',sans-serif;
  --body:'Barlow',sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
html,body{height:100%}
body{background:var(--bg);color:var(--text);font-family:var(--body);font-size:14px}
button{cursor:pointer;font-family:var(--body)}
input,select{font-family:var(--body)}
::-webkit-scrollbar{width:3px;height:3px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background:var(--border2);border-radius:2px}

/* LOGIN */
#login-screen{position:fixed;inset:0;background:var(--bg);display:flex;align-items:center;justify-content:center;z-index:1000}
.login-box{background:var(--card);border:1px solid var(--border);border-radius:8px;padding:36px 32px;width:100%;max-width:380px}
.login-brand{font-family:var(--cond);font-size:26px;font-weight:900;letter-spacing:0.1em;text-align:center;margin-bottom:6px}
.login-brand em{color:var(--red);font-style:normal}
.login-sub{font-size:12px;color:var(--muted2);text-align:center;margin-bottom:28px;font-family:var(--cond);letter-spacing:0.08em;text-transform:uppercase}
.lf{margin-bottom:14px}
.lf label{display:block;font-family:var(--cond);font-size:10px;font-weight:700;letter-spacing:0.16em;text-transform:uppercase;color:var(--muted);margin-bottom:5px}
.lf input{width:100%;background:var(--bg3);border:1px solid var(--border2);color:var(--text);padding:13px 14px;border-radius:4px;font-size:18px;transition:border-color .15s}
.lf input:focus{outline:none;border-color:var(--blue)}
.login-btn{width:100%;background:var(--red);color:#fff;border:none;border-radius:4px;padding:14px;font-family:var(--cond);font-size:16px;font-weight:800;letter-spacing:0.1em;text-transform:uppercase;margin-top:6px;transition:all .15s}
.login-btn:hover{background:#f04030}
.login-btn:active{transform:scale(0.98)}
.login-err{background:var(--red-d);border:1px solid rgba(224,58,47,0.3);border-radius:4px;padding:10px 14px;font-size:13px;color:var(--red);margin-top:10px;display:none;text-align:center}
.login-loading{text-align:center;padding:10px;font-family:var(--cond);font-size:12px;color:var(--muted);letter-spacing:0.1em;display:none}

/* HEADER */
header{background:var(--bg2);border-bottom:1px solid var(--border);padding:0 14px;height:50px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:300}
.brand{font-family:var(--cond);font-size:19px;font-weight:900;letter-spacing:0.1em;text-transform:uppercase}
.brand em{color:var(--red);font-style:normal}
.hdr-right{display:flex;align-items:center;gap:8px}
.user-badge{display:flex;align-items:center;gap:6px;background:var(--bg3);border:1px solid var(--border2);border-radius:4px;padding:5px 10px}
.u-name{font-family:var(--cond);font-size:13px;font-weight:700;letter-spacing:0.08em;text-transform:uppercase}
.u-meta{font-size:10px;color:var(--muted2)}
.u-suc{font-family:var(--cond);font-size:10px;font-weight:700;color:var(--yellow)}
.date-lbl{font-family:var(--cond);font-size:11px;font-weight:600;letter-spacing:0.08em;color:var(--muted2);text-transform:uppercase}
.reset-btn{background:var(--red-d);border:1px solid var(--red);color:var(--red);font-family:var(--cond);font-size:10px;font-weight:700;letter-spacing:0.1em;text-transform:uppercase;padding:5px 9px;border-radius:3px;transition:all .15s}
.reset-btn:hover{background:var(--red);color:#fff}
.logout-btn{background:none;border:1px solid var(--border2);color:var(--muted);font-size:14px;padding:5px 8px;border-radius:3px;transition:all .15s}
.logout-btn:hover{color:var(--red);border-color:var(--red)}

/* SYNC INDICATOR */
.sync-dot{width:7px;height:7px;border-radius:50%;background:var(--muted);display:inline-block;transition:background .3s}
.sync-dot.syncing{background:var(--yellow);animation:pulse .8s infinite}
.sync-dot.ok{background:var(--green)}
.sync-dot.err{background:var(--red)}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.4}}

/* NAV */
nav{background:var(--bg2);border-bottom:1px solid var(--border);display:flex;overflow-x:auto;position:sticky;top:50px;z-index:290;scrollbar-width:none}
nav::-webkit-scrollbar{display:none}
.tab{flex-shrink:0;padding:0 13px;height:42px;background:none;border:none;font-family:var(--cond);font-size:12px;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;color:var(--muted);border-bottom:3px solid transparent;transition:all .15s;display:flex;align-items:center;gap:5px;white-space:nowrap}
.tab:hover{color:var(--text);background:rgba(255,255,255,0.02)}
.tab.active{color:var(--text);border-bottom-color:var(--red)}
.tc{background:var(--red);color:#fff;font-size:9px;font-weight:800;padding:1px 5px;border-radius:10px;min-width:15px;text-align:center;display:none}
.tc.show{display:inline-block}
.tc.ora{background:var(--orange)}

/* PAGES */
.page{display:none;padding:16px;max-width:980px;margin:0 auto}
.page.active{display:block}

/* SECTION */
.st{font-family:var(--cond);font-size:10px;font-weight:700;letter-spacing:0.2em;text-transform:uppercase;color:var(--muted);margin-bottom:10px;margin-top:18px;display:flex;align-items:center;gap:8px}
.st:first-child{margin-top:0}
.st::after{content:'';flex:1;height:1px;background:var(--border)}

/* CARDS */
.card{background:var(--card);border:1px solid var(--border);border-radius:6px;padding:16px;margin-bottom:14px}
.card-t{font-family:var(--cond);font-size:11px;font-weight:800;letter-spacing:0.14em;text-transform:uppercase;color:var(--muted2);margin-bottom:14px}

/* FORMS */
.fr{display:flex;gap:8px;margin-bottom:8px;flex-wrap:wrap}
.fg{display:flex;flex-direction:column;gap:4px;flex:1;min-width:90px}
.fg label{font-family:var(--cond);font-size:10px;font-weight:700;letter-spacing:0.14em;text-transform:uppercase;color:var(--muted)}
.fg input,.fg select{background:var(--bg3);border:1px solid var(--border2);color:var(--text);padding:10px 11px;border-radius:4px;font-size:15px;transition:border-color .15s}
.fg input:focus,.fg select:focus{outline:none;border-color:var(--blue)}
.fg select option{background:var(--bg3)}
.btn{padding:10px 16px;border:none;border-radius:4px;font-family:var(--cond);font-size:13px;font-weight:800;letter-spacing:0.1em;text-transform:uppercase;transition:all .15s;white-space:nowrap}
.btn:active{transform:scale(0.97)}
.btn-r{background:var(--red);color:#fff}.btn-r:hover{background:#f04030}
.btn-g{background:var(--green);color:#fff}.btn-g:hover{background:#35c05a}
.btn-b{background:var(--blue);color:#fff}.btn-b:hover{background:#3d8ff0}
.btn-s{background:var(--bg3);color:var(--text);border:1px solid var(--border2)}.btn-s:hover{border-color:var(--muted)}
.btn-sm{padding:6px 11px;font-size:11px}
.btn-warn{background:rgba(224,122,46,0.15);color:var(--orange);border:1px solid rgba(224,122,46,0.3)}

/* BADGES */
.badge{display:inline-flex;align-items:center;gap:4px;padding:3px 8px;border-radius:3px;font-family:var(--cond);font-size:10px;font-weight:800;letter-spacing:0.08em;text-transform:uppercase;white-space:nowrap}
.b-w{background:var(--yell-d);color:var(--yellow);border:1px solid rgba(212,160,23,0.3)}
.b-ok{background:var(--green-d);color:var(--green);border:1px solid rgba(46,168,78,0.3)}
.b-d{background:var(--red-d);color:var(--red);border:1px solid rgba(224,58,47,0.3)}
.b-p{background:var(--blue-d);color:var(--blue);border:1px solid rgba(46,125,224,0.3)}
.b-o{background:rgba(224,122,46,0.15);color:var(--orange);border:1px solid rgba(224,122,46,0.3)}
.b-m{background:rgba(80,80,80,0.2);color:var(--muted2);border:1px solid var(--border2)}

/* ITEM TAGS */
.it{display:inline-block;padding:2px 7px;border-radius:3px;font-family:var(--cond);font-size:9px;font-weight:800;letter-spacing:0.08em}
.it-cem{background:rgba(212,160,23,0.2);color:var(--yellow)}
.it-cal{background:rgba(224,122,46,0.2);color:var(--orange)}
.it-calh{background:rgba(224,90,46,0.2);color:#e05a2e}
.it-pla{background:rgba(46,125,224,0.2);color:var(--blue)}
.it-pal{background:rgba(46,168,78,0.2);color:var(--green)}

/* TABLE */
.tbl{width:100%;border-collapse:collapse;font-size:12px}
.tbl th{font-family:var(--cond);font-size:9px;font-weight:700;letter-spacing:0.18em;text-transform:uppercase;color:var(--muted);padding:7px 8px;text-align:left;border-bottom:1px solid var(--border)}
.tbl td{padding:9px 8px;border-bottom:1px solid var(--border);vertical-align:middle}
.tbl tr:last-child td{border-bottom:none}
.tbl tr:hover td{background:rgba(255,255,255,0.015)}

/* CONFIRM ROW */
.crow{background:var(--bg3);border:1px solid var(--border);border-radius:6px;padding:12px 14px;margin-bottom:8px;display:flex;align-items:center;gap:10px;flex-wrap:wrap}
.crow.done{opacity:0.4}
.crow-info{flex:1;min-width:150px}
.crow-rem{font-family:var(--cond);font-size:17px;font-weight:800}
.crow-sub{font-size:11px;color:var(--muted2);margin-top:2px}
.crow-aut{font-family:var(--cond);font-size:28px;font-weight:900;color:var(--yellow);min-width:55px;text-align:center;line-height:1}
.crow-aut span{font-size:9px;color:var(--muted);display:block;font-weight:600}
.cinp{background:var(--bg);border:2px solid var(--border2);color:var(--text);padding:9px;border-radius:4px;font-size:20px;font-weight:700;font-family:var(--cond);width:80px;text-align:center;transition:border-color .15s}
.cinp:focus{outline:none;border-color:var(--blue)}
.cinp.match{border-color:var(--green)}
.cinp.nomatch{border-color:var(--red)}
.lock-msg{font-size:11px;color:var(--red);margin-top:4px;display:none}

/* VIAJE */
.vrow{background:var(--bg3);border:1px solid var(--border);border-radius:6px;padding:12px 14px;margin-bottom:8px}
.vrow-head{display:flex;align-items:center;gap:10px;flex-wrap:wrap;margin-bottom:8px}
.vrow-chofer{font-family:var(--cond);font-size:16px;font-weight:800}
.vrow-info{font-size:11px;color:var(--muted2);flex:1}
.parada-item{background:var(--bg);border-left:2px solid var(--border2);padding:6px 10px;margin-bottom:4px;border-radius:0 4px 4px 0;font-size:11px;color:var(--muted2)}
.parada-item.entrega{border-left-color:var(--red)}
.parada-item.retiro{border-left-color:var(--green)}
.parada-item.paso{border-left-color:var(--yellow)}

/* STOCK */
.sg{display:grid;grid-template-columns:repeat(auto-fill,minmax(148px,1fr));gap:8px;margin-bottom:14px}
.sb{background:var(--bg3);border:1px solid var(--border);border-radius:6px;padding:12px}
.sb-name{font-family:var(--cond);font-size:9px;font-weight:800;letter-spacing:0.2em;text-transform:uppercase;color:var(--muted2);margin-bottom:8px}
.sb-row{display:flex;justify-content:space-between;align-items:baseline;margin-bottom:3px}
.sb-lbl{font-size:10px;color:var(--muted)}
.sv{font-family:var(--cond);font-size:18px;font-weight:900;line-height:1}
.sv.ini{color:var(--muted2);font-size:13px}
.sv.cur{color:var(--yellow);font-size:24px}
.sv.neg{color:var(--red);font-size:24px}
.sv.gr{color:var(--green);font-size:13px}
.sv.rd{color:var(--red);font-size:13px}
.sb-div{height:1px;background:var(--border);margin:5px 0}

/* PALLETS SALDO */
.saldo-g{display:grid;grid-template-columns:repeat(auto-fill,minmax(130px,1fr));gap:8px}
.sc{background:var(--bg3);border:1px solid var(--border);border-radius:6px;padding:12px}
.sc-cli{font-family:var(--cond);font-size:10px;font-weight:700;letter-spacing:0.06em;color:var(--muted2);text-transform:uppercase;margin-bottom:3px}
.sc-num{font-family:var(--cond);font-size:30px;font-weight:900;line-height:1}
.sc-num.debe{color:var(--red)}.sc-num.ok{color:var(--green)}.sc-num.cero{color:var(--muted)}
.sc-lbl{font-size:10px;color:var(--muted);margin-top:2px}

/* GLOBAL SUC TABS */
.suc-sel{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:14px}
.suc-btn{background:var(--bg3);border:1px solid var(--border2);border-radius:4px;padding:6px 12px;font-family:var(--cond);font-size:11px;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;color:var(--muted);transition:all .15s}
.suc-btn:hover{color:var(--text);border-color:var(--muted)}
.suc-btn.active{background:var(--red-d);border-color:var(--red);color:var(--red)}
.suc-btn.all{background:var(--blue-d);border-color:rgba(46,125,224,0.4);color:var(--blue)}

/* SUM BOXES */
.sumr{display:flex;gap:8px;margin-bottom:12px;flex-wrap:wrap}
.sumbox{flex:1;min-width:85px;background:var(--bg3);border:1px solid var(--border);border-radius:6px;padding:11px 13px}
.sumbox-l{font-family:var(--cond);font-size:9px;font-weight:700;letter-spacing:0.18em;text-transform:uppercase;color:var(--muted);margin-bottom:5px}
.sumbox-v{font-family:var(--cond);font-size:24px;font-weight:900;line-height:1}
.sumbox-v.r{color:var(--red)}.sumbox-v.g{color:var(--green)}.sumbox-v.y{color:var(--yellow)}

/* MOV COLORS */
.mv-d{color:var(--green);font-weight:700}.mv-r{color:var(--red);font-weight:700}
.mv-a{color:var(--blue);font-weight:700}.mv-p{color:var(--purple);font-weight:700}
.qv-d{color:var(--green);font-family:var(--cond);font-size:14px;font-weight:800}
.qv-r{color:var(--red);font-family:var(--cond);font-size:14px;font-weight:800}
.qv-a{color:var(--blue);font-family:var(--cond);font-size:14px;font-weight:800}
.qv-p{color:var(--purple);font-family:var(--cond);font-size:14px;font-weight:800}

/* ALERTS */
.diff-alert{background:var(--red-d);border:1px solid rgba(224,58,47,0.35);border-radius:6px;padding:10px 14px;margin-bottom:8px;font-size:12px;color:var(--red);display:flex;align-items:center;gap:8px}
.info-alert{background:var(--blue-d);border:1px solid rgba(46,125,224,0.3);border-radius:6px;padding:10px 14px;margin-bottom:10px;font-size:12px;color:var(--blue)}
.ok-alert{background:var(--green-d);border:1px solid rgba(46,168,78,0.3);border-radius:6px;padding:10px 14px;margin-bottom:10px;font-size:12px;color:var(--green)}
.partial-alert{background:var(--yell-d);border:1px solid rgba(212,160,23,0.3);border-radius:6px;padding:10px 14px;margin-bottom:10px;font-size:12px;color:var(--yellow)}

/* CONFIG */
.cff{margin-bottom:12px}
.cff label{display:block;font-family:var(--cond);font-size:10px;font-weight:700;letter-spacing:0.16em;text-transform:uppercase;color:var(--muted);margin-bottom:5px}
.cff input,.cff select{width:100%;background:var(--bg3);border:1px solid var(--border2);color:var(--text);padding:9px 12px;border-radius:4px;font-size:13px}
.cff input:focus{outline:none;border-color:var(--blue)}

/* TOAST */
#toast{position:fixed;bottom:20px;left:50%;transform:translateX(-50%) translateY(50px);background:var(--bg2);color:var(--text);border:1px solid var(--border2);padding:9px 20px;border-radius:4px;font-family:var(--cond);font-size:13px;font-weight:700;letter-spacing:0.08em;z-index:9999;white-space:nowrap;transition:transform .22s cubic-bezier(0.34,1.56,0.64,1),opacity .22s;opacity:0;pointer-events:none;max-width:90vw;text-overflow:ellipsis;overflow:hidden}
#toast.show{transform:translateX(-50%) translateY(0);opacity:1}
#toast.ok{border-left:3px solid var(--green)}
#toast.err{border-left:3px solid var(--red)}

/* EMPTY */
.empty{text-align:center;padding:28px;font-family:var(--cond);font-size:12px;font-weight:600;letter-spacing:0.1em;text-transform:uppercase;color:var(--muted)}

@media(max-width:600px){
  .page{padding:12px}
  .brand{font-size:16px}
  .date-lbl{display:none}
  .sumbox-v{font-size:20px}
  .crow-aut{font-size:22px}
  .user-badge .u-meta{display:none}
}
</style>
</head>
<body>
<div id="toast"></div>

<!-- LOGIN -->
<div id="login-screen">
  <div class="login-box">
    <div class="login-brand">DEP<em>Ó</em>SITO <em>·</em> CONTROL</div>
    <div class="login-sub">Sistema de gestión</div>
    <div class="lf"><label>Usuario</label><input type="text" id="l-user" placeholder="usuario" autocomplete="username" autocapitalize="none" spellcheck="false"></div>
    <div class="lf"><label>Contraseña</label><input type="password" id="l-pass" placeholder="••••••" autocomplete="current-password"></div>
    <button class="login-btn" id="login-btn" onclick="doLogin()">INGRESAR</button>
    <div class="login-loading" id="login-loading">VERIFICANDO...</div>
    <div class="login-err" id="login-err">Usuario o contraseña incorrectos</div>
  </div>
</div>

<!-- APP -->
<div id="app" style="display:none">
  <header>
    <div class="brand">DEP<em>Ó</em>SITO <em>·</em> CONTROL</div>
    <div class="hdr-right">
      <div class="date-lbl" id="dateDisplay"></div>
      <span class="sync-dot" id="syncDot" title="Estado sincronización"></span>
      <div class="user-badge">
        <div>
          <div class="u-name" id="hdr-user"></div>
          <div style="display:flex;gap:5px;align-items:center">
            <span class="u-meta" id="hdr-rol"></span>
            <span class="u-suc" id="hdr-suc"></span>
          </div>
        </div>
      </div>
      <button class="reset-btn" onclick="confirmarReset()" id="btn-reset" style="display:none">↺ Reset</button>
      <button class="logout-btn" onclick="doLogout()">⏻</button>
    </div>
  </header>

  <nav id="mainNav">
    <button class="tab" data-page="panol"   data-roles="operario_panol,encargado,coordinador,propietario" onclick="goTab(this)">📋 Pañol</button>
    <button class="tab" data-page="puerta"  data-roles="operario_puerta,encargado,coordinador,propietario" onclick="goTab(this)">🚛 Puerta <span class="tc" id="cntPuerta">0</span></button>
    <button class="tab" data-page="viajes"  data-roles="operario_puerta,encargado,coordinador,propietario" onclick="goTab(this)">🗺 Viajes <span class="tc ora" id="cntViajes">0</span></button>
    <button class="tab" data-page="fabrica" data-roles="operario_puerta,encargado,coordinador,propietario" onclick="goTab(this)">🏭 Fábrica</button>
    <button class="tab" data-page="ln"      data-roles="encargado,coordinador,propietario" onclick="goTab(this)">⬆ Loma Negra</button>
    <button class="tab" data-page="pallets" data-roles="operario_puerta,operario_panol,encargado,coordinador,propietario" onclick="goTab(this)">📦 Pallets</button>
    <button class="tab" data-page="stock"   data-roles="encargado,coordinador,propietario" onclick="goTab(this)">📊 Stock <span class="tc" id="cntDiff" style="background:var(--red)">0</span></button>
    <button class="tab" data-page="global"  data-roles="coordinador,propietario" onclick="goTab(this)">🌐 Global</button>
    <button class="tab" data-page="admin"   data-roles="propietario" onclick="goTab(this)">⚙ Admin</button>
  </nav>

  <!-- PAÑOL -->
  <div id="page-panol" class="page">
    <div id="panol-partial-alert"></div>
    <div class="card">
      <div class="card-t">Cargar remito de salida</div>
      <div class="fr">
        <div class="fg" style="max-width:130px"><label>N° Remito</label><input type="text" id="p-remito" placeholder="12345" inputmode="numeric" oninput="checkRemitoParcial()"></div>
        <div class="fg" style="max-width:160px"><label>Ítem</label>
          <select id="p-item"><option value="cemento">Cemento</option><option value="cal">Cal</option><option value="calhidratada">Cal Hidratada</option><option value="plasticor">Plasticor</option></select>
        </div>
        <div class="fg" style="max-width:105px"><label>Cant. facturada</label><input type="number" id="p-facturada" placeholder="0" inputmode="numeric" min="0"></div>
        <div class="fg" style="max-width:105px"><label>Cant. autorizada</label><input type="number" id="p-autorizada" placeholder="0" inputmode="numeric" min="0"></div>
        <div class="fg" style="max-width:100px"><label>Pallets (opc.)</label><input type="number" id="p-pallets" placeholder="0" inputmode="numeric" min="0"></div>
      </div>
      <div class="fr">
        <div class="fg"><label>Observaciones</label><input type="text" id="p-obs" placeholder="Ej: cliente retira en dos viajes"></div>
        <button class="btn btn-r" style="align-self:flex-end" onclick="cargarPanol()">+ REGISTRAR</button>
      </div>
    </div>
    <div class="st">Remitos del día</div>
    <div id="panol-lista"></div>
  </div>

  <!-- PUERTA -->
  <div id="page-puerta" class="page">
    <div id="puerta-diffs"></div>
    <div class="st">Pendientes de confirmar</div>
    <div id="puerta-pendientes"></div>
    <div class="st">Confirmados hoy</div>
    <div id="puerta-confirmados"></div>
  </div>

  <!-- VIAJES -->
  <div id="page-viajes" class="page">
    <div class="card">
      <div class="card-t">Registrar salida de chofer</div>
      <div class="fr">
        <div class="fg" style="max-width:120px"><label>N° Remito</label><input type="text" id="v-remito" placeholder="12345" inputmode="numeric"></div>
        <div class="fg"><label>Chofer</label><input type="text" id="v-chofer" placeholder="Nombre del chofer"></div>
        <div class="fg" style="max-width:160px"><label>Destino</label>
          <select id="v-destino"><option value="cliente">Cliente</option><option value="triangulo">El Triángulo</option><option value="entrerios">Entre Ríos</option><option value="armaduras">Armaduras</option><option value="ruta">Ruta</option></select>
        </div>
      </div>
      <div class="fr">
        <div class="fg" style="max-width:160px"><label>Ítem</label>
          <select id="v-item"><option value="cemento">Cemento</option><option value="cal">Cal</option><option value="calhidratada">Cal Hidratada</option><option value="plasticor">Plasticor</option><option value="ninguno">Sin material</option></select>
        </div>
        <div class="fg" style="max-width:100px"><label>Cantidad</label><input type="number" id="v-cantidad" placeholder="0" inputmode="numeric" min="0"></div>
        <div class="fg" style="max-width:100px"><label>Pallets que lleva</label><input type="number" id="v-pallets" placeholder="0" inputmode="numeric" min="0"></div>
        <button class="btn btn-r" style="align-self:flex-end" onclick="registrarSalida()">🚛 SALIDA</button>
      </div>
    </div>
    <div class="st">Viajes abiertos <span style="color:var(--muted2);font-weight:400;font-size:10px">(todas las sucursales)</span></div>
    <div id="viajes-abiertos"></div>
    <div class="st">Cerrados hoy</div>
    <div id="viajes-cerrados"></div>
  </div>

  <!-- FÁBRICA -->
  <div id="page-fabrica" class="page">
    <div class="card">
      <div class="card-t">Registrar ingreso de fábrica</div>
      <div class="fr">
        <div class="fg" style="max-width:160px"><label>Ítem</label>
          <select id="f-item"><option value="cemento">Cemento</option><option value="cal">Cal</option><option value="calhidratada">Cal Hidratada</option><option value="plasticor">Plasticor</option></select>
        </div>
        <div class="fg" style="max-width:100px"><label>Cantidad</label><input type="number" id="f-cantidad" placeholder="0" inputmode="numeric" min="0"></div>
        <div class="fg" style="max-width:110px"><label>Pallets que trae</label><input type="number" id="f-ptrae" placeholder="0" inputmode="numeric" min="0"></div>
        <div class="fg" style="max-width:110px"><label>Pallets que lleva</label><input type="number" id="f-plleva" placeholder="0" inputmode="numeric" min="0"></div>
        <button class="btn btn-b" style="align-self:flex-end" onclick="registrarFabrica()">🏭 REGISTRAR</button>
      </div>
    </div>
    <div class="st">Ingresos de fábrica hoy</div>
    <div id="fabrica-lista"></div>
  </div>

  <!-- LOMA NEGRA -->
  <div id="page-ln" class="page">
    <div class="card">
      <div class="card-t">Pedido / Devolución a Loma Negra</div>
      <div class="fr">
        <div class="fg" style="max-width:160px"><label>Tipo</label>
          <select id="ln-tipo"><option value="pedido">Pedido de material</option><option value="devolucion">Devolución de pallets</option></select>
        </div>
        <div class="fg" style="max-width:160px"><label>Ítem</label>
          <select id="ln-item"><option value="cemento">Cemento</option><option value="cal">Cal</option><option value="calhidratada">Cal Hidratada</option><option value="plasticor">Plasticor</option><option value="pallets">Pallets</option></select>
        </div>
        <div class="fg" style="max-width:100px"><label>Cantidad</label><input type="number" id="ln-cantidad" placeholder="0" inputmode="numeric" min="0"></div>
      </div>
      <div class="fr">
        <div class="fg" style="max-width:150px"><label>N° Factura (opc.)</label><input type="text" id="ln-factura" placeholder="FAC-0001"></div>
        <div class="fg" style="max-width:150px"><label>N° Remito (opc.)</label><input type="text" id="ln-remito" placeholder="REM-0001"></div>
        <div class="fg"><label>Observaciones</label><input type="text" id="ln-obs" placeholder="Notas adicionales"></div>
        <button class="btn btn-r" style="align-self:flex-end" onclick="registrarLN()">+ REGISTRAR</button>
      </div>
    </div>
    <div class="st">Historial Loma Negra</div>
    <div id="ln-lista"></div>
  </div>

  <!-- PALLETS -->
  <div id="page-pallets" class="page">
    <div class="card">
      <div class="card-t">Registrar movimiento de pallets</div>
      <div class="fr">
        <div class="fg" style="max-width:120px"><label>N° Remito</label><input type="text" id="pal-remito" placeholder="12345" inputmode="numeric"></div>
        <div class="fg"><label>Cliente / Origen</label><input type="text" id="pal-cliente" placeholder="Nombre"></div>
        <div class="fg" style="max-width:180px"><label>Movimiento</label>
          <select id="pal-tipo"><option value="devolvio">Devolvió pallets</option><option value="retiro">Retiró pallets (debe)</option><option value="adelanto">Trajo por adelantado</option><option value="propio">Ingreso propio</option></select>
        </div>
        <div class="fg" style="max-width:95px"><label>Cantidad</label><input type="number" id="pal-cantidad" placeholder="0" inputmode="numeric" min="1"></div>
        <button class="btn btn-r" style="align-self:flex-end" onclick="cargarPallet()">+ REGISTRAR</button>
      </div>
    </div>
    <div class="st">Saldos por cliente</div>
    <div id="pallets-saldos" class="saldo-g"></div>
    <div class="st">Movimientos del día</div>
    <div id="pallets-lista"></div>
  </div>

  <!-- STOCK -->
  <div id="page-stock" class="page">
    <div class="st">Stock actual</div>
    <div id="stock-grid" class="sg"></div>
    <div class="card" id="stock-edit-card" style="display:none">
      <div class="card-t">Modificar stock inicial</div>
      <div class="fr" id="stock-edit-row"></div>
      <button class="btn btn-r" onclick="guardarStockInicial()">GUARDAR STOCK INICIAL</button>
    </div>
    <div class="st">Diferencias del día</div>
    <div id="sum-diffs"></div>
    <div class="st">Todos los remitos</div>
    <div class="card" style="padding:0;overflow:hidden">
      <table class="tbl"><thead><tr><th>Remito</th><th>Ítem</th><th>Facturado</th><th>Autorizado</th><th>Cargado</th><th>Pendiente</th><th>Estado</th><th>Hora</th></tr></thead>
      <tbody id="sum-tbody"></tbody></table>
    </div>
    <div style="margin-top:14px;display:flex;gap:8px;flex-wrap:wrap">
      <button class="btn btn-s" onclick="exportarCSV()">⬇ CSV</button>
      <button class="btn btn-s" onclick="copiarResumen()">📋 Copiar resumen</button>
    </div>
  </div>

  <!-- GLOBAL -->
  <div id="page-global" class="page">
    <div class="suc-sel" id="suc-selector"></div>
    <div id="global-content"></div>
  </div>

  <!-- ADMIN -->
  <div id="page-admin" class="page">
    <div class="card">
      <div class="card-t">Google Sheets — Apps Script</div>
      <div class="cff"><label>URL del Apps Script</label><input type="url" id="cfg-script" placeholder="https://script.google.com/macros/s/..."></div>
      <div style="display:flex;gap:8px;flex-wrap:wrap">
        <button class="btn btn-r" onclick="guardarConfig()">GUARDAR</button>
        <button class="btn btn-s" onclick="forzarSync()">↺ Forzar sincronización</button>
      </div>
    </div>
    <div class="card">
      <div class="card-t">Gestión de usuarios</div>
      <p style="font-size:12px;color:var(--muted2);margin-bottom:14px;line-height:1.6">
        Los usuarios se gestionan en Google Sheets en la pestaña <strong style="color:var(--text)">Usuarios</strong>.<br>
        Columnas: <strong style="color:var(--text)">usuario | clave | rol | sucursal | nombre</strong><br><br>
        Roles válidos: <span style="color:var(--yellow)">operario_panol</span> · <span style="color:var(--yellow)">operario_puerta</span> · <span style="color:var(--yellow)">encargado</span> · <span style="color:var(--yellow)">coordinador</span> · <span style="color:var(--yellow)">propietario</span><br>
        Sucursales: <span style="color:var(--yellow)">triangulo</span> · <span style="color:var(--yellow)">entrerios</span> · <span style="color:var(--yellow)">armaduras</span> · <span style="color:var(--yellow)">ruta</span>
      </p>
      <div id="users-lista"></div>
      <button class="btn btn-s" style="margin-top:10px" onclick="cargarUsuarios()">↺ Recargar usuarios</button>
    </div>
    <div class="card">
      <div class="card-t">Código Apps Script</div>
      <p style="font-size:12px;color:var(--muted2);margin-bottom:12px;line-height:1.6">Copiá y pegá en Apps Script. Publicar como aplicación web — acceso: cualquier persona.</p>
      <button class="btn btn-s" onclick="copiarScript()">📋 Copiar código completo</button>
    </div>
  </div>
</div>

<script>
// ══════════════════════════════════════════════════
// CONSTANTES
// ══════════════════════════════════════════════════
const ITEMS = ['cemento','cal','calhidratada','plasticor'];
const IL = {cemento:'Cemento',cal:'Cal',calhidratada:'Cal Hidratada',plasticor:'Plasticor'};
const SUCS = {triangulo:'El Triángulo',entrerios:'Entre Ríos',armaduras:'Armaduras',ruta:'Ruta',cliente:'Cliente'};
const SUCS_LIST = ['triangulo','entrerios','armaduras','ruta'];
const ROLES_L = {propietario:'Propietario',coordinador:'Coordinador',encargado:'Encargado',operario_panol:'Op. Pañol',operario_puerta:'Op. Puerta'};
const SCRIPT_KEY = 'dep_script_v4';

// ══════════════════════════════════════════════════
// STATE
// ══════════════════════════════════════════════════
let session = null;
let scriptURL = localStorage.getItem(SCRIPT_KEY) || '';

function emptyState(suc) {
  return { suc, remitos:[], viajes:[], fabrica:[], pallets:[], ln:[], stockInicial:{cemento:0,cal:0,calhidratada:0,plasticor:0,pallets:0} };
}
let states = {};
function getState(suc){ if(!states[suc]) states[suc]=emptyState(suc); return states[suc]; }
function curState(){ return getState(session?.sucursal||'triangulo'); }

// Global data (cross-sucursal)
let globalData = { remitosGlobal:[], viajesGlobal:[] };

// ══════════════════════════════════════════════════
// LOCAL STORAGE + SYNC
// ══════════════════════════════════════════════════
function todayKey(){ const d=new Date(); return `${d.getFullYear()}-${d.getMonth()}-${d.getDate()}`; }

function saveLocal(){
  localStorage.setItem('dep_v4_'+todayKey(), JSON.stringify({states, globalData}));
}

function loadLocal(){
  const s=localStorage.getItem('dep_v4_'+todayKey());
  if(s) try{ const d=JSON.parse(s); states=d.states||{}; globalData=d.globalData||{remitosGlobal:[],viajesGlobal:[]}; }catch(e){}
}

function setSyncStatus(st){ // 'syncing'|'ok'|'err'|'idle'
  const dot=document.getElementById('syncDot');
  if(!dot) return;
  dot.className='sync-dot'+(st==='idle'?'':' '+st);
}

async function syncToSheets(action, data){
  if(!scriptURL){ saveLocal(); return; }
  setSyncStatus('syncing');
  try{
    await fetch(scriptURL,{method:'POST',mode:'no-cors',body:JSON.stringify({action,data}),headers:{'Content-Type':'text/plain'}});
    setSyncStatus('ok');
    setTimeout(()=>setSyncStatus('idle'),2000);
  }catch(e){ setSyncStatus('err'); console.warn('sync',e); }
  saveLocal();
}

async function loadFromSheets(suc){
  if(!scriptURL) return;
  setSyncStatus('syncing');
  try{
    const res=await fetch(scriptURL+`?action=getData&suc=${suc}&t=`+Date.now());
    if(!res.ok) throw new Error('bad response');
    const d=await res.json();
    if(d.remitos)      getState(suc).remitos      = d.remitos;
    if(d.viajes)       getState(suc).viajes        = d.viajes;
    if(d.fabrica)      getState(suc).fabrica       = d.fabrica;
    if(d.pallets)      getState(suc).pallets       = d.pallets;
    if(d.ln)           getState(suc).ln            = d.ln;
    if(d.stockInicial) getState(suc).stockInicial  = d.stockInicial;
    setSyncStatus('ok');
    setTimeout(()=>setSyncStatus('idle'),2000);
  }catch(e){ setSyncStatus('err'); console.warn('load',e); }
  saveLocal(); renderAll();
}

async function loadGlobalData(){
  if(!scriptURL) return;
  try{
    const res=await fetch(scriptURL+'?action=getGlobal&t='+Date.now());
    if(!res.ok) return;
    const d=await res.json();
    if(d.remitosGlobal) globalData.remitosGlobal=d.remitosGlobal;
    if(d.viajesGlobal)  globalData.viajesGlobal=d.viajesGlobal;
  }catch(e){ console.warn('loadGlobal',e); }
  saveLocal(); renderAll();
}

async function forzarSync(){
  if(!session) return;
  const sucs=canSeeAll()?SUCS_LIST:[session.sucursal];
  for(const s of sucs) await loadFromSheets(s);
  await loadGlobalData();
  toast('Sincronización completa','ok');
}

// ══════════════════════════════════════════════════
// LOGIN
// ══════════════════════════════════════════════════
async function doLogin(){
  const user=document.getElementById('l-user').value.trim().toLowerCase();
  const pass=document.getElementById('l-pass').value.trim();
  if(!user||!pass){ showErr('Completá usuario y contraseña'); return; }

  document.getElementById('login-btn').style.display='none';
  document.getElementById('login-loading').style.display='block';

  let found=null;
  if(scriptURL){
    try{
      const res=await fetch(scriptURL+`?action=auth&u=${encodeURIComponent(user)}&p=${encodeURIComponent(pass)}&t=`+Date.now());
      if(res.ok){ const d=await res.json(); if(d.ok) found=d.user; }
    }catch(e){}
  }
  // fallback admin local
  if(!found && user==='admin' && pass==='admin123')
    found={usuario:'admin',nombre:'Administrador',rol:'propietario',sucursal:'triangulo'};

  document.getElementById('login-btn').style.display='block';
  document.getElementById('login-loading').style.display='none';

  if(!found){ showErr('Usuario o contraseña incorrectos'); return; }
  session=found;
  sessionStorage.setItem('dep_session_v4', JSON.stringify(session));
  startApp();
}

function showErr(msg){ const e=document.getElementById('login-err'); e.textContent=msg; e.style.display='block'; setTimeout(()=>e.style.display='none',3000); }
document.getElementById('l-pass').addEventListener('keydown',e=>{if(e.key==='Enter')doLogin();});
document.getElementById('l-user').addEventListener('keydown',e=>{if(e.key==='Enter')document.getElementById('l-pass').focus();});

function doLogout(){
  sessionStorage.removeItem('dep_session_v4');
  session=null;
  document.getElementById('app').style.display='none';
  document.getElementById('login-screen').style.display='flex';
  document.getElementById('l-user').value='';
  document.getElementById('l-pass').value='';
}

// ══════════════════════════════════════════════════
// START APP
// ══════════════════════════════════════════════════
function canSeeAll(){ return ['coordinador','propietario'].includes(session?.rol); }
function canEdit(){ return ['encargado','coordinador','propietario'].includes(session?.rol); }

function startApp(){
  document.getElementById('login-screen').style.display='none';
  document.getElementById('app').style.display='block';
  document.getElementById('hdr-user').textContent=session.nombre;
  document.getElementById('hdr-rol').textContent=ROLES_L[session.rol]||session.rol;
  document.getElementById('hdr-suc').textContent=canSeeAll()?'Todas':SUCS[session.sucursal]||session.sucursal;
  if(canEdit()) document.getElementById('btn-reset').style.display='';
  if(canEdit()) document.getElementById('stock-edit-card').style.display='';
  document.getElementById('cfg-script').value=scriptURL;

  // setup tabs
  let firstTab=null;
  document.querySelectorAll('.tab').forEach(btn=>{
    const roles=btn.dataset.roles?btn.dataset.roles.split(','):[];
    const vis=roles.includes(session.rol);
    btn.style.display=vis?'':'none';
    if(vis&&!firstTab) firstTab=btn;
  });
  document.querySelectorAll('.tab').forEach(t=>t.classList.remove('active'));
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  if(firstTab){ firstTab.classList.add('active'); document.getElementById('page-'+firstTab.dataset.page).classList.add('active'); }

  initGlobalSelector();
  loadLocal();
  const sucs=canSeeAll()?SUCS_LIST:[session.sucursal];
  sucs.forEach(s=>{ if(!states[s]) states[s]=emptyState(s); if(scriptURL) loadFromSheets(s); });
  if(scriptURL) loadGlobalData();
  renderAll();

  // auto-refresh every 30s
  setInterval(()=>{ if(scriptURL){ const sucs2=canSeeAll()?SUCS_LIST:[session.sucursal]; sucs2.forEach(s=>loadFromSheets(s)); loadGlobalData(); }},30000);
}

// ══════════════════════════════════════════════════
// NAV
// ══════════════════════════════════════════════════
function goTab(btn){
  document.querySelectorAll('.tab').forEach(t=>t.classList.remove('active'));
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  btn.classList.add('active');
  document.getElementById('page-'+btn.dataset.page).classList.add('active');
  renderAll();
}

// ══════════════════════════════════════════════════
// PAÑOL
// ══════════════════════════════════════════════════
function checkRemitoParcial(){
  const num=document.getElementById('p-remito').value.trim();
  const alertDiv=document.getElementById('panol-partial-alert');
  if(!num){ alertDiv.innerHTML=''; return; }
  // search in globalData
  const partial=(globalData.remitosGlobal||[]).find(r=>r.remito===num&&r.estado==='parcial');
  if(partial){
    alertDiv.innerHTML=`<div class="partial-alert">⚠ <strong>Remito ${esc(num)}</strong> tiene una entrega parcial abierta en <strong>${SUCS[partial.sucursalOrigen]||partial.sucursalOrigen}</strong>. Retirado: ${partial.cargada} · <strong>Pendiente: ${partial.pendiente}</strong>. Se completará automáticamente al confirmar en puerta.</div>`;
    // pre-fill
    document.getElementById('p-autorizada').value=partial.pendiente;
    if(partial.item) document.getElementById('p-item').value=partial.item;
  } else {
    alertDiv.innerHTML='';
  }
}

function cargarPanol(){
  const remito=document.getElementById('p-remito').value.trim();
  const item=document.getElementById('p-item').value;
  const fac=parseInt(document.getElementById('p-facturada').value)||0;
  const aut=parseInt(document.getElementById('p-autorizada').value)||0;
  const pals=parseInt(document.getElementById('p-pallets').value)||0;
  const obs=document.getElementById('p-obs').value.trim();
  if(!remito){ toast('Ingresá N° remito','err'); return; }
  if(fac<=0){ toast('Ingresá cant. facturada','err'); return; }
  if(aut<=0){ toast('Ingresá cant. autorizada','err'); return; }

  // check if completing a partial
  const partial=(globalData.remitosGlobal||[]).find(r=>r.remito===remito&&r.estado==='parcial');
  const isCompletion=!!partial;

  const entry={
    id:Date.now(),remito,item,facturada:fac,autorizada:aut,pallets:pals,
    cargada:null,obs,hora:hora(),estado:'espera',
    sucursal:session.sucursal,usuario:session.usuario,
    parcial:false,pendiente:aut,
    esCompletacion:isCompletion,parcialOriginalId:partial?.id||null
  };
  curState().remitos.push(entry);

  // update globalData
  if(!globalData.remitosGlobal) globalData.remitosGlobal=[];
  globalData.remitosGlobal=globalData.remitosGlobal.filter(r=>!(r.remito===remito&&r.estado==='parcial'));
  globalData.remitosGlobal.push({id:entry.id,remito,item,facturada:fac,autorizada:aut,estado:'espera',sucursalOrigen:session.sucursal,cargada:null,pendiente:aut,hora:hora()});

  saveLocal();
  syncToSheets('addRemito',{suc:session.sucursal,data:entry});
  syncToSheets('updateGlobalRemito',{data:{id:entry.id,remito,item,facturada:fac,autorizada:aut,estado:'espera',sucursalOrigen:session.sucursal,cargada:null,pendiente:aut,hora:hora()}});
  renderAll();
  toast('Remito '+remito+(isCompletion?' (completación parcial)':'')+' registrado','ok');
  ['p-remito','p-facturada','p-autorizada','p-pallets','p-obs'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('panol-partial-alert').innerHTML='';
  document.getElementById('p-remito').focus();
}

function editarAutorizado(id){
  const r=curState().remitos.find(x=>x.id===id); if(!r) return;
  const span=document.getElementById('aut-val-'+id); if(!span) return;
  span.outerHTML=`<input id="aut-inp-${id}" type="number" inputmode="numeric" min="1"
    style="background:var(--bg);border:2px solid var(--blue);color:var(--text);padding:5px 7px;border-radius:3px;font-family:var(--cond);font-size:15px;font-weight:700;width:70px;text-align:center"
    value="${r.autorizada}" onkeydown="if(event.key==='Enter')guardarAutorizado(${id})" onblur="guardarAutorizado(${id})">`;
  setTimeout(()=>{ const i=document.getElementById('aut-inp-'+id); if(i){i.focus();i.select();} },50);
}

function guardarAutorizado(id){
  const inp=document.getElementById('aut-inp-'+id); if(!inp) return;
  const r=curState().remitos.find(x=>x.id===id); if(!r) return;
  const val=parseInt(inp.value);
  if(isNaN(val)||val<=0){ renderAll(); return; }
  const ant=r.autorizada; r.autorizada=val; r.pendiente=val;
  // update global
  const gr=(globalData.remitosGlobal||[]).find(x=>x.id===id);
  if(gr){ gr.autorizada=val; gr.pendiente=val; }
  saveLocal();
  syncToSheets('updateRemito',{suc:session.sucursal,data:r});
  syncToSheets('updateGlobalRemito',{data:{id,autorizada:val,pendiente:val}});
  renderAll();
  toast(`Autorizado actualizado: ${ant} → ${val}`,'ok');
}

function renderPanol(){
  const st=curState();
  const lista=document.getElementById('panol-lista');
  if(!st.remitos.length){ lista.innerHTML='<div class="empty">— Sin remitos hoy —</div>'; return; }
  const bM={espera:'b-w',ok:'b-ok',diferencia:'b-d',parcial:'b-p'};
  const lM={espera:'⏳ Esperando',ok:'✓ OK',diferencia:'⚠ Diferencia',parcial:'↩ Parcial'};
  lista.innerHTML=`<div class="card" style="padding:0;overflow:hidden"><table class="tbl">
    <thead><tr><th>Remito</th><th>Ítem</th><th>Facturado</th><th>Autorizado</th><th>Pallets</th><th>Cargado</th><th>Estado</th><th>Hora</th></tr></thead>
    <tbody>${[...st.remitos].reverse().map(r=>`<tr>
      <td style="font-family:var(--cond);font-size:14px;font-weight:800">${esc(r.remito)}${r.esCompletacion?'<br><span style="font-size:9px;color:var(--blue)">completación</span>':''}</td>
      <td><span class="it it-${itC(r.item)}">${IL[r.item]||r.item}</span></td>
      <td style="font-family:var(--cond)">${r.facturada}</td>
      <td style="font-family:var(--cond);color:var(--yellow)">
        ${r.estado==='espera'
          ?`<span id="aut-val-${r.id}">${r.autorizada}</span><button class="btn btn-s btn-sm" style="padding:3px 7px;font-size:10px;margin-left:4px" onclick="editarAutorizado(${r.id})">✏</button>`
          :r.autorizada}
      </td>
      <td style="font-family:var(--cond);color:var(--green)">${r.pallets||'—'}</td>
      <td style="font-family:var(--cond);color:var(--green)">${r.cargada!==null?r.cargada:'—'}</td>
      <td><span class="badge ${bM[r.estado]||'b-w'}">${lM[r.estado]||r.estado}</span></td>
      <td style="color:var(--muted);font-size:10px">${r.hora}</td>
    </tr>`).join('')}</tbody></table></div>`;
}

// ══════════════════════════════════════════════════
// PUERTA
// ══════════════════════════════════════════════════
function renderPuerta(){
  const st=curState();
  const pend=st.remitos.filter(r=>r.estado==='espera');
  const conf=st.remitos.filter(r=>r.estado!=='espera');
  const diff=st.remitos.filter(r=>r.estado==='diferencia');
  const cnt=document.getElementById('cntPuerta');
  cnt.textContent=pend.length; cnt.classList.toggle('show',pend.length>0);

  document.getElementById('puerta-diffs').innerHTML=diff.length
    ?diff.map(r=>`<div class="diff-alert">⚠ <strong>Remito ${esc(r.remito)}</strong> — Autorizado: ${r.autorizada} | Cargado: ${r.cargada} | Dif: ${Math.abs(r.autorizada-r.cargada)}</div>`).join(''):'';

  document.getElementById('puerta-pendientes').innerHTML=pend.length
    ?pend.map(r=>buildCrow(r)).join('')
    :'<div class="empty">— Sin pendientes —</div>';

  document.getElementById('puerta-confirmados').innerHTML=conf.length
    ?[...conf].reverse().map(r=>`<div class="crow done">
        <div class="crow-info">
          <div class="crow-rem">${esc(r.remito)} <span class="it it-${itC(r.item)}" style="font-size:9px">${IL[r.item]||r.item}</span></div>
          <div class="crow-sub">Aut: ${r.autorizada} | Carg: ${r.cargada}${r.parcial?' | <span style="color:var(--yellow)">Pendiente: '+r.pendiente+'</span>':''}</div>
        </div>
        <span class="badge ${r.estado==='ok'?'b-ok':r.estado==='parcial'?'b-p':'b-d'}">${r.estado==='ok'?'✓ OK':r.estado==='parcial'?'↩ Parcial':'⚠ Dif.'}</span>
      </div>`).join('')
    :'<div class="empty">— Ninguno —</div>';
}

function buildCrow(r){
  return `<div class="crow" id="crow-${r.id}">
    <div class="crow-info">
      <div class="crow-rem">${esc(r.remito)} <span class="it it-${itC(r.item)}" style="font-size:9px">${IL[r.item]||r.item}</span>${r.pallets?` <span class="it it-pal" style="font-size:9px">${r.pallets} pal.</span>`:''}</div>
      <div class="crow-sub">${r.obs||'Sin obs.'} · ${r.hora}${r.esCompletacion?' · <span style="color:var(--blue)">completación parcial</span>':''}</div>
    </div>
    <div class="crow-aut">${r.autorizada}<span>autorizado</span></div>
    <div style="display:flex;flex-direction:column;gap:4px">
      <div style="display:flex;gap:6px;align-items:center">
        <input class="cinp" type="number" inputmode="numeric" placeholder="?" id="ci-${r.id}" oninput="checkMatch(${r.id})" min="0">
        <button class="btn btn-g btn-sm" onclick="confirmarPuerta(${r.id})">✓ OK</button>
        <button class="btn btn-s btn-sm" onclick="marcarParcial(${r.id})">↩ Parcial</button>
      </div>
      <div class="lock-msg" id="lock-${r.id}">⛔ No coincide — pedí a pañol que modifique el autorizado</div>
    </div>
  </div>`;
}

function checkMatch(id){
  const r=curState().remitos.find(x=>x.id===id); if(!r) return;
  const inp=document.getElementById('ci-'+id), val=parseInt(inp.value);
  const match=!isNaN(val)&&val===r.autorizada;
  const noMatch=!isNaN(val)&&val!==r.autorizada;
  inp.classList.toggle('match',match);
  inp.classList.toggle('nomatch',noMatch);
  const lockMsg=document.getElementById('lock-'+id);
  if(lockMsg) lockMsg.style.display=noMatch?'block':'none';
}

function confirmarPuerta(id){
  const r=curState().remitos.find(x=>x.id===id); if(!r) return;
  const val=parseInt(document.getElementById('ci-'+id).value);
  if(isNaN(val)||val<0){ toast('Ingresá cantidad cargada','err'); return; }
  if(val!==r.autorizada){
    const lockMsg=document.getElementById('lock-'+id);
    if(lockMsg) lockMsg.style.display='block';
    toast('⛔ No coincide (aut: '+r.autorizada+'). Pedí a pañol que modifique','err');
    return;
  }
  r.cargada=val; r.estado='ok'; r.parcial=false; r.pendiente=0;
  updateGlobalRemito(r,'ok');
  saveLocal(); syncToSheets('updateRemito',{suc:session.sucursal,data:r}); renderAll();
  toast('✓ Confirmado — coincide','ok');
}

function marcarParcial(id){
  const r=curState().remitos.find(x=>x.id===id); if(!r) return;
  const val=parseInt(document.getElementById('ci-'+id).value);
  if(isNaN(val)||val<0){ toast('Ingresá cantidad cargada','err'); return; }
  if(val>=r.autorizada){ toast('Si cargó todo usá ✓ OK','err'); return; }
  r.cargada=val; r.estado='parcial'; r.parcial=true; r.pendiente=r.autorizada-val;
  updateGlobalRemito(r,'parcial');
  saveLocal(); syncToSheets('updateRemito',{suc:session.sucursal,data:r}); renderAll();
  toast(`↩ Parcial — quedan ${r.pendiente} pendientes`,'ok');
}

function updateGlobalRemito(r, estado){
  if(!globalData.remitosGlobal) globalData.remitosGlobal=[];
  const gr=globalData.remitosGlobal.find(x=>x.id===r.id);
  if(gr){ gr.estado=estado; gr.cargada=r.cargada; gr.pendiente=r.pendiente; }
  else { globalData.remitosGlobal.push({id:r.id,remito:r.remito,item:r.item,facturada:r.facturada,autorizada:r.autorizada,estado,sucursalOrigen:session.sucursal,cargada:r.cargada,pendiente:r.pendiente,hora:r.hora}); }
  syncToSheets('updateGlobalRemito',{data:{id:r.id,estado,cargada:r.cargada,pendiente:r.pendiente}});
}

// ══════════════════════════════════════════════════
// VIAJES
// ══════════════════════════════════════════════════
function registrarSalida(){
  const remito=document.getElementById('v-remito').value.trim();
  const chofer=document.getElementById('v-chofer').value.trim();
  const destino=document.getElementById('v-destino').value;
  const item=document.getElementById('v-item').value;
  const cant=parseInt(document.getElementById('v-cantidad').value)||0;
  const pallets=parseInt(document.getElementById('v-pallets').value)||0;
  if(!chofer){ toast('Ingresá el chofer','err'); return; }

  const parada0={sucursal:session.sucursal,tipo:'salida',item,cantidad:cant,pallets,hora:hora(),usuario:session.usuario,destino};
  const entry={id:Date.now(),remito,chofer,sucursalOrigen:session.sucursal,destino,
    paradas:[parada0],hora:hora(),estado:'abierto',
    regresoPallets:null,regresoMaterial:0,regresoHora:null,usuario:session.usuario};

  curState().viajes.push(entry);
  // add to global viajes
  if(!globalData.viajesGlobal) globalData.viajesGlobal=[];
  globalData.viajesGlobal.push({...entry});

  saveLocal();
  syncToSheets('addViaje',{suc:session.sucursal,data:entry});
  syncToSheets('updateGlobalViaje',{data:entry});
  renderAll();
  toast('Salida registrada — '+chofer,'ok');
  ['v-remito','v-chofer','v-cantidad','v-pallets'].forEach(id=>document.getElementById(id).value='');
}

function agregarParada(viajeId){
  const item=document.getElementById('vp-item-'+viajeId)?.value;
  const tipo=document.getElementById('vp-tipo-'+viajeId)?.value;
  const cant=parseInt(document.getElementById('vp-cant-'+viajeId)?.value)||0;
  const pals=parseInt(document.getElementById('vp-pal-'+viajeId)?.value)||0;

  // Find viaje in any state
  let viaje=null, vSuc=null;
  SUCS_LIST.forEach(s=>{ const v=getState(s).viajes.find(x=>x.id===viajeId); if(v){viaje=v;vSuc=s;} });
  if(!viaje) return;

  const parada={sucursal:session.sucursal,tipo,item,cantidad:cant,pallets:pals,hora:hora(),usuario:session.usuario};
  if(!viaje.paradas) viaje.paradas=[];
  viaje.paradas.push(parada);

  // update global
  const gv=(globalData.viajesGlobal||[]).find(x=>x.id===viajeId);
  if(gv){ if(!gv.paradas) gv.paradas=[]; gv.paradas.push(parada); }

  saveLocal();
  syncToSheets('updateViaje',{suc:vSuc,data:viaje});
  syncToSheets('updateGlobalViaje',{data:{id:viajeId,paradas:viaje.paradas}});
  renderAll();
  toast('Parada registrada','ok');
}

function cerrarViaje(viajeId){
  const rpal=parseInt(document.getElementById('vr-pal-'+viajeId)?.value)||0;
  const rmat=parseInt(document.getElementById('vr-mat-'+viajeId)?.value)||0;

  let viaje=null, vSuc=null;
  SUCS_LIST.forEach(s=>{ const v=getState(s).viajes.find(x=>x.id===viajeId); if(v){viaje=v;vSuc=s;} });
  // also check globalData
  if(!viaje){ viaje=(globalData.viajesGlobal||[]).find(x=>x.id===viajeId); vSuc=viaje?.sucursalOrigen; }
  if(!viaje) return;

  viaje.regresoPallets=rpal; viaje.regresoMaterial=rmat; viaje.regresoHora=hora(); viaje.estado='cerrado';
  const paradaCierre={sucursal:session.sucursal,tipo:'cierre',pallets:rpal,cantidad:rmat,hora:hora(),usuario:session.usuario};
  if(!viaje.paradas) viaje.paradas=[];
  viaje.paradas.push(paradaCierre);

  const gv=(globalData.viajesGlobal||[]).find(x=>x.id===viajeId);
  if(gv){ Object.assign(gv,{regresoPallets:rpal,regresoMaterial:rmat,regresoHora:hora(),estado:'cerrado',paradas:viaje.paradas}); }

  saveLocal();
  if(vSuc) syncToSheets('updateViaje',{suc:vSuc,data:viaje});
  syncToSheets('updateGlobalViaje',{data:{id:viajeId,estado:'cerrado',regresoPallets:rpal,regresoMaterial:rmat,regresoHora:hora(),paradas:viaje.paradas}});
  renderAll();
  toast('✓ Viaje cerrado','ok');
}

function renderViajes(){
  // All open viajes from globalData + local
  const allOpen=[];
  const seen=new Set();
  (globalData.viajesGlobal||[]).filter(v=>v.estado==='abierto').forEach(v=>{ if(!seen.has(v.id)){seen.add(v.id);allOpen.push(v);} });
  SUCS_LIST.forEach(s=>getState(s).viajes.filter(v=>v.estado==='abierto').forEach(v=>{ if(!seen.has(v.id)){seen.add(v.id);allOpen.push(v);} }));

  const allClosed=[...curState().viajes.filter(v=>v.estado==='cerrado')];

  const cnt=document.getElementById('cntViajes');
  cnt.textContent=allOpen.length; cnt.classList.toggle('show',allOpen.length>0);

  document.getElementById('viajes-abiertos').innerHTML=allOpen.length
    ?allOpen.map(v=>buildViajeRow(v,true)).join('')
    :'<div class="empty">— Sin viajes abiertos —</div>';

  document.getElementById('viajes-cerrados').innerHTML=allClosed.length
    ?[...allClosed].reverse().map(v=>buildViajeRow(v,false)).join('')
    :'<div class="empty">— Sin cerrados hoy —</div>';
}

function buildViajeRow(v, open){
  const isMine=v.sucursalOrigen===session.sucursal;
  const paradas=(v.paradas||[]);
  const paradaHtml=paradas.map(p=>{
    if(p.tipo==='salida') return `<div class="parada-item entrega">🚛 Salida desde ${SUCS[p.sucursal]||p.sucursal} · ${p.item!=='ninguno'?p.cantidad+' '+(IL[p.item]||p.item)+' + ':''}${p.pallets} pal. → ${SUCS[v.destino]||v.destino} · ${p.hora}</div>`;
    if(p.tipo==='cierre') return `<div class="parada-item paso">🏁 Regreso a ${SUCS[p.sucursal]||p.sucursal} · ${p.pallets} pal. traídos${p.cantidad?' · '+p.cantidad+' mat. no entregado':''} · ${p.hora}</div>`;
    return `<div class="parada-item ${p.tipo}">📍 ${SUCS[p.sucursal]||p.sucursal} · ${p.tipo==='entrega'?'Entregó':'Retiró'}: ${p.cantidad?p.cantidad+' '+(IL[p.item]||p.item)+' + ':''}${p.pallets} pal. · ${p.hora}</div>`;
  }).join('');

  if(!open) return `<div class="vrow" style="opacity:0.45">
    <div class="vrow-head">
      <div class="vrow-chofer">${esc(v.chofer)}</div>
      <span class="badge b-ok">✓ Cerrado</span>
      <div class="vrow-info">${SUCS[v.sucursalOrigen]||v.sucursalOrigen} · ${v.hora}</div>
    </div>
    ${paradaHtml}
  </div>`;

  return `<div class="vrow">
    <div class="vrow-head">
      <div class="vrow-chofer">${esc(v.chofer)}</div>
      <span class="badge b-o">🚛 En ruta</span>
      <div class="vrow-info">${SUCS[v.sucursalOrigen]||v.sucursalOrigen} → ${SUCS[v.destino]||v.destino} · ${v.hora}${v.remito?' · rem. '+esc(v.remito):''}</div>
      ${!isMine?`<span class="badge b-m" style="font-size:9px">${SUCS[v.sucursalOrigen]||v.sucursalOrigen}</span>`:''}
    </div>
    ${paradaHtml}
    <div style="margin-top:10px;background:var(--bg);border:1px solid var(--border);border-radius:5px;padding:10px">
      <div style="font-family:var(--cond);font-size:10px;font-weight:700;letter-spacing:0.14em;text-transform:uppercase;color:var(--muted);margin-bottom:8px">Agregar parada</div>
      <div style="display:flex;gap:6px;flex-wrap:wrap;align-items:flex-end">
        <div class="fg" style="max-width:120px"><label>Tipo</label>
          <select id="vp-tipo-${v.id}" style="background:var(--bg3);border:1px solid var(--border2);color:var(--text);padding:7px;border-radius:4px;font-size:13px">
            <option value="entrega">Entrega</option><option value="retiro">Retiro</option><option value="paso">Paso/Tránsito</option>
          </select>
        </div>
        <div class="fg" style="max-width:140px"><label>Ítem</label>
          <select id="vp-item-${v.id}" style="background:var(--bg3);border:1px solid var(--border2);color:var(--text);padding:7px;border-radius:4px;font-size:13px">
            <option value="cemento">Cemento</option><option value="cal">Cal</option><option value="calhidratada">Cal Hid.</option><option value="plasticor">Plasticor</option><option value="ninguno">Sin material</option>
          </select>
        </div>
        <div class="fg" style="max-width:85px"><label>Cantidad</label><input type="number" id="vp-cant-${v.id}" placeholder="0" inputmode="numeric" min="0" style="background:var(--bg3);border:1px solid var(--border2);color:var(--text);padding:7px;border-radius:4px;font-size:14px"></div>
        <div class="fg" style="max-width:85px"><label>Pallets</label><input type="number" id="vp-pal-${v.id}" placeholder="0" inputmode="numeric" min="0" style="background:var(--bg3);border:1px solid var(--border2);color:var(--text);padding:7px;border-radius:4px;font-size:14px"></div>
        <button class="btn btn-s btn-sm" onclick="agregarParada(${v.id})">+ Parada</button>
      </div>
      ${isMine?`<div style="border-top:1px solid var(--border);margin-top:10px;padding-top:10px">
        <div style="font-family:var(--cond);font-size:10px;font-weight:700;letter-spacing:0.14em;text-transform:uppercase;color:var(--green);margin-bottom:8px">Cerrar viaje (regresó a base)</div>
        <div style="display:flex;gap:6px;flex-wrap:wrap;align-items:flex-end">
          <div class="fg" style="max-width:120px"><label>Pallets que trajo</label><input type="number" id="vr-pal-${v.id}" placeholder="0" inputmode="numeric" min="0" style="background:var(--bg3);border:1px solid var(--border2);color:var(--text);padding:7px;border-radius:4px;font-size:14px"></div>
          <div class="fg" style="max-width:120px"><label>Mat. no entregado</label><input type="number" id="vr-mat-${v.id}" placeholder="0" inputmode="numeric" min="0" style="background:var(--bg3);border:1px solid var(--border2);color:var(--text);padding:7px;border-radius:4px;font-size:14px"></div>
          <button class="btn btn-g btn-sm" onclick="cerrarViaje(${v.id})">✓ REGRESÓ</button>
        </div>
      </div>`:'<div style="font-size:11px;color:var(--muted);margin-top:8px;border-top:1px solid var(--border);padding-top:8px">Solo la sucursal de origen ('+( SUCS[v.sucursalOrigen]||v.sucursalOrigen)+') puede cerrar este viaje</div>'}
    </div>
  </div>`;
}

// ══════════════════════════════════════════════════
// FÁBRICA
// ══════════════════════════════════════════════════
function registrarFabrica(){
  const item=document.getElementById('f-item').value;
  const cant=parseInt(document.getElementById('f-cantidad').value)||0;
  const ptrae=parseInt(document.getElementById('f-ptrae').value)||0;
  const plleva=parseInt(document.getElementById('f-plleva').value)||0;
  if(cant<=0){ toast('Ingresá la cantidad','err'); return; }
  const entry={id:Date.now(),item,cantidad:cant,ptrae,plleva,hora:hora(),sucursal:session.sucursal,usuario:session.usuario,fecha:fechaHoy()};
  curState().fabrica.push(entry);
  saveLocal(); syncToSheets('addFabrica',{suc:session.sucursal,data:entry}); renderAll();
  toast('Ingreso de fábrica registrado','ok');
  ['f-cantidad','f-ptrae','f-plleva'].forEach(id=>document.getElementById(id).value='');
}

function renderFabrica(){
  const lista=document.getElementById('fabrica-lista');
  const fab=curState().fabrica;
  if(!fab.length){ lista.innerHTML='<div class="empty">— Sin ingresos hoy —</div>'; return; }
  const total=fab.reduce((a,f)=>({cant:a.cant+f.cantidad,ptrae:a.ptrae+f.ptrae,plleva:a.plleva+f.plleva}),{cant:0,ptrae:0,plleva:0});
  lista.innerHTML=`<div class="sumr">
    <div class="sumbox"><div class="sumbox-l">Viajes</div><div class="sumbox-v">${fab.length}</div></div>
    <div class="sumbox"><div class="sumbox-l">Total ingresado</div><div class="sumbox-v y">${total.cant}</div></div>
    <div class="sumbox"><div class="sumbox-l">Pallets recibidos</div><div class="sumbox-v g">${total.ptrae}</div></div>
    <div class="sumbox"><div class="sumbox-l">Pallets devueltos</div><div class="sumbox-v r">${total.plleva}</div></div>
  </div>
  <div class="card" style="padding:0;overflow:hidden"><table class="tbl">
    <thead><tr><th>Ítem</th><th>Cantidad</th><th>Pal. trajo</th><th>Pal. llevó</th><th>Hora</th></tr></thead>
    <tbody>${[...fab].reverse().map(f=>`<tr>
      <td><span class="it it-${itC(f.item)}">${IL[f.item]||f.item}</span></td>
      <td style="font-family:var(--cond);font-size:16px;font-weight:800">${f.cantidad}</td>
      <td style="font-family:var(--cond);color:var(--green)">${f.ptrae}</td>
      <td style="font-family:var(--cond);color:var(--red)">${f.plleva}</td>
      <td style="color:var(--muted);font-size:10px">${f.hora}</td>
    </tr>`).join('')}</tbody></table></div>`;
}

// ══════════════════════════════════════════════════
// LOMA NEGRA
// ══════════════════════════════════════════════════
function registrarLN(){
  const tipo=document.getElementById('ln-tipo').value;
  const item=document.getElementById('ln-item').value;
  const cant=parseInt(document.getElementById('ln-cantidad').value)||0;
  const factura=document.getElementById('ln-factura').value.trim();
  const remito=document.getElementById('ln-remito').value.trim();
  const obs=document.getElementById('ln-obs').value.trim();
  if(cant<=0){ toast('Ingresá la cantidad','err'); return; }
  const entry={id:Date.now(),tipo,item,cantidad:cant,factura,remito,obs,hora:hora(),fecha:fechaHoy(),sucursal:session.sucursal,usuario:session.usuario,estado:'registrado'};
  curState().ln.push(entry);
  saveLocal(); syncToSheets('addLN',{suc:session.sucursal,data:entry}); renderAll();
  toast('Registrado en Loma Negra','ok');
  ['ln-cantidad','ln-factura','ln-remito','ln-obs'].forEach(id=>document.getElementById(id).value='');
}

function renderLN(){
  const lista=document.getElementById('ln-lista');
  const lnData=curState().ln;
  if(!lnData.length){ lista.innerHTML='<div class="empty">— Sin registros —</div>'; return; }
  const pedidos=lnData.filter(l=>l.tipo==='pedido');
  const devs=lnData.filter(l=>l.tipo==='devolucion');
  lista.innerHTML=`<div class="sumr">
    <div class="sumbox"><div class="sumbox-l">Pedidos hoy</div><div class="sumbox-v">${pedidos.length}</div></div>
    <div class="sumbox"><div class="sumbox-l">Total pedido</div><div class="sumbox-v y">${pedidos.reduce((s,l)=>s+l.cantidad,0)}</div></div>
    <div class="sumbox"><div class="sumbox-l">Pallets devueltos</div><div class="sumbox-v g">${devs.reduce((s,l)=>s+l.cantidad,0)}</div></div>
  </div>
  <div class="card" style="padding:0;overflow:hidden"><table class="tbl">
    <thead><tr><th>Tipo</th><th>Ítem</th><th>Cantidad</th><th>Factura</th><th>Remito</th><th>Obs.</th><th>Fecha</th></tr></thead>
    <tbody>${[...lnData].reverse().map(l=>`<tr>
      <td><span class="badge ${l.tipo==='pedido'?'b-w':'b-ok'}">${l.tipo==='pedido'?'↓ Pedido':'↑ Devolución'}</span></td>
      <td><span class="it it-${itC(l.item)}">${IL[l.item]||l.item}</span></td>
      <td style="font-family:var(--cond);font-size:15px;font-weight:800">${l.cantidad}</td>
      <td style="font-size:11px">${l.factura||'—'}</td>
      <td style="font-size:11px">${l.remito||'—'}</td>
      <td style="font-size:11px;color:var(--muted2)">${l.obs||'—'}</td>
      <td style="color:var(--muted);font-size:10px">${l.fecha||l.hora}</td>
    </tr>`).join('')}</tbody></table></div>`;
}

// ══════════════════════════════════════════════════
// PALLETS
// ══════════════════════════════════════════════════
function cargarPallet(){
  const remito=document.getElementById('pal-remito').value.trim();
  const cliente=document.getElementById('pal-cliente').value.trim();
  const tipo=document.getElementById('pal-tipo').value;
  const cant=parseInt(document.getElementById('pal-cantidad').value)||0;
  if(!cliente){ toast('Ingresá cliente / origen','err'); return; }
  if(cant<=0){ toast('Ingresá la cantidad','err'); return; }
  const entry={id:Date.now(),remito,cliente,tipo,cantidad:cant,hora:hora(),sucursal:session.sucursal,fecha:fechaHoy()};
  curState().pallets.push(entry);
  saveLocal(); syncToSheets('addPallet',{suc:session.sucursal,data:entry}); renderAll();
  toast('Pallet registrado','ok');
  ['pal-remito','pal-cliente','pal-cantidad'].forEach(id=>document.getElementById(id).value='');
}

function getSaldos(suc){
  const s={};
  (getState(suc).pallets||[]).forEach(p=>{
    if(!s[p.cliente]) s[p.cliente]=0;
    if(p.tipo==='devolvio'||p.tipo==='adelanto'||p.tipo==='propio') s[p.cliente]+=p.cantidad;
    else if(p.tipo==='retiro') s[p.cliente]-=p.cantidad;
  });
  return s;
}

function renderPallets(){
  const saldos=getSaldos(session.sucursal);
  const sDiv=document.getElementById('pallets-saldos');
  sDiv.innerHTML=Object.keys(saldos).length
    ?Object.entries(saldos).map(([c,s])=>{
        const cls=s<0?'debe':s===0?'cero':'ok';
        const lbl=s<0?`Debe ${Math.abs(s)} pal.`:s===0?'Al día':`A favor: ${s}`;
        return `<div class="sc"><div class="sc-cli">${esc(c)}</div><div class="sc-num ${cls}">${s<0?s:'+'+s}</div><div class="sc-lbl">${lbl}</div></div>`;
      }).join('')
    :'<div class="empty" style="grid-column:1/-1">— Sin movimientos —</div>';

  const lista=document.getElementById('pallets-lista');
  const pals=curState().pallets;
  if(!pals.length){ lista.innerHTML='<div class="empty">— Sin movimientos —</div>'; return; }
  const tL={devolvio:'▲ Devolvió',retiro:'▼ Retiró (debe)',adelanto:'● Adelanto',propio:'★ Ingreso propio'};
  const tC={devolvio:'mv-d',retiro:'mv-r',adelanto:'mv-a',propio:'mv-p'};
  const qC={devolvio:'qv-d',retiro:'qv-r',adelanto:'qv-a',propio:'qv-p'};
  lista.innerHTML=`<div class="card" style="padding:0;overflow:hidden"><table class="tbl">
    <thead><tr><th>Remito</th><th>Cliente</th><th>Movimiento</th><th>Cant.</th><th>Hora</th></tr></thead>
    <tbody>${[...pals].reverse().map(p=>`<tr>
      <td style="font-family:var(--cond);font-weight:800">${esc(p.remito||'—')}</td>
      <td>${esc(p.cliente)}</td>
      <td class="${tC[p.tipo]||'mv-a'}">${tL[p.tipo]||p.tipo}</td>
      <td class="${qC[p.tipo]||'qv-a'}">${p.cantidad}</td>
      <td style="color:var(--muted);font-size:10px">${p.hora}</td>
    </tr>`).join('')}</tbody></table></div>`;
}

// ══════════════════════════════════════════════════
// STOCK
// ══════════════════════════════════════════════════
function calcStock(suc){
  const st=getState(suc);
  const res={};
  [...ITEMS,'pallets'].forEach(item=>{
    const ini=st.stockInicial[item]||0;
    let ent=0,sal=0;
    if(item==='pallets'){
      st.fabrica.forEach(f=>{ent+=f.ptrae||0;sal+=f.plleva||0;});
      st.viajes.forEach(v=>{
        const salP=(v.paradas||[]).find(p=>p.tipo==='salida'); if(salP) sal+=salP.pallets||0;
        if(v.regresoPallets!==null&&v.regresoPallets!==undefined) ent+=v.regresoPallets;
      });
      st.pallets.forEach(p=>{
        if(p.tipo==='devolvio'||p.tipo==='adelanto'||p.tipo==='propio') ent+=p.cantidad;
        else if(p.tipo==='retiro') sal+=p.cantidad;
      });
    } else {
      st.fabrica.filter(f=>f.item===item).forEach(f=>ent+=f.cantidad);
      st.viajes.filter(v=>v.paradas&&v.paradas[0]?.item===item).forEach(v=>{
        sal+=v.paradas[0]?.cantidad||0;
        if(v.regresoMaterial) ent+=v.regresoMaterial;
      });
      st.remitos.filter(r=>r.item===item&&r.cargada!==null).forEach(r=>sal+=r.cargada);
    }
    res[item]={ini,ent,sal,cur:ini+ent-sal};
  });
  return res;
}

function renderStock(){
  const stock=calcStock(session.sucursal);
  const allI=[...ITEMS,'pallets'];
  const lbls={...IL,pallets:'Pallets'};
  document.getElementById('stock-grid').innerHTML=allI.map(item=>{
    const s=stock[item];
    const cls=s.cur<0?'neg':'cur';
    return `<div class="sb"><div class="sb-name">${lbls[item]}</div>
      <div class="sb-row"><span class="sb-lbl">Inicial</span><span class="sv ini">${s.ini}</span></div>
      <div class="sb-row"><span class="sb-lbl">+ Entradas</span><span class="sv gr">+${s.ent}</span></div>
      <div class="sb-row"><span class="sb-lbl">− Salidas</span><span class="sv rd">-${s.sal}</span></div>
      <div class="sb-div"></div>
      <div class="sb-row"><span class="sb-lbl">Actual</span><span class="sv ${cls}">${s.cur}</span></div>
    </div>`;
  }).join('');

  if(canEdit()){
    document.getElementById('stock-edit-row').innerHTML=allI.map(item=>`
      <div class="fg" style="max-width:110px">
        <label>${lbls[item]}</label>
        <input type="number" id="si-${item}" value="${curState().stockInicial[item]||0}" inputmode="numeric" min="0">
      </div>`).join('');
  }

  const diffs=curState().remitos.filter(r=>r.estado==='diferencia');
  const cntD=document.getElementById('cntDiff');
  cntD.textContent=diffs.length; cntD.classList.toggle('show',diffs.length>0);

  document.getElementById('sum-diffs').innerHTML=diffs.length
    ?diffs.map(r=>`<div class="diff-alert">⚠ <strong>Remito ${esc(r.remito)}</strong> — Aut: ${r.autorizada} | Carg: ${r.cargada} | Dif: ${Math.abs(r.autorizada-r.cargada)}</div>`).join('')
    :'<div class="empty" style="padding:14px">— Sin diferencias hoy ✓ —</div>';

  const bM={espera:'b-w',ok:'b-ok',diferencia:'b-d',parcial:'b-p'};
  const lM={espera:'⏳ Esp.',ok:'✓ OK',diferencia:'⚠ Dif.',parcial:'↩ Parcial'};
  document.getElementById('sum-tbody').innerHTML=curState().remitos.length
    ?curState().remitos.map(r=>`<tr>
        <td style="font-family:var(--cond);font-size:13px;font-weight:800">${esc(r.remito)}</td>
        <td><span class="it it-${itC(r.item)}">${IL[r.item]||r.item}</span></td>
        <td style="font-family:var(--cond)">${r.facturada}</td>
        <td style="font-family:var(--cond);color:var(--yellow)">${r.autorizada}</td>
        <td style="font-family:var(--cond);color:var(--green)">${r.cargada!==null?r.cargada:'—'}</td>
        <td style="font-family:var(--cond);color:var(--yellow)">${r.pendiente>0?r.pendiente:'—'}</td>
        <td><span class="badge ${bM[r.estado]||'b-w'}">${lM[r.estado]||r.estado}</span></td>
        <td style="color:var(--muted);font-size:10px">${r.hora}</td>
      </tr>`).join('')
    :'<tr><td colspan="8" style="text-align:center;color:var(--muted);padding:20px">Sin datos</td></tr>';
}

function guardarStockInicial(){
  const allI=[...ITEMS,'pallets'];
  allI.forEach(item=>{ const el=document.getElementById('si-'+item); if(el) curState().stockInicial[item]=parseInt(el.value)||0; });
  saveLocal(); syncToSheets('setStock',{suc:session.sucursal,data:curState().stockInicial}); renderAll();
  toast('Stock inicial guardado','ok');
}

// ══════════════════════════════════════════════════
// GLOBAL
// ══════════════════════════════════════════════════
let globalSuc='all';

function initGlobalSelector(){
  const sel=document.getElementById('suc-selector');
  sel.innerHTML=`<button class="suc-btn all active" onclick="setGlobalSuc('all',this)">★ Consolidado</button>`
    +SUCS_LIST.map(s=>`<button class="suc-btn" onclick="setGlobalSuc('${s}',this)">${SUCS[s]}</button>`).join('');
}

function setGlobalSuc(suc,btn){
  globalSuc=suc;
  document.querySelectorAll('.suc-btn').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  renderGlobal();
}

function renderGlobal(){
  const cont=document.getElementById('global-content');
  const lbls={...IL,pallets:'Pallets'};

  if(globalSuc==='all'){
    // Consolidado
    let html='<div class="st">Stock consolidado — todas las sucursales</div><div class="sg">';
    [...ITEMS,'pallets'].forEach(item=>{
      let total=0; SUCS_LIST.forEach(s=>{ total+=calcStock(s)[item]?.cur||0; });
      const cls=total<0?'neg':'cur';
      html+=`<div class="sb"><div class="sb-name">${lbls[item]}</div><div class="sb-div"></div><div class="sb-row"><span class="sb-lbl">Total</span><span class="sv ${cls}">${total}</span></div></div>`;
    });
    html+='</div>';

    // Remitos parciales abiertos
    const partials=(globalData.remitosGlobal||[]).filter(r=>r.estado==='parcial');
    html+=`<div class="st">Remitos parciales abiertos (${partials.length})</div>`;
    html+=partials.length
      ?`<div class="card" style="padding:0;overflow:hidden"><table class="tbl">
          <thead><tr><th>Remito</th><th>Ítem</th><th>Sucursal origen</th><th>Autorizado</th><th>Cargado</th><th>Pendiente</th><th>Hora</th></tr></thead>
          <tbody>${partials.map(r=>`<tr>
            <td style="font-family:var(--cond);font-size:14px;font-weight:800">${esc(r.remito)}</td>
            <td><span class="it it-${itC(r.item)}">${IL[r.item]||r.item}</span></td>
            <td><span class="badge b-p">${SUCS[r.sucursalOrigen]||r.sucursalOrigen}</span></td>
            <td style="font-family:var(--cond)">${r.autorizada}</td>
            <td style="font-family:var(--cond);color:var(--green)">${r.cargada}</td>
            <td style="font-family:var(--cond);color:var(--yellow);font-size:16px;font-weight:800">${r.pendiente}</td>
            <td style="color:var(--muted);font-size:10px">${r.hora}</td>
          </tr>`).join('')}</tbody></table></div>`
      :'<div class="empty" style="padding:14px">— Sin parciales abiertos —</div>';

    // Viajes abiertos
    const vOpen=(globalData.viajesGlobal||[]).filter(v=>v.estado==='abierto');
    html+=`<div class="st">Viajes abiertos (${vOpen.length})</div>`;
    html+=vOpen.length
      ?`<div class="card" style="padding:0;overflow:hidden"><table class="tbl">
          <thead><tr><th>Chofer</th><th>Origen</th><th>Destino</th><th>Ítem</th><th>Salida</th></tr></thead>
          <tbody>${vOpen.map(v=>{const s=v.paradas?.[0]; return `<tr>
            <td style="font-family:var(--cond);font-size:14px;font-weight:800">${esc(v.chofer)}</td>
            <td><span class="badge b-m">${SUCS[v.sucursalOrigen]||v.sucursalOrigen}</span></td>
            <td>${SUCS[v.destino]||v.destino}</td>
            <td>${s&&s.item!=='ninguno'?`<span class="it it-${itC(s.item)}">${IL[s.item]||s.item}</span> ${s.cantidad}`:'—'}</td>
            <td style="color:var(--muted);font-size:10px">${v.hora}</td>
          </tr>`}).join('')}</tbody></table></div>`
      :'<div class="empty" style="padding:14px">— Sin viajes abiertos —</div>';

    // Diferencias globales
    const diffs=[];
    SUCS_LIST.forEach(s=>(getState(s).remitos||[]).filter(r=>r.estado==='diferencia').forEach(r=>diffs.push({...r,_suc:s})));
    html+=`<div class="st">Diferencias (${diffs.length})</div>`;
    html+=diffs.length
      ?diffs.map(r=>`<div class="diff-alert">⚠ <strong>${SUCS[r._suc]}</strong> — Rem ${esc(r.remito)} | Aut: ${r.autorizada} | Carg: ${r.cargada} | Dif: ${Math.abs(r.autorizada-r.cargada)}</div>`).join('')
      :'<div class="empty" style="padding:14px">— Sin diferencias ✓ —</div>';

    cont.innerHTML=html;
  } else {
    // Single sucursal
    const stock=calcStock(globalSuc);
    let html=`<div class="st">Stock — ${SUCS[globalSuc]}</div><div class="sg">`;
    [...ITEMS,'pallets'].forEach(item=>{
      const s=stock[item]; const cls=s.cur<0?'neg':'cur';
      html+=`<div class="sb"><div class="sb-name">${lbls[item]}</div>
        <div class="sb-row"><span class="sb-lbl">Inicial</span><span class="sv ini">${s.ini}</span></div>
        <div class="sb-row"><span class="sb-lbl">+Ent.</span><span class="sv gr">+${s.ent}</span></div>
        <div class="sb-row"><span class="sb-lbl">-Sal.</span><span class="sv rd">-${s.sal}</span></div>
        <div class="sb-div"></div>
        <div class="sb-row"><span class="sb-lbl">Actual</span><span class="sv ${cls}">${s.cur}</span></div>
      </div>`;
    });
    html+='</div>';

    const st=getState(globalSuc);
    const bM={espera:'b-w',ok:'b-ok',diferencia:'b-d',parcial:'b-p'};
    const lM={espera:'⏳ Esp.',ok:'✓ OK',diferencia:'⚠ Dif.',parcial:'↩ Parcial'};
    html+=`<div class="st">Remitos — ${SUCS[globalSuc]}</div>`;
    html+=st.remitos.length
      ?`<div class="card" style="padding:0;overflow:hidden"><table class="tbl">
          <thead><tr><th>Remito</th><th>Ítem</th><th>Aut.</th><th>Cargado</th><th>Pendiente</th><th>Estado</th></tr></thead>
          <tbody>${st.remitos.map(r=>`<tr>
            <td style="font-family:var(--cond);font-weight:800">${esc(r.remito)}</td>
            <td><span class="it it-${itC(r.item)}">${IL[r.item]||r.item}</span></td>
            <td style="font-family:var(--cond);color:var(--yellow)">${r.autorizada}</td>
            <td style="font-family:var(--cond);color:var(--green)">${r.cargada!==null?r.cargada:'—'}</td>
            <td style="font-family:var(--cond);color:var(--yellow)">${r.pendiente>0?r.pendiente:'—'}</td>
            <td><span class="badge ${bM[r.estado]||'b-w'}">${lM[r.estado]||r.estado}</span></td>
          </tr>`).join('')}</tbody></table></div>`
      :'<div class="empty">— Sin remitos —</div>';

    // Pallets saldos
    const saldos=getSaldos(globalSuc);
    html+=`<div class="st">Pallets por cliente — ${SUCS[globalSuc]}</div>`;
    html+=Object.keys(saldos).length
      ?`<div class="saldo-g">${Object.entries(saldos).map(([c,s])=>{
          const cls=s<0?'debe':s===0?'cero':'ok';
          return `<div class="sc"><div class="sc-cli">${esc(c)}</div><div class="sc-num ${cls}">${s<0?s:'+'+s}</div><div class="sc-lbl">${s<0?'Debe':'A favor'}</div></div>`;
        }).join('')}</div>`
      :'<div class="empty">— Sin movimientos —</div>';

    cont.innerHTML=html;
  }
}

// ══════════════════════════════════════════════════
// ADMIN
// ══════════════════════════════════════════════════
function guardarConfig(){
  scriptURL=document.getElementById('cfg-script').value.trim();
  localStorage.setItem(SCRIPT_KEY,scriptURL);
  toast('Configuración guardada','ok');
  if(scriptURL&&session){ const sucs=canSeeAll()?SUCS_LIST:[session.sucursal]; sucs.forEach(s=>loadFromSheets(s)); loadGlobalData(); }
}

async function cargarUsuarios(){
  if(!scriptURL){ toast('Configurá la URL del Apps Script primero','err'); return; }
  try{
    const res=await fetch(scriptURL+'?action=getUsers&t='+Date.now());
    const users=await res.json();
    const lista=document.getElementById('users-lista');
    if(!users.length){ lista.innerHTML='<div class="empty">— Sin usuarios en Sheets —</div>'; return; }
    lista.innerHTML=users.map(u=>`<div style="display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid var(--border)">
      <div style="flex:1">
        <div style="font-family:var(--cond);font-size:14px;font-weight:800">${esc(u.nombre||u.usuario)}</div>
        <div style="font-size:11px;color:var(--muted2)">@${esc(u.usuario)} · ${ROLES_L[u.rol]||u.rol} · ${SUCS[u.sucursal]||u.sucursal}</div>
      </div>
      <span class="badge b-ok">${ROLES_L[u.rol]||u.rol}</span>
    </div>`).join('');
  }catch(e){ toast('Error al cargar usuarios','err'); }
}

// ══════════════════════════════════════════════════
// RESET
// ══════════════════════════════════════════════════
function confirmarReset(){
  if(!confirm('⚠ Resetear el día archiva los datos de hoy y empieza de cero. El stock final pasa como inicial de mañana. ¿Confirmás?')) return;
  const stockFinal=calcStock(session.sucursal);
  const nuevoIni={};
  [...ITEMS,'pallets'].forEach(item=>nuevoIni[item]=stockFinal[item].cur);

  // Archive before reset
  const archivoData={ fecha:fechaHoy(), sucursal:session.sucursal, remitos:[...curState().remitos], viajes:[...curState().viajes], fabrica:[...curState().fabrica], pallets:[...curState().pallets], ln:[...curState().ln], stockFinal };
  syncToSheets('archivarDia',{suc:session.sucursal,data:archivoData});

  states[session.sucursal]=emptyState(session.sucursal);
  states[session.sucursal].stockInicial=nuevoIni;

  // keep open partials and viajes in global
  globalData.remitosGlobal=(globalData.remitosGlobal||[]).filter(r=>r.estado==='parcial'&&r.sucursalOrigen!==session.sucursal);
  globalData.viajesGlobal=(globalData.viajesGlobal||[]).filter(v=>v.estado==='abierto');

  saveLocal();
  syncToSheets('resetDay',{suc:session.sucursal,stockInicial:nuevoIni});
  renderAll();
  toast('Día reseteado — datos archivados','ok');
}

// ══════════════════════════════════════════════════
// EXPORT
// ══════════════════════════════════════════════════
function exportarCSV(){
  const hoy=fechaHoy();
  let csv='Fecha,Sucursal,Remito,Item,Facturado,Autorizado,Cargado,Pendiente,Estado,Hora\n';
  curState().remitos.forEach(r=>csv+=`${hoy},${session.sucursal},${r.remito},${r.item},${r.facturada},${r.autorizada},${r.cargada??''},${r.pendiente||0},${r.estado},${r.hora}\n`);
  const a=document.createElement('a');
  a.href=URL.createObjectURL(new Blob([csv],{type:'text/csv'}));
  a.download=`deposito-${hoy}.csv`; a.click();
}

function copiarResumen(){
  const hoy=fechaHoy();
  const stock=calcStock(session.sucursal);
  let txt=`📦 CONTROL DEPÓSITO — ${SUCS[session.sucursal]||session.sucursal} — ${hoy}\n${'─'.repeat(36)}\n`;
  [...ITEMS,'pallets'].forEach(item=>{
    const s=stock[item]; const lbl={...IL,pallets:'Pallets'}[item];
    txt+=`${lbl}: ini ${s.ini} | +${s.ent} | -${s.sal} | = ${s.cur}\n`;
  });
  const diffs=curState().remitos.filter(r=>r.estado==='diferencia');
  const partials=curState().remitos.filter(r=>r.estado==='parcial');
  if(diffs.length){ txt+=`\n⚠ DIFERENCIAS (${diffs.length})\n`; diffs.forEach(r=>txt+=`  Rem ${r.remito}: aut ${r.autorizada} / carg ${r.cargada}\n`); }
  if(partials.length){ txt+=`\n↩ PARCIALES ABIERTOS (${partials.length})\n`; partials.forEach(r=>txt+=`  Rem ${r.remito}: pendiente ${r.pendiente}\n`); }
  const vAb=curState().viajes.filter(v=>v.estado==='abierto');
  if(vAb.length) txt+=`\n🚛 VIAJES ABIERTOS: ${vAb.map(v=>v.chofer).join(', ')}\n`;
  txt+=`\n✓ Sin diferencias\n`;
  navigator.clipboard.writeText(txt).then(()=>toast('Resumen copiado','ok'));
}

// ══════════════════════════════════════════════════
// APPS SCRIPT
// ══════════════════════════════════════════════════
function copiarScript(){
  const code=`// ═══════════════════════════════════════════════════
// DEPÓSITO CONTROL — Apps Script v4
// Pegá este código completo en Apps Script
// Implementar como Aplicación Web — acceso: Cualquier persona
// ═══════════════════════════════════════════════════

function doPost(e) {
  let data; try{ data=JSON.parse(e.postData.contents); }catch(err){ return r('error'); }
  const ss=SpreadsheetApp.getActiveSpreadsheet();
  const {action,data:d}=data;
  const suc=d?.suc||'triangulo';
  function sh(name){ return ss.getSheetByName(suc+'_'+name)||ss.insertSheet(suc+'_'+name); }
  function gsh(name){ return ss.getSheetByName('Global_'+name)||ss.insertSheet('Global_'+name); }

  if(action==='addRemito'){
    const s=sh('Remitos'); if(s.getLastRow()===0) s.appendRow(['ID','Remito','Item','Facturada','Autorizada','Pallets','Cargada','Estado','Obs','Hora','Usuario','Parcial','Pendiente','EsCompletacion','Fecha']);
    const x=d.data; s.appendRow([x.id,x.remito,x.item,x.facturada,x.autorizada,x.pallets||0,x.cargada||'',x.estado,x.obs||'',x.hora,x.usuario||'',x.parcial||false,x.pendiente||0,x.esCompletacion||false,new Date().toLocaleDateString('es-AR')]);
  }
  if(action==='updateRemito'){
    const s=sh('Remitos'); if(!s) return r('ok');
    const rows=s.getDataRange().getValues(); const x=d.data;
    for(let i=1;i<rows.length;i++) if(rows[i][0]==x.id){ s.getRange(i+1,7).setValue(x.cargada); s.getRange(i+1,8).setValue(x.estado); s.getRange(i+1,12).setValue(x.parcial||false); s.getRange(i+1,13).setValue(x.pendiente||0); s.getRange(i+1,6).setValue(x.autorizada||rows[i][5]); break; }
  }
  if(action==='updateGlobalRemito'){
    const s=gsh('Remitos'); if(s.getLastRow()===0) s.appendRow(['ID','Remito','Item','Facturada','Autorizada','Estado','SucursalOrigen','Cargada','Pendiente','Hora']);
    const x=d.data;
    if(x.remito){ s.appendRow([x.id,x.remito,x.item,x.facturada,x.autorizada,x.estado,x.sucursalOrigen,x.cargada||'',x.pendiente||0,x.hora]); return r('ok'); }
    const rows=s.getDataRange().getValues();
    for(let i=1;i<rows.length;i++) if(rows[i][0]==x.id){ if(x.estado) s.getRange(i+1,6).setValue(x.estado); if(x.cargada!==undefined) s.getRange(i+1,8).setValue(x.cargada); if(x.pendiente!==undefined) s.getRange(i+1,9).setValue(x.pendiente); if(x.autorizada) s.getRange(i+1,5).setValue(x.autorizada); break; }
  }
  if(action==='addViaje'){
    const s=sh('Viajes'); if(s.getLastRow()===0) s.appendRow(['ID','Remito','Chofer','SucursalOrigen','Destino','Hora','Estado','RegPal','RegMat','RegHora','Usuario','Paradas','Fecha']);
    const x=d.data; s.appendRow([x.id,x.remito||'',x.chofer,x.sucursalOrigen,x.destino,x.hora,x.estado,'','',0,'',x.usuario||'',JSON.stringify(x.paradas||[]),new Date().toLocaleDateString('es-AR')]);
  }
  if(action==='updateViaje'){
    const s=sh('Viajes'); if(!s) return r('ok');
    const rows=s.getDataRange().getValues(); const x=d.data;
    for(let i=1;i<rows.length;i++) if(rows[i][0]==x.id){ s.getRange(i+1,7).setValue(x.estado); s.getRange(i+1,8).setValue(x.regresoPallets||''); s.getRange(i+1,9).setValue(x.regresoMaterial||0); s.getRange(i+1,10).setValue(x.regresoHora||''); s.getRange(i+1,13).setValue(JSON.stringify(x.paradas||[])); break; }
  }
  if(action==='updateGlobalViaje'){
    const s=gsh('Viajes'); if(s.getLastRow()===0) s.appendRow(['ID','Remito','Chofer','SucursalOrigen','Destino','Hora','Estado','RegPal','RegMat','RegHora','Paradas']);
    const x=d.data;
    if(x.chofer){ s.appendRow([x.id,x.remito||'',x.chofer,x.sucursalOrigen,x.destino,x.hora,x.estado,'','','',JSON.stringify(x.paradas||[])]); return r('ok'); }
    const rows=s.getDataRange().getValues();
    for(let i=1;i<rows.length;i++) if(rows[i][0]==x.id){ if(x.estado) s.getRange(i+1,7).setValue(x.estado); if(x.regresoPallets!==undefined) s.getRange(i+1,8).setValue(x.regresoPallets); if(x.regresoMaterial!==undefined) s.getRange(i+1,9).setValue(x.regresoMaterial); if(x.regresoHora) s.getRange(i+1,10).setValue(x.regresoHora); if(x.paradas) s.getRange(i+1,11).setValue(JSON.stringify(x.paradas)); break; }
  }
  if(action==='addFabrica'){
    const s=sh('Fabrica'); if(s.getLastRow()===0) s.appendRow(['ID','Item','Cantidad','PalTrae','PalLleva','Hora','Sucursal','Usuario','Fecha']);
    const x=d.data; s.appendRow([x.id,x.item,x.cantidad,x.ptrae,x.plleva,x.hora,x.sucursal||'',x.usuario||'',x.fecha||new Date().toLocaleDateString('es-AR')]);
  }
  if(action==='addPallet'){
    const s=sh('Pallets'); if(s.getLastRow()===0) s.appendRow(['ID','Remito','Cliente','Tipo','Cantidad','Hora','Sucursal','Fecha']);
    const x=d.data; s.appendRow([x.id,x.remito||'',x.cliente,x.tipo,x.cantidad,x.hora,x.sucursal||'',x.fecha||new Date().toLocaleDateString('es-AR')]);
  }
  if(action==='addLN'){
    const s=ss.getSheetByName('LomaNegra')||ss.insertSheet('LomaNegra');
    if(s.getLastRow()===0) s.appendRow(['ID','Tipo','Item','Cantidad','Factura','Remito','Obs','Hora','Fecha','Sucursal','Usuario','Estado']);
    const x=d.data; s.appendRow([x.id,x.tipo,x.item,x.cantidad,x.factura||'',x.remito||'',x.obs||'',x.hora,x.fecha,x.sucursal,x.usuario||'','registrado']);
  }
  if(action==='setStock'){
    const s=sh('Config'); s.clearContents(); s.appendRow(['clave','valor']);
    Object.entries(d.data).forEach(([k,v])=>s.appendRow([k,v]));
  }
  if(action==='archivarDia'){
    const arch=ss.getSheetByName('Historico')||ss.insertSheet('Historico');
    if(arch.getLastRow()===0) arch.appendRow(['Fecha','Sucursal','Tipo','Datos']);
    arch.appendRow([d.data.fecha,d.data.sucursal,'dia_completo',JSON.stringify(d.data)]);
  }
  if(action==='resetDay'){
    ['Remitos','Viajes','Fabrica','Pallets'].forEach(name=>{ const s=sh(name); if(s&&s.getLastRow()>1) s.deleteRows(2,s.getLastRow()-1); });
    if(d.stockInicial){ const s=sh('Config'); s.clearContents(); s.appendRow(['clave','valor']); Object.entries(d.stockInicial).forEach(([k,v])=>s.appendRow([k,v])); }
  }
  return r('ok');
}

function doGet(e) {
  const ss=SpreadsheetApp.getActiveSpreadsheet();
  const action=e.parameter.action||'getData';
  const suc=e.parameter.suc||'triangulo';
  function sh(name){ return ss.getSheetByName(suc+'_'+name); }
  function gsh(name){ return ss.getSheetByName('Global_'+name); }
  function rows(s,cols){ if(!s||s.getLastRow()<2) return []; return s.getRange(2,1,s.getLastRow()-1,cols).getValues(); }

  if(action==='auth'){
    const u=e.parameter.u, p=e.parameter.p;
    const s=ss.getSheetByName('Usuarios'); if(!s) return j({ok:false});
    const data=s.getDataRange().getValues();
    for(let i=1;i<data.length;i++) if(data[i][0]==u&&data[i][1]==p) return j({ok:true,user:{usuario:data[i][0],rol:data[i][2],sucursal:data[i][3],nombre:data[i][4]||data[i][0]}});
    return j({ok:false});
  }
  if(action==='getUsers'){
    const s=ss.getSheetByName('Usuarios'); if(!s||s.getLastRow()<2) return j([]);
    return j(s.getRange(2,1,s.getLastRow()-1,5).getValues().map(r=>({usuario:r[0],rol:r[2],sucursal:r[3],nombre:r[4]||r[0]})));
  }
  if(action==='getData'){
    const remitos=[],viajes=[],fabrica=[],pallets=[],ln=[];
    let stockInicial={cemento:0,cal:0,calhidratada:0,plasticor:0,pallets:0};
    rows(sh('Remitos'),15).forEach(r=>remitos.push({id:r[0],remito:r[1],item:r[2],facturada:r[3],autorizada:r[4],pallets:r[5],cargada:r[6]===''?null:r[6],estado:r[7],obs:r[8],hora:r[9],usuario:r[10],parcial:r[11],pendiente:r[12],esCompletacion:r[13]}));
    rows(sh('Viajes'),13).forEach(r=>{ let paradas=[]; try{paradas=JSON.parse(r[12]||'[]');}catch(e){} viajes.push({id:r[0],remito:r[1],chofer:r[2],sucursalOrigen:r[3],destino:r[4],hora:r[5],estado:r[6],regresoPallets:r[7]===''?null:r[7],regresoMaterial:r[8],regresoHora:r[9]||null,usuario:r[11],paradas}); });
    rows(sh('Fabrica'),9).forEach(r=>fabrica.push({id:r[0],item:r[1],cantidad:r[2],ptrae:r[3],plleva:r[4],hora:r[5],fecha:r[8]}));
    rows(sh('Pallets'),8).forEach(r=>pallets.push({id:r[0],remito:r[1],cliente:r[2],tipo:r[3],cantidad:r[4],hora:r[5],fecha:r[7]}));
    const lnSh=ss.getSheetByName('LomaNegra'); if(lnSh&&lnSh.getLastRow()>1) lnSh.getRange(2,1,lnSh.getLastRow()-1,12).getValues().filter(r=>r[9]==suc).forEach(r=>ln.push({id:r[0],tipo:r[1],item:r[2],cantidad:r[3],factura:r[4],remito:r[5],obs:r[6],hora:r[7],fecha:r[8],sucursal:r[9],usuario:r[10],estado:r[11]}));
    const cSh=sh('Config'); if(cSh&&cSh.getLastRow()>1) cSh.getRange(2,1,cSh.getLastRow()-1,2).getValues().forEach(r=>{if(r[0]) stockInicial[r[0]]=Number(r[1])||0;});
    return j({remitos,viajes,fabrica,pallets,ln,stockInicial});
  }
  if(action==='getGlobal'){
    const remitosGlobal=[],viajesGlobal=[];
    const rs=gsh('Remitos'); if(rs&&rs.getLastRow()>1) rs.getRange(2,1,rs.getLastRow()-1,10).getValues().forEach(r=>remitosGlobal.push({id:r[0],remito:r[1],item:r[2],facturada:r[3],autorizada:r[4],estado:r[5],sucursalOrigen:r[6],cargada:r[7]===''?null:r[7],pendiente:r[8],hora:r[9]}));
    const vs=gsh('Viajes'); if(vs&&vs.getLastRow()>1) vs.getRange(2,1,vs.getLastRow()-1,11).getValues().forEach(r=>{ let p=[]; try{p=JSON.parse(r[10]||'[]');}catch(e){} viajesGlobal.push({id:r[0],remito:r[1],chofer:r[2],sucursalOrigen:r[3],destino:r[4],hora:r[5],estado:r[6],regresoPallets:r[7],regresoMaterial:r[8],regresoHora:r[9],paradas:p}); });
    return j({remitosGlobal,viajesGlobal});
  }
  return j({});
}
function r(msg){ return ContentService.createTextOutput(msg).setMimeType(ContentService.MimeType.TEXT); }
function j(obj){ return ContentService.createTextOutput(JSON.stringify(obj)).setMimeType(ContentService.MimeType.JSON); }`;
  navigator.clipboard.writeText(code).then(()=>toast('Código copiado — pegalo en Apps Script','ok'));
}

// ══════════════════════════════════════════════════
// HELPERS
// ══════════════════════════════════════════════════
function renderAll(){
  if(!session) return;
  renderPanol(); renderPuerta(); renderViajes(); renderFabrica(); renderLN(); renderPallets(); renderStock();
  const gp=document.getElementById('page-global');
  if(gp&&gp.classList.contains('active')) renderGlobal();
}
function hora(){ return new Date().toLocaleTimeString('es-AR',{hour:'2-digit',minute:'2-digit'}); }
function fechaHoy(){ return new Date().toLocaleDateString('es-AR'); }
function esc(s){ return String(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;'); }
function itC(item){ if(item==='cemento') return 'cem'; if(item==='cal') return 'cal'; if(item==='calhidratada') return 'calh'; if(item==='plasticor') return 'pla'; return 'pal'; }

let toastTmr;
function toast(msg,type=''){
  const el=document.getElementById('toast');
  el.textContent=msg; el.className='show '+type;
  clearTimeout(toastTmr);
  toastTmr=setTimeout(()=>el.className=type,3000);
}

// ══════════════════════════════════════════════════
// INIT
// ══════════════════════════════════════════════════
document.getElementById('dateDisplay').textContent=new Date().toLocaleDateString('es-AR',{weekday:'long',day:'numeric',month:'long'});

const savedSession=sessionStorage.getItem('dep_session_v4');
if(savedSession){ try{ session=JSON.parse(savedSession); startApp(); }catch(e){} }
</script>
</body>
</html>
