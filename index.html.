<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Cờ Vua Âm Thanh</title>
<style>
:root{--bg:#111319;--panel:#1b1f29;--panel2:#242a36;--text:#f4f5f7;--muted:#aeb5c3;--gold:#e5b85c;--green:#79bd8c;--light:#eee7d5;--dark:#72916e}
*{box-sizing:border-box}body{margin:0;background:radial-gradient(circle at top,#242a38,#101217 65%);color:var(--text);font-family:system-ui,-apple-system,Segoe UI,sans-serif;min-height:100vh}
button,select{font:inherit}button{cursor:pointer;border:0;border-radius:12px;padding:12px 15px;font-weight:750;transition:transform .12s,filter .12s}button:active{transform:scale(.98)}.primary{background:var(--gold);color:#171717}.secondary{background:#303747;color:#fff;border:1px solid #444c5d}.muted{color:var(--muted)}
.wrap{max-width:980px;margin:auto;padding:18px 14px 30px}.top{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-bottom:18px}.brand{display:flex;align-items:center;gap:10px;font-size:clamp(20px,4vw,28px);font-weight:900;letter-spacing:.3px}.logo{display:grid;place-items:center;width:42px;height:42px;border-radius:12px;background:var(--gold);color:#171717;font-size:27px}.elo-pill{background:var(--panel);border:1px solid #343a49;padding:9px 13px;border-radius:999px;font-weight:800;white-space:nowrap}
.panel{background:linear-gradient(145deg,#202531,#191d26);border:1px solid #343a49;border-radius:20px;padding:clamp(16px,4vw,28px);box-shadow:0 16px 40px #0003}.home{max-width:620px;margin:28px auto}.eyebrow{color:var(--gold);font-weight:800;font-size:12px;letter-spacing:2px;text-transform:uppercase}.home h1{font-size:clamp(30px,7vw,48px);line-height:1.06;margin:10px 0}.home p{color:var(--muted);line-height:1.6}.choice-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin:20px 0}.choice{min-height:100px;background:#292f3c;border:1px solid #454d5e;color:#fff;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:8px}.choice .piece{font-size:34px;line-height:1}.choice.active{border:2px solid var(--gold);background:#3a3427;box-shadow:0 0 0 2px #e5b85c22}.time-title{font-weight:800;margin:20px 0 10px}.time-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:8px}.time-btn{background:#292f3c;border:1px solid #454d5e;color:#fff;padding:12px 4px}.time-btn.active{background:var(--gold);color:#171717;border-color:var(--gold)}.start{width:100%;margin-top:22px;padding:16px;font-size:17px}.note{font-size:12px;color:var(--muted);text-align:center;margin-top:14px}
.game{display:none}.game-layout{display:grid;grid-template-columns:minmax(0,1.25fr) minmax(240px,.75fr);gap:18px;align-items:start}.board-shell{width:100%;max-width:600px;margin:auto;border:7px solid #34303a;border-radius:10px;overflow:hidden;box-shadow:0 15px 30px #0005}.board{display:grid;grid-template-columns:repeat(8,1fr);aspect-ratio:1}.sq{position:relative;display:grid;place-items:center;aspect-ratio:1;border-radius:0;padding:0;color:#171717;min-width:0;min-height:0}.sq.light{background:var(--light)}.sq.dark{background:var(--dark)}.sq.selected{box-shadow:inset 0 0 0 5px #e5b85c}.sq.last{background-image:linear-gradient(#f2d45b66,#f2d45b66)}.sq.legal:after{content:"";width:24%;height:24%;border-radius:50%;background:#17201655;position:absolute}.sq.legal.has-piece:after{width:78%;height:78%;background:transparent;border:5px solid #17201655}.piece{font-family:"DejaVu Sans", "Noto Sans Symbols 2",serif;font-size:clamp(28px,7.5vw,62px);line-height:1;z-index:1;user-select:none}.sq.white-piece .piece{color:#fff;text-shadow:-1px -1px 1px #282828,1px -1px 1px #282828,-1px 1px 1px #282828,2px 3px 2px #0008}.sq.black-piece .piece{color:#222;text-shadow:0 1px 1px #fff5}.coords{position:absolute;font-size:9px;bottom:2px;left:3px;opacity:.7;font-weight:800;z-index:2}.sq.dark .coords{color:#fff}.sq.light .coords{color:#333}
.side{display:flex;flex-direction:column;gap:12px}.player{display:flex;justify-content:space-between;align-items:center;background:var(--panel);border:1px solid #343a49;padding:13px 14px;border-radius:14px;gap:8px}.player.active{border-color:var(--gold);box-shadow:0 0 0 1px #e5b85c33}.player-name{font-weight:800}.clock{font-size:clamp(23px,5vw,31px);font-variant-numeric:tabular-nums;font-weight:900;letter-spacing:1px}.clock.low{color:#ff7b70}.status{padding:13px;border-radius:12px;background:#2a303d;color:#e6e8ee;font-weight:700;min-height:48px}.actions{display:grid;grid-template-columns:1fr 1fr;gap:8px}.actions button{padding:11px 8px}.side h3{margin:4px 0 0;font-size:15px}.moves{background:#151820;border:1px solid #343a49;border-radius:12px;padding:10px;min-height:90px;max-height:190px;overflow:auto;font-family:ui-monospace,monospace;color:#cbd2df;font-size:13px;line-height:1.8}.footer-note{font-size:11px;color:var(--muted);line-height:1.5}.overlay{display:none;position:fixed;inset:0;background:#050609bb;z-index:5;align-items:center;justify-content:center;padding:20px}.modal{width:min(400px,100%);background:#202531;border:1px solid #454d5e;border-radius:20px;padding:22px;text-align:center;box-shadow:0 20px 70px #0009}.modal h2{margin-top:0}.promo-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:8px}.promo-grid button{font-size:35px;padding:14px 4px;background:#303747;color:white;border:1px solid #4b5365}.modal-actions{display:flex;gap:8px;margin-top:16px}.modal-actions button{flex:1}.hidden{display:none!important}
@media(max-width:760px){.game-layout{grid-template-columns:1fr}.board-shell{max-width:560px}.side{display:grid;grid-template-columns:1fr 1fr}.side .player,.side .status,.side .actions,.side h3,.side .moves,.side .footer-note{grid-column:1/-1}.side .player{padding:10px 12px}.moves{max-height:120px}.wrap{padding:12px}.game-layout{gap:12px}}
@media(max-width:390px){.choice-grid{gap:6px}.choice{padding:8px 3px;font-size:13px}.time-grid{gap:5px}.time-btn{font-size:13px}.piece{font-size:clamp(25px,8vw,38px)}.sq{overflow:hidden}}
</style>
</head>
<body>
<div class="wrap">
<header class="top"><div class="brand"><div class="logo">♞</div><span>CỜ VUA <span style="color:var(--gold)">ARENA</span></span></div><div class="elo-pill">♜ Elo <span id="eloTop">1200</span></div></header>
<main id="home" class="panel home">
<div class="eyebrow">Chess • Think • Win</div><h1>Đến lượt bạn<br>làm chủ bàn cờ.</h1><p>Chọn màu quân, đặt thời gian và bắt đầu một ván cờ. Âm thanh có thể bật/tắt trong khi chơi.</p>
<div class="time-title">Bạn muốn chơi quân nào?</div>
<div class="choice-grid">
<button class="choice active" data-color="random"><span class="piece">♔♚</span><span>Ngẫu nhiên</span></button>
<button class="choice" data-color="white"><span class="piece">♔</span><span>Quân Trắng</span></button>
<button class="choice" data-color="black"><span class="piece">♚</span><span>Quân Đen</span></button>
</div>
<div class="time-title">Thời gian mỗi bên</div>
<div class="time-grid">
<button class="time-btn" data-min="15">15 phút</button><button class="time-btn active" data-min="20">20 phút</button><button class="time-btn" data-min="25">25 phút</button><button class="time-btn" data-min="30">30 phút</button>
</div>
<button id="startBtn" class="primary start">♟　BẮT ĐẦU CHƠI</button>
<div class="note">Chơi một mình với máy • Elo được lưu trên thiết bị này</div>
</main>
<section id="game" class="game">
<div class="game-layout">
<div>
<div id="topPlayer" class="player"><div><div class="player-name">Quân Đen</div><div class="muted" style="font-size:12px">Đối thủ</div></div><div class="clock" id="blackClock">20:00</div></div>
<div class="board-shell"><div id="board" class="board" aria-label="Bàn cờ vua"></div></div>
<div id="bottomPlayer" class="player"><div><div class="player-name">Quân Trắng</div><div class="muted" style="font-size:12px">Người chơi</div></div><div class="clock" id="whiteClock">20:00</div></div>
</div>
<aside class="side">
<div class="status" id="status">Trắng đi trước.</div>
<div class="actions"><button id="undoBtn" class="secondary">↶ Đi lại</button><button id="soundBtn" class="secondary">🔊 Âm thanh: Bật</button><button id="newBtn" class="secondary">＋ Ván mới</button><button id="homeBtn" class="secondary">⌂ Màn hình chính</button></div>
<h3>Lịch sử nước đi</h3><div class="moves" id="moves">Chưa có nước đi.</div>
<div class="footer-note">Elo cập nhật theo kết quả ván chơi trên thiết bị này. Nước đi hợp lệ và phong cấp được kiểm tra bằng thư viện cờ vua.</div>
</aside>
</div>
</section>
</div>
<div class="overlay" id="promotionOverlay"><div class="modal"><h2>Phong cấp tốt</h2><p class="muted">Chọn quân bạn muốn đổi thành</p><div class="promo-grid"><button data-promo="q" aria-label="Hậu">♛</button><button data-promo="r" aria-label="Xe">♜</button><button data-promo="n" aria-label="Mã">♞</button><button data-promo="b" aria-label="Tượng">♝</button></div><p>Hậu · Xe · Mã · Tượng</p></div></div>
<div class="overlay" id="resultOverlay"><div class="modal"><div style="font-size:42px">♔</div><h2 id="resultTitle">Kết thúc ván</h2><p id="resultText" class="muted"></p><div class="modal-actions"><button id="againBtn" class="primary">Chơi lại</button><button id="resultHomeBtn" class="secondary">Màn hình chính</button></div></div></div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/chess.js/0.10.3/chess.min.js"></script>
<script>
(() => {
const $=id=>document.getElementById(id);
let selectedColor='random', minutes=20, game=null, selected=null, legal=[], lastMove=null, soundOn=true, audioCtx=null, timer=null, remaining={w:1200,b:1200}, activeClock='w', pendingPromotion=null, started=false, history=[], humanColor='w', aiBusy=false;
let elo=Number(localStorage.getItem('chessArenaElo')||1200); $('eloTop').textContent=elo;
const unicode={wk:'♔',wq:'♕',wr:'♖',wb:'♗',wn:'♘',wp:'♙',bk:'♚',bq:'♛',br:'♜',bb:'♝',bn:'♞',bp:'♟'};
function audio(type='move'){
 if(!soundOn)return;
 try{audioCtx=audioCtx||new (window.AudioContext||window.webkitAudioContext)(); if(audioCtx.state==='suspended')audioCtx.resume();
 const now=audioCtx.currentTime, osc=audioCtx.createOscillator(), gain=audioCtx.createGain();
 const presets={move:[520,.07,'sine'],capture:[240,.12,'triangle'],check:[760,.15,'sine'],end:[330,.28,'triangle'],start:[640,.08,'sine']};
 const [freq,dur,wave]=presets[type]||presets.move;osc.type=wave;osc.frequency.setValueAtTime(freq,now);if(type==='capture')osc.frequency.exponentialRampToValueAtTime(130,now+dur);
 gain.gain.setValueAtTime(.0001,now);gain.gain.exponentialRampToValueAtTime(.12,now+.012);gain.gain.exponentialRampToValueAtTime(.0001,now+dur);
 osc.connect(gain);gain.connect(audioCtx.destination);osc.start(now);osc.stop(now+dur+.02);
 }catch(e){}
}
document.querySelectorAll('[data-color]').forEach(b=>b.addEventListener('click',()=>{selectedColor=b.dataset.color;document.querySelectorAll('[data-color]').forEach(x=>x.classList.toggle('active',x===b));}));
document.querySelectorAll('[data-min]').forEach(b=>b.addEventListener('click',()=>{minutes=Number(b.dataset.min);document.querySelectorAll('[data-min]').forEach(x=>x.classList.toggle('active',x===b));}));
function showHome(){stopTimer();$('game').style.display='none';$('home').style.display='block';$('promotionOverlay').style.display='none';$('resultOverlay').style.display='none';}
function startGame(){
 if(typeof Chess==='undefined'){alert('Không tải được bộ luật cờ vua. Hãy kiểm tra Internet rồi mở lại game.');return;}
 stopTimer();game=new Chess();selected=null;legal=[];lastMove=null;pendingPromotion=null;started=true;history=[];remaining={w:minutes*60,b:minutes*60};activeClock='w';
 let user=selectedColor==='random'?(Math.random()<.5?'w':'b'):selectedColor==='white'?'w':'b';humanColor=user;aiBusy=false;
 $('topPlayer').querySelector('.player-name').textContent='Quân '+(user==='w'?'Đen':'Trắng');
 $('topPlayer').querySelector('.muted').textContent='Người chơi '+(user==='w'?'đối diện':'đối diện');
 $('bottomPlayer').querySelector('.player-name').textContent='Quân '+(user==='w'?'Trắng':'Đen');
 $('bottomPlayer').querySelector('.muted').textContent='Người chơi';
 // User color shown at bottom; board rotates for black user
 $('board').dataset.orientation=user==='w'?'white':'black';
 $('home').style.display='none';$('game').style.display='block';$('resultOverlay').style.display='none';
 $('status').textContent='Bạn chơi quân '+(humanColor==='w'?'Trắng':'Đen')+'. Máy chơi quân '+(humanColor==='w'?'Đen':'Trắng')+'.';render();updateClocks();updatePlayers();$('moves').textContent='Chưa có nước đi.';audio('start');startTimer();if(game.turn()!==humanColor)maybeAIMove();
}
function stopTimer(){if(timer){clearInterval(timer);timer=null;}}
function startTimer(){stopTimer();timer=setInterval(()=>{if(!started||!game||game.game_over())return;remaining[activeClock]--;updateClocks();if(remaining[activeClock]<=0){remaining[activeClock]=0;updateClocks();started=false;stopTimer();finish(activeClock==='w'?'b':'w','hết giờ');}},1000);}
function fmt(n){return String(Math.floor(n/60)).padStart(2,'0')+':'+String(n%60).padStart(2,'0');}
function updateClocks(){ $('whiteClock').textContent=fmt(remaining.w);$('blackClock').textContent=fmt(remaining.b);$('whiteClock').classList.toggle('low',remaining.w<=30);$('blackClock').classList.toggle('low',remaining.b<=30);}
function updatePlayers(){let turn=game.turn();$('topPlayer').classList.toggle('active',turn===($('board').dataset.orientation==='white'?'b':'w'));$('bottomPlayer').classList.toggle('active',turn===($('board').dataset.orientation==='white'?'w':'b'));$('topPlayer').querySelector('.muted').textContent=(($('board').dataset.orientation==='white'?'b':'w')===humanColor)?'Bạn':'Máy';$('bottomPlayer').querySelector('.muted').textContent=(($('board').dataset.orientation==='white'?'w':'b')===humanColor)?'Bạn':'Máy';}
function render(){
 const board=$('board');board.innerHTML='';const orient=board.dataset.orientation||'white';const arr=game.board();
 for(let ri=0;ri<8;ri++){for(let ci=0;ci<8;ci++){
 let r=orient==='white'?ri:7-ri,c=orient==='white'?ci:7-ci,sq=String.fromCharCode(97+c)+(8-r),p=arr[r][c];
 const el=document.createElement('button');el.className='sq '+((r+c)%2===0?'light':'dark');el.dataset.sq=sq;el.setAttribute('aria-label',sq);
 if(selected===sq)el.classList.add('selected');if(lastMove&&(lastMove.from===sq||lastMove.to===sq))el.classList.add('last');if(legal.includes(sq))el.classList.add('legal');if(p)el.classList.add('has-piece',p.color==='w'?'white-piece':'black-piece');
 if(p){const sp=document.createElement('span');sp.className='piece';sp.textContent=unicode[p.color+p.type];el.appendChild(sp);}
 if(ci===0){const co=document.createElement('span');co.className='coords';co.textContent=8-r;el.appendChild(co);}if(ri===7){const co=document.createElement('span');co.className='coords';co.style.left='auto';co.style.right='3px';co.style.bottom='auto';co.style.top='2px';co.textContent=String.fromCharCode(97+c);el.appendChild(co);}
 el.addEventListener('click',()=>clickSquare(sq));board.appendChild(el);
 }}updatePlayers();
}
function clickSquare(sq){
 if(!started||!game||game.game_over()||pendingPromotion||aiBusy||game.turn()!==humanColor)return;
 const piece=game.get(sq);
 if(selected&&legal.includes(sq)){
  const moving=game.get(selected);
  if(moving&&moving.type==='p'&&(sq[1]==='8'||sq[1]==='1')){pendingPromotion={from:selected,to:sq};$('promotionOverlay').style.display='flex';return;}
  doMove(selected,sq);return;
 }
 if(piece&&piece.color===game.turn()){selected=sq;legal=game.moves({square:sq,verbose:true}).map(m=>m.to);render();}
 else{selected=null;legal=[];render();}
}
function doMove(from,to,promotion='q'){
 const before=game.fen();const result=game.move({from,to,promotion});if(!result)return;
 history.push({before,remaining:{...remaining},lastMove:{...lastMove}});
 lastMove={from:result.from,to:result.to};selected=null;legal=[];activeClock=game.turn();
 $('moves').innerHTML='';const hist=game.history();if(!hist.length)$('moves').textContent='Chưa có nước đi.';else{for(let i=0;i<hist.length;i+=2){const line=document.createElement('div');line.textContent=(Math.floor(i/2)+1)+'. '+hist[i]+(hist[i+1]?'　'+hist[i+1]:'');$('moves').appendChild(line);}$('moves').scrollTop=$('moves').scrollHeight;}
 audio(result.flags.includes('c')||result.flags.includes('e')?'capture':'move');
 if(game.in_checkmate()){render();audio('end');finish(game.turn()==='w'?'b':'w','chiếu hết');return;}
 if(game.in_draw()){render();finish(null,game.in_stalemate()?'hòa do hết nước đi':'ván hòa');return;}
 if(game.in_check()){ $('status').textContent='⚠ Chiếu vua! '+(game.turn()==='w'?'Trắng':'Đen')+' cần bảo vệ vua.';audio('check');}
 else $('status').textContent=(game.turn()==='w'?'Trắng':'Đen')+' đi.';
 render();
 if(started && !game.game_over()) maybeAIMove();
}
const VALUES={p:100,n:320,b:330,r:500,q:900,k:20000};
function evalBoard(g){if(g.in_checkmate())return g.turn()==='w'?-100000:100000;if(g.in_draw())return 0;let score=0,b=g.board();for(let r=0;r<8;r++)for(let c=0;c<8;c++){let p=b[r][c];if(!p)continue;let v=VALUES[p.type],center=3.5-(Math.abs(3.5-r)+Math.abs(3.5-c))/2;if(p.type==='p')v+=(p.color==='w'?(6-r):(r-1))*7;if(['n','b'].includes(p.type))v+=center*8;score+=(p.color==='w'?v:-v);}return score;}
function minimax(g,depth,alpha,beta,maximizing){if(depth===0||g.game_over())return evalBoard(g);let moves=g.moves({verbose:true});moves.sort((a,b)=>((b.captured?VALUES[b.captured]:0)+(b.promotion?800:0))-((a.captured?VALUES[a.captured]:0)+(a.promotion?800:0)));if(maximizing){let best=-Infinity;for(const m of moves){g.move({from:m.from,to:m.to,promotion:m.promotion||'q'});let v=minimax(g,depth-1,alpha,beta,false);g.undo();best=Math.max(best,v);alpha=Math.max(alpha,best);if(beta<=alpha)break;}return best;}let best=Infinity;for(const m of moves){g.move({from:m.from,to:m.to,promotion:m.promotion||'q'});let v=minimax(g,depth-1,alpha,beta,true);g.undo();best=Math.min(best,v);beta=Math.min(beta,best);if(beta<=alpha)break;}return best;}
function maybeAIMove(){if(!started||!game||game.game_over()||game.turn()===humanColor||aiBusy)return;aiBusy=true;$('status').textContent='Máy đang suy nghĩ…';setTimeout(()=>{if(!started||!game||game.game_over()){aiBusy=false;return;}const moves=game.moves({verbose:true});if(!moves.length){aiBusy=false;return;}let bestMove=null,bestScore=game.turn()==='w'?-Infinity:Infinity;const maximizing=game.turn()==='w';for(const m of moves){game.move({from:m.from,to:m.to,promotion:m.promotion||'q'});const score=minimax(game,2,-Infinity,Infinity,!maximizing);game.undo();if((maximizing&&score>bestScore)||(!maximizing&&score<bestScore)){bestScore=score;bestMove=m;}}aiBusy=false;if(bestMove)doMove(bestMove.from,bestMove.to,bestMove.promotion||'q');},350);}
document.querySelectorAll('[data-promo]').forEach(b=>b.addEventListener('click',()=>{if(!pendingPromotion)return;const p=pendingPromotion;pendingPromotion=null;$('promotionOverlay').style.display='none';doMove(p.from,p.to,b.dataset.promo);}));
function finish(winner,reason){
 started=false;stopTimer();audio('end');let text='';
 if(winner){text=(winner==='w'?'Quân Trắng':'Quân Đen')+' thắng ('+reason+').';const userColor=humanColor;let score=winner===userColor?1:0;let expected=1/(1+Math.pow(10,(1200-elo)/400));elo=Math.max(100,Math.round(elo+24*(score-expected)));localStorage.setItem('chessArenaElo',elo);$('eloTop').textContent=elo;}
 else text='Kết quả: '+reason+'. Elo không thay đổi.';
 $('status').textContent=text;$('resultTitle').textContent=winner?(winner===humanColor?'Bạn đã thắng!':'Máy đã thắng'): 'Ván hòa';$('resultText').textContent=text+' Elo hiện tại: '+elo+'.';$('resultOverlay').style.display='flex';
}
$('startBtn').addEventListener('click',startGame);$('newBtn').addEventListener('click',startGame);$('homeBtn').addEventListener('click',showHome);$('resultHomeBtn').addEventListener('click',showHome);$('againBtn').addEventListener('click',startGame);
$('soundBtn').addEventListener('click',()=>{soundOn=!soundOn;$('soundBtn').textContent=soundOn?'🔊 Âm thanh: Bật':'🔇 Âm thanh: Tắt';if(soundOn)audio('move');});
$('undoBtn').addEventListener('click',()=>{if(!game||!history.length||!started||aiBusy)return;const h=history.pop();game.load(h.before);remaining=h.remaining;lastMove=h.lastMove;selected=null;legal=[];activeClock=game.turn();$('status').textContent='Đã đi lại một nước.';render();updateClocks();const hist=game.history();$('moves').innerHTML='';if(!hist.length)$('moves').textContent='Chưa có nước đi.';else for(let i=0;i<hist.length;i+=2){const line=document.createElement('div');line.textContent=(Math.floor(i/2)+1)+'. '+hist[i]+(hist[i+1]?'　'+hist[i+1]:'');$('moves').appendChild(line);}});
document.addEventListener('visibilitychange',()=>{if(document.hidden&&started){/* timer continues while tab is backgrounded where supported */}});
})();
</script>
</body>
</html>
