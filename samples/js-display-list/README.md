# Display List JavaScript Client-Side Web Part

## Summary
Simplistic sample Web Part that demonstrates the use of JavaScript in creating a SharePoint Framework web part. The properties pane for this web part display a drop down list of lists in the current web. Once the user selects one of the lists, the web part display the contents of the list.


![Screeshot of the Display List web part](./assets/display-list-preview.png).

> Does only show data when hosted in SharePoint. No mock data at this point for local testing the rendering.

## Used SharePoint Framework Version 
![drop](https://img.shields.io/badge/drop-drop3-red.svg)

## Applies to

* [SharePoint Framework Developer Preview](http://dev.office.com/sharepoint/docs/spfx/sharepoint-framework-overview)
* [Office 365 developer tenant](http://dev.office.com/sharepoint/docs/spfx/set-up-your-developer-tenant)


## Solution

Solution|Author(s)
--------|---------
js-display-list|Naamat Al-Aswad, P.Eng.


## Version history

Version|Date|Comments
-------|----|--------
1.0|September 22, 2016|Initial release


## Disclaimer
**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

- Clone this repository
- in the command line run:
  - `npm install`
  - `tsd install`
  - `gulp serve`
  - `Open the *workbench* on your Office 365 Developer tenant`
      - Basic functionality can be tested locally, data is only shown when used in context of SharePoint

## Features
The js-display-list web part displays the content of the list specified in the web part properties pane.

This Web Part illustrates the following concepts on top of the SharePoint Framework:

* Using a dynamic drop down box in the web part properties pane to display the titles of the lists in the current web
* The use of a Loading Indicator
* Logging
* Rendering error messages.

<img src="https://telemetry.sharepointpnp.com/sp-dev-fx-webparts/samples/js-display-list" />