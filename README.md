# vue-loader-webpack-layer-error

Demo for webpack layers error in `vue-loader`

## Steps

1.) Clone repo and run `npm install`

2.) Run `npm run build`

3.) There is an error: [webpack-cli] Error: Compiling RuleSet failed: Properties issuerLayer are unknown (at clonedRuleSet-2.oneOf[0]: [object Object])

```
[webpack-cli] Error: Compiling RuleSet failed: Properties issuerLayer are unknown (at clonedRuleSet-2.oneOf[0]: [object Object])
    at RuleSetCompiler.error (node_modules\webpack\lib\rules\RuleSetCompiler.js:373:10)
    at RuleSetCompiler.compileRule (node_modules\webpack\lib\rules\RuleSetCompiler.js:196:15)
    at node_modules\webpack\lib\rules\RuleSetCompiler.js:154:9
    at Array.map (<anonymous>)
    at RuleSetCompiler.compileRules (node_modules\webpack\lib\rules\RuleSetCompiler.js:153:16)
    at RuleSetCompiler.compileRule (node_modules\webpack\lib\rules\RuleSetCompiler.js:192:30)
    at cloneRule (node_modules\vue-loader\dist\pluginWebpack5.js:173:42)
    at node_modules\vue-loader\dist\pluginWebpack5.js:101:31
    at Array.map (<anonymous>)
    at VueLoaderPlugin.apply (node_modules\vue-loader\dist\pluginWebpack5.js:101:14)
```
