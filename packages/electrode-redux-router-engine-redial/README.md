# Electrode Redux Router Engine - with support for Redial

Refer to the original [Redial] repository for documentation

## Install

```
npm install -save electrode-redux-router-engine-redial
```

## Usage

Just pass an extra **"enableRedial"** flag to the options object either when calling the **electrode-redux-router-engine-redux** constructor (OR) while calling the render method.

```
routerEngine = new ElectrodeReduxRouterEngineRedial({ routes, createReduxStore, enableRedial: true });
```

**OR**

```
routerEngine.render(req, { enableRedial: true })
```


This module is **NOT** a part of the [Electrode Platform] yet. I will add more features and open a PR.

[electrode platform]: http://www.electrode.io/
[redial]: https://github.com/markdalgleish/redial
