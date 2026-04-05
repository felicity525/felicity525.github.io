---
title: music
date: 2026-04-05 21:10:00
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aplayer/dist/APlayer.min.css">

<div id="aplayer" style="margin-top: 30px;"></div>

<script src="https://cdn.jsdelivr.net/npm/aplayer/dist/APlayer.min.js"></script>

<script>
  const ap = new APlayer({
      container: document.getElementById('aplayer'),
      listFolded: false,      // 默认展开列表
      listMaxHeight: 340,     // 列表最大高度
      lrcType: 3,
      audio: [
          {
              name: 'Anti-Romantic',
              artist: 'TOMORROW X TOGETHER',
              url: '/music/Anti-Romantic.mp3',
              cover: '/music/anti_romantic_cover.jpg',
              lrc: '/music/TOMORROW X TOGETHER - Anti-Romantic.lrc'
          },
          {
              name: 'DANCING ALONE',
              artist: 'KiiiKiii',
              url: '/music/DANCING ALONE.mp3',
              cover: '/music/dancing_alone_cover.png'
          }
      ]
  });
</script>
