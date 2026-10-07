<svg xmlns="http://www.w3.org/2000/svg" width="900" height="160" viewBox="0 0 900 160">
  <defs>
    <linearGradient id="rgb" x1="0" y1="0" x2="900" y2="0" gradientUnits="userSpaceOnUse" spreadMethod="repeat">
      <stop offset="0%" stop-color="#ff0040"/>
      <stop offset="16%" stop-color="#ff8c00"/>
      <stop offset="33%" stop-color="#ffee00"/>
      <stop offset="50%" stop-color="#00ff6a"/>
      <stop offset="66%" stop-color="#00c8ff"/>
      <stop offset="83%" stop-color="#8a2be2"/>
      <stop offset="100%" stop-color="#ff0040"/>
      <animateTransform attributeName="gradientTransform" type="translate" from="0 0" to="900 0" dur="3s" repeatCount="indefinite"/>
    </linearGradient>
    <filter id="glow" x="-20%" y="-50%" width="140%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <text x="50%" y="48%" text-anchor="middle" dominant-baseline="middle" font-family="Segoe UI, Verdana, Arial, sans-serif" font-size="72" font-weight="800" letter-spacing="4" fill="url(#rgb)" stroke="#000" stroke-width="3" paint-order="stroke" filter="url(#glow)">Nguyen Khoa 12</text>
  <rect x="150" y="122" width="600" height="6" rx="3" fill="url(#rgb)" stroke="#000" stroke-width="1.5" filter="url(#glow)"/>
</svg>
