---
page_type: sample
products:
- office-sp
languages:
- javascript
- typescript
extensions:
  contentType: tools
  technologies:
  - SharePoint Framework
  createdDate: 1/1/2016 12:00:00 AM
---
# Extending webpack in the SharePoint Framework toolchain

## Summary
[Webpack](https://webpack.github.io/) is a JavaScript module bundler that takes your JavaScript files and its dependencies and generates one or more JavaScript bundles so you can load different bundles for different scenarios.

One common task you would want to add to the SharePoint Framework toolchain is to extend the webpack configuration with custom loaders and plugins.

This sample shows how to use the webpack [markdown-loader](https://www.npmjs.com/package/markdown-loader) to preprocess markdown files to HTML string.

Read the following documentation for detailed information on working with webpack loaders in SharePoint Framework:

- [Extending webpack in the SharePoint Framework toolchain](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/toolchain/extending-webpack-in-build-pipeline)

## Compatibility

![SPFx 1.3.0](https://img.shields.io/badge/SPFx-1.3.0-green.svg)
![Node.js v6](https://img.shields.io/badge/Node.js-v6-green.svg) 
![Compatible with SharePoint Online](https://img.shields.io/badge/SharePoint%20Online-Compatible-green.svg)
![Compatible SharePoint 2019](https://img.shields.io/badge/SharePoint%20Server%202019-Compatible-green.svg)
![Does not work with SharePoint 2016 (Feature Pack 2)](https://img.shields.io/badge/SharePoint%20Server%202016%20(Feature%20Pack%202)-Incompatible-red.svg)
![Local Workbench Compatible](https://img.shields.io/badge/Local%20Workbench-Compatible-green.svg)
![Hosted Workbench Compatible](https://img.shields.io/badge/Hosted%20Workbench-Compatible-green.svg)


## Applies to

* [SharePoint Framework Developer](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)
* [Office 365 developer tenant](https://docs.microsoft.com/sharepoint/dev/spfx/set-up-your-developer-tenant)

## Solution

Solution|Author(s)
--------|---------
js-extend-webpack | Chakkaradeep Chandran (@chakkaradeep)
Updated to GA Version| Velin Georgiev ([@VelinGeorgiev](https://twitter.com/velingeorgiev))

## Version history

Version|Date|Comments
-------|----|--------
1.0|January 25th, 2017|Initial release
1.1|July 9th, 2017|Updated to GA Version

## Disclaimer
**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

- Clone this repository
- in the command line run:
  - `npm install`
  - `gulp serve`

<img src="https://telemetry.sharepointpnp.com/sp-dev-fx-webparts/samples/js-extend-webpack" />
