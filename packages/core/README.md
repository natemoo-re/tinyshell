# `tinyshell`

A very tiny `node:child_process` wrapper that makes executing shell scripts less painful. Kinda like [`execa`](https://github.com/sindresorhus/execa), but built with modern Node (v16+) features.

```js
import { shell } from 'tinyshell';

const result = await shell('node', ['--version'])
console.log(result) // { stdout: 'v18.17.1', stderr: '', exitCode: 0 }
```
