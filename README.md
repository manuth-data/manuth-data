<svg width="1200" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0d1220"/>
      <stop offset="50%" stop-color="#101a2e"/>
      <stop offset="100%" stop-color="#0b1120"/>
    </linearGradient>
    <linearGradient id="bars" x1="0%" y1="100%" x2="0%" y2="0%">
      <stop offset="0%" stop-color="#3b82f6" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#60a5fa" stop-opacity="0.15"/>
    </linearGradient>
    <radialGradient id="glow" cx="50%" cy="35%" r="65%">
      <stop offset="0%" stop-color="#1e40af" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#1e40af" stop-opacity="0"/>
    </radialGradient>
  </defs>

  <rect width="1200" height="300" fill="url(#bg)"/>
  <rect width="1200" height="300" fill="url(#glow)"/>

  <!-- decorative bar chart, left -->
  <g opacity="0.9">
    <rect x="40"  y="210" width="18" height="60" fill="url(#bars)"/>
    <rect x="66"  y="180" width="18" height="90" fill="url(#bars)"/>
    <rect x="92"  y="150" width="18" height="120" fill="url(#bars)"/>
    <rect x="118" y="195" width="18" height="75" fill="url(#bars)"/>
    <rect x="144" y="130" width="18" height="140" fill="url(#bars)"/>
    <rect x="170" y="165" width="18" height="105" fill="url(#bars)"/>
    <rect x="196" y="110" width="18" height="160" fill="url(#bars)"/>
  </g>

  <!-- decorative node network, right -->
  <g stroke="#3b82f6" stroke-opacity="0.45" stroke-width="1.2">
    <line x1="980" y1="70"  x2="1050" y2="110"/>
    <line x1="1050" y1="110" x2="1010" y2="170"/>
    <line x1="1050" y1="110" x2="1120" y2="90"/>
    <line x1="1010" y1="170" x2="1090" y2="200"/>
    <line x1="1120" y1="90" x2="1150" y2="150"/>
    <line x1="1090" y1="200" x2="1150" y2="150"/>
  </g>
  <g fill="#60a5fa">
    <circle cx="980" cy="70" r="4"/>
    <circle cx="1050" cy="110" r="5"/>
    <circle cx="1010" cy="170" r="4"/>
    <circle cx="1120" cy="90" r="4"/>
    <circle cx="1090" cy="200" r="4"/>
    <circle cx="1150" cy="150" r="5"/>
  </g>

  <!-- title -->
  <text x="600" y="118" text-anchor="middle" font-family="Segoe UI, Arial, sans-serif" font-size="56" font-weight="700" fill="#f5f7fa" letter-spacing="2">RA MANUTH</text>

  <!-- subtitle -->
  <text x="600" y="155" text-anchor="middle" font-family="Segoe UI, Arial, sans-serif" font-size="16" font-weight="600" fill="#7ea8f0" letter-spacing="4">DATA SCIENCE  •  MACHINE LEARNING  •  FINTECH</text>

  <!-- pill badge -->
  <rect x="410" y="190" width="380" height="42" rx="21" fill="#111a2e" stroke="#3b5a9a" stroke-width="1.2"/>
  <text x="600" y="217" text-anchor="middle" font-family="Segoe UI, Arial, sans-serif" font-size="15" fill="#c9d6f0">Turning Data into Meaningful Insights</text>
</svg>
