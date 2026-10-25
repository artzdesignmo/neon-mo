# openx-mo card — Neon Mo (wire AFTER repo push + Pages live)

Add to the PROJECTS array in the openx-mo web artifact (via the artifact builder flow),
replacing the next placeholder card. Do NOT push until https://artzdesignmo.github.io/neon-mo/ is live.

```js
{
  id: 'neon-mo', state: 'live', cover: 'cover-proj',
  title: { en: 'Neon Mo', zh: 'Neon Mo' },
  sub: { en: 'A neon sign studio that glows as you type', zh: '打字即發光嘅霓虹燈招牌工作室' },
  desc: { en: 'Type text and watch it glow on a brick wall: 6 tube fonts, 10 neon colours, 3 tube styles, Steady / Pulse / Flicker animation, 6 presets, Shuffle, PNG export. Fully offline, single HTML file.', zh: '打字即喺磚牆上發光：6 款燈管字體、10 種霓虹顏色、3 款燈管、恆亮／呼吸／閃爍動畫、6 個預設、隨機掣、PNG 匯出。完全離線，單一 HTML。' },
  demo: 'https://artzdesignmo.github.io/neon-mo/',
  github: 'https://github.com/artzdesignmo/neon-mo',
  art: '<svg class="cover-art" viewBox="0 0 400 310" preserveAspectRatio="xMidYMid slice" aria-hidden="true"><rect width="400" height="310" fill="#1c1512"/><rect x="0" y="0" width="400" height="310" fill="none" stroke="#000" stroke-opacity=".3"/><text x="200" y="150" text-anchor="middle" font-family="cursive" font-size="64" fill="none" stroke="#ff2e88" stroke-width="2">OPEN</text><text x="200" y="200" text-anchor="middle" font-family="cursive" font-size="28" fill="none" stroke="#00e5ff" stroke-width="1.5">all night</text></svg><div class="proj-tag">6 fonts · 10 colours · PNG</div><div class="proj-week">Project 21</div>'
}
```

Card order rule: Neon Mo replaces the next placeholder/soon card in sequence (not appended at the end).
After pushing the artifact change, push index.html to `artzdesignmo/openx-mo` and verify
https://openx-mo.vercel.app shows the new card.
