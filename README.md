

<p align="center">
  <img alt="Logo" src="https://www.snowpack.dev/img/logo.png" height="240">
</p>

<p align="center">
   <strong>Snowpack</strong><br/>Install npm packages to run directly in the browser. No bundler required.
</p>

``` bash
npm install --dev snowpack
```

- Build your web application with less tooling and 10x faster iteration.
- Snowpack removes the need for a bundler (Webpack, Parcel, Rollup) in your web app build process.
- Instead of bundling your app on every change, just run Snowpack once (right after `npm install`).
2. Snowpack installs your dependencies as single JS files to a new `web_modules/` directory.
3. Write your application code, import those dependencies via an ESM `import`, and then run it all in the browser. 
4. 💥 See changes reflected instantly in the browser. **(0ms!)**

**💁 More info at the official [Snowpack website ➞](https://snowpack.dev)**


## Examples

🆕 **Check out [`npx @pika/init`](https://github.com/pikapkg/init)**! Instantly bootstrap a starter app with Snowpack, Preact, TypeScript, and more!

- A basic, three-dependency project: [[Source]](https://glitch.com/edit/#!/pika-web-example-simple) [[Live Demo]](https://pika-web-example-simple.glitch.me/)
- Preact + HTM: [[Source]](https://glitch.com/edit/#!/pika-web-example-preact-htm) [[Live Demo]](https://pika-web-example-preact-htm.glitch.me)
- Electron (using Three.js): [[Source]](https://github.com/br3tt/electron-three)
- TypeScript (using Preact): [[Source]](https://glitch.com/edit/#!/pika-web-ts-preact) [[Live Demo]](https://pika-web-ts-preact.glitch.me/)
- Vue (using httpVueLoader): [[Source]](https://glitch.com/edit/#!/pika-web-vue-httpvueloader) [[Live Demo]](https://pika-web-vue-httpvueloader.glitch.me/) [By: [@thiagoabreu](https://github.com/thiagoabreu)]
- PWA-Starter-Kit (lit-html + Redux): [[Source]](https://github.com/Polymer/pwa-starter-kit/issues/339)
- LitElement + lit-html PWA: [[Source]](https://github.com/thepassle/reddit-pwa) [[Live Demo]](https://angry-turing-4769b3.netlify.com/)  
- Terminal Homepage (Preact + Typescript + Babel): [[Source]](https://github.com/ndom91/terminal-homepage) [[Live Demo]](https://termy.netlify.com)  
- 🙋‍♀️ Have a great example you'd like to share? Create it on [CodeSandbox](https://codesandbox.io/), [Glitch](https://glitch.com), or [GitHub](https://github.com/new). Then add it here via PR.
