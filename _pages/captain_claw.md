---
layout: page
title: "Roadplay"
permalink: /captain_claw_page/
---

# Roadplay

Here you can "play" Roadplay and read the documentation that is currently on Github


<p>
  <a href="[/Roadplay](https://github.com/martin-mikulic/Roadplay)" target="_blank" rel="noopener">Open in full screen</a>
</p>

<div class="iframe-container">
  <iframe src="/Roadplay" frameborder="0" allowfullscreen></iframe>
</div>

<p>
  <a href="/Roadplay" target="_blank" rel="noopener">Open in full screen</a>
</p>

<style>
.iframe-container {
  position: relative;
  width: 100%;
  padding-bottom: 62.5%; /* 960/600 aspect ratio */
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

# 🛣️ Roadplay

> **"World is yours to build."**
> Build it in public.

**Roadplay** is a nostalgic, playful web project inspired by the iconic city road rugs from our childhood bedrooms - where we built stories with toy cars, buildings, and imagination.

Now, that world is yours to build - digitally.

## 🌍 What is Roadplay?
### 🚧 Preview

![Roadplay Preview](readme_assets/roadplay-preview.gif)

**Roadplay** is a creative, open-source experience built with Unity (WebGL). It brings to life the classic "city carpet" pattern in a stylized, animated 3D scene that runs right in your browser.

It’s about:

* 🚗 Reimagining nostalgia as interactive art
* 🧱 Building playful environments
* 🌐 Creating in public with open-source values

## 🔧 Built With

* [Unity URP](https://unity.com/universal-render-pipeline) - for stylized visuals
* WebGL - export to browser
* GitHub Pages - easy open hosting
* Public commits & changelogs - for full transparency

## 💡 Why Build It in Public?

This project isn’t just a finished piece - it’s a growing, evolving process. You can:

* Give it a star ⭐
* Watch it develop in real time
* Suggest ideas or improvements
* Fork and remix your own version
* Learn by example or contribute code

**This is more than a portfolio - it's a playground.**

## 🎮 Gameplay Concept

The world of **Roadplay** is divided into sectors.&#x20;
You start at the **spawn sector** - this sector is the "perfect" reference point.

As you explore, every other sector differs slightly from the spawn sector by one small detail, like:

* Different materials on tiny cars driving the roads
* An extra floor added to some buildings
* Other subtle environmental changes

The twist is - the further you move away from the spawn sector, the harder it becomes to spot these differences. This encourages careful observation, exploration, and discovery.

You have complete freedom to move to any sector on the grid from the spawn point, making each journey a playful challenge of perception and memory.

## 🏆 Score MVP

Each sector gives you a score reward based on its distance from the home sector:


---

### Points Grid

```
⬛⬛⬛⬛⬛
⬛🟦🟦🟦⬛
⬛🟦🟩🟦⬛
⬛🟦🟦🟦⬛
⬛⬛⬛⬛⬛
```



Legend:

* 🟩 = Home sector (0 points)
* 🟦 = Adjacent sectors (1 point)
* ⬛ = Further sectors (2 points)

---


* The home sector gives **0 points**. 
* Sectors directly adjacent to the home sector give **1 point**.
* Sectors further away give **2 points**.
```
+-------+-------+-------+-------+-------+
|   2   |   2   |   2   |   2   |   2   |
+-------+-------+-------+-------+-------+
|   2   |   1   |   1   |   1   |   2   |
+-------+-------+-------+-------+-------+
|   2   |   1   |   0   |   1   |   2   |
+-------+-------+-------+-------+-------+
|   2   |   1   |   1   |   1   |   2   |
+-------+-------+-------+-------+-------+
|   2   |   2   |   2   |   2   |   2   |
+-------+-------+-------+-------+-------+
```
This simple scoring system encourages exploration as you move away from the familiar and discover new, slightly different sectors.

## 📦 Try It Out

👉 https://martin-mikulic.github.io/Roadplay

(patience while loading please because for now I am using uncommpressed assets 50MB for faster iteration, they will be 15MB once compressed)

No install needed - works in your browser! (hopefully will be interactive on mobile too one day)

## ✨ Contribute

Pull requests and feedback are welcome! Whether it’s:

* Asset design
* Unity tweaks
* Performance suggestions
* New map ideas
* Or sharing your own memory of the road rug...

**Everyone’s welcome here.**

## 📜 License

MIT License - open source, for everyone.

---

> Made with 🚙 and ☁️ by [Martin Mikulić](https://www.artstation.com/martinmikulic)

---
