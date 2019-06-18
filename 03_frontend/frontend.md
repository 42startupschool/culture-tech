
# 03 Frontend

## Awesome or overkill

---

# How work the web

---

## What is a browser

![inline](assets/browser_components.png)

^ User Interface (Window / Bookmarks / Etc)
^ UI Backend (external widgets)
^ Networking (HTTP / HTTPS)

---

### Javascript Engine

Javascript interpreter

- SpiderMonkey
- JavascriptCore
- Chrome V8

^ SpiderMonkey: Mozilla
^ JavascriptCore: Apple
^ Chrome V8: Google, know thanks to NodeJS and Electron

---

### Data Storage

- localStorage
- IndexedDB
- WebSQL
- FileSystem

^ IndexedDB: A KV Store on the browser

---

### Browser & Renderer Engine

HTML + CSS Renderer

- Gecko/Quantum
- Wekkit
- Blink

^ Quantum is the new name of project that include Servo/Stylo/etc (Rust component)
^ Webkit the Apple's renderer engine
^ Blink is a fork of Webkit made by Google

---

![inline](assets/render_engine_life_cycle.png)

^ 1. The engine receive data by chunk of 8Kb. If one rootNode is complete The process start
^ 2. Create the DOM
^ 3. Update positions of element according to the layout
^ 4. Apply CSS

---

## What is DOM

---

![inline](assets/not_dom_example.png)

^ Not DOM, this is HTML

---

![inline](assets/dom_example.png)

^ Can only be visible with "Inspect Element tool"

---

HTML > DOM

![inline](assets/template_html.png) ![inline](assets/template_dom.png)

^ The template is not seen by the web renderer. It should be use by javascript.

---

DOM API

![inline](assets/html_js.png)

---

JQuery

![inline](assets/jquery.png)

---

## What is Shadow DOM

---

[Example](https://jsfiddle.net/bfntoh2p/23/)

---

## What is Virtual DOM

---

![inline](assets/virtual_dom.png)

---

# Frameworks

---

## Angular

![inline](https://www.eurelis.com/sites/default/files/styles/image_article/public/images/angular-5.png?itok=RX5HjDRE)

---

- Created by a google engineer for making internal google project
- 2010: The birth of AngularJS
- 2014 — 2015: The Great Rewrite
- 2016: The Panic Period
- 2017 — 2018: Emerging from the rubble
- Now Version 7

---

- Framework
- Shadow Dom
- Architrecture MVC
- 2 way data-binding
- Dependency injection
- Routing
- Testing

---

### Basics

![inline](assets/angular_basic.png)

---

### Controller

![inline](assets/angular_controlleur_js.png) ![inline](assets/angular_controlleur_html.png)

---

### Directives

![inline](assets/angular_directives.png)

---

### Routing (HTML)

![inline](assets/angular_routing.png)

---

### Routing (JS)

![inline](assets/angular_routing_js.png)

---

## VueJS

![inline](https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1200px-Vue.js_Logo_2.svg.png)

---

- Library
- Virtual DOM + Shadow DOM
- Component based
- HTML syntax
- Easy to learn

---

![inline](https://fr.vuejs.org/images/vue-component.png)

---

- VueX
- VueRouter

---

Tooling

- [Nuxt.js](https://fr.nuxtjs.org/)

---

## React

![inline](https://humancoders-formations.s3.amazonaws.com/uploads/course/logo/89/formation-react-native.png)

---

- Library
- Virtual DOM + Shadow DOM
- Component based
- JS syntax
- Not easy to maintain

---

- Redux
- reactive flow

---

Tooling

- [React Native](https://facebook.github.io/react-native/)
- [Preact](https://preactjs.com/)
- [Next.js](https://nextjs.org/)
