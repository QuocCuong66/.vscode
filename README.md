<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Chúc mừng sinh nhật Vân Anh 18/10/2025</title>
  <meta name="description" content="Trang chúc mừng sinh nhật tông hồng với trái tim nhỏ rơi xung quanh, tối giản chỉ 1 nút.">
  <style>
    /* ===== Reset & base ===== */
    :root{
      --pink-100: #fff0f4;
      --pink-200: #ffd7e8;
      --pink-300: #ffb3d2;
      --pink-400: #ff7aa6;
      --pink-500: #ff4d8a;
      --white-80: rgba(255,255,255,0.8);
      --glass-border: rgba(255,255,255,0.55);
      --text-dark: #5b2130;
      --shadow: 0 10px 30px rgba(156, 39, 176, 0.12);
    }
    *{box-sizing:border-box;margin:0;padding:0}
    html,body,#app{height:100%}
    body{
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: linear-gradient(180deg, #fff6f9 0%, #ffe9f2 40%, #ffdfe9 100%);
      color:var(--text-dark);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      overflow:hidden;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:20px;
    }

    /* ===== Layout card ===== */
    .card{
      width:100%;
      max-width:960px;
      border-radius:24px;
      background: linear-gradient(180deg, rgba(255,255,255,0.72), rgba(255,255,255,0.55));
      border: 1px solid var(--glass-border);
      box-shadow: var(--shadow);
      padding:36px;
      position:relative;
      backdrop-filter: blur(8px) saturate(120%);
      overflow:visible;
    }

    .grid{
      display:grid;
      grid-template-columns: 1fr;
      gap: 18px;
      align-items:center;
    }
    @media(min-width:880px){
      .grid{grid-template-columns: 380px 1fr}
    }

    /* ===== Left - big button ===== */
    .heart-wrap{
      display:flex;
      align-items:center;
      justify-content:center;
      gap:18px;
      flex-direction:column;
    }
    .btn-heart{
      width:180px;
      height:180px;
      border-radius:999px;
      background: linear-gradient(135deg, #ff76a9 0%, #ff4d8a 55%, #ff2d6f 100%);
      display:flex;
      align-items:center;
      justify-content:center;
      color:white;
      font-size:40px;
      border:none;
      cursor:pointer;
      box-shadow: 0 20px 40px rgba(255,77,138,0.18), inset 0 -6px 20px rgba(255,255,255,0.06);
      transition: transform .16s ease, box-shadow .16s ease;
      position:relative;
      z-index:4;
    }
    .btn-heart:active{ transform: scale(.96) }
    .btn-heart:focus{ outline:3px solid rgba(255,77,138,0.18); outline-offset:6px }

    .btn-heart .emoji{
      font-size:48px;
      filter: drop-shadow(0 6px 18px rgba(0,0,0,0.12));
      animation: pulseEmoji 1.4s infinite;
    }
    @keyframes pulseEmoji {
      0%{ transform: scale(1) }
      50%{ transform: scale(1.06) rotate(-3deg) }
      100%{ transform: scale(1) }
    }

    .small-note{
      color:#a23b5d;
      font-weight:600;
      font-size:15px;
      text-align:center;
      margin-top:6px;
    }

    /* ===== Right - message card ===== */
    .message{
      padding:18px;
      border-radius:16px;
      background: linear-gradient(180deg, rgba(255,255,255,0.7), rgba(255,255,255,0.55));
      border:1px solid rgba(255,255,255,0.5);
      box-shadow: 0 6px 18px rgba(131, 58, 180, 0.06);
    }
    .title{
      font-size:24px;
      font-weight:800;
      color:#741737;
      margin-bottom:8px;
      letter-spacing:-0.4px;
      text-shadow: 0 2px 14px rgba(255,115,168,0.08);
    }
    .subtitle{
      color:#9b3a61;
      font-weight:600;
      margin-bottom:14px;
    }
    .text{
      color:#5b2130;
      line-height:1.55;
      font-size:16px;
      margin-bottom:14px;
    }
    .small-muted{
      font-size:12px;
      color:#a86b86;
    }

    /* ===== Decorative floating shapes ===== */
    .orb{
      position:absolute;
      border-radius:999px;
      filter: blur(36px);
      opacity:0.4;
      z-index:0;
      transform: translate3d(0,0,0);
      animation: floatOrb 8s ease-in-out infinite;
      pointer-events:none;
    }
    .orb.one{ width:380px;height:380px; left:-90px; top:-80px; background: radial-gradient(circle at 20% 20%, #ffd0e2, #ff9ec2 40%, transparent 60%);}
    .orb.two{ width:260px;height:260px; right:-80px; bottom:-60px; background: radial-gradient(circle at 70% 80%, #ffcae4, #ff7aa6 30%, transparent 60%); animation-duration:9s; }
    @keyframes floatOrb{ 0%{ transform: translateY(0) } 50%{ transform: translateY(-18px) } 100%{ transform: translateY(0) } }

    /* ===== Canvas hearts (on top of background, under content) ===== */
    #hearts-canvas{
      position:fixed;
      inset:0;
      z-index:1;
      pointer-events:none;
    }

    /* ===== Flash/star burst when clicked ===== */
    .burst{
      position:absolute;
      left:50%;
      top:50%;
      transform:translate(-50%,-50%);
      width:520px;
      height:520px;
      border-radius:50%;
      pointer-events:none;
      z-index:3;
      mix-blend-mode:screen;
      opacity:0;
    }
    .burst.show{
      animation: burstAnim .9s ease forwards;
    }
    @keyframes burstAnim{
      0%{ opacity:0; transform:translate(-50%,-50%) scale(.6) }
      20%{ opacity:1; transform:translate(-50%,-50%) scale(1) }
      100%{ opacity:0; transform:translate(-50%,-50%) scale(1.25) }
    }

    /* ===== Confetti hearts (small CSS hearts) - appearing on click briefly ===== */
    .confetti-wrap{ position:absolute; inset:0; z-index:5; pointer-events:none; overflow:visible }

    /* ===== Footer tag ===== */
    .tag{
      position:fixed;
      bottom:18px;
      left:50%;
      transform:translateX(-50%);
      background:var(--white-80);
      padding:8px 14px;
      border-radius:999px;
      border:1px solid rgba(255,255,255,0.6);
      font-size:13px;
      color:#9b3a61;
      z-index:6;
      box-shadow: 0 6px 20px rgba(144, 57, 93, 0.06);
    }
  </style>
</head>
<body>
  <canvas id="hearts-canvas" aria-hidden="true"></canvas>

  <div id="app" class="card" role="main" aria-labelledby="main-title">
    <div class="orb one" aria-hidden="true"></div>
    <div class="orb two" aria-hidden="true"></div>

    <div class="grid">
      <!-- LEFT: Big heart button -->
      <div class="heart-wrap" aria-hidden="false">
        <button id="mainBtn" class="btn-heart" aria-pressed="false" aria-label="Nhấn trái tim để hiện lời chúc của Quốc Cường">
          <span class="emoji">💗</span>
        </button>
        <div class="small-note">Nhấn dô đâyy</div>
      </div>

      <!-- RIGHT: Message -->
      <div class="message" id="messageCard" aria-live="polite">
        <div class="title" id="main-title">Chúc mừng sinh nhật!</div>
        <div class="subtitle">Gửi đến EMiu của toii</div>

        <div id="messageText" class="text">
          Nhấn vào trái tim bên trái để nhận lời chúc và xem hiệu ứng lung linh ✨
        </div>

        <div class="small-muted">Trang nhẹ, trong trẻo & tối giản — chỉ 1 nút duy nhất.</div>
      </div>
    </div>

    <!-- Burst visual (for flash) -->
    <div id="burst" class="burst" aria-hidden="true" ></div>

    <!-- Confetti container -->
    <div id="confetti" class="confetti-wrap" aria-hidden="true"></div>

  </div>

  <div class="tag">Thiết kế bởi Quốc Cường 💖</div>

  <!-- Optional audio: nếu muốn đổi, thay URL hoặc bỏ dòng <audio> -->
  <audio id="bgAudio" src="https://cdn.pixabay.com/download/audio/2021/08/08/audio_3d5f7b1b5d.mp3?filename=happy-birthday-ambient-110691.mp3" preload="auto"></audio>

  <script>
    /* =============================
       Canvas Hearts: falling hearts
       - lightweight, optimized
       - many sizes, alpha, slight sway
       ============================= */
    (function(){
      const canvas = document.getElementById('hearts-canvas');
      const ctx = canvas.getContext('2d');
      let W = canvas.width = innerWidth;
      let H = canvas.height = innerHeight;
      const hearts = [];
      const HEART_COUNT = Math.max(40, Math.floor((W*H)/20000)); // adaptive
      const COLORS = ['#fff7fa','#ffb3d2','#ff9ec0','#ffcce6','#ffeef6'];

      function rand(min, max){ return Math.random()*(max-min)+min }

      function HeartObj(){
        this.x = rand(0, W);
        this.y = rand(-H, H);
        this.size = rand(6, 22);
        this.speed = rand(0.35, 1.6);
        this.alpha = rand(0.18, 0.85);
        this.color = COLORS[Math.floor(rand(0, COLORS.length))];
        this.phase = rand(0, Math.PI*2);
        this.sway = rand(8, 28);
      }
      function createHearts(){
        hearts.length = 0;
        for(let i=0;i<HEART_COUNT;i++) hearts.push(new HeartObj());
      }

      function drawHeartShape(x,y,s,color,a){
        // Draw a cute heart using bezier curves scaled by s
        ctx.save();
        ctx.translate(x,y);
        ctx.scale(s/10, s/10); // base shape uses size 10
        ctx.beginPath();
        ctx.moveTo(0,0);
        ctx.bezierCurveTo(0,-3,-5,-3,-5,1);
        ctx.bezierCurveTo(-5,5,0,8,0,10);
        ctx.bezierCurveTo(0,8,5,5,5,1);
        ctx.bezierCurveTo(5,-3,0,-3,0,0);
        ctx.closePath();
        ctx.fillStyle = color;
        ctx.globalAlpha = a;
        ctx.fill();
        ctx.restore();
      }

      function resize(){
        W = canvas.width = innerWidth;
        H = canvas.height = innerHeight;
        createHearts();
      }

      function render(){
        ctx.clearRect(0,0,W,H);
        for(let i=0;i<hearts.length;i++){
          const h = hearts[i];
          const swayX = Math.sin((h.phase + performance.now()/4000) * 2) * h.sway;
          drawHeartShape(h.x + swayX, h.y, h.size, h.color, h.alpha);
          h.y += h.speed;
          h.phase += 0.01 + h.speed*0.002;
          if(h.y > H + 20){ h.y = -20; h.x = rand(0,W); }
        }
        requestAnimationFrame(render);
      }

      addEventListener('resize', resize);
      createHearts();
      requestAnimationFrame(render);

      // expose for debugging if needed
      window._hearts_anim = { canvas, ctx, hearts };
    })();

    /* =============================
       Main interactivity:
        - one button toggles message + effects
        - show burst, spawn confetti hearts and play audio
       ============================= */
    (function(){
      const btn = document.getElementById('mainBtn');
      const messageText = document.getElementById('messageText');
      const burst = document.getElementById('burst');
      const confettiWrap = document.getElementById('confetti');
      const audio = document.getElementById('bgAudio');

      let clicked = false;

      function createConfettiHeart(x,y,delay){
        // create a small DOM heart that floats up and fades
        const el = document.createElement('div');
        el.style.position = 'absolute';
        el.style.left = (x - 8) + 'px';
        el.style.top = (y - 8) + 'px';
        el.style.width = '14px';
        el.style.height = '14px';
        el.style.pointerEvents = 'none';
        el.style.zIndex = 20;
        // SVG heart via background-image for crispness
        const hue = Math.random()*30 + 330; // pinkish hues
        const light = Math.random()*30 + 70;
        el.style.backgroundImage = 'url("data:image/svg+xml;utf8,' + encodeURIComponent('<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 32 29\"><path fill=\"'+('#ff' + Math.floor(Math.random()*100+20).toString(16))+'\" d=\"M23.6 0c-2.3 0-4.3 1.3-5.6 3.2C16.7 1.3 14.7 0 12.4 0 7.6 0 4 4 4 8.8c0 4.2 2.2 7.2 11.1 14.2l.9.7.9-.7C25.8 16 28 13 28 8.8 28 4 24.4 0 19.6 0z\"/></svg>') + '")';
        el.style.backgroundSize = 'contain';
        el.style.opacity = '0';
        el.style.transform = 'translateY(0) scale(.8) rotate(' + (Math.random()*60-30) + 'deg)';
        confettiWrap.appendChild(el);

        // animate via JS
        setTimeout(()=>{
          el.animate([
            { transform: el.style.transform, opacity:0 },
            { transform: 'translateY(' + ( - (60 + Math.random()*120)) + 'px) scale(1)', opacity:1 },
            { transform: 'translateY(' + ( - (140 + Math.random()*240)) + 'px) scale(.8)', opacity:0 }
          ], {
            duration: 1100 + Math.random()*900,
            easing: 'cubic-bezier(.2,.8,.2,1)'
          });
          setTimeout(()=> el.remove(), 2200);
        }, delay);
      }

      function spawnConfettiBurst(centerX, centerY, count){
        for(let i=0;i<count;i++){
          const angle = Math.random()*Math.PI*2;
          const r = Math.random()*80 + 20;
          const x = centerX + Math.cos(angle)*r + (Math.random()*40-20);
          const y = centerY + Math.sin(angle)*r + (Math.random()*40-20);
          createConfettiHeart(x,y, Math.random()*120);
        }
      }

      function showBurst(){
        burst.classList.remove('show');
        // random radial gradient
        burst.style.background = 'radial-gradient(circle at 50% 40%, rgba(255, 255, 255, 0.95), rgba(255,150,190,0.25) 15%, rgba(255,150,190,0.08) 35%, transparent 65%)';
        void burst.offsetWidth;
        burst.classList.add('show');
        setTimeout(()=> burst.classList.remove('show'), 950);
      }

      btn.addEventListener('click', (e) => {
        const rect = btn.getBoundingClientRect();
        const cx = rect.left + rect.width/2;
        const cy = rect.top + rect.height/2;

        // toggle message only first click opens
        if(!clicked){
          messageText.textContent = '💖 Chúc em sinh nhật thật là zui zui , sống hạnh phúc , ngày càng xinh đẹp , học giỏi , siêng năng chăm chỉ cần mẫn biết quan tâm yêu bản thân nhiều dô , yêu Quốc Cường nhìu nhìu hơn nữa nhee. 💫';
          // sound: try play (user gesture present)
          try { audio.currentTime = 0; audio.play().catch(()=>{}); } catch(e){}
          // effects
          showBurst();
          spawnConfettiBurst(cx, cy, 18);
          // also spawn rising hearts at multiple x positions
          for(let i=0;i<24;i++){
            createConfettiHeart(cx + (Math.random()*220-110), cy + (Math.random()*40-20), i*20);
          }
          // pulse btn
          btn.animate([
            { transform: 'scale(1)' },
            { transform: 'scale(1.08)' },
            { transform: 'scale(1)' },
            { transform: 'scale(1.04)' },
            { transform: 'scale(1)' }
          ], { duration: 700, easing: 'cubic-bezier(.2,.9,.2,1)'});
          btn.setAttribute('aria-pressed','true');
          clicked = true;
        } else {
          // if clicked again, do a soft sparkle and small confetti
          showBurst();
          spawnConfettiBurst(cx, cy, 8);
          for(let i=0;i<12;i++) createConfettiHeart(cx + (Math.random()*180-90), cy, i*30);
        }
      });

      // keyboard accessibility: Enter / Space triggers
      btn.addEventListener('keydown', (ev) => {
        if(ev.key === 'Enter' || ev.key === ' '){
          ev.preventDefault();
          btn.click();
        }
      });

      // mobile: autoplay audio often blocked; allow tap to start background audio separately
      // but we already play on button click (which is a user gesture) — good.

    })();
  </script>
</body>
</html>
