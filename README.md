# React + Vite
This is Block28 Workshop - React Router.  My netlify deploy failed.  This is a snip of the deploy log.
10:50:58 PM: x Build failed in 44ms
10:50:58 PM: error during build:
10:50:58 PM: Error: [vite]: Rollup failed to resolve import "react-router-dom" from "/opt/build/repo/src/main.jsx".
10:50:58 PM: This is most likely unintended because it can break your application at runtime.
10:50:58 PM: If you do want to externalize this module explicitly add it to
10:50:58 PM: `build.rollupOptions.external`
10:50:58 PM:     at viteWarn (file:///opt/build/repo/node_modules/vite/dist/node/chunks/dep-DkOS1hkm.js:67620:27)
10:50:58 PM:     at onwarn (file:///opt/build/repo/node_modules/@vitejs/plugin-react/dist/index.mjs:250:9)
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
