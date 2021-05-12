---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# background: 'https://images.unsplash.com/photo-1498887960847-2a5e46312788?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2100&q=80'
---

<div>
  <img src="https://vitejs.dev/logo.svg" class="w-1/4 m-auto"/>
</div>

# Vite, the new kid on the block

<a href="https://github.com/eagleera" target="_blank" alt="GitHub"
  class="abs-br m-6 text-xl icon-btn opacity-50 !border-none !hover:text-white">
  <carbon-logo-github />
</a>

<!--
Let's talk about next generation code bundlers
-->

---

# What exactly is Vite?

<p class="text-white">No-bundle Build tool for faster development experience.</p>
  

- 🔥 **Hot Module Replacement**
- 🛠 **Rollup bundler**
- 🎨 **Templates**
- 🔌 **Plugins**
- 🧰 **SSR (WIP), static assets, env handlers, + more**

---

# How big is the community?

- 🧑‍🎤 **Written by Vue creator**
- 🏷 **Version 2.3.0**
- 🌟 **+25k stars on github**
- 🧑‍💻👩‍💻👨‍💻 **+250 contributors**

---

# Comparisons with alternatives

|     |     |
| --- | --- |
| <b>esbuild</b> | Written in Go, no HMR, big community, not stable yet, focused on build |
| <b>Snowpack</b> | can use esbuild for building, HMR, templates, focused on dev server |
| <b>wmr</b> | creator of preact, 0 npm dependencies, rollup, no Templates|
| <b>Vite</b> | more opinionated, best of both worlds, templates, rollup |

---
layout: image-right
image: 'https://images.unsplash.com/photo-1555066931-4365d14bab8c?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80'
---

# How to use?

As easy as runnning one command on your terminal to start a project

```bash{1|2|3|4|5-12}
$ npm init @vitejs/app
✔ Project name: · sample
✔ Select a framework: · react
✔ Select a variant: · TypeScript

Scaffolding project in /Users/dev/sample...

Done. Now run:

  cd sample
  npm install
  npm run dev
```

---

# Fast and furious🏎

<div>
  <div class="flex">
    <div class="flex flex-col justify-center">
      <b>Development server</b>
      <p class="pt-4">Vite vs CRA</p>
    </div>
  <video controls width="400" class="m-auto p-4">
    <source src="/vite.mov" type="video/mp4">
  </video>
  <video controls width="400" class="m-auto p-4">
    <source src="/react-app.mov" type="video/mp4">
  </video>
  </div>
</div>
<div>
  <div class="flex justify-around">
    <div class="flex flex-col justify-center">
      <b>Build process</b>
      <p class="pt-4">Vite vs CRA</p>
    </div>
    <div class="flex">
      <video controls width="300" class="m-auto p-4">
        <source src="/vite-build.mov" type="video/mp4">
      </video>
      <video controls width="300" class="m-auto p-4">
        <source src="/cra-build.mov" type="video/mp4">
      </video>
    </div>
  </div>
</div>

---

# Sources:

- https://vitejs.dev/
- https://github.com/vitejs/vite
- https://css-tricks.com/comparing-the-new-generation-of-build-tools/


<h2 class="text-center pt-24 text-xxl">Thanks for your attention!</h2>