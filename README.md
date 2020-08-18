[Converse](https://conversejs.org) is a web based [XMPP/Jabber](https://xmpp.org) chat client.

You can either use it as a webchat app, or you can integrate it into your own website.

## Converse modes

### Embedded

In embedded mode, Converse can be embedded into an element in the DOM.

### NOTE

Generating a plugin with Yeoman

The rest of this document explains how to write a plugin for Converse and ends with a documented example of a plugin.

There is a Yeoman code generator, called generator-conversejs, which you can use to generate plugin scaffolding/boilerplate that serves as a starting point and basis for writing your plugin.

Please refer to the [generator-conversejs](https://github.com/conversejs/generator-conversejs) README for information on how to use it.

### created plugin named "converse-hellotest"

A [converse.js](https://conversejs.org) plugin.

To demo the plugin, go to the converse-hellotest plugin folder and first run `npm install` and then `npm start`.
You can then open `http://localhost:8080` in your browser and the plugin will be loaded.
