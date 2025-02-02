## xterm-addon-webgl

An addon for [xterm.js](https://github.com/xtermjs/xterm.js) that enables a WebGL2-based renderer. This addon requires xterm.js v4+.

### Install

```bash
npm install --save xterm-addon-webgl
```

### Usage

```ts
import { Terminal } from 'xterm';
import { WebglAddon } from 'xterm-addon-webgl';

const terminal = new Terminal();
terminal.loadAddon(new WebglAddon());
```

See the full [API](https://github.com/xtermjs/xterm.js/blob/master/addons/xterm-addon-webgl/typings/xterm-addon-webgl.d.ts) for more advanced usage.
