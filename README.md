<!doctype html>
<html lang="vi">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Chúc mừng sinh nhật Vân Anh 18/10/2025</title>
<meta name="description" content="Chúc mừng sinh nhật Vân Anh - Emiu của anh :))))">
<style>
:root{
  --pink-100:#fff0f5;--pink-200:#ffd6e9;--pink-300:#ffb3d9;
  --pink-400:#ff8ec4;--pink-500:#ff5da2;--text-dark:#64293b;
  --white-80:rgba(255,255,255,0.8);--glass-border:rgba(255,255,255,0.55);
}
*{box-sizing:border-box;margin:0;padding:0}
html,body{height:100%}
body{
  font-family:'Poppins',sans-serif;
  background:linear-gradient(180deg,#fff5f9 0%,#ffe4ef 40%,#ffd1e4 100%);
  display:flex;align-items:center;justify-content:center;overflow:hidden;
  color:var(--text-dark);padding:20px;
}

/* ===== CARD ===== */
.card{
  position:relative;z-index:2;
  width:100%;max-width:960px;
  border-radius:28px;
  background:rgba(255,255,255,0.6);
  border:1px solid var(--glass-border);
  box-shadow:0 8px 28px rgba(255,105,180,0.15);
  backdrop-filter:blur(10px) saturate(120%);
  padding:36px;
}
.grid{display:grid;grid-template-columns:1fr;gap:20px;align-items:center}
@media(min-width:860px){.grid{grid-template-columns:360px 1fr}}

/* ===== BUTTON ===== */
.btn-heart{
  width:180px;height:180px;border-radius:50%;
  background:radial-gradient(circle at 30% 30%,#ff7aa6,#ff4d8a 70%,#ff2d6f 100%);
  box-shadow:0 0 35px rgba(255,77,138,0.45);
  border:none;cursor:pointer;position:relative;
  display:flex;align-items:center;justify-content:center;
  transition:transform 0.2s ease;
}
.btn-heart:hover{transform:scale(1.05)}
.btn-heart:active{transform:scale(0.95)}
.btn-heart::before{
  content:"";position:absolute;inset:-10px;
  border-radius:50%;background:radial-gradient(circle,#ff9ec2 0%,transparent 70%);
  opacity:.6;animation:pulse 2s infinite ease-in-out;
}
@keyframes pulse{0%,100%{transform:scale(1);opacity:.6}50%{transform:scale(1.15);opacity:.9}}
.btn-heart .emoji{font-size:58px;position:relative;z-index:2;animation:bounce 1.6s infinite ease-in-out}
@keyframes bounce{0%,100%{transform:translateY(0)}50%{transform:translateY(-6px)}}
.small-note{text-align:center;margin-top:10px;font-weight:600;color:#a33b5e}

/* ===== MESSAGE ===== */
.message{
  padding:20px;border-radius:16px;
  background:rgba(255,255,255,0.7);
  border:1px solid rgba(255,255,255,0.6);
  box-shadow:0 4px 16px rgba(255,100,150,0.1);
}
.title{font-size:26px;font-weight:800;color:#741737;margin-bottom:6px;text-shadow:0 2px 14px rgba(255,115,168,0.1)}
.subtitle{color:#a13c63;font-weight:600;margin-bottom:12px}
.text{color:#5b2130;font-size:17px;line-height:1.6;min-height:60px}
.decode-task{margin-top:12px;padding:12px;background:rgba(255,240,245,0.75);
  border-radius:12px;border:1px dashed #ff8ab8;font-size:15px;color:#741737;display:none}
.small-muted{font-size:14px;color:#a05573}

/* ===== BACKGROUND EFFECTS ===== */
canvas#hearts-canvas,canvas#sparkles{position:fixed;inset:0;pointer-events:none;z-index:0}

/* ===== ORBS ===== */
.orb{position:absolute;border-radius:50%;filter:blur(40px);opacity:.4;animation:floatOrb 8s ease-in-out infinite alternate}
.orb.one{width:360px;height:360px;left:-80px;top:-60px;background:radial-gradient(circle at 30% 30%,#ffd0e2,#ff9ec2 50%,transparent 70%)}
.orb.two{width:260px;height:260px;right:-80px;bottom:-60px;background:radial-gradient(circle at 60% 70%,#ffcae4,#ff7aa6 40%,transparent 70%);animation-duration:10s}
@keyframes floatOrb{0%{transform:translateY(0)}100%{transform:translateY(-20px)}}

/* ===== BURST ===== */
.burst{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);width:500px;height:500px;border-radius:50%;pointer-events:none;mix-blend-mode:screen;opacity:0;z-index:3}
.burst.show{animation:burstAnim 0.9s ease forwards}
@keyframes burstAnim{
  0%{opacity:0;transform:translate(-50%,-50%) scale(0.6)}
  20%{opacity:1;transform:translate(-50%,-50%) scale(1)}
  100%{opacity:0;transform:translate(-50%,-50%) scale(1.3)}
}

/* ===== TAG ===== */
.tag{position:fixed;bottom:18px;left:50%;transform:translateX(-50%);background:var(--white-80);
padding:8px 14px;border-radius:999px;border:1px solid rgba(255,255,255,0.6);font-size:13px;color:#9b3a61;z-index:4}
</style>
</head>
<body>
<canvas id="hearts-canvas"></canvas>
<canvas id="sparkles"></canvas>
<div class="card">
  <div class="orb one"></div><div class="orb two"></div>
  <div class="grid">
    <div class="heart-wrap">
      <button id="mainBtn" class="btn-heart"><span class="emoji">💗</span></button>
      <div class="small-note">Nhấn dô đâyy</div>
    </div>
    <div class="message">
      <div class="title">Chúc mừng sinh nhật nhaa</div>
      <div class="subtitle">Gửi đến EMiu của toii</div>
      <div id="messageText" class="text">Nhấn vào trái tim bên trái✨</div>
      <div id="decodeTask" class="decode-task"></div>
      <div class="small-muted">Trang này được tạo ra dành riêng cho Vân Anh 💞</div>
    </div>
  </div>
  <div id="burst" class="burst"></div>
</div>
<div class="tag">Thiết kế bởi Quốc Cường 💖</div>
<audio id="bgAudio" src="https://cdn.pixabay.com/download/audio/2021/08/08/audio_3d5f7b1b5d.mp3?filename=happy-birthday-ambient-110691.mp3" preload="auto"></audio>

<script>
/* ===== HEARTS FALL ===== */
(function(){
  const c=document.getElementById('hearts-canvas'),x=c.getContext('2d');
  let W=innerWidth,H=innerHeight;c.width=W;c.height=H;
  const COLORS=['#fff7fa','#ffb3d2','#ff9ec0','#ffcce6','#ffeef6'];
  const hearts=[];
  const N=Math.max(40,Math.floor(W*H/22000));
  const R=(a,b)=>Math.random()*(b-a)+a;
  function Heart(){this.x=R(0,W);this.y=R(-H,H);this.s=R(6,20);this.v=R(.4,1.5);this.a=R(.4,.9);this.c=COLORS[Math.floor(R(0,COLORS.length))];this.p=R(0,Math.PI*2);}
  for(let i=0;i<N;i++)hearts.push(new Heart());
  function drawHeart(x0,y0,s,c,a){
    x.save();x.translate(x0,y0);x.scale(s/10,s/10);
    x.beginPath();x.moveTo(0,0);
    x.bezierCurveTo(0,-3,-5,-3,-5,1);
    x.bezierCurveTo(-5,5,0,9,0,11);
    x.bezierCurveTo(0,9,5,5,5,1);
    x.bezierCurveTo(5,-3,0,-3,0,0);
    x.closePath();x.fillStyle=c;x.globalAlpha=a;x.fill();x.restore();
  }
  function loop(){
    x.clearRect(0,0,W,H);
    for(const h of hearts){
      const sway=Math.sin((h.p+performance.now()/4000)*2)*12;
      drawHeart(h.x+sway,h.y,h.s,h.c,h.a);
      h.y+=h.v;h.p+=.01+h.v*.002;
      if(h.y>H+20){h.y=-20;h.x=R(0,W);}
    }
    requestAnimationFrame(loop);
  }
  loop();
})();

/* ===== SPARKLES ===== */
(function(){
  const c=document.getElementById('sparkles'),ctx=c.getContext('2d');
  let W=innerWidth,H=innerHeight;c.width=W;c.height=H;
  const S=[];for(let i=0;i<80;i++)S.push({x:Math.random()*W,y:Math.random()*H,r:Math.random()*2,sp:Math.random()*0.8});
  function loop(){
    ctx.clearRect(0,0,W,H);
    for(const s of S){
      ctx.beginPath();ctx.arc(s.x,s.y,s.r,0,Math.PI*2);
      ctx.fillStyle='rgba(255,255,255,'+(0.6+Math.sin(Date.now()/1000+s.x)*0.4)+')';
      ctx.fill();
      s.y+=s.sp;if(s.y>H){s.y=0;s.x=Math.random()*W;}
    }
    requestAnimationFrame(loop);
  }
  loop();
})();

/* ===== BUTTON ACTION ===== */
(function(){
  const btn=document.getElementById('mainBtn');
  const msg=document.getElementById('messageText');
  const task=document.getElementById('decodeTask');
  const burst=document.getElementById('burst');
  const audio=document.getElementById('bgAudio');
  let clickCount=0;
  function typeText(el,text){
    el.textContent='';let i=0;
    const inter=setInterval(()=>{el.textContent=text.slice(0,++i);
      if(i>=text.length)clearInterval(inter);},45);
  }
  function showBurst(){
    burst.style.background='radial-gradient(circle at 50% 40%,rgba(255,255,255,0.95),rgba(255,150,190,0.3)15%,rgba(255,150,190,0.1)35%,transparent 65%)';
    burst.classList.add('show');
    setTimeout(()=>burst.classList.remove('show'),950);
  }
  btn.addEventListener('click',()=>{
    clickCount++;
    showBurst();
    if(clickCount===1){
      typeText(msg,'💖 Chúc em sinh nhật thật vui, hạnh phúc, xinh đẹp và yêu Quốc Cường nhiều hơn nhee 💫');
      audio.currentTime=0;audio.play().catch(()=>{});
    }else if(clickCount===2){
      task.style.display='block';
      task.innerHTML='🧩 <b>Bài tập giải mã:</b><br>Giải mã đoạn mật mã: <b>ANDMSCCU</b><br>với ma trận khóa K = [[1,2],[1,2]].';
    }
  });
})();
</script>
</body>
</html>
