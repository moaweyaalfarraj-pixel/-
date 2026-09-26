
<!doctype html>
<html lang="en" manifest="cache.appcache">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="theme-color" content="#010301" />
    <title>HACKING // ACCESS PANEL</title>
    <style>
      :root {
        --green: #39ff14;
        --green-2: #b4ff9f;
        --dim: #397046;
        --black: #010301;
        --glass: rgba(1, 8, 3, .76);
        --line: rgba(57, 255, 20, .25);
        --red: #ff3158;
        --amber: #ffc857;
      }

      * { box-sizing: border-box; }
      html, body { min-height: 100%; }
      body {
        margin: 0;
        color: var(--green-2);
        background:
          radial-gradient(ellipse at 50% 45%, rgba(0, 70, 16, .18), transparent 48%),
          #010301;
        font: 13px/1.55 "SFMono-Regular", Consolas, "Liberation Mono", monospace;
      }
      #number-rain {
        position: fixed;
        inset: 0;
        z-index: 0;
        overflow: hidden;
        pointer-events: none;
        opacity: .48;
        mask-image: linear-gradient(to bottom, transparent, #000 15%, #000 78%, transparent);
      }
      #number-rain span {
        position: absolute;
        top: -18vh;
        color: var(--green);
        font-size: clamp(13px, 1.6vw, 23px);
        line-height: 1;
        text-shadow: 0 0 8px var(--green);
        writing-mode: vertical-rl;
        animation: number-fall linear infinite;
      }
      @keyframes number-fall {
        from { transform: translateY(-25vh); opacity: 0; }
        12% { opacity: .8; }
        82% { opacity: .35; }
        to { transform: translateY(135vh); opacity: 0; }
      }
      .layout { position: relative; z-index: 1; }

      body::before {
        position: fixed;
        inset: 0;
        z-index: -1;
        pointer-events: none;
        content: "";
        background: radial-gradient(ellipse at center, transparent 25%, rgba(0,0,0,.7) 100%);
      }
      body::after {
        position: fixed;
        inset: 0;
        z-index: 5;
        pointer-events: none;
        content: "";
        opacity: .22;
        background: repeating-linear-gradient(0deg, transparent 0 3px, rgba(57,255,20,.06) 4px);
      }

      #brand {
        display: flex;
        align-items: center;
        justify-content: space-between;
        min-height: 64px;
        padding: 0 clamp(18px, 5vw, 66px);
        border-bottom: 1px solid var(--line);
        background: rgba(0, 3, 1, .9);
        box-shadow: 0 5px 25px rgba(0,0,0,.5);
      }
      .identity { display: flex; align-items: center; gap: 12px; }
      .skull {
        display: grid;
        width: 38px;
        height: 38px;
        place-items: center;
        border: 1px solid var(--green);
        color: var(--green);
        font-size: 21px;
        text-shadow: 0 0 8px var(--green);
        box-shadow: 0 0 16px rgba(57,255,20,.32), inset 0 0 12px rgba(57,255,20,.14);
      }
      #brand b { color: var(--green); font-size: 17px; letter-spacing: .32em; text-shadow: 0 0 12px rgba(57,255,20,.8); }
      .connection { color: var(--dim); font-size: 10px; letter-spacing: .12em; text-transform: uppercase; }
      .connection i { display: inline-block; width: 6px; height: 6px; margin-right: 6px; border-radius: 50%; background: var(--green); box-shadow: 0 0 7px var(--green); }

      #wrap { min-height: calc(100vh - 64px); padding: 34px clamp(14px, 5vw, 72px) 50px; }
      .layout { display: block; width: min(900px, 100%); margin: auto; }

      .sidebar { border: 1px solid var(--line); background: var(--glass); box-shadow: 0 18px 55px rgba(0,0,0,.5); backdrop-filter: blur(8px); }
      .main-panel { background: transparent; max-width: 900px; margin: auto; }
      .sidebar { align-self: start; padding: 19px 14px; }
      .side-title { margin: 0 0 18px 6px; color: var(--dim); font-size: 10px; letter-spacing: .15em; text-transform: uppercase; }
      .nav-item { display: flex; align-items: center; gap: 10px; padding: 11px 9px; color: var(--dim); font-size: 11px; border-left: 2px solid transparent; }
      .nav-item.active { border-left-color: var(--green); color: var(--green); background: rgba(57,255,20,.08); }
      .nav-item span { width: 17px; color: var(--green); text-align: center; }
      .side-status { margin-top: 32px; padding: 12px 8px; border-top: 1px solid var(--line); color: var(--dim); font-size: 10px; }
      .side-status strong { display: block; margin-top: 5px; color: var(--green); font-size: 11px; font-weight: 400; }

      .main-panel { min-width: 0; }
      .panel-head { display: flex; align-items: center; justify-content: space-between; padding: 13px 19px; border-bottom: 1px solid rgba(57,255,20,.12); background: transparent; color: var(--dim); font-size: 10px; letter-spacing: .12em; text-transform: uppercase; }
      .panel-head strong { color: var(--green); font-weight: 400; }
      .panel-content { padding: clamp(28px, 6vw, 65px) clamp(20px, 7vw, 82px) 42px; text-align: center; }
      .target { margin: 0 0 10px; color: var(--dim); font-size: 11px; letter-spacing: .2em; text-transform: uppercase; }
      h1 { margin: 0; color: var(--green); font-size: clamp(32px, 8vw, 68px); font-weight: 400; letter-spacing: .13em; line-height: 1; text-shadow: 0 0 9px var(--green), 0 0 30px rgba(57,255,20,.55); }

      .meter-wrap { margin: 35px auto 13px; max-width: 520px; text-align: left; }
      .meter-label { display: flex; justify-content: space-between; margin-bottom: 6px; color: var(--dim); font-size: 10px; }
      .meter-label b { color: var(--green); font-weight: 400; }
      .meter { height: 9px; padding: 2px; overflow: hidden; border: 1px solid var(--line); background: #010501; }
      .meter span { display: block; width: 52%; height: 100%; background: repeating-linear-gradient(90deg, var(--green) 0 8px, transparent 8px 11px); filter: drop-shadow(0 0 5px var(--green)); animation: progress 2.1s linear infinite; }
      @keyframes progress { 0% { transform: translateX(-100%); } 100% { transform: translateX(190%); } }


      #spin { position: fixed; width: 1px; height: 1px; opacity: 0; }
      #msg { display: none; margin-top: 25px; color: var(--red); font-weight: 700; letter-spacing: .1em; }
      #state, #out { display: none; }
      body.done .meter-wrap, body.fail .meter-wrap { display: none; }
      body.done #msg { display: block; color: var(--green); }
      body.fail #msg { display: block; }
      body.fail h1 { color: var(--red); text-shadow: 0 0 9px var(--red); }

      body.log #wrap { padding: 28px clamp(14px, 5vw, 72px); }
      body.log .layout { display: block; max-width: 1120px; }
      body.log body.log .target, body.log h1, body.log .meter-wrap, body.log #msg { display: none; }
      body.log .panel-content { padding: 24px; text-align: left; }
      body.log #state { display: block; margin-bottom: 13px; color: var(--green); font-size: 18px; }
      body.log #out { display: block; min-height: calc(100vh - 185px); padding: 16px; overflow: auto; border: 1px solid var(--line); color: #b9eebf; background: rgba(0, 4, 1, .7); font: 12px/1.7 "SFMono-Regular", Consolas, monospace; white-space: pre-wrap; }

      .ok, .safe { color: var(--green); }
      .bad, .danger { color: var(--red); }
      .warn { color: var(--amber); }
      code { color: var(--green-2); }

      @media (max-width: 700px) {
        .sidebar { display: none; }
        #brand { min-height: 58px; }
        #wrap { min-height: calc(100vh - 58px); padding: 21px 11px 35px; }
        .connection { display: none; }
        .panel-content { padding: 38px 16px 31px; }
      }
    </style>
  </head>
  <body>
    <header id="brand">
      <div class="identity"><span class="skull" aria-hidden="true">☠</span><b>HACKING</b></div>
      <div class="connection"><i></i> anonymous channel / encrypted</div>
    </header>

    <div id="number-rain" aria-hidden="true"></div>
    <div id="spin" aria-hidden="true"></div>
    <div id="wrap">
      <div class="layout">


        <main class="main-panel" aria-live="polite">
          <div class="panel-head"><span>root@anonymous: /access</span><strong>session active</strong></div>
          <div class="panel-content">
            <p class="target">target interface detected</p>
            <h1>HACKING</h1>
            <div class="meter-wrap">
              <div class="meter-label"><span>ACCESS PROTOCOL</span><b>IN PROGRESS</b></div>
              <div class="meter"><span></span></div>
            </div>
            <div id="msg">CONNECTION FAILED // RESTART YOUR CONSOLE</div>
            <div id="state"></div>
            <div id="out"></div>
          </div>
        </main>
      </div>
    </div>

    <script>
      const rain = document.getElementById("number-rain");
      const digits = "0123456789";
      for (let i = 0; i < 86; i++) {
        const stream = document.createElement("span");
        const length = 5 + Math.floor(Math.random() * 14);
        stream.textContent = Array.from({ length }, () => digits[Math.floor(Math.random() * digits.length)]).join("\n");
        stream.style.left = `${Math.random() * 100}%`;
        stream.style.animationDuration = `${5 + Math.random() * 9}s`;
        stream.style.animationDelay = `${-Math.random() * 12}s`;
        stream.style.opacity = `${.18 + Math.random() * .62}`;
        rain.appendChild(stream);
      }
    </script>
    <script type="module">
      import "./jb.js?v=19";
    </script>
  </body>
</html>
