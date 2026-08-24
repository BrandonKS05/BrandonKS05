<svg width="830" height="478" viewBox="0 0 830 478" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Status window: Brandon Lee, full-stack developer">
  <style>
    text {
      font-family: "SFMono-Regular", "Cascadia Mono", "JetBrains Mono", Menlo, Consolas, "Liberation Mono", monospace;
    }
    .hdr   { fill: #cfeaff; font-size: 14px; letter-spacing: 7px; }
    .label { fill: #66a9dd; font-size: 13px; }
    .value { fill: #e9f5ff; font-size: 13px; }
    .group { fill: #5f9bc9; font-size: 11px; letter-spacing: 3px; }
    .item  { fill: #c9e4fa; font-size: 13px; }
    .dim   { fill: #7fa9cc; font-size: 13px; }
    .mark  { fill: #dff1ff; font-size: 13px; font-weight: bold; }
    @keyframes pulse { 0%, 100% { opacity: 0.35; } 50% { opacity: 0.9; } }
    .pulse { animation: pulse 3.4s ease-in-out infinite; }
    @keyframes blink { 0%, 49% { opacity: 1; } 50%, 100% { opacity: 0; } }
    .cursor { animation: blink 1.1s steps(1) infinite; fill: #4db8ff; }
  </style>
  <defs>
    <linearGradient id="panel" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0" stop-color="#0d1726"/>
      <stop offset="1" stop-color="#0a111c"/>
    </linearGradient>
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3.5" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- panel -->
  <rect x="6" y="6" width="818" height="466" rx="10" fill="url(#panel)"/>
  <rect class="pulse" x="6" y="6" width="818" height="466" rx="10" fill="none" stroke="#4db8ff" stroke-width="1.5" filter="url(#glow)"/>
  <rect x="6" y="6" width="818" height="466" rx="10" fill="none" stroke="#4db8ff" stroke-opacity="0.85" stroke-width="1.2"/>
  <rect x="13" y="13" width="804" height="452" rx="6" fill="none" stroke="#4db8ff" stroke-opacity="0.16"/>

  <!-- header -->
  <g filter="url(#glow)">
    <path d="M 415 31 L 428 44 L 415 57 L 402 44 Z" fill="#4db8ff" fill-opacity="0.10" stroke="#4db8ff" stroke-width="1.3"/>
  </g>
  <text x="415" y="49" text-anchor="middle" class="mark">!</text>
  <text x="418.5" y="88" text-anchor="middle" class="hdr">STATUS WINDOW</text>
  <line x1="44" y1="108" x2="786" y2="108" stroke="#4db8ff" stroke-opacity="0.28"/>

  <!-- info -->
  <text x="48" y="140" class="label">NAME: <tspan class="value">BRANDON LEE</tspan></text>
  <text x="436" y="140" class="label">JOB: <tspan class="value">FULL-STACK DEVELOPER</tspan></text>
  <text x="48" y="166" class="label">LEVEL: <tspan class="value">n+1</tspan> <tspan class="dim">▲</tspan></text>
  <text x="436" y="166" class="label">TITLE: <tspan class="value">ALWAYS SHIPPING</tspan></text>

  <line x1="44" y1="192" x2="786" y2="192" stroke="#4db8ff" stroke-opacity="0.28"/>
  <text x="416.5" y="220" text-anchor="middle" class="group">SKILLS</text>

  <!-- left column -->
  <text x="48" y="250" class="group">LANGUAGES</text>
  <text x="48" y="274" class="item">python · java · c++ · javascript ·</text>
  <text x="48" y="296" class="item">typescript · c · go · html/css · sql</text>
  <text x="48" y="336" class="group">FRAMEWORKS</text>
  <text x="48" y="360" class="item">react · next.js · angular · node.js ·</text>
  <text x="48" y="382" class="item">express · spring boot · tailwindcss ·</text>
  <text x="48" y="404" class="item">flask · discord.py</text>

  <!-- right column -->
  <text x="436" y="250" class="group">DATABASES</text>
  <text x="436" y="274" class="item">mongodb · postgresql · redis · mysql ·</text>
  <text x="436" y="296" class="item">sqlite · firebase · supabase</text>
  <text x="436" y="336" class="group">TOOLS</text>
  <text x="436" y="360" class="item">azure · docker · vercel · nginx ·</text>
  <text x="436" y="382" class="item">oauth 2.0 · unix · git</text>

  <line x1="44" y1="430" x2="786" y2="430" stroke="#4db8ff" stroke-opacity="0.28"/>
  <text x="415" y="456" text-anchor="middle" class="dim">&gt; always building · always learning <tspan class="cursor">▍</tspan></text>
</svg>
