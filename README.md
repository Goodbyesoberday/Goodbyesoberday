- 👋 Hi, I’m @Goodbyesoberday
- 👀 I’m interested in death metal, nintendo and mind altering substances
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ... don't 
- 😄 Pronouns: ... adult male human
- ⚡ Fun fact: ...

<!---
Goodbyesoberday/Goodbyesoberday is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<svg viewBox="0 0 450 140" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="shieldGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#8b5cf6;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#7c3aed;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#6d28d9;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="aiGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#06b6d4;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0891b2;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="textGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#06b6d4;stop-opacity:1" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge> 
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="textShadow">
      <feDropShadow dx="1" dy="1" stdDeviation="1" flood-color="#00000020"/>
    </filter>
  </defs>
  
  <!-- Animated background particles -->
  <g opacity="0.1">
    <circle cx="50" cy="30" r="1" fill="#8b5cf6">
      <animate attributeName="cy" values="30;25;30" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="380" cy="50" r="1.5" fill="#06b6d4">
      <animate attributeName="cy" values="50;45;50" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="200" cy="20" r="1" fill="#3b82f6">
      <animate attributeName="cy" values="20;15;20" dur="2.5s" repeatCount="indefinite"/>
    </circle>
  </g>
  
  <!-- Enhanced Shield Symbol -->
  <g transform="translate(15, 25)">
    <!-- Outer glow ring -->
    <circle cx="40" cy="40" r="35" fill="none" stroke="url(#shieldGradient)" stroke-width="1" opacity="0.3">
      <animate attributeName="stroke-opacity" values="0.3;0.6;0.3" dur="2s" repeatCount="indefinite"/>
    </circle>
    
    <!-- Main shield -->
    <path d="M30 10 L30 5 C30 2 32 0 35 0 L45 0 C48 0 50 2 50 5 L50 10 L55 15 L55 45 C55 55 45 65 40 70 C35 65 25 55 25 45 L25 15 Z" 
          fill="url(#shieldGradient)" stroke="#6d28d9" stroke-width="2" filter="url(#glow)"/>
    
    <!-- Enhanced AI Circuit Pattern -->
    <g transform="translate(32, 20)">
      <circle cx="8" cy="8" r="2.5" fill="#ffffff" opacity="0.95">
        <animate attributeName="opacity" values="0.95;0.7;0.95" dur="1.5s" repeatCount="indefinite"/>
      </circle>
      <circle cx="16" cy="8" r="2.5" fill="#ffffff" opacity="0.95">
        <animate attributeName="opacity" values="0.7;0.95;0.7" dur="1.5s" repeatCount="indefinite"/>
      </circle>
      <circle cx="8" cy="16" r="2.5" fill="#ffffff" opacity="0.95">
        <animate attributeName="opacity" values="0.95;0.7;0.95" dur="1.5s" repeatCount="indefinite" begin="0.5s"/>
      </circle>
      <circle cx="16" cy="16" r="2.5" fill="#ffffff" opacity="0.95">
        <animate attributeName="opacity" values="0.7;0.95;0.7" dur="1.5s" repeatCount="indefinite" begin="0.5s"/>
      </circle>
      
      <!-- Animated connection lines -->
      <line x1="8" y1="8" x2="16" y2="8" stroke="#00d4ff" stroke-width="2" opacity="0.8">
        <animate attributeName="stroke-opacity" values="0.8;0.3;0.8" dur="2s" repeatCount="indefinite"/>
      </line>
      <line x1="8" y1="8" x2="8" y2="16" stroke="#00d4ff" stroke-width="2" opacity="0.8">
        <animate attributeName="stroke-opacity" values="0.3;0.8;0.3" dur="2s" repeatCount="indefinite" begin="0.5s"/>
      </line>
      <line x1="16" y1="8" x2="16" y2="16" stroke="#00d4ff" stroke-width="2" opacity="0.8">
        <animate attributeName="stroke-opacity" values="0.8;0.3;0.8" dur="2s" repeatCount="indefinite" begin="1s"/>
      </line>
      <line x1="8" y1="16" x2="16" y2="16" stroke="#00d4ff" stroke-width="2" opacity="0.8">
        <animate attributeName="stroke-opacity" values="0.3;0.8;0.3" dur="2s" repeatCount="indefinite" begin="1.5s"/>
      </line>
    </g>
    
    <!-- Enhanced checkmark with animation -->
    <path d="M35 35 L38 38 L45 28" stroke="#00ff88" stroke-width="4" fill="none" stroke-linecap="round" stroke-linejoin="round" opacity="0">
      <animate attributeName="opacity" values="0;1;1;0" dur="3s" repeatCount="indefinite" begin="1s"/>
      <animate attributeName="stroke-dasharray" values="0 20;20 0;20 0;0 20" dur="3s" repeatCount="indefinite" begin="1s"/>
    </path>
  </g>
  
  <!-- Enhanced Company Name with gradient -->
  <text x="95" y="45" font-family="Arial, sans-serif" font-size="22" font-weight="bold" fill="url(#textGradient)" filter="url(#textShadow)">
    Khlysty AI
  </text>
  
  <!-- Stylized Global Safety Text -->
  <g transform="translate(95, 65)">
    <text x="0" y="0" font-family="Arial, sans-serif" font-size="11" font-weight="600" fill="#6b7280" letter-spacing="2px">
      GLOBAL
    </text>
    <text x="55" y="0" font-family="Arial, sans-serif" font-size="11" font-weight="600" fill="#8b5cf6" letter-spacing="2px">
      SAFETY
    </text>
    <!-- Underline animation -->
    <line x1="0" y1="5" x2="0" y2="5" stroke="#8b5cf6" stroke-width="2">
      <animate attributeName="x2" values="0;90;90;0" dur="4s" repeatCount="indefinite"/>
    </line>
  </g>
  
  <!-- Enhanced AI Network -->
  <g transform="translate(250, 35)">
    <circle cx="0" cy="0" r="4" fill="url(#aiGradient)" filter="url(#glow)">
      <animate attributeName="r" values="4;6;4" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="20" cy="-8" r="3" fill="url(#aiGradient)" opacity="0.9">
      <animate attributeName="r" values="3;5;3" dur="2.5s" repeatCount="indefinite" begin="0.5s"/>
    </circle>
    <circle cx="35" cy="8" r="3" fill="url(#aiGradient)" opacity="0.9">
      <animate attributeName="r" values="3;5;3" dur="2.2s" repeatCount="indefinite" begin="1s"/>
    </circle>
    <circle cx="15" cy="18" r="3" fill="url(#aiGradient)" opacity="0.9">
      <animate attributeName="r" values="3;5;3" dur="2.8s" repeatCount="indefinite" begin="1.5s"/>
    </circle>
    
    <!-- Pulsing connection lines -->
    <line x1="0" y1="0" x2="20" y2="-8" stroke="#06b6d4" stroke-width="2" opacity="0.7">
      <animate attributeName="stroke-opacity" values="0.7;0.2;0.7" dur="1.5s" repeatCount="indefinite"/>
    </line>
    <line x1="0" y1="0" x2="35" y2="8" stroke="#06b6d4" stroke-width="2" opacity="0.7">
      <animate attributeName="stroke-opacity" values="0.2;0.7;0.2" dur="1.5s" repeatCount="indefinite" begin="0.5s"/>
    </line>
    <line x1="0" y1="0" x2="15" y2="18" stroke="#06b6d4" stroke-width="2" opacity="0.7">
      <animate attributeName="stroke-opacity" values="0.7;0.2;0.7" dur="1.5s" repeatCount="indefinite" begin="1s"/>
    </line>
  </g>
  
  <!-- Enhanced Globe with rotation -->
  <g transform="translate(360, 50)">
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0 20 0;360 20 0" dur="20s" repeatCount="indefinite"/>
      <circle cx="20" cy="0" r="22" fill="none" stroke="#e5e7eb" stroke-width="1.5" opacity="0.6"/>
      <ellipse cx="20" cy="0" rx="22" ry="11" fill="none" stroke="#06b6d4" stroke-width="1" opacity="0.4"/>
      <ellipse cx="20" cy="0" rx="11" ry="22" fill="none" stroke="#8b5cf6" stroke-width="1" opacity="0.4"/>
      <line x1="-2" y1="0" x2="42" y2="0" stroke="#e5e7eb" stroke-width="1" opacity="0.6"/>
    </g>
    
    <!-- Orbiting dots -->
    <circle cx="42" cy="0" r="2" fill="#06b6d4" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" values="0 20 0;360 20 0" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="20" cy="-22" r="1.5" fill="#8b5cf6" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" values="0 20 0;-360 20 0" dur="12s" repeatCount="indefinite"/>
    </circle>
  </g>
  
  <!-- Subtle corner accent -->
  <path d="M420 10 L430 10 L430 20" stroke="url(#aiGradient)" stroke-width="2" fill="none" opacity="0.5"/>
  <path d="M10 120 L20 120 L20 110" stroke="url(#shieldGradient)" stroke-width="2" fill="none" opacity="0.5"/>
</svg>