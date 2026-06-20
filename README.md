```aura width=800 height=200
<div style={{
  display: 'flex',
  flexDirection: 'column',
  justifyContent: 'center',
  padding: '40px 48px',
  background: 'linear-gradient(135deg, #0d0d0d 0%, #111111 100%)',
  width: '100%',
  height: '100%',
  fontFamily: 'Inter',
}}>
  <div style={{ display: 'flex', flexDirection: 'column', gap: '8px' }}>
    <span style={{ fontSize: 32, fontWeight: 700, color: '#ffffff', letterSpacing: '-0.5px' }}>
      darkiifr
    </span>
    <span style={{ fontSize: 15, color: '#888888', letterSpacing: '0.2px' }}>
      indie dev · vins studio · france
    </span>
  </div>
  <div style={{
    display: 'flex',
    gap: '8px',
    marginTop: '24px',
  }}>
    {['C#', 'SvelteKit', 'Tauri', 'Rust', 'TypeScript'].map((tech) => (
      <div key={tech} style={{
        background: '#1a1a1a',
        border: '1px solid #2a2a2a',
        borderRadius: '6px',
        padding: '4px 12px',
        fontSize: 12,
        color: '#aaaaaa',
      }}>
        {tech}
      </div>
    ))}
  </div>
</div>
```

<br/>

```aura width=800 height=130
<div style={{
  display: 'flex',
  alignItems: 'center',
  justifyContent: 'space-between',
  padding: '28px 48px',
  background: '#0d0d0d',
  width: '100%',
  height: '100%',
  fontFamily: 'Inter',
  borderTop: '1px solid #1e1e1e',
}}>
  <div style={{ display: 'flex', flexDirection: 'column', gap: '4px' }}>
    <span style={{ fontSize: 11, color: '#555555', textTransform: 'uppercase', letterSpacing: '1px' }}>projects</span>
    <span style={{ fontSize: 14, color: '#cccccc' }}>Fiip · Caltemp · DynamicWin · ITunesRPC</span>
  </div>
  <div style={{ display: 'flex', gap: '24px' }}>
    {[
      { label: 'Discord', color: '#5865F2', url: 'discord.gg/9T6BBERXTP' },
      { label: 'YouTube', color: '#FF0000', url: 'youtube.com/@UCZBAbJDBD4rLOcGJ0QUsQDg' },
      { label: 'Ko-fi', color: '#FF5E5B', url: 'ko-fi.com/darkiifr' },
    ].map(({ label, color }) => (
      <div key={label} style={{ display: 'flex', alignItems: 'center', gap: '6px' }}>
        <div style={{ width: 6, height: 6, borderRadius: '50%', background: color }} />
        <span style={{ fontSize: 13, color: '#777777' }}>{label}</span>
      </div>
    ))}
  </div>
</div>
```

<br/>

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=darkiifr&theme=shadow_blue&hide_border=true&show_icons=true&include_all_commits=false&count_private=false&hide=issues,contribs&rank_icon=github)

---

<sub>contact@vinsstudio.xyz · built with [readme-aura](https://github.com/collectioneur/readme-aura)</sub>
