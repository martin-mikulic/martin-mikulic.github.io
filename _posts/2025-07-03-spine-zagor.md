---
title: "Spine Zagor WebGL Demo"
date: 2025-07-03
categories:
  - Unity Projects
tags:
  - Unity
  - WebGL
  - Game Demo
header:
  image: /assets/images/spine-zagor-header.jpg
  caption: "Playable demo built with Unity WebGL"
excerpt: "Try the Spine Zagor game in Landscape and Portrait modes directly in your browser."
---

![Gameplay Screenshot](/assets/images/spine-zagor-screenshot.jpg)

# 🦅 Zagor Spine - Live Wallpaper Showcase

Welcome to **Zagor Spine**, an experimental **live wallpaper** project inspired by the classic Italian comic hero **Zagor**.  
This project is part of my learning journey exploring **Spine 2D workflows**, Unity integration, and web deployment.

Below you can try the **Landscape Mode** immediately. The **Portrait Mode** build will only load when you choose to.
And here you can read more [View project README](https://martin-mikulic.github.io/Spine_Zagor/)

---

## 🌄 Landscape Mode

<div class="iframe-container">
  <iframe src="/Spine_Zagor/landscape/index.html" frameborder="0" allowfullscreen></iframe>
</div>

<p>
  <a href="/Spine_Zagor/landscape/index.html" target="_blank" rel="noopener">Open Landscape Full Screen</a>
</p>

---

## 📱 Portrait Mode

<p>
  <button id="loadPortrait">Load Portrait Mode</button>
</p>

<div id="portraitContainer"></div>

<p>
  <a href="/Spine_Zagor/portrait/index.html" target="_blank" rel="noopener">Open Portrait Full Screen</a>
</p>

<style>
.iframe-container {
  position: relative;
  width: 100%;
  padding-bottom: 62.5%;
  height: 0;
  margin-bottom: 1em;
}
.iframe-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 1px solid #ccc;
}
</style>

<script>
document.getElementById("loadPortrait").addEventListener("click", function() {
  var container = document.getElementById("portraitContainer");
  container.innerHTML = '<div class="iframe-container"><iframe src="/Spine_Zagor/portrait/index.html" frameborder="0" allowfullscreen></iframe></div>';
  this.disabled = true;
  this.innerText = "Portrait Mode Loading...";
});
</script>
