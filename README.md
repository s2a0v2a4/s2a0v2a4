<svg xmlns="http://www.w3.org/2000/svg" width="1000" height="300" viewBox="0 0 1000 300">
<defs>
<linearGradient id="txt" x1="0" x2="1"><stop offset="0" stop-color="#00F5D4"/><stop offset=".5" stop-color="#BD5BFF"/><stop offset="1" stop-color="#FF286B"/></linearGradient>
<radialGradient id="o1"><stop offset="0" stop-color="#00DDB3" stop-opacity=".35"/><stop offset="1" stop-color="#00DDB3" stop-opacity="0"/></radialGradient>
<radialGradient id="o2"><stop offset="0" stop-color="#FF286B" stop-opacity=".3"/><stop offset="1" stop-color="#FF286B" stop-opacity="0"/></radialGradient>
<linearGradient id="scan" x1="0" x2="0" y1="0" y2="1"><stop offset="0" stop-color="#00F5D4" stop-opacity="0"/><stop offset=".5" stop-color="#00F5D4" stop-opacity=".22"/><stop offset="1" stop-color="#00F5D4" stop-opacity="0"/></linearGradient>
<pattern id="grid" width="28" height="28" patternUnits="userSpaceOnUse"><path d="M28 0H0V28" fill="none" stroke="#00F5D4" stroke-opacity=".07"/></pattern>
<pattern id="lines" width="4" height="4" patternUnits="userSpaceOnUse"><rect width="4" height="1" fill="#000" fill-opacity=".25"/></pattern>
<filter id="glow" x="-20%" y="-50%" width="140%" height="200%"><feGaussianBlur stdDeviation="10"/></filter>
<clipPath id="r"><rect width="1000" height="300" rx="16"/></clipPath>
</defs>
<style>
.f{font-family:'Segoe UI','Helvetica Neue',Arial,sans-serif;font-weight:900}
.m{font-family:'JetBrains Mono',Consolas,'Courier New',monospace}
.in{opacity:0;animation:in .9s cubic-bezier(.2,.8,.2,1) forwards}
@keyframes in{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:none}}
.g1{animation:g1 4s steps(1) infinite}
.g2{animation:g2 4s steps(1) infinite}
@keyframes g1{0%,86%,100%{transform:none;opacity:0}87%{transform:translate(-6px,2px);opacity:.85}89%{transform:translate(4px,-2px);opacity:.85}91%{transform:translate(-3px,0);opacity:.6}93%{opacity:0}}
@keyframes g2{0%,86%,100%{transform:none;opacity:0}87%{transform:translate(6px,-2px);opacity:.85}89%{transform:translate(-4px,2px);opacity:.85}91%{transform:translate(3px,0);opacity:.6}93%{opacity:0}}
.s{animation:sw 5s linear infinite}
@keyframes sw{from{transform:translateY(-90px)}to{transform:translateY(320px)}}
.pulse{animation:p 2.4s ease-in-out infinite}
@keyframes p{0%,100%{opacity:.35}50%{opacity:.8}}
.blink{animation:b 1s steps(1) infinite}
@keyframes b{50%{opacity:0}}
.orb{animation:fl 9s ease-in-out infinite alternate}
@keyframes fl{to{transform:translate(40px,-20px)}}
</style>

<g clip-path="url(#r)">
<rect width="1000" height="300" fill="#0D1117"/>
<rect width="1000" height="300" fill="url(#grid)"/>
<ellipse class="orb" cx="170" cy="70" rx="330" ry="200" fill="url(#o1)"/>
<ellipse class="orb" cx="860" cy="250" rx="330" ry="200" fill="url(#o2)" style="animation-direction:alternate-reverse"/>

<!-- HUD corners -->
<g stroke="#00F5D4" stroke-width="2" fill="none" opacity=".7">
<path d="M24 54V24h30"/><path d="M976 54V24h-30"/><path d="M24 246v30h30"/><path d="M976 246v30h-30"/>
</g>

<!-- top / bottom terminal labels -->
<text x="64" y="40" class="m in" font-size="12" fill="#8B949E" letter-spacing="2">[ SYS://SECURE ]  <tspan fill="#00F5D4">● ONLINE</tspan></text>
<text x="936" y="40" class="m in" font-size="12" fill="#8B949E" text-anchor="end" letter-spacing="2">s2a0v2a4@berlin</text>
<text x="64" y="270" class="m in" font-size="12" fill="#8B949E" letter-spacing="2">0x5EC · TLS 1.3 · AES-256</text>
<text x="936" y="270" class="m in" font-size="12" fill="#8B949E" text-anchor="end" letter-spacing="2">&gt;_ <tspan class="blink" fill="#FF286B">█</tspan></text>

<!-- title with glow + glitch layers -->
<g class="in" style="animation-delay:.15s">
<text x="500" y="160" text-anchor="middle" class="f pulse" font-size="92" textLength="760" lengthAdjust="spacingAndGlyphs" fill="url(#txt)" filter="url(#glow)">CYBERSECURITY</text>
<text x="500" y="160" text-anchor="middle" class="f g1" font-size="92" textLength="760" lengthAdjust="spacingAndGlyphs" fill="#00F5D4">CYBERSECURITY</text>
<text x="500" y="160" text-anchor="middle" class="f g2" font-size="92" textLength="760" lengthAdjust="spacingAndGlyphs" fill="#FF286B">CYBERSECURITY</text>
<text x="500" y="160" text-anchor="middle" class="f" font-size="92" textLength="760" lengthAdjust="spacingAndGlyphs" fill="url(#txt)">CYBERSECURITY</text>
</g>

<!-- subtitle -->
<g class="in" style="animation-delay:.35s">
<text x="500" y="201" text-anchor="middle" class="m" font-size="15" fill="#E6EDF3" letter-spacing="5">ETHICAL HACKING <tspan fill="#BD5BFF">•</tspan> SECURITY RESEARCH</text>
</g>

<rect width="1000" height="300" fill="url(#lines)"/>
<rect class="s" width="1000" height="90" fill="url(#scan)"/>
</g>
<rect x=".5" y=".5" width="999" height="299" rx="16" fill="none" stroke="#30363D"/>
</svg>
