```aura width=860 height=200 link="https://github.com/elcinco55"
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter',
  position: 'relative', overflow: 'hidden', borderRadius: 16,
  border: '1px solid rgba(110,80,220,0.18)'
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
        <stop offset="0%" stopColor="rgba(110,20,210,0.72)" />
        <stop offset="40%" stopColor="rgba(90,15,180,0.35)" />
        <stop offset="70%" stopColor="rgba(90,15,180,0)" />
      </radialGradient>
      <radialGradient id="g2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(40,60,255,0.6)" />
        <stop offset="45%" stopColor="rgba(30,50,200,0.25)" />
        <stop offset="70%" stopColor="rgba(30,50,200,0)" />
      </radialGradient>
      <radialGradient id="g3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,173,216,0.45)" />
        <stop offset="50%" stopColor="rgba(0,120,180,0.18)" />
        <stop offset="70%" stopColor="rgba(0,120,180,0)" />
      </radialGradient>
      <radialGradient id="g4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,190,230,0.32)" />
        <stop offset="70%" stopColor="rgba(0,190,230,0)" />
      </radialGradient>
      <radialGradient id="g5" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(160,30,255,0.55)" />
        <stop offset="45%" stopColor="rgba(130,20,220,0.22)" />
        <stop offset="70%" stopColor="rgba(130,20,220,0)" />
      </radialGradient>
      <radialGradient id="g6" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(20,60,255,0.42)" />
        <stop offset="50%" stopColor="rgba(10,40,200,0.16)" />
        <stop offset="70%" stopColor="rgba(10,40,200,0)" />
      </radialGradient>
    </defs>

    <ellipse id="glow-1" cx="180" cy="185" rx="260" ry="190" fill="url(#g1)" />
    <ellipse id="glow-2" cx="300" cy="195" rx="220" ry="160" fill="url(#g2)" />
    <ellipse id="glow-3" cx="420" cy="195" rx="180" ry="140" fill="url(#g3)" />
    <ellipse id="glow-4" cx="550" cy="200" rx="150" ry="120" fill="url(#g4)" />
    <ellipse id="glow-5" cx="300" cy="195" rx="180" ry="140" fill="url(#g5)" />
    <ellipse id="glow-6" cx="490" cy="185" rx="220" ry="170" fill="url(#g6)" />
  </svg>

  <div style={{
    position: 'absolute', left: 48, top: 52, width: 96, height: 96,
    borderRadius: 48, background: 'linear-gradient(135deg, #6622ee, #00ADD8)',
    display: 'flex', alignItems: 'center', justifyContent: 'center',
  }}>
    <img src=".github/img/avatar.png" width={88} height={88} style={{ borderRadius: 44 }} />
  </div>

  <div style={{ display:'flex', flexDirection:'column', marginLeft:168, gap:8 }}>
    <div style={{ display:'flex', fontSize:38, fontWeight:700, color:'#ffffff', letterSpacing:'-1px', lineHeight:1 }}>
      Vitor Tavares
    </div>
    <div style={{ display:'flex', fontSize:15, color:'rgba(180,165,255,0.85)', letterSpacing:'0.3px' }}>
      Full-stack dev @ Powerbizz.ai — cybersecurity @ PUC Campinas
    </div>
    <div style={{ display:'flex', gap:8, marginTop:6, flexWrap:'wrap' }}>
      {['Go', 'Pentesting', 'Open source', 'BlackArch'].map(function(tag, i) {
        return (
          <div key={tag + '-' + i} style={{
            display:'flex', padding:'4px 12px', borderRadius:20,
            background:'rgba(80,40,220,0.18)', border:'1px solid rgba(100,70,240,0.32)',
            color:'rgba(205,195,255,0.9)', fontSize:12, fontWeight:700,
          }}>{tag}</div>
        );
      })}
    </div>
  </div>
</div>
```

<p align="center">
I build things end to end — Go is my main language, but I use whatever gets the job done.<br />
Always breaking something to understand how it works.
</p>

