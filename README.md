```
> yarn
> yarn build
$ babel index.js
TypeError: Cannot read property 'some' of null
    at isPureAnnotated (<dir>/node_modules/@babel/helper-annotate-as-pure/lib/index.js:19:26)
    at annotateAsPure (<dir>/node_modules/@babel/helper-annotate-as-pure/lib/index.js:27:7)
    at _default (<dir>/node_modules/@babel/helper-remap-async-to-generator/lib/index.js:74:39)
    at PluginPass.Function (<dir>/node_modules/@babel/plugin-transform-async-to-generator/lib/index.js:43:50)
    at newFn (<dir>/node_modules/@babel/traverse/lib/visitors.js:223:21)
    at NodePath._call (<dir>/node_modules/@babel/traverse/lib/path/context.js:64:19)
    at NodePath.call (<dir>/node_modules/@babel/traverse/lib/path/context.js:38:17)
    at NodePath.visit (<dir>/node_modules/@babel/traverse/lib/path/context.js:99:12)
    at TraversalContext.visitQueue (<dir>/node_modules/@babel/traverse/lib/context.js:139:18)
    at TraversalContext.visitSingle (<dir>/node_modules/@babel/traverse/lib/context.js:98:19)
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```
