```aura width=860 height=200 link="https://github.com/elcinco55"
<div style={{
  width: '100%', height: '100%', background: '#0a0a08',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter',
  position: 'relative', overflow: 'hidden', borderRadius: 16,
  border: '1px solid rgba(223,218,92,0.20)'
}}>

  <style>{`
      @keyframes float-slow {
        0%, 100% { transform: translateX(0px); opacity: 0.8; }
        50% { transform: translateX(350px); opacity: 1.2; }
      }
      @keyframes float-medium {
        0%, 100% { transform: translateX(0px); opacity: 0.7; }
        50% { transform: translateX(-250px); opacity: 1.1; }
      }
      @keyframes float-fast {
        0%, 100% { transform: translateX(0px); opacity: 0.9; }
        50% { transform: translateX(200px); opacity: 0.6; }
      }
      @keyframes float-diagonal {
        0%, 100% { transform: translateX(0px); opacity: 0.75; }
        50% { transform: translateX(300px); opacity: 1.0; }
      }
      @keyframes float-wave {
        0%, 100% { transform: translateX(0px); opacity: 0.65; }
        33% { transform: translateX(-160px); opacity: 0.9; }
        66% { transform: translateX(80px); opacity: 1.0; }
      }
      #glow-1 { animation: float-slow 8s ease-in-out infinite; }
      #glow-2 { animation: float-medium 12s ease-in-out infinite; }
      #glow-3 { animation: float-fast 9s ease-in-out infinite; }
      #glow-4 { animation: float-slow 11s ease-in-out infinite reverse; }
      #glow-5 { animation: float-diagonal 10s ease-in-out infinite; }
      #glow-6 { animation: float-wave 13s ease-in-out infinite; }
    `}</style>

  <svg width="860" height="200" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(223,218,92,0.55)" />
        <stop offset="40%" stopColor="rgba(172,166,66,0.26)" />
        <stop offset="70%" stopColor="rgba(172,166,66,0)" />
      </radialGradient>
      <radialGradient id="g2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(172,166,66,0.48)" />
        <stop offset="45%" stopColor="rgba(140,136,52,0.20)" />
        <stop offset="70%" stopColor="rgba(140,136,52,0)" />
      </radialGradient>
      <radialGradient id="g3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(206,201,74,0.40)" />
        <stop offset="50%" stopColor="rgba(160,155,58,0.16)" />
        <stop offset="70%" stopColor="rgba(160,155,58,0)" />
      </radialGradient>
      <radialGradient id="g4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(240,236,140,0.30)" />
        <stop offset="70%" stopColor="rgba(240,236,140,0)" />
      </radialGradient>
      <radialGradient id="g5" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(190,184,60,0.38)" />
        <stop offset="45%" stopColor="rgba(150,145,48,0.16)" />
        <stop offset="70%" stopColor="rgba(150,145,48,0)" />
      </radialGradient>
      <radialGradient id="g6" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(126,122,40,0.34)" />
        <stop offset="50%" stopColor="rgba(100,97,30,0.14)" />
        <stop offset="70%" stopColor="rgba(100,97,30,0)" />
      </radialGradient>
      <linearGradient id="sheen" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stopColor="rgba(255,255,255,0.055)" />
        <stop offset="45%" stopColor="rgba(255,255,255,0.012)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0.30)" />
      </linearGradient>
      <filter id="grain" x="0" y="0" width="100%" height="100%">
        <feTurbulence type="fractalNoise" baseFrequency="0.9" numOctaves="2" stitchTiles="stitch" result="noise" />
        <feColorMatrix type="saturate" values="0" />
      </filter>
      <radialGradient id="edge" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="#000000" />
        <stop offset="42%" stopColor="#000000" />
        <stop offset="63%" stopColor="#ffffff" />
        <stop offset="82%" stopColor="#000000" />
      </radialGradient>
      <mask id="glow-edge">
        <ellipse cx="330" cy="195" rx="390" ry="255" fill="url(#edge)" />
      </mask>
    </defs>

    <ellipse id="glow-1" cx="180" cy="185" rx="260" ry="190" fill="url(#g1)" />
    <ellipse id="glow-2" cx="300" cy="195" rx="220" ry="160" fill="url(#g2)" />
    <ellipse id="glow-3" cx="420" cy="195" rx="180" ry="140" fill="url(#g3)" />
    <ellipse id="glow-4" cx="550" cy="200" rx="150" ry="120" fill="url(#g4)" />
    <ellipse id="glow-5" cx="300" cy="195" rx="180" ry="140" fill="url(#g5)" />
    <ellipse id="glow-6" cx="490" cy="185" rx="220" ry="170" fill="url(#g6)" />

    <rect x="0" y="0" width="860" height="200" fill="url(#sheen)" />
    <g mask="url(#glow-edge)">
      <rect x="0" y="0" width="860" height="200" filter="url(#grain)" opacity="0.16" />
    </g>
  </svg>

  <div style={{
    position: 'absolute', left: 48, top: 52, width: 96, height: 96,
    borderRadius: 48, background: 'linear-gradient(135deg, #DFDA5C, #ACA642)',
    display: 'flex', alignItems: 'center', justifyContent: 'center',
  }}>
    <img src=".github/img/avatar.png" width={88} height={88} style={{ borderRadius: 44 }} />
  </div>

  <div style={{ display:'flex', flexDirection:'column', marginLeft:168, gap:8 }}>
    <div style={{ display:'flex', fontSize:38, fontWeight:700, color:'#ffffff', letterSpacing:'-1px', lineHeight:1 }}>
      Vitor Tavares
    </div>
    <div style={{ display:'flex', fontSize:15, color:'rgba(233,229,175,0.85)', letterSpacing:'0.3px' }}>
      Full-stack dev @ Powerbizz.ai — cybersecurity @ PUC Campinas
    </div>
    <div style={{ display:'flex', gap:8, marginTop:6, flexWrap:'wrap' }}>
      {['Go', 'Pentesting', 'Open source', 'BlackArch'].map(function(tag, i) {
        return (
          <div key={tag + '-' + i} style={{
            display:'flex', padding:'4px 12px', borderRadius:20,
            background:'rgba(172,166,66,0.16)', border:'1px solid rgba(223,218,92,0.34)',
            color:'rgba(240,236,180,0.92)', fontSize:12, fontWeight:700,
          }}>{tag}</div>
        );
      })}
    </div>
  </div>
</div>
```