```aura width=860 height=238
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', flexDirection: 'column', fontFamily: 'Inter',
  borderRadius: 16, border: '1px solid rgba(110,80,220,0.18)',
  padding: 28, boxSizing: 'border-box', gap: 14,
}}>
  <div style={{ display:'flex', fontSize:13, fontWeight:700, color:'rgba(180,165,255,0.7)', letterSpacing:'2px' }}>
    TECH I WORK WITH
  </div>

  {[
    { label: 'Languages',  items: [['Go','#00ADD8'],['PHP','#777BB4'],['Java','#ED8B00'],['C','#00599C'],['Lua','#2C2D72'],['Ruby','#CC342D']] },
    { label: 'Frameworks', items: [['Laravel','#FF2D20'],['Spring Boot','#6DB33F'],['Gin','#00ADD8']] },
    { label: 'Databases',  items: [['PostgreSQL','#316192'],['MySQL','#4479A1'],['MariaDB','#C0765A'],['SQLite','#3AA3DC']] },
    { label: 'Infra',      items: [['Docker','#2496ED'],['Kubernetes','#326CE5'],['AWS','#FF9900']] },
  ].map(function(row, r) {
    return (
      <div key={row.label} style={{ display:'flex', flexDirection:'row', alignItems:'center', gap:14 }}>
        <div style={{ display:'flex', width:96, fontSize:12, fontWeight:700, color:'rgba(150,140,200,0.75)' }}>
          {row.label}
        </div>
        <div style={{ display:'flex', flexDirection:'row', gap:7, flexWrap:'wrap' }}>
          {row.items.map(function(it, i) {
            return (
              <div key={it[0]} style={{
                display:'flex', flexDirection:'row', alignItems:'center', gap:6,
                padding:'5px 11px', borderRadius:8,
                background:'rgba(255,255,255,0.04)', border:'1px solid rgba(120,90,240,0.22)',
              }}>
                <div style={{ display:'flex', width:7, height:7, borderRadius:4, background:it[1] }} />
                <div style={{ display:'flex', fontSize:12, fontWeight:700, color:'rgba(228,224,255,0.92)' }}>{it[0]}</div>
              </div>
            );
          })}
        </div>
      </div>
    );
  })}
</div>
```

```aura width=200 height=44 link="https://www.linkedin.com/in/vitor-tavares-398481331/" inline align=center
<div style={{
  width:'100%', height:'100%', display:'flex', alignItems:'center', justifyContent:'center',
  fontFamily:'Inter', background:'#08080c', borderRadius:22,
  border:'1px solid rgba(120,90,240,0.35)',
}}>
  <div style={{ display:'flex', flexDirection:'row', alignItems:'center', gap:8 }}>
    <div style={{ display:'flex', width:8, height:8, borderRadius:4, background:'#0A66C2' }} />
    <div style={{ display:'flex', fontSize:13, fontWeight:700, color:'#f0eeff' }}>LinkedIn</div>
  </div>
</div>
```

```aura width=260 height=44 link="mailto:vitor.tavares.leite@gmail.com" inline align=center
<div style={{
  width:'100%', height:'100%', display:'flex', alignItems:'center', justifyContent:'center',
  fontFamily:'Inter', background:'#08080c', borderRadius:22,
  border:'1px solid rgba(120,90,240,0.35)',
}}>
  <div style={{ display:'flex', flexDirection:'row', alignItems:'center', gap:8 }}>
    <div style={{ display:'flex', width:8, height:8, borderRadius:4, background:'#00ADD8' }} />
    <div style={{ display:'flex', fontSize:13, fontWeight:700, color:'#f0eeff' }}>vitor.tavares.leite@gmail.com</div>
  </div>
</div>
```

```aura width=200 height=44 inline align=center
<div style={{
  width:'100%', height:'100%', display:'flex', alignItems:'center', justifyContent:'center',
  fontFamily:'Inter', background:'#08080c', borderRadius:22,
  border:'1px solid rgba(120,90,240,0.35)',
}}>
  <div style={{ display:'flex', flexDirection:'row', alignItems:'center', gap:8 }}>
    <div style={{ display:'flex', width:8, height:8, borderRadius:4, background:'#5865F2' }} />
    <div style={{ display:'flex', fontSize:13, fontWeight:700, color:'#f0eeff' }}>cincao_</div>
  </div>
</div>
```
