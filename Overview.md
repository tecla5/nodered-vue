# Overview

This app aims to be a NodeRed application which integrates [red-api](https://github.com/tecla5/red-api) and [red-editor](https://github.com/tecla5/red-editor) in a Vue app. This will make it much easier to customize and extend the app with extra components, routes etc.

## How to guide

The [red-editor](https://github.com/tecla5/red-editor) should import and use the [red-api](https://github.com/tecla5/red-api) and test each UI component individually.

The Vue app should then only import the fully working [red-editor](https://github.com/tecla5/red-editor) and compose the application from the components available.

Wrapping the NodeRed App in a Progressive Vue app, allows the app to run on multiple platforms:

- browser
- desktop
- mobile (Android + iPhone)

We can then integrate with the backend!
