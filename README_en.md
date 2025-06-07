<p align="center">
  <picture style="width: 320px">
    <source media="(prefers-color-scheme: light)" srcset="./apps/web/public/logo/logo_drawnix_h.svg" />
    <source media="(prefers-color-scheme: dark)" srcset="./apps/web/public/logo/logo_drawnix_h_dark.svg" />
    <img src="./apps/web/public/logo/logo_drawnix_h.svg" width="360" alt="Drawnix logo and name" />
  </picture>
</p>
<div align="center">
  <h2>
    Open-source whiteboard tool (SaaS), an all-in-one collaborative canvas that includes mind mapping, flowcharts, freehand and more.
  <br />
  </h2>
</div>

<div align="center">
  <figure>
    <a target="_blank" rel="noopener">
      <img src="./apps/web/public/product_showcase/case-2.png" alt="Product showcase" width="80%" />
    </a>
    <figcaption>
      <p align="center">
      Whiteboard with mind mapping, flowcharts, freehand drawing and more
      </p>
    </figcaption>
  </figure>
</div>

[*中文*](README.md)

## Features

- 💯 Free and Open Source
- ⚒️ Mind Maps and Flowcharts
- 🖌 Freehand
- 😀 Image Support
- 🚀 Plugin-based Architecture - Extensible
- 🖼️ 📃 Export to PNG, JPG, JSON(.drawnix)
- 💾 Auto-save (Browser Storage)
- ⚡ Edit Features: Undo, Redo, Copy, Paste, etc.
- 🌌 Infinite Canvas: Zoom, Pan
- 🎨 Theme Support
- 📱 Mobile-friendly
- 📈 Support mermaid syntax conversion to flowchart
- ✨ Support markdown text conversion to mind map（New 🔥🔥🔥）


## About the Name

***Drawnix*** is born from the interweaving of ***Draw*** and ***Phoenix***, a fusion of artistic inspiration.

The *Phoenix* symbolizes endless creativity, while *Draw* represents humanity's most fundamental form of expression. Here, each creation is an artistic rebirth, every stroke a renaissance of inspiration.

Like a Phoenix, creativity must rise from the flames to be reborn, and ***Drawnix*** stands as the guardian of both technical and creative fire.

*Draw Beyond, Rise Above.*

## About Plait Drawing Framework

*Drawnix* is positioned as an out-of-the-box, *open-source*, and free tool product. It is built on top of the *Plait* framework, which is our company's *open-source* drawing framework representing significant technical accumulation in knowledge base products.


*Drawnix* uses a *plugin architecture*, which is technically more complex than the previously mentioned *open-source* tools. However, this *plugin architecture* has its advantages: it supports multiple *UI frameworks* (*Angular*, *React*), integrates with different *rich text frameworks* (currently only supporting *Slate* framework), enables better business layer separation in development, allows development of various fine-grained reusable plugins, and can expand to more whiteboard application scenarios.

## Repository Structure

```
drawnix/
├── apps/
│   ├── web                   # zymn.cc
│   │    └── index.html       # HTML
├── dist/                     # Build artifacts
├── packages/
│   └── drawnix/              # Whiteboard application core
│   └── react-board/          # Whiteboard react view layer
│   └── react-text/           # Text rendering module
├── package.json
├── ...
└── README.md
└── README_en.md

```

## Try It Out

*https://zymn.cc* is the minimal application of *drawnix*.

I will be iterating frequently on *zymn.cc* until the release of the *Dawn* version.


## Development

```
npm install

npm run start
```