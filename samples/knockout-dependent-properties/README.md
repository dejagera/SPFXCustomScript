---
page_type: sample
products:
- office-sp
languages:
- javascript
- typescript
extensions:
  contentType: samples
  technologies:
  - SharePoint Framework
  platforms:
  - Knockout
  createdDate: 1/1/2016 12:00:00 AM
---
# Dependent Property Pane Properties

## Summary
Sample Web Part illustrating
* requesting Lists and Views data from SharePoint REST API
* creating Knockout dropdown custom component with Fabric UI styling
* creating dependent properties (dropdowns) in Client-Side Web Part Property Pane

![Sample Web Part implementing dependent properties in Property Pane](./assets/dep-props.png)


## Compatibility

![SPFx 1.0.1](https://img.shields.io/badge/SPFx-1.0.1-green.svg)
![Node.js v6](https://img.shields.io/badge/Node.js-v6-green.svg) 
![Compatible with SharePoint Online](https://img.shields.io/badge/SharePoint%20Online-Compatible-green.svg)
![Compatible SharePoint 2019](https://img.shields.io/badge/SharePoint%20Server%202019-Compatible-green.svg)
![Compatible with SharePoint 2016 (Feature Pack 2)](https://img.shields.io/badge/SharePoint%20Server%202016%20(Feature%20Pack%202)-Compatible-green.svg)
![Local Workbench Compatible](https://img.shields.io/badge/Local%20Workbench-Compatible-green.svg)
![Hosted Workbench Compatible](https://img.shields.io/badge/Hosted%20Workbench-Compatible-green.svg)



## Applies to

* [SharePoint Framework Developer Preview](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)

## Solution

Solution|Author(s)
--------|---------
ko-dependent-properties | Alex Terentiev (Sharepointalist Inc., @alexaterentiev)

## Version history

Version|Date|Comments
-------|----|--------
1.0|October 12, 2016|Initial release
1.1|May 20, 2017| Update to GA

## Disclaimer
**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

- Clone this repository
- in the command line run:
  - `npm i`
  - `gulp serve`

> Include any additional steps as needed.

## Features
This project contains Client-Side Web Part built on the SharePoint Framework illustrating how to create dependent properties in Web Part Property Pane.
This Web Part illustrates the following concepts on top of the SharePoint Framework:

- loading Lists and Views data from SharePoint REST API
- creating custom Knockout data bindings
- creating custom Knockout components
- styling components to match Fabric UI experience
- creating custom Property Pane fields (custom markup, logic) based on Knockout.js framework

<img src="https://telemetry.sharepointpnp.com/sp-dev-fx-webparts/samples/knockout-dependent-properties" />
