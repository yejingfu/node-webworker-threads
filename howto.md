Build with node-gyp
===================

#### Install node-gyp chain
```bash
  $ sudo npm install -g node-gyp
```

#### Install dependencies
```bash
  $ npm install
```

#### Configure project
```bash
  $ node-gyp configure
```

#### Build project
```bash
  $ node-gyp build
```
When build succeed, the npm module is created at `build/Release/WebWorkerThreads.node`
