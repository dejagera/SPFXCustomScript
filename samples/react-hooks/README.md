# React Hooks Form WebPart

## Summary
The `React Hooks web part` is an example of how to implement Hooks in SPFx. 
Hooks is a new feature included in React version 16.8, with the new version of **SharePoint Framework (SPFx) version 1.9.1**  we can use them in our developments. In this example we are going to see the different types of hooks that are available and with the comparison of how this implementation can be done without the Hooks to be able to observe the benefits of using it.
![Brithdays Web Part](./assets/webpart.PNG)



# Compatibility

![SPFx 1.9.1](https://img.shields.io/badge/SPFx-1.9.1-green.svg) 
![Node.js v10 | v8](https://img.shields.io/badge/Node.js-v10%20%7C%20v8-green.svg) 
![Compatible with SharePoint Online](https://img.shields.io/badge/SharePoint%20Online-Compatible-green.svg)
![Does not work with SharePoint 2019](https://img.shields.io/badge/SharePoint%20Server%202019-Incompatible-red.svg)
![Does not work with SharePoint 2016 (Feature Pack 2)](https://img.shields.io/badge/SharePoint%20Server%202016%20(Feature%20Pack%202)-Incompatible-red.svg "SharePoint Server 2016 Feature Pack 2 requires SPFx 1.1")
![Local Workbench Compatible](https://img.shields.io/badge/Local%20Workbench-Compatible-green.svg)
![Hosted Workbench Compatible](https://img.shields.io/badge/Hosted%20Workbench-Compatible-green.svg)

## Applies to

* [SharePoint Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)
* [Office 365 tenant](https://docs.microsoft.com/sharepoint/dev/spfx/set-up-your-development-environment)

## Prerequisites
Existing list in tenant root site, with the Title "AvengersList"  and columns:

Column Internal Name|Type|Required|Comments
--------------------|----|--------|----------
Title| Text| true


## Solution

Solution|Author(s)
--------|---------
react-hooks|Adrián Díaz [@AdrianDiaz81](https://www.twitter.com/adriandiaz81)

## Version history

Version|Date|Comments
-------|----|--------
1.0.0|August 19, 2019|Initial release


## Disclaimer
**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

- Clone this repository
- in the command line run:
  - `npm install`
  - `gulp serve`

## Features

This Web Part illustrates the following concepts on top of the SharePoint Framework:

- Using React Hooks for building SharePoint Framework client-side web parts.
- Using @PnP/PnPjs to read items ...

<img src="https://telemetry.sharepointpnp.com/sp-dev-fx-webparts/samples/react-hooks" />