<p align="center">
Go is my main language, but I use whatever gets the job done.
</p>

```aura width=860 height=238
<div style={{
  width: '100%', height: '100%', background: '#0a0a08',
  display: 'flex', flexDirection: 'column', fontFamily: 'Inter',
  borderRadius: 16, border: '1px solid rgba(223,218,92,0.20)',
  padding: 28, boxSizing: 'border-box', gap: 14,
}}>
  <div style={{ display:'flex', fontSize:13, fontWeight:700, color:'rgba(223,218,92,0.78)', letterSpacing:'2px' }}>
    TECH I WORK WITH
  </div>

  {[
    { label: 'Languages',  items: [['Go','#DFDA5C'],['PHP','#C9C34E'],['Java','#B8B144'],['C','#A69F3E'],['Lua','#948E36'],['Ruby','#847E30']] },
    { label: 'Frameworks', items: [['Laravel','#DFDA5C'],['Spring Boot','#C0BA48'],['Gin','#A29C3C']] },
    { label: 'Databases',  items: [['PostgreSQL','#DFDA5C'],['MySQL','#C0BA48'],['MariaDB','#A29C3C'],['SQLite','#8A8432']] },
    { label: 'Infra',      items: [['Docker','#DFDA5C'],['Kubernetes','#C0BA48'],['AWS','#A29C3C']] },
  ].map(function(row, r) {
    return (
      <div key={row.label} style={{ display:'flex', flexDirection:'row', alignItems:'center', gap:14 }}>
        <div style={{ display:'flex', width:96, fontSize:12, fontWeight:700, color:'rgba(196,190,130,0.75)' }}>
          {row.label}
        </div>
        <div style={{ display:'flex', flexDirection:'row', gap:7, flexWrap:'wrap' }}>
          {row.items.map(function(it, i) {
            return (
              <div key={it[0]} style={{
                display:'flex', flexDirection:'row', alignItems:'center', gap:6,
                padding:'5px 11px', borderRadius:8,
                background:'rgba(223,218,92,0.06)', border:'1px solid rgba(172,166,66,0.30)',
              }}>
                <div style={{ display:'flex', width:7, height:7, borderRadius:4, background:it[1] }} />
                <div style={{ display:'flex', fontSize:12, fontWeight:700, color:'rgba(242,239,214,0.92)' }}>{it[0]}</div>
              </div>
            );
          })}
        </div>
      </div>
    );
  })}
</div>
```

```aura width=200 height=44 link="https://www.linkedin.com/in/vitor-leite-398481331/" inline align=center
<div style={{
  width:'100%', height:'100%', display:'flex', alignItems:'center', justifyContent:'center',
  fontFamily:'Inter', background:'#0a0a08', borderRadius:22,
  border:'1px solid rgba(223,218,92,0.38)',
}}>
  <div style={{ display:'flex', flexDirection:'row', alignItems:'center', gap:8 }}>
    <div style={{ display:'flex', width:8, height:8, borderRadius:4, background:'#DFDA5C' }} />
    <div style={{ display:'flex', fontSize:13, fontWeight:700, color:'#f4f1d8' }}>LinkedIn</div>
  </div>
</div>
```

```aura width=260 height=44 link="mailto:vitor.tavares.leite@gmail.com" inline align=center
<div style={{
  width:'100%', height:'100%', display:'flex', alignItems:'center', justifyContent:'center',
  fontFamily:'Inter', background:'#0a0a08', borderRadius:22,
  border:'1px solid rgba(223,218,92,0.38)',
}}>
  <div style={{ display:'flex', flexDirection:'row', alignItems:'center', gap:8 }}>
    <div style={{ display:'flex', width:8, height:8, borderRadius:4, background:'#DFDA5C' }} />
    <div style={{ display:'flex', fontSize:13, fontWeight:700, color:'#f4f1d8' }}>vitor.tavares.leite@gmail.com</div>
  </div>
</div>
```

```aura width=200 height=44 inline align=center
<div style={{
  width:'100%', height:'100%', display:'flex', alignItems:'center', justifyContent:'center',
  fontFamily:'Inter', background:'#0a0a08', borderRadius:22,
  border:'1px solid rgba(223,218,92,0.38)',
}}>
  <div style={{ display:'flex', flexDirection:'row', alignItems:'center', gap:8 }}>
    <div style={{ display:'flex', width:8, height:8, borderRadius:4, background:'#DFDA5C' }} />
    <div style={{ display:'flex', fontSize:13, fontWeight:700, color:'#f4f1d8' }}>cincao_</div>
  </div>
</div>
```
