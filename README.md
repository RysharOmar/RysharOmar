## Hi there 👋
<svg width="580" height="290" viewBox="0 0 580 290" xmlns="http://www.w3.org/2000/svg">
  <style>
    text { font-family: 'SF Mono', 'Fira Code', 'Courier New', monospace; }
  </style>

  <!-- Fondo terminal -->
  <rect width="580" height="290" rx="10" fill="#0D1117" stroke="#21262D" stroke-width="1.5"/>

  <!-- Barra de título -->
  <rect width="580" height="36" rx="10" fill="#161B22"/>
  <rect y="26" width="580" height="10" fill="#161B22"/>
  <circle cx="20" cy="18" r="6" fill="#FF5F57"/>
  <circle cx="40" cy="18" r="6" fill="#FEBC2E"/>
  <circle cx="60" cy="18" r="6" fill="#28C840"/>
  <text x="290" y="22" text-anchor="middle" font-size="11" fill="#484F58">ryshar@secops — zsh — 142×48</text>

  <!-- Línea 1: Comando -->
  <text x="20" y="64" font-size="12.5" fill="#3FB950" opacity="0">
    $ secure-deploy --target=production --audit=full --zero-trust
    <animate attributeName="opacity" from="0" to="1" begin="0.3s" dur="0.15s" fill="freeze"/>
  </text>

  <!-- Línea 2: Escaneo -->
  <text x="20" y="90" font-size="12" fill="#8B949E" opacity="0">
    [SCAN] Mapping attack surface — 847 endpoints detected...
    <animate attributeName="opacity" from="0" to="1" begin="1.3s" dur="0.15s" fill="freeze"/>
  </text>

  <!-- Línea 3: Cero vulnerabilidades -->
  <text x="20" y="116" font-size="12" fill="#3FB950" font-weight="bold" opacity="0">
    ✓ Zero critical vulnerabilities — attack surface: minimal
    <animate attributeName="opacity" from="0" to="1" begin="2.3s" dur="0.15s" fill="freeze"/>
  </text>

  <!-- Línea 4: Deploy -->
  <text x="20" y="142" font-size="12" fill="#8B949E" opacity="0">
    [DEPLOY] Provisioning resilient architecture...
    <animate attributeName="opacity" from="0" to="1" begin="3.1s" dur="0.15s" fill="freeze"/>
  </text>

  <!-- Barra de progreso -->
  <rect x="20" y="152" width="540" height="3" rx="1.5" fill="#21262D" opacity="0">
    <animate attributeName="opacity" from="0" to="1" begin="3.2s" dur="0.1s" fill="freeze"/>
  </rect>
  <rect x="20" y="152" width="0" height="3" rx="1.5" fill="#EF4444" opacity="0">
    <animate attributeName="opacity" from="0" to="1" begin="3.2s" dur="0.1s" fill="freeze"/>
    <animate attributeName="width" from="0" to="540" begin="3.2s" dur="1.8s" fill="freeze" calcMode="spline" keySplines="0.25 0.1 0.25 1"/>
  </rect>

  <!-- Línea 5: Failover -->
  <text x="20" y="178" font-size="12" fill="#3FB950" opacity="0">
    ✓ Active failover — E2E encryption verified
    <animate attributeName="opacity" from="0" to="1" begin="5.2s" dur="0.15s" fill="freeze"/>
  </text>

  <!-- Línea 6: Balanceo -->
  <text x="20" y="204" font-size="12" fill="#3FB950" opacity="0">
    ✓ Load balancers online — avg latency: 11ms — HA cluster: healthy
    <animate attributeName="opacity" from="0" to="1" begin="5.9s" dur="0.15s" fill="freeze"/>
  </text>

  <!-- Línea 7: Legacy -->
  <text x="20" y="230" font-size="12" fill="#3FB950" opacity="0">
    ✓ Legacy DB bridge — zero exposed credentials — rotation: active
    <animate attributeName="opacity" from="0" to="1" begin="6.6s" dur="0.15s" fill="freeze"/>
  </text>

  <!-- Separador -->
  <line x1="20" y1="248" x2="560" y2="248" stroke="#21262D" stroke-width="1" opacity="0">
    <animate attributeName="opacity" from="0" to="1" begin="7.3s" dur="0.15s" fill="freeze"/>
  </line>

  <!-- Status final -->
  <text x="290" y="274" text-anchor="middle" font-size="14" font-weight="bold" fill="#EF4444" letter-spacing="3" opacity="0">
    ● OPERATIONAL — THREAT LEVEL: 0
    <animate attributeName="opacity" from="0" to="1" begin="7.6s" dur="0.4s" fill="freeze"/>
  </text>

  <!-- Cursor parpadeo -->
  <rect x="20" y="282" width="8" height="3" rx="1" fill="#EF4444">
    <animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;0.45;0.5;0.95;1" dur="1.1s" begin="8s" repeatCount="indefinite"/>
  </rect>
</svg>
<!--
**RysharOmar/RysharOmar** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
