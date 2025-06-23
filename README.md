# threejs-model-viewer - Build & Run Guide

##  1. Prerequisites

*  Node.js v16 or higher: [https://nodejs.org/](https://nodejs.org/)
*  Basic knowledge of npm / git

##  2. Clone the source code

```bash
git clone https://github.com/Adjam93/threejs-model-viewer.git
cd threejs-model-viewer
```

##  3. Install dependencies

```bash
npm install
```

##  4. Build the source

```bash
npm run build
```

This will build the code into the `dist` directory.

##  5. Run locally


```bash
npm run start
```

Open the browser at `http://localhost:3000`

##  6. Check results

If successful, the viewer interface will be shown in the browser. Try loading a `.gltf` or `.glb` model.

##  7. Common errors & fixes

| Error                | Cause                   | Solution                                                         |
| -------------------- | ----------------------- | ---------------------------------------------------------------- |
| `npm install` error  | Node.js version too low | Upgrade to version ≥16                                           |
| `Error: port in use` | Port (3000) is occupied | Change port in `package.json` or kill the process using the port |
| Model not loading    | Incorrect resource path | Check `.gltf/.glb` link in the code                              |

## Summary

1. `git clone` → Get the source code.
2. `npm install` → Install dependencies.
3. `npm run build` → Build into `dist` directory.
4. `npm run start` → Run in the browser.

