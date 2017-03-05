<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [Plugin](#plugin)
    -   [name](#name)
    -   [nodes](#nodes)
    -   [marks](#marks)
    -   [plugins](#plugins)
    -   [onKeyDown](#onkeydown)
    -   [hoverButtons](#hoverbuttons)
    -   [toolbarButtons](#toolbarbuttons)

## Plugin

[packages/plugins/content/slate/src/plugins/Plugin.js:9-53](https://github.com/ory/editor/blob/d780f8a2764165ebdadbec36260fae4d036c27c3/packages/plugins/content/slate/src/plugins/Plugin.js#L9-L53 "Source code on GitHub")

### name

[packages/plugins/content/slate/src/plugins/Plugin.js:13-13](https://github.com/ory/editor/blob/d780f8a2764165ebdadbec36260fae4d036c27c3/packages/plugins/content/slate/src/plugins/Plugin.js#L13-L13 "Source code on GitHub")

Type: [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)

### nodes

[packages/plugins/content/slate/src/plugins/Plugin.js:18-18](https://github.com/ory/editor/blob/d780f8a2764165ebdadbec36260fae4d036c27c3/packages/plugins/content/slate/src/plugins/Plugin.js#L18-L18 "Source code on GitHub")

Type: {}

### marks

[packages/plugins/content/slate/src/plugins/Plugin.js:23-23](https://github.com/ory/editor/blob/d780f8a2764165ebdadbec36260fae4d036c27c3/packages/plugins/content/slate/src/plugins/Plugin.js#L23-L23 "Source code on GitHub")

Type: {}

### plugins

[packages/plugins/content/slate/src/plugins/Plugin.js:28-28](https://github.com/ory/editor/blob/d780f8a2764165ebdadbec36260fae4d036c27c3/packages/plugins/content/slate/src/plugins/Plugin.js#L28-L28 "Source code on GitHub")

Type: [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)&lt;any>

### onKeyDown

[packages/plugins/content/slate/src/plugins/Plugin.js:38-42](https://github.com/ory/editor/blob/d780f8a2764165ebdadbec36260fae4d036c27c3/packages/plugins/content/slate/src/plugins/Plugin.js#L38-L42 "Source code on GitHub")

This handler is called when any key is pressed

**Parameters**

-   `e`  the keydown event
-   `data`  utilities for hotkey logic
-   `state`  the current editor state

Returns **any** the new editor state if the plugin handles the hotkey

### hoverButtons

[packages/plugins/content/slate/src/plugins/Plugin.js:47-47](https://github.com/ory/editor/blob/d780f8a2764165ebdadbec36260fae4d036c27c3/packages/plugins/content/slate/src/plugins/Plugin.js#L47-L47 "Source code on GitHub")

Type: [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)&lt;Component&lt;any, any, any>>

### toolbarButtons

[packages/plugins/content/slate/src/plugins/Plugin.js:52-52](https://github.com/ory/editor/blob/d780f8a2764165ebdadbec36260fae4d036c27c3/packages/plugins/content/slate/src/plugins/Plugin.js#L52-L52 "Source code on GitHub")

Type: [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)&lt;Component&lt;any, any, any>>