# capacitor-bug-webview
Bug when using live webview with plugins

Make sure to change the url in `capacitor.config.json` to match your computers url

```
npm install
npm run dev:android
```
Then launch the application on your android phone and open devtools in chrome: 
`chrome://inspect/#devices`
and see the error...

``` 
Uncaught (in promise) Error: "Storage" plugin is not implemented on android
    at createPluginMethod (index.js:187)
    at index.js:194
    at async initData (App.svelte:4)
    ``` 