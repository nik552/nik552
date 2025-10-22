<!-- Header + visitor badge top-right -->
<div style="position:relative; padding: 8px 0 18px 0;">
  <div style="text-align:center;">
    <h1 style="margin:0; font-size:48px; font-weight:800;">Hi, I'm Nikabou 👋</h1>
  </div>

  <!-- badge visitor (top-right) -->
  <div style="position:absolute; right:0; top:0;">
    <a href="https://github.com/Nikabou">
      <img src="https://komarev.com/ghpvc/?username=Nikabou&label=Visitors&color=0e75b6&style=flat-square" alt="visitor badge" />
    </a>
  </div>

  <hr style="margin-top:12px; margin-bottom:8px;"/>
  <div style="text-align:center;">
    <h2 style="margin:8px 0 0 0;">🛠️ Tech Stack</h2>
  </div>
</div>

<!-- Animated "Snake-like" GitHub activity heatmap (SVG) -->
<div align="center" style="margin-top: 12px;">
  <!-- Inline SVG: 7 rows x 14 cols. Certain cells are sequenced to simulate a moving snake. -->
  <svg width="560" height="160" viewBox="0 0 560 160" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="GitHub activity snake heatmap">
    <style>
      .cell { rx:3; ry:3; fill:#dfe9f3; opacity:0.28; }
      .snake-seq { fill:#16a34a; opacity:0.95; }
      /* Pulse animation for snake body: head bright, tail fades */
      @keyframes snakePulse {
        0%   { opacity:0.05; transform:scale(0.85); }
        30%  { opacity:1; transform:scale(1.05); }
        70%  { opacity:0.6; transform:scale(1.0); }
        100% { opacity:0.05; transform:scale(0.85); }
      }
      /* Apply animation; custom delay per cell via style="--d:0.xxs" */
      .snake-seq { animation: snakePulse 1.6s linear infinite; transform-origin:center; }
    </style>

    <!-- Grid parameters -->
    <!-- rows = 7, cols = 14, cell 32x32 spacing 8 -->
    <!-- draw background grid -->
    <!-- We'll generate each rect manually with coordinates. -->
    <!-- Row loop in head: y = row*(cell+hgap) -->
    <!-- For readability this is explicit: -->
    <!-- Background cells -->
    <!-- Row 0 -->
    <g id="grid">
      <!-- create a 7x14 light grid -->
      <!-- x = col*(cell + gap) -->
      <!-- cell=28 gap=12 => step=40; left padding 8 -->
      <!-- draw background cells -->
      <!-- (We keep them as plain faint squares) -->
      <!-- Row 0 -->
      <rect class="cell" x="8"  y="8"  width="28" height="28" />
      <rect class="cell" x="48" y="8"  width="28" height="28" />
      <rect class="cell" x="88" y="8"  width="28" height="28" />
      <rect class="cell" x="128" y="8" width="28" height="28" />
      <rect class="cell" x="168" y="8" width="28" height="28" />
      <rect class="cell" x="208" y="8" width="28" height="28" />
      <rect class="cell" x="248" y="8" width="28" height="28" />
      <rect class="cell" x="288" y="8" width="28" height="28" />
      <rect class="cell" x="328" y="8" width="28" height="28" />
      <rect class="cell" x="368" y="8" width="28" height="28" />
      <rect class="cell" x="408" y="8" width="28" height="28" />
      <rect class="cell" x="448" y="8" width="28" height="28" />
      <rect class="cell" x="488" y="8" width="28" height="28" />
      <rect class="cell" x="528" y="8" width="28" height="28" />

      <!-- Row 1 -->
      <rect class="cell" x="8"  y="48" width="28" height="28" />
      <rect class="cell" x="48" y="48" width="28" height="28" />
      <rect class="cell" x="88" y="48" width="28" height="28" />
      <rect class="cell" x="128" y="48" width="28" height="28" />
      <rect class="cell" x="168" y="48" width="28" height="28" />
      <rect class="cell" x="208" y="48" width="28" height="28" />
      <rect class="cell" x="248" y="48" width="28" height="28" />
      <rect class="cell" x="288" y="48" width="28" height="28" />
      <rect class="cell" x="328" y="48" width="28" height="28" />
      <rect class="cell" x="368" y="48" width="28" height="28" />
      <rect class="cell" x="408" y="48" width="28" height="28" />
      <rect class="cell" x="448" y="48" width="28" height="28" />
      <rect class="cell" x="488" y="48" width="28" height="28" />
      <rect class="cell" x="528" y="48" width="28" height="28" />

      <!-- Row 2 -->
      <rect class="cell" x="8"  y="88" width="28" height="28" />
      <rect class="cell" x="48" y="88" width="28" height="28" />
      <rect class="cell" x="88" y="88" width="28" height="28" />
      <rect class="cell" x="128" y="88" width="28" height="28" />
      <rect class="cell" x="168" y="88" width="28" height="28" />
      <rect class="cell" x="208" y="88" width="28" height="28" />
      <rect class="cell" x="248" y="88" width="28" height="28" />
      <rect class="cell" x="288" y="88" width="28" height="28" />
      <rect class="cell" x="328" y="88" width="28" height="28" />
      <rect class="cell" x="368" y="88" width="28" height="28" />
      <rect class="cell" x="408" y="88" width="28" height="28" />
      <rect class="cell" x="448" y="88" width="28" height="28" />
      <rect class="cell" x="488" y="88" width="28" height="28" />
      <rect class="cell" x="528" y="88" width="28" height="28" />

      <!-- Row 3 -->
      <rect class="cell" x="8"  y="128" width="28" height="28" />
      <rect class="cell" x="48" y="128" width="28" height="28" />
      <rect class="cell" x="88" y="128" width="28" height="28" />
      <rect class="cell" x="128" y="128" width="28" height="28" />
      <rect class="cell" x="168" y="128" width="28" height="28" />
      <rect class="cell" x="208" y="128" width="28" height="28" />
      <rect class="cell" x="248" y="128" width="28" height="28" />
      <rect class="cell" x="288" y="128" width="28" height="28" />
      <rect class="cell" x="328" y="128" width="28" height="28" />
      <rect class="cell" x="368" y="128" width="28" height="28" />
      <rect class="cell" x="408" y="128" width="28" height="28" />
      <rect class="cell" x="448" y="128" width="28" height="28" />
      <rect class="cell" x="488" y="128" width="28" height="28" />
      <rect class="cell" x="528" y="128" width="28" height="28" />
    </g>

    <!-- Snake sequence overlay: we animate many cells with staggered delays to create a moving trail -->
    <!-- We'll "light up" a serpentine path across the grid by placing rects on top with the snake-seq class -->
    <!-- Each rect has an inline style --d: Xs used as animation delay. -->
    <!-- Example path: left-to-right on row0, then row1 right-to-left, etc. -->
    <!-- Row 0 left->right -->
    <g id="snake">
      <!-- row 0 -->
      <rect class="snake-seq" x="8"  y="8"  width="28" height="28" style="animation-delay:0s;" />
      <rect class="snake-seq" x="48" y="8"  width="28" height="28" style="animation-delay:0.08s;" />
      <rect class="snake-seq" x="88" y="8"  width="28" height="28" style="animation-delay:0.16s;" />
      <rect class="snake-seq" x="128" y="8" width="28" height="28" style="animation-delay:0.24s;" />
      <rect class="snake-seq" x="168" y="8" width="28" height="28" style="animation-delay:0.32s;" />
      <rect class="snake-seq" x="208" y="8" width="28" height="28" style="animation-delay:0.40s;" />
      <rect class="snake-seq" x="248" y="8" width="28" height="28" style="animation-delay:0.48s;" />
      <rect class="snake-seq" x="288" y="8" width="28" height="28" style="animation-delay:0.56s;" />
      <rect class="snake-seq" x="328" y="8" width="28" height="28" style="animation-delay:0.64s;" />
      <rect class="snake-seq" x="368" y="8" width="28" height="28" style="animation-delay:0.72s;" />
      <rect class="snake-seq" x="408" y="8" width="28" height="28" style="animation-delay:0.80s;" />
      <rect class="snake-seq" x="448" y="8" width="28" height="28" style="animation-delay:0.88s;" />
      <rect class="snake-seq" x="488" y="8" width="28" height="28" style="animation-delay:0.96s;" />
      <rect class="snake-seq" x="528" y="8" width="28" height="28" style="animation-delay:1.04s;" />

      <!-- row 1 right->left -->
      <rect class="snake-seq" x="528" y="48" width="28" height="28" style="animation-delay:1.12s;" />
      <rect class="snake-seq" x="488" y="48" width="28" height="28" style="animation-delay:1.20s;" />
      <rect class="snake-seq" x="448" y="48" width="28" height="28" style="animation-delay:1.28s;" />
      <rect class="snake-seq" x="408" y="48" width="28" height="28" style="animation-delay:1.36s;" />
      <rect class="snake-seq" x="368" y="48" width="28" height="28" style="animation-delay:1.44s;" />
      <rect class="snake-seq" x="328" y="48" width="28" height="28" style="animation-delay:1.52s;" />
      <rect class="snake-seq" x="288" y="48" width="28" height="28" style="animation-delay:1.60s;" />
      <rect class="snake-seq" x="248" y="48" width="28" height="28" style="animation-delay:1.68s;" />
      <rect class="snake-seq" x="208" y="48" width="28" height="28" style="animation-delay:1.76s;" />
      <rect class="snake-seq" x="168" y="48" width="28" height="28" style="animation-delay:1.84s;" />
      <rect class="snake-seq" x="128" y="48" width="28" height="28" style="animation-delay:1.92s;" />
      <rect class="snake-seq" x="88" y="48" width="28" height="28" style="animation-delay:2.00s;" />
      <rect class="snake-seq" x="48" y="48" width="28" height="28" style="animation-delay:2.08s;" />
      <rect class="snake-seq" x="8"  y="48" width="28" height="28" style="animation-delay:2.16s;" />

      <!-- row 2 left->right (continue snake) -->
      <rect class="snake-seq" x="8"  y="88" width="28" height="28" style="animation-delay:2.24s;" />
      <rect class="snake-seq" x="48" y="88" width="28" height="28" style="animation-delay:2.32s;" />
      <rect class="snake-seq" x="88" y="88" width="28" height="28" style="animation-delay:2.40s;" />
      <rect class="snake-seq" x="128" y="88" width="28" height="28" style="animation-delay:2.48s;" />
      <rect class="snake-seq" x="168" y="88" width="28" height="28" style="animation-delay:2.56s;" />
      <rect class="snake-seq" x="208" y="88" width="28" height="28" style="animation-delay:2.64s;" />
      <rect class="snake-seq" x="248" y="88" width="28" height="28" style="animation-delay:2.72s;" />
      <rect class="snake-seq" x="288" y="88" width="28" height="28" style="animation-delay:2.80s;" />
      <rect class="snake-seq" x="328" y="88" width="28" height="28" style="animation-delay:2.88s;" />
      <rect class="snake-seq" x="368" y="88" width="28" height="28" style="animation-delay:2.96s;" />
      <rect class="snake-seq" x="408" y="88" width="28" height="28" style="animation-delay:3.04s;" />
      <rect class="snake-seq" x="448" y="88" width="28" height="28" style="animation-delay:3.12s;" />
      <rect class="snake-seq" x="488" y="88" width="28" height="28" style="animation-delay:3.20s;" />
      <rect class="snake-seq" x="528" y="88" width="28" height="28" style="animation-delay:3.28s;" />

      <!-- row 3 right->left -->
      <rect class="snake-seq" x="528" y="128" width="28" height="28" style="animation-delay:3.36s;" />
      <rect class="snake-seq" x="488" y="128" width="28" height="28" style="animation-delay:3.44s;" />
      <rect class="snake-seq" x="448" y="128" width="28" height="28" style="animation-delay:3.52s;" />
      <rect class="snake-seq" x="408" y="128" width="28" height="28" style="animation-delay:3.60s;" />
      <rect class="snake-seq" x="368" y="128" width="28" height="28" style="animation-delay:3.68s;" />
      <rect class="snake-seq" x="328" y="128" width="28" height="28" style="animation-delay:3.76s;" />
      <rect class="snake-seq" x="288" y="128" width="28" height="28" style="animation-delay:3.84s;" />
      <rect class="snake-seq" x="248" y="128" width="28" height="28" style="animation-delay:3.92s;" />
      <rect class="snake-seq" x="208" y="128" width="28" height="28" style="animation-delay:4.00s;" />
      <rect class="snake-seq" x="168" y="128" width="28" height="28" style="animation-delay:4.08s;" />
      <rect class="snake-seq" x="128" y="128" width="28" height="28" style="animation-delay:4.16s;" />
      <rect class="snake-seq" x="88" y="128" width="28" height="28" style="animation-delay:4.24s;" />
      <rect class="snake-seq" x="48" y="128" width="28" height="28" style="animation-delay:4.32s;" />
      <rect class="snake-seq" x="8"  y="128" width="28" height="28" style="animation-delay:4.40s;" />
    </g>
  </svg>
</div>
