<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>⚔️ MathBattle 1v1</title>
<link href="https://fonts.googleapis.com/css2?family=Prompt:wght@300;400;500;600;700;900&family=Kanit:wght@300;400;500;700;900&display=swap" rel="stylesheet">
<style>
/* ===== RESET ===== */
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box}
:root{
  --bg:#0a0e1a;--bg2:#111827;--bg3:#1a2234;--card:#161d2e;
  --border:#2d3748;--text:#f1f5f9;--text2:#94a3b8;
  --accent:#f59e0b;--acdk:#d97706;--red:#ef4444;
  --green:#10b981;--blue:#3b82f6;--purple:#8b5cf6;--gold:#fbbf24;
  --shadow:0 4px 24px rgba(0,0,0,.5);
  --r8:8px;--r12:12px;--r16:16px;
}
html{scroll-behavior:smooth}
body{font-family:'Prompt',sans-serif;background:var(--bg);color:var(--text);min-height:100vh;overflow-x:hidden;font-size:14px;line-height:1.5}
h1,h2,h3{font-family:'Kanit',sans-serif}

/* ===== STARS ===== */
.stars-bg{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden}
.star{position:absolute;width:2px;height:2px;background:#fff;border-radius:50%;animation:twinkle var(--d,3s) infinite}
@keyframes twinkle{0%,100%{opacity:.1}50%{opacity:.8}}

/* ===== SCREENS ===== */
.screen{display:none;min-height:100vh;flex-direction:column;align-items:center}
.screen.active{display:flex}

/* ===== LOGIN SCREEN ===== */
#screen-login{justify-content:center;padding:20px;background:linear-gradient(135deg,#0a0e1a,#0f1729,#0a0e1a)}
.login-wrap{width:100%;max-width:400px;position:relative;z-index:1}
.login-logo{text-align:center;margin-bottom:28px}
.login-logo h1{font-size:clamp(28px,6vw,48px);background:linear-gradient(135deg,#f59e0b,#ef4444,#8b5cf6);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;line-height:1.1;margin-bottom:6px}
.login-logo p{color:var(--text2);font-size:12px;letter-spacing:2px;text-transform:uppercase}
.login-card{background:var(--card);border:1px solid var(--border);border-radius:var(--r16);padding:24px;box-shadow:var(--shadow)}
.login-tabs{display:flex;gap:6px;margin-bottom:20px}
.login-tab{flex:1;padding:9px;background:var(--bg3);border:1px solid var(--border);border-radius:var(--r8);cursor:pointer;text-align:center;font-size:13px;color:var(--text2);font-family:'Prompt',sans-serif;transition:all .2s}
.login-tab.active{background:var(--accent);color:#000;border-color:var(--accent);font-weight:700}
.login-field{margin-bottom:14px}
.login-field label{display:block;font-size:11px;color:var(--text2);margin-bottom:6px;text-transform:uppercase;letter-spacing:1px}
.login-err{background:rgba(239,68,68,.12);border:1px solid rgba(239,68,68,.3);color:var(--red);border-radius:var(--r8);padding:10px 13px;font-size:13px;margin-bottom:14px;display:none}
.login-ok{background:rgba(16,185,129,.12);border:1px solid rgba(16,185,129,.3);color:var(--green);border-radius:var(--r8);padding:10px 13px;font-size:13px;margin-bottom:14px;display:none}
.profile-bar{display:flex;align-items:center;gap:10px;background:var(--bg3);border:1px solid var(--border);border-radius:var(--r12);padding:10px 14px;margin-bottom:14px}
.profile-avatar{width:38px;height:38px;border-radius:50%;background:linear-gradient(135deg,var(--accent),var(--purple));display:flex;align-items:center;justify-content:center;font-size:18px;font-weight:700;color:#fff;flex-shrink:0}
.profile-info{flex:1;min-width:0}
.profile-name{font-weight:700;font-size:14px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.profile-stars{font-size:12px;color:var(--gold)}
.logout-btn{background:none;border:1px solid var(--border);border-radius:var(--r8);color:var(--text2);font-size:11px;padding:5px 10px;cursor:pointer;font-family:'Prompt',sans-serif;transition:all .2s;white-space:nowrap}
.logout-btn:hover{border-color:var(--red);color:var(--red)}

/* ===== HOME ===== */
#screen-home{justify-content:center;padding:20px;background:linear-gradient(135deg,#0a0e1a,#0f1729,#0a0e1a)}
.home-logo{text-align:center;margin-bottom:28px;position:relative;z-index:1}
.home-logo h1{font-size:clamp(32px,6vw,56px);background:linear-gradient(135deg,#f59e0b,#ef4444,#8b5cf6);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;line-height:1.1;margin-bottom:8px}
.home-logo p{color:var(--text2);font-size:13px;letter-spacing:2px;text-transform:uppercase}
.menu-box{background:var(--card);border:1px solid var(--border);border-radius:var(--r16);padding:22px;width:100%;max-width:420px;position:relative;z-index:1;box-shadow:var(--shadow)}
.home-profile{display:flex;align-items:center;gap:10px;background:var(--bg3);border:1px solid var(--border);border-radius:var(--r12);padding:10px 14px;margin-bottom:16px}
.home-profile .profile-avatar{width:34px;height:34px;font-size:16px}

/* ===== INPUTS ===== */
.name-sec{margin-bottom:18px}
.name-sec label{display:block;font-size:11px;color:var(--text2);margin-bottom:6px;text-transform:uppercase;letter-spacing:1px}
.inp{width:100%;background:var(--bg3);border:1px solid var(--border);border-radius:var(--r8);padding:11px 13px;color:var(--text);font-family:'Prompt',sans-serif;font-size:14px;outline:none;transition:border-color .2s}
.inp:focus{border-color:var(--accent)}
.inp::placeholder{color:var(--text2)}

/* ===== BUTTONS ===== */
.btn{display:flex;align-items:center;justify-content:center;gap:8px;width:100%;padding:13px;border-radius:var(--r12);border:none;font-family:'Prompt',sans-serif;font-size:14px;font-weight:600;cursor:pointer;transition:all .2s;letter-spacing:.3px}
.btn:disabled{opacity:.5;cursor:not-allowed;transform:none!important}
.btn-p{background:linear-gradient(135deg,var(--accent),var(--acdk));color:#000}
.btn-p:hover{transform:translateY(-2px);box-shadow:0 8px 24px rgba(245,158,11,.4)}
.btn-s{background:var(--bg3);color:var(--text2);border:1px solid var(--border)}
.btn-s:hover{background:var(--border);color:var(--text)}
.btn-b{background:linear-gradient(135deg,var(--blue),#2563eb);color:#fff}
.btn-b:hover{transform:translateY(-2px);box-shadow:0 8px 24px rgba(59,130,246,.4)}
.btn-g{background:linear-gradient(135deg,var(--green),#059669);color:#fff}
.btn-g:hover{transform:translateY(-2px);box-shadow:0 8px 24px rgba(16,185,129,.4)}
.btn-r{background:linear-gradient(135deg,var(--red),#dc2626);color:#fff}
.btn-r:hover{transform:translateY(-2px)}
.btn-pu{background:linear-gradient(135deg,var(--purple),#7c3aed);color:#fff}
.btn-pu:hover{transform:translateY(-2px);box-shadow:0 8px 24px rgba(139,92,246,.4)}

/* ===== TABS ===== */
.tabs{display:flex;gap:6px;margin-bottom:16px}
.tab{flex:1;padding:9px;background:var(--bg3);border:1px solid var(--border);border-radius:var(--r8);cursor:pointer;text-align:center;font-size:13px;color:var(--text2);font-family:'Prompt',sans-serif;transition:all .2s}
.tab.active{background:var(--accent);color:#000;border-color:var(--accent);font-weight:700}

/* ===== HELPERS ===== */
.mtitle{font-size:11px;color:var(--text2);text-transform:uppercase;letter-spacing:1px;margin-bottom:10px}
.div{height:1px;background:var(--border);margin:14px 0}
.flex-gap{display:flex;gap:10px}
.mt16{margin-top:16px}
.tc{text-align:center}
.tmuted{color:var(--text2)}

/* ===== ONLINE LIST ===== */
.fsearch{display:flex;gap:8px;margin-bottom:10px}
.fsearch input{flex:1}
.fi{display:flex;align-items:center;justify-content:space-between;padding:10px 12px;background:var(--bg3);border-radius:var(--r8);margin-bottom:6px;border:1px solid var(--border)}
.fi .fn{font-weight:600;font-size:13px}
.fi .fstars{font-size:11px;color:var(--gold);margin-top:2px}
.dot-on{width:8px;height:8px;background:var(--green);border-radius:50%;margin-right:6px;display:inline-block}
.dot-reg{width:8px;height:8px;background:var(--blue);border-radius:50%;margin-right:6px;display:inline-block}

/* ===== SETUP ===== */
.setup{width:100%;max-width:480px;position:relative;z-index:1;padding:20px}
.stitle{font-size:20px;font-weight:700;margin-bottom:20px;text-align:center;font-family:'Kanit',sans-serif}
.back-btn{display:flex;align-items:center;gap:6px;background:none;border:none;color:var(--text2);cursor:pointer;font-family:'Prompt',sans-serif;font-size:13px;padding:8px 0;margin-bottom:14px}
.back-btn:hover{color:var(--text)}
.tgrid{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:20px}
.tbtn{padding:20px 12px;border-radius:var(--r12);border:2px solid rgba(99,179,237,.25);background:linear-gradient(135deg,rgba(13,20,45,.95),rgba(20,30,60,.9));cursor:pointer;text-align:center;transition:all .25s;color:var(--text);position:relative;overflow:hidden;box-shadow:0 0 12px rgba(99,179,237,.08),inset 0 1px 0 rgba(255,255,255,.05)}
.tbtn::before{content:'';position:absolute;inset:0;background:linear-gradient(135deg,transparent 40%,rgba(99,179,237,.04));pointer-events:none}
.tbtn::after{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,rgba(99,179,237,.4),transparent)}
.tbtn:hover,.tbtn.sel{border-color:rgba(99,179,237,.7);transform:translateY(-3px);box-shadow:0 0 20px rgba(99,179,237,.2),0 8px 24px rgba(0,0,0,.4)}
.tbtn.sel{background:linear-gradient(135deg,rgba(13,30,70,.95),rgba(20,50,100,.9))}
.tbtn .ti{font-size:28px;margin-bottom:6px}
.tbtn .tn{font-weight:700;font-size:13px}
.llist{display:flex;flex-direction:column;gap:10px;margin-bottom:20px}
.lbtn{padding:15px 18px;border-radius:var(--r12);border:1px solid rgba(139,92,246,.3);background:linear-gradient(135deg,rgba(13,20,45,.95),rgba(20,15,50,.9));cursor:pointer;display:flex;align-items:center;gap:13px;transition:all .25s;color:var(--text);position:relative;overflow:hidden;box-shadow:0 0 10px rgba(139,92,246,.06),inset 0 1px 0 rgba(255,255,255,.04)}
.lbtn::after{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,rgba(139,92,246,.5),transparent)}
.lbtn:hover,.lbtn.sel{border-color:rgba(139,92,246,.7);transform:translateX(5px);box-shadow:0 0 20px rgba(139,92,246,.2),0 8px 20px rgba(0,0,0,.4)}
.lbtn.sel{background:linear-gradient(135deg,rgba(30,15,70,.95),rgba(50,20,100,.9))}
.lbtn .li{font-size:24px}
.lbtn .ln{font-weight:700;font-size:14px}
.lbtn .ld{font-size:11px;color:var(--text2);margin-top:2px}

/* ===== LEADERBOARD ===== */
.lbi{display:flex;align-items:center;gap:12px;padding:11px;background:var(--bg3);border-radius:var(--r8);margin-bottom:8px;border:1px solid var(--border)}
.lbr{font-size:17px;font-weight:900;width:30px;text-align:center;color:var(--text2)}
.lbr.gold{color:#fbbf24}.lbr.silver{color:#94a3b8}.lbr.bronze{color:#92400e}
.lbn{flex:1;font-weight:600}
.lbs{color:var(--gold);font-size:13px}

/* ===== MODAL ===== */
.mover{position:fixed;inset:0;background:rgba(0,0,0,.8);display:flex;align-items:center;justify-content:center;z-index:200;backdrop-filter:blur(4px)}
.mbox{background:linear-gradient(160deg,rgba(8,12,40,.99),rgba(18,10,50,.97));border:1px solid rgba(139,92,246,.3);border-radius:20px;padding:24px;max-width:400px;width:90%;animation:popIn .3s ease;max-height:90vh;overflow-y:auto;box-shadow:0 0 40px rgba(139,92,246,.12),inset 0 1px 0 rgba(255,255,255,.05)}
.mtit{font-size:18px;font-weight:700;margin-bottom:4px;text-align:center}
.msub{font-size:13px;color:var(--text2);text-align:center;margin-bottom:18px}

/* ===== ABILITY PICK ===== */
.apgrid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin:14px 0}
.apc{border:1px solid rgba(139,92,246,.3);border-radius:var(--r12);background:linear-gradient(160deg,rgba(18,10,50,.95),rgba(30,15,60,.9));padding:13px 8px;cursor:pointer;text-align:center;transition:all .25s;position:relative;overflow:hidden;box-shadow:0 0 14px rgba(139,92,246,.07),inset 0 1px 0 rgba(255,255,255,.05)}
.apc::before{content:'';position:absolute;top:0;left:-100%;width:100%;height:100%;background:linear-gradient(90deg,transparent,rgba(139,92,246,.06),transparent);transition:left .4s}
.apc:hover::before{left:100%}
.apc:hover{border-color:rgba(139,92,246,.8);transform:translateY(-5px);box-shadow:0 0 24px rgba(139,92,246,.3),0 10px 30px rgba(0,0,0,.5)}
.apc.sel{border-color:rgba(139,92,246,.9);background:linear-gradient(160deg,rgba(40,15,100,.95),rgba(60,20,120,.9));box-shadow:0 0 28px rgba(139,92,246,.4)}
.apc .api{font-size:26px;margin-bottom:7px}
.apc .apn{font-size:11px;font-weight:700;margin-bottom:4px}
.apc .apd{font-size:10px;color:var(--text2);line-height:1.4}

/* ===== GAME ===== */
.glayout{display:flex;flex-direction:column;width:100%;min-height:100vh}
.ghdr{display:flex;align-items:center;justify-content:space-between;padding:10px 16px;background:var(--bg2);border-bottom:1px solid var(--border);position:sticky;top:0;z-index:10}
.phdr{display:flex;align-items:center;gap:10px}
.pntag{font-weight:700;font-size:13px;margin-bottom:3px}
.rdis{font-size:11px;color:var(--text2);margin-top:2px}
.hearts{display:flex;gap:3px}
.heart{font-size:17px;transition:all .3s}
.heart.empty{opacity:.2;filter:grayscale(1)}
.vstag{background:var(--red);color:#fff;padding:4px 12px;border-radius:20px;font-weight:900;font-size:13px}

/* ===== BOARD ===== */
.bsec{flex:1;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:16px;min-height:280px}
.rinfo{text-align:center;margin-bottom:14px}
.rbadge{background:var(--accent);color:#000;padding:4px 16px;border-radius:20px;font-size:12px;font-weight:700;display:inline-block;margin-bottom:5px}
.pdesc{font-size:12px;color:var(--text2)}
.qdis{text-align:center;margin-bottom:18px}
.qcard{background:linear-gradient(135deg,rgba(8,15,40,.98),rgba(15,25,60,.95));border:1px solid rgba(99,179,237,.2);border-radius:var(--r16);padding:20px 28px;min-width:260px;text-align:center;position:relative;overflow:hidden;transition:all .3s;box-shadow:0 0 30px rgba(59,130,246,.08),inset 0 1px 0 rgba(255,255,255,.06),inset 0 -1px 0 rgba(0,0,0,.3)}
.qcard::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,transparent,rgba(99,179,237,.5),rgba(139,92,246,.5),transparent)}
.qcard::after{content:'';position:absolute;bottom:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,rgba(59,130,246,.2),transparent)}
.qcard.rev{border-color:rgba(245,158,11,.5);background:linear-gradient(135deg,rgba(20,15,5,.98),rgba(40,25,8,.95));box-shadow:0 0 40px rgba(245,158,11,.12),inset 0 1px 0 rgba(245,158,11,.1)}
.qtxt{font-size:clamp(24px,5vw,40px);font-weight:900;font-family:'Kanit',sans-serif;letter-spacing:2px;min-height:52px;display:flex;align-items:center;justify-content:center}
.qhid{font-size:38px;color:var(--text2);letter-spacing:8px}
.blurn{filter:blur(6px);user-select:none}

/* ===== ANSWERS ===== */
.ansec{display:flex;gap:20px;justify-content:center;align-items:flex-start;margin-bottom:14px;flex-wrap:wrap}
.albl{font-size:11px;color:var(--text2);margin-bottom:5px;font-weight:600;text-transform:uppercase;letter-spacing:1px}
.ainp{width:140px;background:var(--bg3);border:2px solid var(--border);border-radius:var(--r8);padding:11px 12px;color:var(--text);font-family:'Prompt',sans-serif;font-size:22px;font-weight:700;text-align:center;outline:none;transition:all .2s;display:block;margin-bottom:7px}
.ainp:focus{border-color:var(--accent)}
.ainp:disabled{opacity:.4}
.vsdiv{font-size:24px;color:var(--text2);padding-top:28px}
.asbtn{width:140px;padding:10px;background:linear-gradient(135deg,var(--green),#059669);border:none;border-radius:var(--r8);color:#fff;font-family:'Prompt',sans-serif;font-size:13px;font-weight:700;cursor:pointer;transition:all .2s;display:block}
.asbtn:hover{transform:translateY(-2px);box-shadow:0 6px 18px rgba(16,185,129,.4)}
.asbtn:disabled{opacity:.5;cursor:not-allowed;transform:none}
.chgrid{display:grid;grid-template-columns:1fr 1fr;gap:10px;max-width:340px;margin:0 auto}
.chbtn{padding:13px;border-radius:var(--r8);border:2px solid var(--border);background:var(--bg3);cursor:pointer;font-family:'Prompt',sans-serif;font-size:16px;font-weight:700;color:var(--text);transition:all .2s}
.chbtn:hover{border-color:var(--accent);background:rgba(245,158,11,.1)}
.chbtn.cor{border-color:var(--green);background:rgba(16,185,129,.15);color:var(--green)}
.chbtn.wrg{border-color:var(--red);background:rgba(239,68,68,.15);color:var(--red)}
.chbtn:disabled{cursor:default}

/* ===== HAND CARDS ===== */
.hsec{padding:11px 14px;border-top:1px solid var(--border)}
.hp1{background:var(--bg2)}
.hhdr{display:flex;justify-content:space-between;align-items:center;margin-bottom:8px}
.clbl{font-size:11px;color:var(--text2);text-transform:uppercase;letter-spacing:1px}
.hhint{font-size:11px;color:var(--accent)}
.hcards{display:flex;gap:8px;justify-content:center;flex-wrap:wrap}
.hcard{width:66px;height:88px;border-radius:var(--r8);border:1px solid rgba(99,179,237,.25);background:linear-gradient(160deg,rgba(8,18,45,.98),rgba(15,30,70,.95));cursor:pointer;display:flex;flex-direction:column;align-items:center;justify-content:center;transition:all .25s;flex-shrink:0;position:relative;overflow:hidden;box-shadow:0 0 10px rgba(59,130,246,.06),inset 0 1px 0 rgba(255,255,255,.06)}
.hcard::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,rgba(99,179,237,.6),transparent)}
.hcard::after{content:'🛸';position:absolute;bottom:2px;right:3px;font-size:8px;opacity:.3}
.hcard:hover{transform:translateY(-10px);border-color:rgba(99,179,237,.8);box-shadow:0 0 20px rgba(59,130,246,.3),0 10px 24px rgba(0,0,0,.5)}
.hcard.sel{border-color:rgba(245,158,11,.9);transform:translateY(-10px);box-shadow:0 0 24px rgba(245,158,11,.5),0 10px 24px rgba(0,0,0,.5);background:linear-gradient(160deg,rgba(30,20,5,.98),rgba(50,35,8,.95))}
.hcard.used{opacity:.2;pointer-events:none;filter:grayscale(1)}
.cnum{font-size:11px;font-weight:700;color:var(--accent);margin-top:4px}
.confbar{padding:12px 16px;background:var(--bg2);border-top:1px solid var(--border);text-align:center}
.confbar .btn{max-width:300px;margin:0 auto}

/* ===== ABILITY CARDS ===== */
.csec{padding:11px 14px;background:var(--bg2);border-top:1px solid var(--border)}
.abrow{display:flex;justify-content:space-between}
.crow{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}
.abcard{width:70px;min-height:88px;border-radius:var(--r8);border:1px solid rgba(139,92,246,.3);background:linear-gradient(160deg,rgba(18,8,45,.98),rgba(30,12,65,.95));cursor:pointer;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:8px 4px;gap:4px;transition:all .25s;text-align:center;flex-shrink:0;position:relative;overflow:hidden;box-shadow:0 0 10px rgba(139,92,246,.07),inset 0 1px 0 rgba(255,255,255,.06)}
.abcard::before{content:'';position:absolute;top:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,rgba(139,92,246,.7),transparent)}
.abcard:hover{transform:translateY(-8px);border-color:rgba(139,92,246,.8);box-shadow:0 0 22px rgba(139,92,246,.35),0 8px 20px rgba(0,0,0,.5)}
.abcard.used{opacity:.18;pointer-events:none;filter:grayscale(1) blur(1px)}
.abcard .ai{font-size:22px}
.abcard .an{font-size:9px;color:var(--text2);line-height:1.2;font-weight:600}

/* ===== BOT ===== */
.botthink{display:flex;align-items:center;gap:6px;font-size:13px;color:var(--text2);margin:8px 0;justify-content:center}
.d{width:6px;height:6px;background:var(--text2);border-radius:50%;animation:db .8s ease infinite}
.d:nth-child(2){animation-delay:.15s}
.d:nth-child(3){animation-delay:.3s}
@keyframes db{0%,100%{transform:translateY(0)}50%{transform:translateY(-5px)}}

/* ===== STATUS ===== */
.smsg{padding:8px 14px;border-radius:var(--r8);font-size:13px;font-weight:600;margin:6px 0;animation:fs .3s ease}
.sw{background:rgba(16,185,129,.15);color:var(--green);border:1px solid rgba(16,185,129,.3)}
.sl{background:rgba(239,68,68,.15);color:var(--red);border:1px solid rgba(239,68,68,.3)}
.si{background:rgba(59,130,246,.15);color:var(--blue);border:1px solid rgba(59,130,246,.3)}
.sa{background:rgba(139,92,246,.15);color:var(--purple);border:1px solid rgba(139,92,246,.3)}
@keyframes fs{from{opacity:0;transform:translateY(-4px)}to{opacity:1;transform:translateY(0)}}

/* ===== ROUND RESULT ===== */
.rrover{position:fixed;inset:0;background:rgba(0,0,0,.75);display:flex;align-items:center;justify-content:center;z-index:100;backdrop-filter:blur(4px)}
.rrbox{background:linear-gradient(160deg,rgba(8,15,45,.99),rgba(15,25,65,.97));border:1px solid rgba(99,179,237,.3);border-radius:20px;padding:28px;text-align:center;max-width:320px;width:90%;animation:popIn .3s ease;box-shadow:0 0 40px rgba(59,130,246,.12),inset 0 1px 0 rgba(255,255,255,.06)}
.rico{font-size:52px;margin-bottom:10px}
.rtit{font-size:26px;font-weight:900;font-family:'Kanit',sans-serif;margin-bottom:6px}
.rsub{color:var(--text2);font-size:13px;margin-bottom:10px}
.rdet{font-size:13px;color:var(--text2);margin:8px 0}

/* ===== GAME OVER ===== */
#screen-gameover{justify-content:center;padding:20px}
.goscreen{text-align:center;padding:24px;position:relative;z-index:1;width:100%;max-width:400px}
.goico{font-size:60px;margin-bottom:14px;animation:bounce 1s ease infinite}
.gotit{font-size:36px;font-weight:900;font-family:'Kanit',sans-serif;margin-bottom:6px}
.gost{font-size:26px;margin:12px 0;letter-spacing:4px}
.godesc{color:var(--text2);font-size:14px;margin-bottom:18px}
.gostats{background:var(--card);border-radius:var(--r12);padding:16px;margin-bottom:18px;text-align:left;border:1px solid var(--border)}
.fzmsg{text-align:center;padding:7px;color:var(--blue);font-weight:700;font-size:14px;margin:4px 0}

/* ===== ANIMS ===== */
@keyframes popIn{from{transform:scale(.8);opacity:0}to{transform:scale(1);opacity:1}}
@keyframes bounce{0%,100%{transform:translateY(0)}50%{transform:translateY(-10px)}}


/* ===== GAME TITLE SUBTITLE ===== */
.subtitle-game{color:var(--gold);font-size:10px;letter-spacing:4px;text-transform:uppercase;font-weight:700;margin-bottom:4px;display:block}

/* ===== CANVAS BG ===== */
#bgCanvas{position:fixed;inset:0;z-index:0;pointer-events:none;opacity:.55}

/* ===== FLOATING SYMBOLS ===== */
.float-sym{position:fixed;pointer-events:none;z-index:0;font-family:'Kanit',sans-serif;font-weight:900;color:rgba(245,158,11,.12);animation:floatUp linear infinite;user-select:none;text-shadow:0 0 20px rgba(245,158,11,.3)}
@keyframes floatUp{0%{transform:translateY(0) rotate(0deg);opacity:0}10%{opacity:1}90%{opacity:.8}100%{transform:translateY(-100vh) rotate(360deg);opacity:0}}

/* ===== PARTICLE RUNE RING (decorative) ===== */
.rune-ring{position:fixed;pointer-events:none;z-index:0;border-radius:50%;border:1px solid rgba(139,92,246,.08);animation:spinRing linear infinite}
@keyframes spinRing{from{transform:rotate(0deg)}to{transform:rotate(360deg)}}

/* ===== SCREEN AURA ===== */
.screen-aura{position:absolute;border-radius:50%;filter:blur(80px);pointer-events:none;z-index:0}

/* ===== SCROLLBAR ===== */
::-webkit-scrollbar{width:6px}
::-webkit-scrollbar-track{background:var(--bg2)}
::-webkit-scrollbar-thumb{background:var(--border);border-radius:3px}

/* ===== RESPONSIVE ===== */
@media(max-width:480px){
  .ansec{gap:12px}
  .ainp{width:120px;font-size:18px}
  .asbtn{width:120px}
  .abcard{width:60px}
  .hcard{width:58px;height:76px}
}
</style>
</head>
<body>

<canvas id="bgCanvas"></canvas>
<div class="stars-bg" id="starsBg"></div>
<div class="rune-ring" id="rr1" style="width:600px;height:600px;top:-100px;left:-150px;animation-duration:40s"></div>
<div class="rune-ring" id="rr2" style="width:400px;height:400px;bottom:-80px;right:-80px;border-color:rgba(245,158,11,.06);animation-duration:28s;animation-direction:reverse"></div>
<div class="rune-ring" id="rr3" style="width:250px;height:250px;top:40%;left:60%;border-color:rgba(239,68,68,.05);animation-duration:20s"></div>
<div id="floatSymWrap"></div>

<!-- ===== LOGIN SCREEN ===== -->
<div class="screen active" id="screen-login">
  <div class="screen-aura" style="width:400px;height:400px;top:-100px;left:50%;margin-left:-200px;background:radial-gradient(circle,rgba(139,92,246,.15),transparent 70%)"></div>
<div class="screen-aura" style="width:300px;height:300px;bottom:0;right:-50px;background:radial-gradient(circle,rgba(245,158,11,.1),transparent 70%)"></div>
<div class="login-wrap">
    <div class="login-logo">
      <h1>⚔️ MATH BATTLE</h1>
      <span class="subtitle-game">LEGENDS OF NUMBERS</span>
      <p>สนามแข่งคณิตศาสตร์ 1v1</p>
    </div>
    <div class="login-card">
      <div id="loginErrMsg" class="login-err"></div>
      <div id="loginOkMsg" class="login-ok"></div>
      <div class="login-tabs">
        <button class="login-tab active" onclick="switchLoginTab('login',this)">🔑 เข้าสู่ระบบ</button>
        <button class="login-tab" onclick="switchLoginTab('register',this)">✨ สมัครสมาชิก</button>
      </div>
      <!-- Login Form -->
      <div id="loginForm">
        <div class="login-field">
          <label>ชื่อผู้เล่น</label>
          <input type="text" class="inp" id="loginName" placeholder="ใส่ชื่อของคุณ..." maxlength="20" onkeydown="if(event.key==='Enter')doLogin()">
        </div>
        <div class="login-field">
          <label>รหัสผ่าน</label>
          <input type="password" class="inp" id="loginPass" placeholder="รหัสผ่าน..." maxlength="30" onkeydown="if(event.key==='Enter')doLogin()">
        </div>
        <button class="btn btn-p" onclick="doLogin()">เข้าสู่ระบบ ▶</button>
        <div style="margin-top:12px;text-align:center;font-size:12px;color:var(--text2)">ยังไม่มีบัญชี? <span style="color:var(--accent);cursor:pointer" onclick="switchLoginTab('register',null)">สมัครเลย</span></div>
      </div>
      <!-- Register Form -->
      <div id="registerForm" style="display:none">
        <div class="login-field">
          <label>ชื่อผู้เล่น (แสดงในเกม)</label>
          <input type="text" class="inp" id="regName" placeholder="ชื่อที่อยากใช้..." maxlength="20" onkeydown="if(event.key==='Enter')doRegister()">
        </div>
        <div class="login-field">
          <label>รหัสผ่าน</label>
          <input type="password" class="inp" id="regPass" placeholder="ตั้งรหัสผ่าน..." maxlength="30" onkeydown="if(event.key==='Enter')doRegister()">
        </div>
        <div class="login-field">
          <label>ยืนยันรหัสผ่าน</label>
          <input type="password" class="inp" id="regPass2" placeholder="พิมพ์รหัสผ่านอีกครั้ง..." maxlength="30" onkeydown="if(event.key==='Enter')doRegister()">
        </div>
        <button class="btn btn-g" onclick="doRegister()">สมัครสมาชิก ✨</button>
        <div style="margin-top:12px;text-align:center;font-size:12px;color:var(--text2)">มีบัญชีแล้ว? <span style="color:var(--accent);cursor:pointer" onclick="switchLoginTab('login',null)">เข้าสู่ระบบ</span></div>
      </div>
    </div>
  </div>
</div>

<!-- ===== HOME ===== -->
<div class="screen" id="screen-home">
  <div class="home-logo">
    <h1>⚔️ MATH BATTLE</h1>
    <span class="subtitle-game">LEGENDS OF NUMBERS</span>
    <p>สนามแข่งคณิตศาสตร์ 1v1</p>
  </div>
  <div class="menu-box">
    <!-- Profile bar -->
    <div class="home-profile" id="homeProfile">
      <div class="profile-avatar" id="homeAvatar">?</div>
      <div class="profile-info">
        <div class="profile-name" id="homeProfileName">ผู้เล่น</div>
        <div class="profile-stars" id="homeProfileStars">⭐ 0 ดาว</div>
      </div>
      <button class="logout-btn" onclick="doLogout()">ออกจากระบบ</button>
    </div>
    <div class="tabs">
      <button class="tab active" onclick="switchTab('online',event)">🌐 ค้นหาคู่แข่ง</button>
      <button class="tab" onclick="switchTab('bot',event)">🤖 VS บอท</button>
      <button class="tab" onclick="switchTab('lb',event)">🏆 ลีดเดอร์</button>
    </div>
    <div id="tab-online">
      <div class="mtitle">ค้นหาผู้เล่นที่ลงทะเบียน</div>
      <div class="fsearch">
        <input type="text" class="inp" id="searchInput" placeholder="พิมพ์ชื่อผู้เล่น..." oninput="searchFriend(this.value)">
        <button class="btn btn-p" style="width:auto;padding:10px 16px" onclick="searchFriend(document.getElementById('searchInput').value)">ค้นหา</button>
      </div>
      <div id="searchResults"></div>
      <div class="div"></div>
      <div class="mtitle">ผู้เล่นที่ลงทะเบียนทั้งหมด</div>
      <div id="onlinePlayers"></div>
    </div>
    <div id="tab-bot" style="display:none">
      <div class="mtitle">เลือกความยากของบอท</div>
      <div class="llist" id="botLevelList">
        <div class="lbtn" onclick="selBotLv('easy',this)"><span class="li">😊</span><div><div class="ln">ง่าย</div><div class="ld">บอทตอบช้า ผิดบ้าง 35%</div></div></div>
        <div class="lbtn" onclick="selBotLv('medium',this)"><span class="li">😐</span><div><div class="ln">ปานกลาง</div><div class="ld">บอทตอบปานกลาง ผิด 15%</div></div></div>
        <div class="lbtn" onclick="selBotLv('hard',this)"><span class="li">😈</span><div><div class="ln">ยาก</div><div class="ld">บอทตอบเร็วมาก แทบไม่ผิด 3%</div></div></div>
      </div>
      <button class="btn btn-p" id="botStartBtn" onclick="startVsBot()" style="opacity:.5" disabled>เริ่มเกมกับบอท ▶</button>
    </div>
    <div id="tab-lb" style="display:none">
      <div class="mtitle">🏆 Top 10 ผู้เล่น</div>
      <div id="lbList"></div>
    </div>
  </div>
</div>

<!-- ===== TOPIC ===== -->
<div class="screen" id="screen-topic">
  <div class="setup">
    <button class="back-btn" onclick="showScreen('screen-home')">← กลับ</button>
    <div class="stitle">📚 เลือกหัวข้อ</div>
    <div class="tgrid">
      <div class="tbtn" onclick="selTopic('add',this)"><div class="ti">➕</div><div class="tn">การบวก</div></div>
      <div class="tbtn" onclick="selTopic('sub',this)"><div class="ti">➖</div><div class="tn">การลบ</div></div>
      <div class="tbtn" onclick="selTopic('mul',this)"><div class="ti">✖️</div><div class="tn">การคูณ</div></div>
      <div class="tbtn" onclick="selTopic('div',this)"><div class="ti">➗</div><div class="tn">การหาร</div></div>
      <div class="tbtn" onclick="selTopic('mixed',this)"><div class="ti">🔀</div><div class="tn">รวมทุกอย่าง</div></div>
      <div class="tbtn" onclick="selTopic('frac',this)"><div class="ti">🔢</div><div class="tn">เศษส่วน</div></div>
    </div>
    <button class="btn btn-p" id="topicNextBtn" style="opacity:.5" disabled onclick="showScreen('screen-level')">ถัดไป ›</button>
  </div>
</div>

<!-- ===== LEVEL ===== -->
<div class="screen" id="screen-level">
  <div class="setup">
    <button class="back-btn" onclick="showScreen('screen-topic')">← กลับ</button>
    <div class="stitle">⚡ เลือกระดับความยาก</div>
    <div class="llist" id="diffLvList">
      <div class="lbtn" onclick="selLevel('easy',this)"><span class="li">🌱</span><div><div class="ln">ง่าย</div><div class="ld">ตัวเลข 1–10</div></div></div>
      <div class="lbtn" onclick="selLevel('medium',this)"><span class="li">🔥</span><div><div class="ln">ปานกลาง</div><div class="ld">ตัวเลข 2 หลัก</div></div></div>
      <div class="lbtn" onclick="selLevel('hard',this)"><span class="li">💀</span><div><div class="ln">ยาก</div><div class="ld">ตัวเลข 3 หลัก</div></div></div>
      <div class="lbtn" onclick="selLevel('extreme',this)"><span class="li">☠️</span><div><div class="ln">ยากมาก</div><div class="ld">ตัวเลขขนาดใหญ่</div></div></div>
    </div>
    <button class="btn btn-p" id="levelNextBtn" style="opacity:.5" disabled onclick="startGame()">เริ่มเกม! ⚔️</button>
  </div>
</div>

<!-- ===== MODAL: ABILITY PICK ===== -->
<div class="mover" id="apModal" style="display:none">
  <div class="mbox">
    <div class="mtit">🃏 เลือกการ์ดความสามารถ</div>
    <div class="msub" id="apSub">เลือก 1 ใบจาก 3 ใบ</div>
    <div class="apgrid" id="apGrid"></div>
    <button class="btn btn-pu" id="apConfirm" onclick="confirmAbPick()" style="opacity:.5" disabled>ยืนยันเลือก</button>
  </div>
</div>

<!-- ===== MODAL: SWAP ===== -->
<div class="mover" id="swapModal" style="display:none">
  <div class="mbox">
    <div class="mtit">🔄 สลับโจทย์?</div>
    <div class="msub">ต้องการสลับโจทย์กับฝ่ายตรงข้ามไหม?</div>
    <div class="flex-gap mt16">
      <button class="btn btn-r" onclick="confirmSwap(true)">สลับ ✅</button>
      <button class="btn btn-s" onclick="confirmSwap(false)">ไม่สลับ ❌</button>
    </div>
  </div>
</div>

<!-- ===== GAME ===== -->
<div class="screen" id="screen-game">
  <div class="glayout">
    <div class="ghdr">
      <div class="phdr">
        <div>
          <div class="pntag" id="p1Name">P1</div>
          <div class="hearts" id="p1Hearts"></div>
        </div>
      </div>
      <div class="tc">
        <div class="vstag">VS</div>
        <div class="rdis" id="roundDis">รอบที่ 1</div>
      </div>
      <div class="phdr" style="flex-direction:row-reverse">
        <div style="text-align:right">
          <div class="pntag" id="p2Name">P2</div>
          <div class="hearts" style="justify-content:flex-end" id="p2Hearts"></div>
        </div>
      </div>
    </div>
    <div id="statusArea" style="padding:0 16px"></div>
    <div class="bsec">
      <div class="rinfo">
        <div class="rbadge" id="phaseBadge">เลือกการ์ดโจทย์</div>
        <div class="pdesc" id="phaseDesc">แต่ละฝ่ายเลือก 1 ใบจากมือ</div>
      </div>
      <div class="qdis">
        <div class="qcard" id="qCard">
          <div class="qtxt" id="qText"><span class="qhid">? ? ?</span></div>
        </div>
        <div id="botArea" style="display:none">
          <div class="botthink"><div class="d"></div><div class="d"></div><div class="d"></div><span>บอทกำลังคิด...</span></div>
        </div>
      </div>
      <div id="ansSec" style="display:none">
        <div class="ansec">
          <div>
            <div class="albl" id="p1AnsLbl">P1</div>
            <input type="number" class="ainp" id="p1Ans" placeholder="?" onkeydown="if(event.key==='Enter')submitAns(1)">
            <button class="asbtn" id="p1Btn" onclick="submitAns(1)">ยืนยัน</button>
          </div>
          <div class="vsdiv">—</div>
          <div>
            <div class="albl" id="p2AnsLbl">P2</div>
            <input type="number" class="ainp" id="p2Ans" placeholder="?" onkeydown="if(event.key==='Enter')submitAns(2)">
            <button class="asbtn" id="p2Btn" onclick="submitAns(2)">ยืนยัน</button>
          </div>
        </div>
        <div id="mcWrap" style="display:none;margin-top:12px">
          <div class="chgrid" id="chGrid"></div>
        </div>
      </div>
    </div>
    <div class="hsec hp1" id="p1HSec">
      <div class="hhdr"><div class="clbl">🃏 <span id="p1HL">P1</span> — การ์ดโจทย์</div><div class="hhint">เลือก 1 ใบ</div></div>
      <div class="hcards" id="p1HCards"></div>
    </div>
    <div class="hsec" id="p2HSec">
      <div class="hhdr"><div class="clbl">🃏 <span id="p2HL">P2</span> — การ์ดโจทย์</div><div class="hhint">เลือก 1 ใบ</div></div>
      <div class="hcards" id="p2HCards"></div>
    </div>
    <div id="confBar" style="display:none" class="confbar">
      <button class="btn btn-g" onclick="confirmCardSel()">✅ ยืนยันการ์ดที่เลือก</button>
    </div>
    <div class="csec">
      <div class="abrow">
        <div>
          <div class="clbl">🌟 <span id="p1AL">P1</span> การ์ดพิเศษ</div>
          <div class="crow" id="p1AbCards"></div>
        </div>
        <div style="text-align:right">
          <div class="clbl">🌟 <span id="p2AL">P2</span> การ์ดพิเศษ</div>
          <div class="crow" id="p2AbCards" style="justify-content:flex-end"></div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ===== ROUND RESULT ===== -->
<div class="rrover" id="rrOver" style="display:none">
  <div class="rrbox">
    <div class="rico" id="rIcon">🏆</div>
    <div class="rtit" id="rTitle">ชนะ!</div>
    <div class="rsub" id="rSub"></div>
    <div class="rdet" id="rDet"></div>
    <button class="btn btn-p mt16" onclick="nextRound()">ถัดไป ▶</button>
  </div>
</div>

<!-- ===== GAME OVER ===== -->
<div class="screen" id="screen-gameover">
  <div class="goscreen">
    <div class="goico" id="goIco">🏆</div>
    <div class="gotit" id="goTit">ชนะ!</div>
    <div class="gost" id="goSt">⭐</div>
    <div class="godesc" id="goDesc"></div>
    <div class="gostats" id="goStats"></div>
    <div class="flex-gap">
      <button class="btn btn-p" onclick="playAgain()">เล่นอีกครั้ง ↺</button>
      <button class="btn btn-s" onclick="goHome()">หน้าหลัก 🏠</button>
    </div>
  </div>
</div>

<script>
/* ============================================================
   AUTH & PLAYER REGISTRY
============================================================ */
// Storage keys
const PLAYERS_KEY = 'mb_players';   // { name -> { pass, stars, wins, losses, created } }
const SESSION_KEY = 'mb_session';   // { name }
const LB_KEY      = 'mb_lb';
const STARS_KEY   = 'mb_stars';

function loadPlayers(){ try{return JSON.parse(localStorage.getItem(PLAYERS_KEY)||'{}')}catch(e){return{}} }
function savePlayers(p){ localStorage.setItem(PLAYERS_KEY,JSON.stringify(p)) }
function loadSession(){ try{return JSON.parse(localStorage.getItem(SESSION_KEY)||'null')}catch(e){return null} }
function saveSession(s){ localStorage.setItem(SESSION_KEY,JSON.stringify(s)) }

// Simple hash (not secure, but fine for a game)
function hashPass(s){ let h=0;for(let i=0;i<s.length;i++){h=((h<<5)-h)+s.charCodeAt(i);h|=0}return h.toString(16) }

function switchLoginTab(tab, el){
  if(el){document.querySelectorAll('.login-tab').forEach(t=>t.classList.remove('active'));el.classList.add('login-tab active')}
  else{
    document.querySelectorAll('.login-tab').forEach((t,i)=>{t.classList.toggle('active',(tab==='login'&&i===0)||(tab==='register'&&i===1))});
  }
  document.getElementById('loginForm').style.display=tab==='login'?'block':'none';
  document.getElementById('registerForm').style.display=tab==='register'?'block':'none';
  document.getElementById('loginErrMsg').style.display='none';
  document.getElementById('loginOkMsg').style.display='none';
}

function showLoginMsg(msg,isOk){
  const e=document.getElementById('loginErrMsg'),o=document.getElementById('loginOkMsg');
  if(isOk){o.textContent=msg;o.style.display='block';e.style.display='none'}
  else{e.textContent=msg;e.style.display='block';o.style.display='none'}
}

function doRegister(){
  const name=(document.getElementById('regName').value||'').trim();
  const pass=document.getElementById('regPass').value;
  const pass2=document.getElementById('regPass2').value;
  if(!name){showLoginMsg('กรุณาใส่ชื่อผู้เล่น');return}
  if(name.length<2){showLoginMsg('ชื่อต้องมีอย่างน้อย 2 ตัวอักษร');return}
  if(!pass||pass.length<4){showLoginMsg('รหัสผ่านต้องมีอย่างน้อย 4 ตัวอักษร');return}
  if(pass!==pass2){showLoginMsg('รหัสผ่านไม่ตรงกัน');return}
  const players=loadPlayers();
  const key=name.toLowerCase();
  if(Object.keys(players).find(k=>k===key)){showLoginMsg('ชื่อนี้ถูกใช้แล้ว กรุณาเลือกชื่ออื่น');return}
  players[key]={name,pass:hashPass(pass),stars:0,wins:0,losses:0,created:Date.now()};
  savePlayers(players);
  showLoginMsg('สมัครสำเร็จ! กรุณาเข้าสู่ระบบ',true);
  setTimeout(()=>switchLoginTab('login',null),1200);
  document.getElementById('loginName').value=name;
}

function doLogin(){
  const name=(document.getElementById('loginName').value||'').trim();
  const pass=document.getElementById('loginPass').value;
  if(!name){showLoginMsg('กรุณาใส่ชื่อผู้เล่น');return}
  if(!pass){showLoginMsg('กรุณาใส่รหัสผ่าน');return}
  const players=loadPlayers();
  const key=name.toLowerCase();
  const p=Object.values(players).find(p=>p.name.toLowerCase()===key);
  if(!p){showLoginMsg('ไม่พบชื่อผู้เล่นนี้');return}
  if(p.pass!==hashPass(pass)){showLoginMsg('รหัสผ่านไม่ถูกต้อง');return}
  saveSession({name:p.name});
  afterLogin(p.name);
}

function doLogout(){
  saveSession(null);
  showScreen('screen-login');
  document.getElementById('loginPass').value='';
  document.getElementById('loginErrMsg').style.display='none';
  document.getElementById('loginOkMsg').style.display='none';
}

function afterLogin(name){
  G.myName=name;
  loadData();
  updateHomeProfile();
  renderOnline();
  renderLB();
  showScreen('screen-home');
}

function updateHomeProfile(){
  const name=G.myName||'ผู้เล่น';
  document.getElementById('homeProfileName').textContent=name;
  document.getElementById('homeProfileStars').textContent=`⭐ ${G.stars[name]||0} ดาว`;
  document.getElementById('homeAvatar').textContent=name.charAt(0).toUpperCase();
}

/* ============================================================
   ABILITY DEFINITIONS
============================================================ */
const ALL_AB=[
  {id:'godMode',icon:'🛡️',name:'การ์ดกันตาย',desc:'เมื่อเหลือ 1HP แพ้ = ไม่เสียชีวิต (1ครั้ง)'},
  {id:'swap',icon:'🔄',name:'การ์ดสลับโจทย์',desc:'สลับโจทย์กับฝ่ายตรงข้ามหลังเปิดการ์ด (1ครั้ง)'},
  {id:'freeze',icon:'❄️',name:'การ์ดหยุดเวลา',desc:'ฝ่ายตรงข้ามตอบไม่ได้ 3 วิ (1ครั้ง)'},
  {id:'hint',icon:'💡',name:'การช่วยตอบ',desc:'แสดง 4 ตัวเลือก มี 1 ถูก (1ครั้ง)'},
  {id:'double',icon:'💀',name:'การ์ดลดชีวิต×2',desc:'ถ้าชนะรอบนี้ ฝ่ายตรงข้ามเสีย 2HP (1ครั้ง)'},
  {id:'heal',icon:'❤️',name:'การ์ดเพิ่มชีวิต',desc:'เพิ่ม 1HP ทันที (1ครั้ง)'},
  {id:'shield',icon:'🪬',name:'การ์ดป้องกัน',desc:'ป้องกัน สลับโจทย์ + ลดชีวิต×2 (1ครั้ง)'},
  {id:'blur',icon:'🌫️',name:'การ์ดเบลอตัวเลข',desc:'เบลอเลข 1 ตัวในโจทย์ฝ่ายตรงข้าม (1ครั้ง)'}
];

/* ============================================================
   GAME STATE
============================================================ */
const G={
  myName:'',opName:'',isBot:false,botLv:null,topic:null,level:null,
  round:1,p1HP:5,p2HP:5,
  p1Cards:[],p2Cards:[],p1Sel:null,p2Sel:null,
  p1Ab:[],p2Ab:[],p1AbUsed:{},p2AbUsed:{},
  p1God:false,p2God:false,p1Shield:false,p2Shield:false,
  p1Dbl:false,p2Dbl:false,p1Frz:false,p2Frz:false,
  curQ:null,p1Ans:null,p2Ans:null,p1Ms:null,p2Ms:null,qTime:null,
  abRound:0,pendPP:null,abSelIdx:null,
  botCancel:null,phase:'cardSelect',stars:{},lb:[]
};

let selTopic_=null,selLevel_=null,selBotLv_=null;

/* ============================================================
   DATA PERSIST
============================================================ */
function loadData(){
  try{G.stars=JSON.parse(localStorage.getItem(STARS_KEY)||'{}');G.lb=JSON.parse(localStorage.getItem(LB_KEY)||'[]')}catch(e){}
}
function saveData(){
  try{localStorage.setItem(STARS_KEY,JSON.stringify(G.stars));localStorage.setItem(LB_KEY,JSON.stringify(G.lb))}catch(e){}
}
function addStars(name,d){
  if(!name||G.isBot)return;
  G.stars[name]=Math.max(0,(G.stars[name]||0)+d);
  // sync to players registry
  const players=loadPlayers();
  const key=name.toLowerCase();
  const pk=Object.keys(players).find(k=>k===key);
  if(pk){players[pk].stars=G.stars[name];if(d>0)players[pk].wins=(players[pk].wins||0)+1;else if(d<0)players[pk].losses=(players[pk].losses||0)+1;savePlayers(players)}
  const idx=G.lb.findIndex(x=>x.name===name);
  if(idx>=0)G.lb[idx].stars=G.stars[name];else G.lb.push({name,stars:G.stars[name]});
  G.lb.sort((a,b)=>b.stars-a.stars);
  if(G.lb.length>50)G.lb.splice(50);
  saveData();
}

/* ============================================================
   MATH QUESTIONS
============================================================ */
function gcd(a,b){return b===0?a:gcd(b,a%b)}
function ri(mn,mx){return Math.floor(Math.random()*(mx-mn+1))+mn}
const LR={easy:[1,10],medium:[2,50],hard:[10,100],extreme:[20,500]};
const MR={easy:[1,9],medium:[2,12],hard:[2,25],extreme:[5,50]};

function genQ(topic,level){
  const ts=['add','sub','mul','div'];
  const t=topic==='mixed'?ts[ri(0,3)]:topic;
  const[mn,mx]=LR[level];
  const r=()=>ri(mn,mx);
  if(t==='frac'){
    const md=level==='easy'?6:level==='medium'?10:level==='hard'?16:20;
    const d1=ri(2,md),d2=ri(2,md),n1=ri(1,d1-1),n2=ri(1,d2-1);
    const nr=n1*d2+n2*d1,dr=d1*d2,g=gcd(nr,dr);
    return{display:`${n1}/${d1} + ${n2}/${d2}`,ans:nr/dr,isFrac:true};
  }
  let a,b,ans,display;
  if(t==='add'){a=r();b=r();ans=a+b;display=`${a} + ${b}`}
  else if(t==='sub'){a=r();b=r();if(a<b)[a,b]=[b,a];ans=a-b;display=`${a} − ${b}`}
  else if(t==='mul'){const[mm,mx2]=MR[level];a=ri(mm,mx2);b=ri(mm,mx2);ans=a*b;display=`${a} × ${b}`}
  else{const divs=[2,3,4,5,6,7,8,9,10,11,12];b=divs[ri(0,Math.min(divs.length-1,level==='easy'?3:level==='medium'?7:11))];ans=r();a=ans*b;display=`${a} ÷ ${b}`}
  return{display,ans,isFrac:false};
}
function genHand(n){return Array.from({length:n},(_,i)=>({id:`c_${Date.now()}_${i}_${Math.random().toString(36).slice(2)}`,q:genQ(G.topic,G.level),used:false}))}
function isCorrect(val,q){const v=parseFloat(val);if(isNaN(v))return false;return Math.abs(v-q.ans)<=(q.isFrac?0.005:0)}

/* ============================================================
   BOOT
============================================================ */
document.addEventListener('DOMContentLoaded',()=>{
  createStars();
  // Check existing session
  const sess=loadSession();
  if(sess&&sess.name){
    const players=loadPlayers();
    const pk=Object.keys(players).find(k=>k===sess.name.toLowerCase());
    if(pk){afterLogin(players[pk].name);return}
    else saveSession(null);
  }
  showScreen('screen-login');
  document.addEventListener('keydown',e=>{
    if(e.key==='Escape'){['apModal','swapModal'].forEach(id=>{const el=document.getElementById(id);if(el)el.style.display='none'})}
  });
});
function createStars(){
  const c=document.getElementById('starsBg');
  for(let i=0;i<90;i++){const s=document.createElement('div');s.className='star';s.style.cssText=`left:${Math.random()*100}%;top:${Math.random()*100}%;--d:${2+Math.random()*5}s;animation-delay:${Math.random()*5}s;opacity:${.1+Math.random()*.4}`;c.appendChild(s)}
}

/* ============================================================
   SCREEN NAV
============================================================ */
function showScreen(id){document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));document.getElementById(id)?.classList.add('active');window.scrollTo(0,0)}
function goHome(){showScreen('screen-home');updateHomeProfile();renderLB();renderOnline()}

/* ============================================================
   HOME TABS
============================================================ */
function switchTab(tab,e){
  document.querySelectorAll('.tab').forEach(t=>t.classList.remove('active'));
  e?.currentTarget?.classList.add('active');
  ['online','bot','lb'].forEach(t=>{document.getElementById(`tab-${t}`).style.display=t===tab?'block':'none'});
  if(tab==='lb')renderLB();
  if(tab==='online')renderOnline();
}

/* ============================================================
   ONLINE PLAYERS — from registry
============================================================ */
function renderOnline(){
  const players=loadPlayers();
  const el=document.getElementById('onlinePlayers');
  const all=Object.values(players).filter(p=>p.name!==G.myName).sort((a,b)=>(b.stars||0)-(a.stars||0));
  if(!all.length){el.innerHTML=`<div class="tmuted" style="padding:8px 0;text-align:center">ยังไม่มีผู้เล่นคนอื่น<br><small>ชวนเพื่อนมาสมัครสมาชิก!</small></div>`;return}
  el.innerHTML=all.slice(0,8).map(p=>`
    <div class="fi">
      <span>
        <span class="dot-reg"></span>
        <span>
          <span class="fn">${esc(p.name)}</span>
          <div class="fstars">⭐ ${p.stars||0} ดาว | ชนะ ${p.wins||0} แพ้ ${p.losses||0}</div>
        </span>
      </span>
      <button class="btn btn-b" style="width:auto;padding:6px 14px;font-size:12px" onclick="inviteP('${esc(p.name)}')">เชิญ ▶</button>
    </div>`).join('');
}

function searchFriend(v){
  const r=document.getElementById('searchResults');
  const q=(v||'').trim();
  if(!q){r.innerHTML='';return}
  const players=loadPlayers();
  const m=Object.values(players).filter(p=>p.name!==G.myName&&(p.name.toLowerCase().includes(q.toLowerCase())));
  if(!m.length){r.innerHTML=`<div class="tmuted" style="padding:8px 0">ไม่พบผู้เล่น "${esc(q)}"</div>`;return}
  r.innerHTML=m.map(p=>`<div class="fi"><span><span class="dot-reg"></span><span><span class="fn">${esc(p.name)}</span><div class="fstars">⭐ ${p.stars||0} ดาว</div></span></span>
    <button class="btn btn-g" style="width:auto;padding:6px 14px;font-size:12px" onclick="inviteP('${esc(p.name)}')">เชิญ ▶</button></div>`).join('');
}

function inviteP(name){
  G.opName=name;G.isBot=false;G.botLv=null;showScreen('screen-topic');
}

/* ============================================================
   BOT SETUP
============================================================ */
function selBotLv(lv,el){
  selBotLv_=lv;
  document.querySelectorAll('#botLevelList .lbtn').forEach(b=>b.classList.remove('sel'));
  el.classList.add('sel');
  const btn=document.getElementById('botStartBtn');btn.disabled=false;btn.style.opacity='1';
}
function startVsBot(){
  if(!selBotLv_)return;
  G.isBot=true;G.botLv=selBotLv_;
  G.opName={easy:'บอท (ง่าย)',medium:'บอท (ปานกลาง)',hard:'บอท (ยาก)'}[selBotLv_];
  showScreen('screen-topic');
}

/* ============================================================
   TOPIC & LEVEL
============================================================ */
function selTopic(t,el){
  selTopic_=t;G.topic=t;
  document.querySelectorAll('.tbtn').forEach(b=>b.classList.remove('sel'));
  el.classList.add('sel');
  const btn=document.getElementById('topicNextBtn');btn.disabled=false;btn.style.opacity='1';
}
function selLevel(lv,el){
  selLevel_=lv;G.level=lv;
  document.querySelectorAll('#diffLvList .lbtn').forEach(b=>b.classList.remove('sel'));
  el.classList.add('sel');
  const btn=document.getElementById('levelNextBtn');btn.disabled=false;btn.style.opacity='1';
}

/* ============================================================
   LEADERBOARD
============================================================ */
function renderLB(){
  const el=document.getElementById('lbList');if(!el)return;
  // Build LB from player registry
  const players=loadPlayers();
  const all=Object.values(players).sort((a,b)=>(b.stars||0)-(a.stars||0)).slice(0,10);
  if(!all.length){el.innerHTML=`<div class="tmuted tc" style="padding:20px">ยังไม่มีข้อมูล</div>`;return}
  el.innerHTML=all.map((p,i)=>{
    const rc=i===0?'gold':i===1?'silver':i===2?'bronze':'';
    const m=i===0?'🥇':i===1?'🥈':i===2?'🥉':i+1;
    const isMe=p.name===G.myName;
    return`<div class="lbi" style="${isMe?'border-color:var(--accent);background:rgba(245,158,11,.07)':''}"><div class="lbr ${rc}">${m}</div><div class="lbn">${esc(p.name)}${isMe?' 👈':''}</div><div class="lbs">⭐ ${p.stars||0}</div></div>`;
  }).join('');
}

/* ============================================================
   GAME START / RESET
============================================================ */
function startGame(){
  if(!G.level)return;
  G.round=1;G.p1HP=5;G.p2HP=5;G.phase='cardSelect';G.abRound=0;
  G.p1Ab=[];G.p2Ab=[];G.p1AbUsed={};G.p2AbUsed={};
  G.p1God=false;G.p2God=false;G.p1Shield=false;G.p2Shield=false;
  G.p1Dbl=false;G.p2Dbl=false;G.p1Frz=false;G.p2Frz=false;
  G.p1Cards=genHand(5);G.p2Cards=genHand(5);
  G.p1Sel=null;G.p2Sel=null;
  showScreen('screen-game');
  updateUI();
  setTimeout(()=>openAbPick(0),400);
}
function playAgain(){if(G.botCancel){G.botCancel();G.botCancel=null}startGame()}

function resetRound(){
  G.p1God=false;G.p2God=false;G.p1Shield=false;G.p2Shield=false;
  G.p1Dbl=false;G.p2Dbl=false;G.p1Frz=false;G.p2Frz=false;
  G.p1Ans=null;G.p2Ans=null;G.p1Ms=null;G.p2Ms=null;G.qTime=null;
  G.curQ=null;G.p1Sel=null;G.p2Sel=null;
}

/* ============================================================
   CARD SELECTION
============================================================ */
function selCard(player,idx){
  if(G.phase!=='cardSelect')return;
  const cards=player==='p1'?G.p1Cards:G.p2Cards;
  if(!cards[idx]||cards[idx].used)return;
  if(player==='p1')G.p1Sel=idx;else G.p2Sel=idx;
  renderHandCards();checkConf();
  if(G.isBot&&G.p1Sel!==null&&G.p2Sel===null){
    const av=G.p2Cards.map((c,i)=>({c,i})).filter(x=>!x.c.used);
    if(av.length)G.p2Sel=av[Math.floor(Math.random()*av.length)].i;
    renderHandCards();checkConf();
  }
}
function checkConf(){
  const ok=G.p1Sel!==null&&(G.isBot||G.p2Sel!==null);
  document.getElementById('confBar').style.display=ok?'block':'none';
}
function confirmCardSel(){
  if(G.p1Sel===null)return;
  if(!G.isBot&&G.p2Sel===null)return;
  G.phase='answer';revealQ();
}

/* ============================================================
   REVEAL QUESTION
============================================================ */
function revealQ(){
  G.curQ={...G.p1Cards[G.p1Sel].q};
  G.qTime=Date.now();
  document.getElementById('qCard').classList.add('rev');
  document.getElementById('qText').textContent=G.curQ.display;
  const as=document.getElementById('ansSec');as.style.display='block';
  const i1=document.getElementById('p1Ans'),i2=document.getElementById('p2Ans');
  const b1=document.getElementById('p1Btn'),b2=document.getElementById('p2Btn');
  i1.value='';i2.value='';i1.disabled=false;i2.disabled=false;
  b1.disabled=false;b2.disabled=false;
  document.getElementById('p1HSec').style.display='none';
  document.getElementById('p2HSec').style.display='none';
  document.getElementById('confBar').style.display='none';
  setPhaseBadge();
  if(G.p2Frz)applyFreezeUI('p2',3);
  if(G.p1Frz)applyFreezeUI('p1',3);
  i1.focus();
  if(G.isBot){
    document.getElementById('botArea').style.display='block';
    const ba=botDecideAb();
    if(ba)setTimeout(()=>useAbility('p2',ba),600);
    const cfg={easy:[4500,10000,.35],medium:[2000,5000,.15],hard:[700,2500,.03]}[G.botLv]||[2000,5000,.15];
    const delay=cfg[0]+Math.random()*(cfg[1]-cfg[0]);
    let cancelled=false;
    const t=setTimeout(()=>{
      if(cancelled||G.phase!=='answer'||G.p2Ans!==null)return;
      document.getElementById('botArea').style.display='none';
      let ans=G.curQ.ans;
      if(Math.random()<cfg[2]){const off=Math.ceil(Math.random()*Math.max(3,Math.abs(ans)*.25));ans=ans+(Math.random()<.5?off:-off);ans=G.curQ.isFrac?parseFloat(ans.toFixed(2)):Math.round(ans)}
      G.p2Ans=ans;G.p2Ms=Date.now()-G.qTime;
      i2.value=ans;i2.disabled=true;b2.disabled=true;
      if(G.p1Ans!==null)evalRound();
    },delay);
    G.botCancel=()=>{cancelled=true;clearTimeout(t)};
  }
}
function botDecideAb(){
  const ord={easy:['heal','hint','shield','godMode'],medium:['heal','freeze','double','hint'],hard:['double','freeze','blur','swap','heal']}[G.botLv]||[];
  for(const id of ord){if(G.p2Ab.find(a=>a.id===id)&&!G.p2AbUsed[id]&&canUseAb(id,'answer'))return id}
  return null;
}
function canUseAb(id,phase){
  const inst=['godMode','shield','heal','double'];
  return inst.includes(id)||phase==='answer';
}
function applyFreezeUI(player,sec){
  const n=player==='p1'?1:2;
  const inp=document.getElementById(`p${n}Ans`),btn=document.getElementById(`p${n}Btn`);
  if(!inp)return;
  inp.disabled=true;btn.disabled=true;
  const msg=document.createElement('div');msg.className='fzmsg';msg.id=`fz${player}`;
  msg.textContent=`❄️ ${player.toUpperCase()} ถูกหยุดเวลา... ${sec}s`;
  document.getElementById('ansSec').appendChild(msg);
  let cnt=sec;
  const iv=setInterval(()=>{cnt--;if(msg.parentNode)msg.textContent=`❄️ ${player.toUpperCase()} ถูกหยุดเวลา... ${cnt}s`;if(cnt<=0){clearInterval(iv);if(G.phase!=='answer')return;inp.disabled=false;btn.disabled=false;if(msg.parentNode)msg.parentNode.removeChild(msg);inp.focus()}},1000);
}

/* ============================================================
   SUBMIT ANSWER
============================================================ */
function submitAns(p){
  if(G.phase!=='answer')return;
  const inp=document.getElementById(`p${p}Ans`);
  const val=parseFloat(inp.value);
  if(isNaN(val)){inp.focus();return}
  const key=`p${p}Ans`,ms=`p${p}Ms`;
  if(G[key]!==null)return;
  G[key]=val;G[ms]=Date.now()-G.qTime;
  inp.disabled=true;document.getElementById(`p${p}Btn`).disabled=true;
  if(G.p1Ans!==null&&G.p2Ans!==null)evalRound();
}

/* ============================================================
   EVALUATE ROUND
============================================================ */
function evalRound(){
  if(G.botCancel){G.botCancel();G.botCancel=null}
  G.phase='result';
  const q=G.curQ;
  const c1=isCorrect(G.p1Ans,q),c2=isCorrect(G.p2Ans,q);
  let winner=null;
  if(c1&&c2)winner=G.p1Ms<=G.p2Ms?'p1':'p2';
  else if(c1)winner='p1';
  else if(c2)winner='p2';
  else winner='draw';

  let extra='';
  if(winner==='p1'){
    let dmg=(G.p1Dbl&&!G.p2Shield)?2:1;
    if(G.p1Dbl&&G.p2Shield){G.p2Shield=false;extra='🪬 P2 โล่ป้องกัน ลดชีวิต×2!';dmg=1}
    if(dmg===2)extra='💀 การ์ดลดชีวิต×2 ทำงาน!';
    if(G.p2God&&G.p2HP<=1){dmg=0;G.p2God=false;extra='🛡️ P2 การ์ดกันตาย!'}
    G.p2HP=Math.max(0,G.p2HP-dmg);if(G.p1Dbl)G.p1Dbl=false;
  }else if(winner==='p2'){
    let dmg=(G.p2Dbl&&!G.p1Shield)?2:1;
    if(G.p2Dbl&&G.p1Shield){G.p1Shield=false;extra='🪬 P1 โล่ป้องกัน ลดชีวิต×2!';dmg=1}
    if(dmg===2)extra='💀 การ์ดลดชีวิต×2 ทำงาน!';
    if(G.p1God&&G.p1HP<=1){dmg=0;G.p1God=false;extra='🛡️ P1 การ์ดกันตาย!'}
    G.p1HP=Math.max(0,G.p1HP-dmg);if(G.p2Dbl)G.p2Dbl=false;
  }

  if(G.p1Sel!==null)G.p1Cards[G.p1Sel].used=true;
  if(G.p2Sel!==null)G.p2Cards[G.p2Sel].used=true;
  G.p1Frz=false;G.p2Frz=false;

  showRR(winner,c1,c2,extra);renderHearts();
}

/* ============================================================
   NEXT ROUND
============================================================ */
function nextRound(){
  document.getElementById('rrOver').style.display='none';
  if(G.p1HP<=0||G.p2HP<=0){endGame();return}
  G.round++;
  if(G.p1Cards.filter(c=>!c.used).length===0)G.p1Cards=genHand(5);
  if(G.p2Cards.filter(c=>!c.used).length===0)G.p2Cards=genHand(5);
  resetRound();G.phase='cardSelect';
  updateUI();
  if(G.round===3&&G.abRound===1){G.abRound=2;setTimeout(()=>openAbPick(0),400)}
}

/* ============================================================
   END GAME
============================================================ */
function endGame(){
  const w1=G.p2HP<=0&&G.p1HP>0,w2=G.p1HP<=0&&G.p2HP>0;
  if(!G.isBot){
    if(w1){addStars(G.myName,1);addStars(G.opName,-1)}
    else if(w2){addStars(G.opName,1);addStars(G.myName,-1)}
  }
  updateHomeProfile();
  document.getElementById('goIco').textContent=w1?'🏆':w2?'💔':'🤝';
  document.getElementById('goTit').textContent=w1?`${esc(G.myName)} ชนะ! 🎉`:w2?`${esc(G.opName)} ชนะ!`:'เสมอ! 🤝';
  document.getElementById('goSt').textContent=G.isBot?'🤖 ไม่นับดาว':w1?'⭐ +1 ดาว':w2?'💔 −1 ดาว':'➖ ±0 ดาว';
  document.getElementById('goDesc').textContent=G.isBot?`เล่นกับ ${G.opName}`:`เล่นกับ ${esc(G.opName)}`;
  document.getElementById('goStats').innerHTML=`
    <div style="display:flex;justify-content:space-between;margin-bottom:8px"><span>❤️ ${esc(G.myName)}</span><strong>${G.p1HP} HP</strong></div>
    <div style="display:flex;justify-content:space-between${G.isBot?'':';margin-bottom:12px'}"><span>❤️ ${esc(G.opName)}</span><strong>${G.p2HP} HP</strong></div>
    ${!G.isBot?`<div style="margin-top:12px;padding-top:12px;border-top:1px solid var(--border);font-size:12px;color:var(--text2)">ดาวของคุณ: <strong style="color:var(--gold)">⭐ ${G.stars[G.myName]||0}</strong></div>`:''}`;
  showScreen('screen-gameover');renderLB();
}

/* ============================================================
   ABILITY PICK FLOW
============================================================ */
function openAbPick(pi){
  G.pendPP=pi;G.abSelIdx=null;
  const owned=(pi===0?G.p1Ab:G.p2Ab).map(a=>a.id);
  const avail=ALL_AB.filter(a=>!owned.includes(a.id)).sort(()=>Math.random()-.5).slice(0,3);
  if(!avail.length){finishAbPick(pi);return}
  const pn=pi===0?(G.myName||'P1'):(G.opName||'P2');
  document.getElementById('apSub').textContent=`${esc(pn)}: เลือก 1 ใบจาก 3 ใบ`;
  const grid=document.getElementById('apGrid');
  grid._ch=avail;
  grid.innerHTML=avail.map((a,i)=>`<div class="apc" id="apc${i}" onclick="selAbCard(${i})"><div class="api">${a.icon}</div><div class="apn">${a.name}</div><div class="apd">${a.desc}</div></div>`).join('');
  const cb=document.getElementById('apConfirm');cb.disabled=true;cb.style.opacity='0.5';
  document.getElementById('apModal').style.display='flex';
}
function selAbCard(i){
  G.abSelIdx=i;
  document.querySelectorAll('.apc').forEach((el,j)=>el.classList.toggle('sel',j===i));
  const cb=document.getElementById('apConfirm');cb.disabled=false;cb.style.opacity='1';
}
function confirmAbPick(){
  if(G.abSelIdx===null)return;
  const grid=document.getElementById('apGrid');
  const card={...grid._ch[G.abSelIdx]};
  if(G.pendPP===0)G.p1Ab.push(card);else G.p2Ab.push(card);
  document.getElementById('apModal').style.display='none';
  finishAbPick(G.pendPP);
}
function finishAbPick(pi){
  if(pi===0){
    if(G.isBot){
      const owned=G.p2Ab.map(a=>a.id);
      const avail=ALL_AB.filter(a=>!owned.includes(a.id));
      const pref=['heal','godMode','double','freeze','shield','blur','swap','hint'];
      for(const id of pref){const f=avail.find(a=>a.id===id);if(f){G.p2Ab.push({...f});break}}
      if(G.abRound===0)G.abRound=1;
      updateUI();
    }else{setTimeout(()=>openAbPick(1),300)}
  }else{
    if(G.abRound===0)G.abRound=1;
    updateUI();
  }
}

/* ============================================================
   USE ABILITY
============================================================ */
function useAbility(player,id){
  const um=player==='p1'?G.p1AbUsed:G.p2AbUsed;
  const ab=player==='p1'?G.p1Ab:G.p2Ab;
  if(um[id])return;
  if(!ab.find(a=>a.id===id))return;
  if(!canUseAb(id,G.phase)){showStatus(`⚠️ ใช้การ์ดนี้ได้เฉพาะตอนตอบคำถาม`,'si');return}
  const opp=player==='p1'?'p2':'p1';
  const pn=player==='p1'?(G.myName||'P1'):(G.opName||'P2');
  const on=opp==='p1'?(G.myName||'P1'):(G.opName||'P2');
  switch(id){
    case 'heal':
      if(player==='p1')G.p1HP=Math.min(9,G.p1HP+1);else G.p2HP=Math.min(9,G.p2HP+1);
      um[id]=true;showStatus(`❤️ ${esc(pn)} เพิ่ม 1HP!`,'sa');renderHearts();break;
    case 'godMode':
      if(player==='p1')G.p1God=true;else G.p2God=true;
      um[id]=true;showStatus(`🛡️ ${esc(pn)} เปิดการ์ดกันตาย!`,'sa');break;
    case 'shield':
      if(player==='p1')G.p1Shield=true;else G.p2Shield=true;
      um[id]=true;showStatus(`🪬 ${esc(pn)} วางโล่ป้องกัน!`,'sa');break;
    case 'double':
      if(player==='p1')G.p1Dbl=true;else G.p2Dbl=true;
      um[id]=true;showStatus(`💀 ${esc(pn)} เปิดโหมดลดชีวิต×2!`,'sa');break;
    case 'freeze':
      if(G.phase!=='answer')return;
      if(player==='p1')G.p2Frz=true;else G.p1Frz=true;
      um[id]=true;applyFreezeUI(opp,3);showStatus(`❄️ ${esc(on)} ถูกหยุดเวลา 3 วิ!`,'sa');break;
    case 'hint':
      if(G.phase!=='answer')return;
      um[id]=true;showHint();break;
    case 'swap':
      if(G.phase!=='answer')return;
      const os=opp==='p1'?G.p1Shield:G.p2Shield;
      if(os){if(opp==='p1')G.p1Shield=false;else G.p2Shield=false;um[id]=true;showStatus(`🪬 ${esc(on)} มีโล่! สลับโจทย์ไม่ได้`,'si');renderAbCards();return}
      um[id]=true;document.getElementById('swapModal').style.display='flex';break;
    case 'blur':
      if(G.phase!=='answer')return;
      um[id]=true;applyBlur();showStatus(`🌫️ ${esc(pn)} เบลอตัวเลขในโจทย์!`,'sa');break;
  }
  renderAbCards();
}
function confirmSwap(doIt){
  document.getElementById('swapModal').style.display='none';
  if(!doIt)return;
  const q2=G.p2Cards[G.p2Sel]?.q;
  if(q2){G.curQ={...q2};document.getElementById('qText').textContent=G.curQ.display;showStatus('🔄 สลับโจทย์แล้ว!','sa')}
}
function applyBlur(){
  const el=document.getElementById('qText');const txt=el.textContent;
  const nums=txt.match(/\d+/g);if(!nums)return;
  const t=nums[Math.floor(Math.random()*nums.length)];let done=false;
  el.innerHTML=txt.replace(/\d+/g,m=>{if(!done&&m===t){done=true;return`<span class="blurn">${m}</span>`}return m});
}
function showHint(){
  const ca=Math.round(G.curQ.ans);const ws=new Set();
  while(ws.size<3){const o=Math.ceil(Math.random()*Math.max(5,Math.abs(ca)*.4));const c=ca+(Math.random()<.5?o:-o);if(c!==ca)ws.add(Math.round(c))}
  const ch=[ca,...ws].sort(()=>Math.random()-.5);
  document.getElementById('chGrid').innerHTML=ch.map(c=>`<button class="chbtn" onclick="pickHint(${c},${ca},this)">${c}</button>`).join('');
  document.getElementById('mcWrap').style.display='block';
}
function pickHint(v,ca,el){
  document.querySelectorAll('.chbtn').forEach(b=>b.disabled=true);
  el.classList.add(v===ca?'cor':'wrg');
  if(v!==ca)document.querySelectorAll('.chbtn').forEach(b=>{if(parseInt(b.textContent)===ca)b.classList.add('cor')});
  setTimeout(()=>{document.getElementById('p1Ans').value=v;document.getElementById('mcWrap').style.display='none'},900);
}

/* ============================================================
   UI RENDER
============================================================ */
function updateUI(){
  document.getElementById('p1Name').textContent=G.myName||'P1';
  document.getElementById('p2Name').textContent=G.opName||'P2';
  document.getElementById('p1HL').textContent=G.myName||'P1';
  document.getElementById('p2HL').textContent=G.opName||'P2';
  document.getElementById('p1AL').textContent=G.myName||'P1';
  document.getElementById('p2AL').textContent=G.opName||'P2';
  document.getElementById('p1AnsLbl').textContent=G.myName||'P1';
  document.getElementById('p2AnsLbl').textContent=G.opName||'P2';
  document.getElementById('roundDis').textContent=`รอบที่ ${G.round}`;
  renderHearts();renderHandCards();renderAbCards();setPhaseBadge();resetQDisplay();
}
function renderHearts(){
  ['p1','p2'].forEach(p=>{
    const hp=p==='p1'?G.p1HP:G.p2HP;
    document.getElementById(`${p}Hearts`).innerHTML=Array.from({length:5},(_,i)=>`<span class="heart${i>=hp?' empty':''}">❤️</span>`).join('');
  });
}
function renderHandCards(){
  ['p1','p2'].forEach(p=>{
    const cards=p==='p1'?G.p1Cards:G.p2Cards;
    const sel=p==='p1'?G.p1Sel:G.p2Sel;
    const el=document.getElementById(`${p}HCards`);
    const sec=document.getElementById(`${p}HSec`);
    if(G.phase!=='cardSelect'){sec.style.display='none';return}
    sec.style.display='';
    el.innerHTML=cards.map((c,i)=>`<div class="hcard${c.used?' used':''}${sel===i?' sel':''}" onclick="selCard('${p}',${i})"><span style="font-size:26px">🃏</span><div class="cnum">#${i+1}</div></div>`).join('');
  });
  checkConf();
}
function renderAbCards(){
  ['p1','p2'].forEach(p=>{
    const ab=p==='p1'?G.p1Ab:G.p2Ab;
    const um=p==='p1'?G.p1AbUsed:G.p2AbUsed;
    document.getElementById(`${p}AbCards`).innerHTML=ab.map(a=>`<div class="abcard${um[a.id]?' used':''}" onclick="useAbility('${p}','${a.id}')" title="${a.desc}"><div class="ai">${a.icon}</div><div class="an">${a.name}</div></div>`).join('');
  });
}
function setPhaseBadge(){
  const b=document.getElementById('phaseBadge'),d=document.getElementById('phaseDesc');
  if(G.phase==='cardSelect'){b.textContent='เลือกการ์ดโจทย์';d.textContent='แต่ละฝ่ายเลือก 1 ใบจากมือ (หน้าคว่ำ)';document.getElementById('ansSec').style.display='none';document.getElementById('mcWrap').style.display='none';document.getElementById('botArea').style.display='none'}
  else if(G.phase==='answer'){b.textContent='ตอบคำถาม!';d.textContent='ใครตอบถูกก่อน — ชนะรอบ!'}
  else{b.textContent='ผลการแข่ง';d.textContent=''}
}
function resetQDisplay(){
  document.getElementById('qCard').classList.remove('rev');
  document.getElementById('qText').innerHTML='<span class="qhid">? ? ?</span>';
  document.getElementById('ansSec').style.display='none';
  document.getElementById('mcWrap').style.display='none';
  document.getElementById('botArea').style.display='none';
  document.getElementById('p1HSec').style.display='';
  document.getElementById('p2HSec').style.display='';
}
function showRR(winner,c1,c2,extra){
  const p1=G.myName||'P1',p2=G.opName||'P2';
  let icon,title,sub;
  if(winner==='draw'){icon='🤝';title='เสมอ!';sub='ทั้งสองฝ่ายตอบไม่ถูก'}
  else if(winner==='p1'){icon='🏅';title=`${esc(p1)} ชนะ!`;sub=`ตอบถูกใน ${(G.p1Ms/1000).toFixed(2)}s`}
  else{icon=G.isBot?'🤖':'🏅';title=`${esc(p2)} ชนะ!`;sub=`ตอบถูกใน ${(G.p2Ms/1000).toFixed(2)}s`}
  document.getElementById('rIcon').textContent=icon;
  document.getElementById('rTitle').textContent=title;
  document.getElementById('rSub').textContent=sub;
  document.getElementById('rDet').innerHTML=`${extra?`<div>${extra}</div>`:''}<div style="margin-top:6px;font-size:12px">${esc(p1)}: ${c1?'✅ ถูก':'❌ ผิด'} | ${esc(p2)}: ${c2?'✅ ถูก':'❌ ผิด'}</div><div style="margin-top:4px;font-size:12px;color:var(--text2)">❤️ ${esc(p1)}: ${G.p1HP}HP | ${esc(p2)}: ${G.p2HP}HP</div>`;
  document.getElementById('rrOver').style.display='flex';
}

let _stTimer=null;
function showStatus(msg,cls='si'){
  const el=document.getElementById('statusArea');
  el.innerHTML=`<div class="smsg ${cls}">${msg}</div>`;
  clearTimeout(_stTimer);_stTimer=setTimeout(()=>{if(el)el.innerHTML=''},3200);
}
function esc(s){return String(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;')}
/* ============================================================
   SPACE BACKGROUND ENGINE — SPACESHIP VS ALIENS
============================================================ */
(function(){
  const canvas=document.getElementById('bgCanvas');
  if(!canvas)return;
  const ctx=canvas.getContext('2d');
  let W,H;
  const STARS=[],ALIENS=[],BULLETS=[],EXPLOSIONS=[];
  let ship={x:0,y:0,vx:0,vy:0,angle:0,targetX:0,targetY:0,trail:[]};
  let tick=0,lastFire=0,lastSpawn=0;

  function resize(){
    W=canvas.width=window.innerWidth;H=canvas.height=window.innerHeight;
    ship.x=W*.15;ship.y=H*.5;ship.targetX=W*.3;ship.targetY=H*.4;
    buildStars();
  }
  function buildStars(){
    STARS.length=0;
    for(let i=0;i<200;i++)STARS.push({x:Math.random()*W,y:Math.random()*H,
      r:.3+Math.random()*1.4,sp:.08+Math.random()*.5,op:.15+Math.random()*.75,
      col:Math.random()<.12?'#f59e0b':Math.random()<.08?'#c084fc':'#c8d8ff'});
  }
  function spawnAlien(){
    if(ALIENS.length>=7)return;
    const s=Math.random();
    const ax=s<.65?W+60:Math.random()*W;
    const ay=s<.65?Math.random()*H:s<.82?-60:H+60;
    ALIENS.push({x:ax,y:ay,vx:0,vy:0,hp:3,wobble:Math.random()*Math.PI*2,
      wobbleSpd:.03+Math.random()*.05,size:16+Math.random()*14,
      type:Math.random()<.5?0:1,col:Math.random()<.5?'#10b981':'#a855f7',
      gp:Math.random()*Math.PI*2});
  }
  function drawNebula(){
    [[W*.2,H*.25,300,'rgba(139,92,246,.035)'],[W*.75,H*.65,350,'rgba(59,130,246,.028)'],[W*.5,H*.4,450,'rgba(16,185,129,.015)']].forEach(([cx,cy,r,c])=>{
      const g=ctx.createRadialGradient(cx,cy,0,cx,cy,r);
      g.addColorStop(0,c);g.addColorStop(1,'transparent');
      ctx.fillStyle=g;ctx.beginPath();ctx.arc(cx,cy,r,0,Math.PI*2);ctx.fill();
    });
  }
  function drawStars(){
    STARS.forEach(s=>{
      s.x-=s.sp*.35;if(s.x<-2)s.x=W+2;
      ctx.globalAlpha=s.op*(.65+.35*Math.sin(tick*.9+s.x*.012));
      ctx.fillStyle=s.col;ctx.beginPath();ctx.arc(s.x,s.y,s.r,0,Math.PI*2);ctx.fill();
    });ctx.globalAlpha=1;
  }
  function drawShip(){
    const dx=ship.targetX-ship.x,dy=ship.targetY-ship.y;
    ship.vx=(ship.vx+dx*.02)*.91;ship.vy=(ship.vy+dy*.02)*.91;
    ship.x+=ship.vx;ship.y+=ship.vy;
    ship.angle=Math.atan2(ship.vy,ship.vx);
    ship.trail.push({x:ship.x,y:ship.y});
    if(ship.trail.length>32)ship.trail.shift();
    ship.trail.forEach((p,i)=>{
      const t=i/ship.trail.length;
      ctx.globalAlpha=t*.35;ctx.fillStyle=`hsl(${195+t*35},80%,65%)`;
      ctx.beginPath();ctx.arc(p.x,p.y,2.5*t,0,Math.PI*2);ctx.fill();
    });ctx.globalAlpha=1;
    ctx.save();ctx.translate(ship.x,ship.y);ctx.rotate(ship.angle);
    // engine glow
    const eg=ctx.createRadialGradient(-20,0,0,-20,0,20);
    eg.addColorStop(0,'rgba(80,200,255,.65)');eg.addColorStop(1,'transparent');
    ctx.fillStyle=eg;ctx.beginPath();ctx.arc(-20,0,20,0,Math.PI*2);ctx.fill();
    // flame
    const fl=5+Math.sin(tick*14)*3;
    ctx.fillStyle='rgba(255,150,30,.85)';
    ctx.beginPath();ctx.moveTo(-14,0);ctx.lineTo(-14-fl,-4.5);ctx.lineTo(-14-fl*1.7,0);ctx.lineTo(-14-fl,4.5);ctx.closePath();ctx.fill();
    ctx.fillStyle='rgba(255,220,80,.6)';
    ctx.beginPath();ctx.moveTo(-14,0);ctx.lineTo(-14-fl*.6,-2);ctx.lineTo(-14-fl*.9,0);ctx.lineTo(-14-fl*.6,2);ctx.closePath();ctx.fill();
    // body
    ctx.fillStyle='#d0e8ff';
    ctx.beginPath();ctx.moveTo(22,0);ctx.lineTo(-9,9);ctx.lineTo(-14,5);ctx.lineTo(-12,0);ctx.lineTo(-14,-5);ctx.lineTo(-9,-9);ctx.closePath();ctx.fill();
    // wings
    ctx.fillStyle='#88b4e0';
    ctx.beginPath();ctx.moveTo(-3,0);ctx.lineTo(-11,17);ctx.lineTo(-15,11);ctx.lineTo(-7,0);ctx.closePath();ctx.fill();
    ctx.beginPath();ctx.moveTo(-3,0);ctx.lineTo(-11,-17);ctx.lineTo(-15,-11);ctx.lineTo(-7,0);ctx.closePath();ctx.fill();
    // cockpit
    ctx.fillStyle='rgba(140,220,255,.9)';ctx.beginPath();ctx.ellipse(9,0,7,4.5,0,0,Math.PI*2);ctx.fill();
    // cannon
    ctx.fillStyle='#f59e0b';ctx.fillRect(20,-1.5,10,3);
    ctx.restore();
  }
  function drawAlien(a){
    a.wobble+=a.wobbleSpd;a.gp+=.055;
    const glow=.55+.45*Math.sin(a.gp);
    ctx.save();ctx.translate(a.x,a.y+Math.sin(a.wobble)*5.5);
    if(a.type===0){
      // saucer
      const sg=ctx.createRadialGradient(0,0,0,0,0,a.size*1.3);
      sg.addColorStop(0,a.col+'66');sg.addColorStop(1,'transparent');
      ctx.globalAlpha=glow*.45;ctx.fillStyle=sg;ctx.beginPath();ctx.arc(0,0,a.size*1.3,0,Math.PI*2);ctx.fill();ctx.globalAlpha=1;
      ctx.fillStyle=a.col;ctx.beginPath();ctx.ellipse(0,3,a.size,a.size*.38,0,0,Math.PI*2);ctx.fill();
      ctx.fillStyle=a.col+'cc';ctx.beginPath();ctx.ellipse(0,-1,a.size*.5,a.size*.48,0,0,Math.PI*2);ctx.fill();
      [-a.size*.55,-a.size*.18,a.size*.18,a.size*.55].forEach((lx,i)=>{
        ctx.globalAlpha=.7+.3*Math.sin(tick*5+i*1.2);
        ctx.fillStyle=i%2===0?'#fbbf24':'#34d399';
        ctx.beginPath();ctx.arc(lx,3.5,2.5,0,Math.PI*2);ctx.fill();
      });ctx.globalAlpha=1;
    } else {
      // jellyfish alien
      ctx.globalAlpha=.88;ctx.fillStyle=a.col;
      ctx.beginPath();ctx.arc(0,-3,a.size*.58,Math.PI,0);ctx.closePath();ctx.fill();
      ctx.globalAlpha=.55;ctx.lineWidth=1.8;ctx.strokeStyle=a.col;
      for(let t=0;t<5;t++){
        const tx=-a.size*.38+t*a.size*.19,tl=a.size*.45+Math.sin(a.wobble+t*1.3)*5;
        ctx.beginPath();ctx.moveTo(tx,0);ctx.quadraticCurveTo(tx+3.5,tl*.5,tx,tl);ctx.stroke();
      }
      ctx.globalAlpha=.85;ctx.fillStyle='#fff';
      ctx.beginPath();ctx.arc(-5.5,-5,3.5,0,Math.PI*2);ctx.fill();
      ctx.beginPath();ctx.arc(5.5,-5,3.5,0,Math.PI*2);ctx.fill();
      ctx.fillStyle='#1e1b4b';
      ctx.beginPath();ctx.arc(-4.5,-4,1.8,0,Math.PI*2);ctx.fill();
      ctx.beginPath();ctx.arc(6.5,-4,1.8,0,Math.PI*2);ctx.fill();
      ctx.globalAlpha=1;
    }
    // hp bar
    if(a.hp<3){
      ctx.fillStyle='rgba(0,0,0,.5)';ctx.fillRect(-a.size,-a.size-6,a.size*2,4);
      ctx.fillStyle=a.hp>1?'#10b981':'#ef4444';
      ctx.fillRect(-a.size,-a.size-6,a.size*2*(a.hp/3),4);
    }
    ctx.restore();
  }
  function drawBullet(b){
    ctx.save();ctx.translate(b.x,b.y);
    const g=ctx.createRadialGradient(0,0,0,0,0,7);
    g.addColorStop(0,'rgba(255,230,80,1)');g.addColorStop(1,'transparent');
    ctx.fillStyle=g;ctx.beginPath();ctx.arc(0,0,7,0,Math.PI*2);ctx.fill();
    ctx.fillStyle='#fff';ctx.beginPath();ctx.arc(0,0,2.5,0,Math.PI*2);ctx.fill();
    ctx.restore();
  }
  function drawExplosion(e){
    e.particles.forEach(p=>{
      p.x+=p.vx;p.y+=p.vy;p.life-=.028;p.vx*=.95;p.vy*=.95;
      if(p.life<=0)return;
      ctx.globalAlpha=p.life*.9;ctx.fillStyle=p.col;
      ctx.beginPath();ctx.arc(p.x,p.y,p.r*p.life,0,Math.PI*2);ctx.fill();
    });ctx.globalAlpha=1;e.life-=.022;
  }
  function explode(x,y,col){
    const ps=[];
    for(let i=0;i<22;i++){
      const a=Math.random()*Math.PI*2,sp=1.5+Math.random()*6;
      ps.push({x,y,vx:Math.cos(a)*sp,vy:Math.sin(a)*sp,
        col:Math.random()<.5?col:Math.random()<.5?'#f59e0b':'#fff',
        r:2.5+Math.random()*4.5,life:1});
    }
    EXPLOSIONS.push({particles:ps,life:1});
  }

  function loop(){
    tick+=.016;
    ctx.clearRect(0,0,W,H);
    const bg=ctx.createRadialGradient(W*.4,H*.35,0,W*.4,H*.35,Math.max(W,H));
    bg.addColorStop(0,'rgba(14,8,32,1)');bg.addColorStop(.5,'rgba(6,12,28,1)');bg.addColorStop(1,'rgba(2,4,14,1)');
    ctx.fillStyle=bg;ctx.fillRect(0,0,W,H);
    drawNebula();drawStars();

    if(tick-lastSpawn>2.2+Math.random()*2.5){lastSpawn=tick;spawnAlien();}

    ALIENS.forEach(a=>{
      const dx=ship.x-a.x,dy=ship.y-a.y,d=Math.sqrt(dx*dx+dy*dy)||1;
      a.vx=(a.vx+dx/d*.055)*.96;a.vy=(a.vy+dy/d*.055)*.96;
      a.x+=a.vx;a.y+=a.vy;
    });

    // auto-fire at nearest alien
    if(tick-lastFire>1.2&&ALIENS.length){
      let best=null,bd=9999;
      ALIENS.forEach(a=>{const d=Math.hypot(a.x-ship.x,a.y-ship.y);if(d<bd){bd=d;best=a;}});
      if(best&&bd<600){
        const dx=best.x-ship.x,dy=best.y-ship.y,d=Math.sqrt(dx*dx+dy*dy)||1;
        BULLETS.push({x:ship.x+Math.cos(ship.angle)*26,y:ship.y+Math.sin(ship.angle)*26,
          vx:dx/d*9.5+ship.vx*.25,vy:dy/d*9.5+ship.vy*.25,life:1});
        lastFire=tick;
      }
    }

    ship.targetX=W*.5+Math.cos(tick*.17)*W*.3;
    ship.targetY=H*.5+Math.sin(tick*.26)*H*.28;

    for(let i=BULLETS.length-1;i>=0;i--){
      const b=BULLETS[i];b.x+=b.vx;b.y+=b.vy;b.life-=.016;
      if(b.life<=0||b.x<0||b.x>W||b.y<0||b.y>H){BULLETS.splice(i,1);continue;}
      let hit=false;
      for(let j=ALIENS.length-1;j>=0;j--){
        const a=ALIENS[j];
        if(Math.hypot(b.x-a.x,b.y-a.y)<a.size*.9){
          a.hp--;BULLETS.splice(i,1);hit=true;
          if(a.hp<=0){explode(a.x,a.y,a.col);ALIENS.splice(j,1);}
          break;
        }
      }
      if(!hit)drawBullet(b);
    }
    ALIENS.forEach(a=>drawAlien(a));
    drawShip();
    for(let i=EXPLOSIONS.length-1;i>=0;i--){
      drawExplosion(EXPLOSIONS[i]);
      if(EXPLOSIONS[i].life<=0)EXPLOSIONS.splice(i,1);
    }
    requestAnimationFrame(loop);
  }

  window.addEventListener('resize',resize);resize();
  for(let i=0;i<3;i++)spawnAlien();
  loop();

  const syms=['∑','∫','π','∞','√','±','×','÷','=','²','³','Δ','∇','∈','≠'];
  const wrap=document.getElementById('floatSymWrap');
  function spawnSym(){
    const el=document.createElement('div');el.className='float-sym';
    const sz=13+Math.random()*26;
    el.style.cssText=`left:${Math.random()*100}vw;bottom:-50px;font-size:${sz}px;animation-duration:${12+Math.random()*18}s;opacity:0`;
    el.textContent=syms[Math.floor(Math.random()*syms.length)];
    wrap.appendChild(el);setTimeout(()=>el.remove(),35000);
  }
  setInterval(spawnSym,900);for(let i=0;i<8;i++)setTimeout(spawnSym,i*350);
})();

</script>
</body>
</html>
