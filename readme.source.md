```aura width=860 height=200
<div style={{
  width: 860, height: 200,
  background: 'linear-gradient(135deg, #0d0d14 0%, #111827 50%, #0d1117 100%)',
  display: 'flex', flexDirection: 'column', justifyContent: 'center',
  padding: '0 40px', position: 'relative', overflow: 'hidden',
  fontFamily: 'monospace',
}}>
  <div style={{
    position: 'absolute', left: 30, top: 20, bottom: 20,
    width: 3, borderRadius: 2,
    background: 'linear-gradient(180deg, #00ffb4, #7c3aed, #00b4ff)',
  }} />

  <div style={{ display: 'flex', flexDirection: 'column', paddingLeft: 22 }}>
    <span style={{ color: '#00ffb4', fontSize: 13, letterSpacing: 4, marginBottom: 8, opacity: 0.8 }}>
      ~/0LucasMatheus $
    </span>
    <span style={{ fontSize: 38, fontWeight: 700, color: '#e2e8f0', letterSpacing: 1 }}>
      Lucas Matheus
    </span>
    <span style={{ color: '#94a3b8', fontSize: 15, marginTop: 8, letterSpacing: 1 }}>
      Software Engineering Student · Linux · IoT · DevOps
    </span>
  </div>

  <div style={{
    position: 'absolute', right: 40, top: 30,
    color: '#00ffb4', fontSize: 11, opacity: 0.4, letterSpacing: 2,
    display: 'flex',
  }}>
    [connected]
  </div>
</div>
```

```aura width=860 height=260
<div style={{
  width: 860, height: 260,
  background: '#0d1117',
  display: 'flex',
  fontFamily: 'monospace',
}}>
  <div style={{
    flex: 1, padding: '28px 30px',
    borderRight: '1px solid rgba(0,255,180,0.1)',
    display: 'flex', flexDirection: 'column',
  }}>
    <div style={{ color: '#00ffb4', fontSize: 11, letterSpacing: 3, marginBottom: 18, opacity: 0.7, display: 'flex' }}>
      ▸ WORKING_ON
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', gap: 14 }}>
      {[
        { icon: '🏥', text: 'Automação de sistemas clínicos' },
        { icon: '🐠', text: 'Sistema IoT de aquário inteligente' },
        { icon: '🖥️', text: 'Home server com Orange Pi' },
      ].map((item, i) => (
        <div key={i} style={{ display: 'flex', alignItems: 'center', gap: 10 }}>
          <span style={{ fontSize: 16 }}>{item.icon}</span>
          <span style={{ color: '#cbd5e1', fontSize: 13 }}>{item.text}</span>
        </div>
      ))}
    </div>
  </div>

  <div style={{ flex: 1, padding: '28px 30px', display: 'flex', flexDirection: 'column' }}>
    <div style={{ color: '#818cf8', fontSize: 11, letterSpacing: 3, marginBottom: 16, opacity: 0.7, display: 'flex' }}>
      ▸ STUDYING
    </div>
    <div style={{ display: 'flex', flexWrap: 'wrap', gap: 8 }}>
      {[
        { label: 'DevOps', color: '#00ffb4' },
        { label: 'CI/CD', color: '#818cf8' },
        { label: 'Linux', color: '#fbbf24' },
        { label: 'Nix', color: '#60a5fa' },
        { label: 'Docker', color: '#38bdf8' },
        { label: 'Embarcados', color: '#f472b6' },
        { label: 'Redes', color: '#34d399' },
      ].map((s, i) => (
        <div key={i} style={{
          padding: '5px 12px', borderRadius: 4,
          border: '1px solid ' + s.color + '44',
          background: s.color + '11',
          color: s.color,
          fontSize: 12, letterSpacing: 1,
          display: 'flex',
        }}>
          {s.label}
        </div>
      ))}
    </div>
    <div style={{ marginTop: 18, paddingTop: 14, borderTop: '1px solid rgba(255,255,255,0.05)', display: 'flex', flexDirection: 'column', gap: 6 }}>
      <div style={{ color: '#64748b', fontSize: 11, letterSpacing: 2, display: 'flex' }}>▸ ASK_ME_ABOUT</div>
      <div style={{ color: '#94a3b8', fontSize: 13, display: 'flex' }}>
        🐧 Linux · 🐍 Python · 📡 IoT · 📟 Embarcados
      </div>
    </div>
  </div>
</div>
```

```aura width=860 height=100
<div style={{
  width: 860, height: 100,
  background: '#0d1117',
  display: 'flex', flexDirection: 'column', justifyContent: 'center',
  padding: '0 30px',
  fontFamily: 'monospace',
  borderTop: '1px solid rgba(0,255,180,0.08)',
}}>
  <div style={{ color: '#64748b', fontSize: 10, letterSpacing: 3, marginBottom: 12, display: 'flex' }}>
    ▸ TECH_STACK
  </div>
  <div style={{ display: 'flex', flexWrap: 'wrap', gap: 8 }}>
    {[
      { name: 'Python', color: '#fbbf24' },
      { name: 'Java', color: '#f97316' },
      { name: 'JavaScript', color: '#facc15' },
      { name: 'React', color: '#38bdf8' },
      { name: 'Spring', color: '#4ade80' },
      { name: 'Flask', color: '#a78bfa' },
      { name: 'Flutter', color: '#22d3ee' },
      { name: 'Docker', color: '#60a5fa' },
      { name: 'Linux', color: '#00ffb4' },
      { name: 'Arduino', color: '#34d399' },
      { name: 'MySQL', color: '#fb923c' },
      { name: 'MongoDB', color: '#4ade80' },
      { name: 'Git', color: '#f87171' },
    ].map((t, i) => (
      <div key={i} style={{
        padding: '3px 10px', borderRadius: 3,
        background: t.color + '15',
        border: '1px solid ' + t.color + '33',
        color: t.color, fontSize: 12,
        display: 'flex',
      }}>
        {t.name}
      </div>
    ))}
  </div>
</div>
```

```aura width=860 height=80
<div style={{
  width: 860, height: 80,
  background: 'linear-gradient(135deg, #0d1117 0%, #0d0d14 100%)',
  display: 'flex', alignItems: 'center',
  padding: '0 30px', gap: 50,
  fontFamily: 'monospace',
  borderTop: '1px solid rgba(129,140,248,0.12)',
}}>
  {[
    { label: 'github', value: '0LucasMatheus', color: '#e2e8f0' },
    { label: 'linkedin', value: '0lucasmatheus', color: '#60a5fa' },
    { label: 'leetcode', value: '0lucasmatheus', color: '#fbbf24' },
    { label: 'email', value: '0lucasmatheus5305@gmail.com', color: '#f472b6' },
  ].map((l, i) => (
    <div key={i} style={{ display: 'flex', flexDirection: 'column', gap: 4 }}>
      <span style={{ color: '#475569', fontSize: 10, letterSpacing: 2 }}>{l.label}</span>
      <span style={{ color: l.color, fontSize: 12 }}>{l.value}</span>
    </div>
  ))}
</div>
```

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=0LucasMatheus&show_icons=true&theme=transparent&hide_border=true&title_color=00ffb4&icon_color=818cf8&text_color=94a3b8&bg_color=0d1117)
&nbsp;&nbsp;
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=0LucasMatheus&layout=compact&theme=transparent&hide_border=true&title_color=00ffb4&text_color=94a3b8&bg_color=0d1117)

</div>
