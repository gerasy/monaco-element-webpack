
# Monaco Element

Standalone Monaco Element sample with webpack

## Running

```
git clone git@github.com:gerasy/monaco-element-webpack.git
cd monaco-element-webpack
npm install .
npx webpack
```

Go to dist folder and open up the index.html

## Problem
* webpack won't bundle up the loader used by monaco-element inside the node_modules folder, thats why the only working solution for now is to copy the entire node_modules/monaco-editor folder into the dist folder. Any help on how to properly configure webpack to resolve this issue is appreciated.


## License

MIT
