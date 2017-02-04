# SharePoint Framework client-side web part samples & tutorial materials

This repo contains the samples that demonstrate different usage patterns for the SharePoint Framework client-side web parts. 

> Note: The SharePoint Framework is currently in preview and is subject to change. SharePoint Framework client-side web parts are not currently supported for use in production enviornments.

SharePoint client-side web parts are controls that appear inside a SharePoint page but run locally in the browser. They're the bulding blocks of pages that appear on a SharePoint site. You can build client-side web parts using modern script development tools and the SharePoint workbench (a development test surface), and you can deploy your client-side web parts to classic web part pages in Office 365 Developer tenants. In addition to plain JavaScript projects, you can build web parts alongside common scripting frameworks, such as AngularJS and React. For example, you can use React along with components from Office UI Fabric React to quickly create experiences based on the same components used in Office 365
 
# Additional resources 

* [Overview of the SharePoint Framework](http://dev.office.com/sharepoint/docs/spfx/sharepoint-framework-overview)
* [SharePoint Framework development tools and libraries](http://dev.office.com/sharepoint/docs/spfx/tools-and-libraries)
* [SharePoint Framework Reference](https://sharepoint.github.io/)

# Using the samples

To build and start using these projects, you'll need to clone and build the projects. 

Clone this repo by executing the following command in your console:

```
git clone https://github.com/SharePoint/sp-dev-fx-webparts.git
```

Navigate to the cloned repo folder which should be the same as the repo name:

```
cd sp-dev-fx-webparts
```

To access the samples use the following command, where you replace `sample-folder-name` with the name of the sample you want to access. 

```
cd samples
cd sample-folder-name

```
and for the tutorials, use the following command:
```
cd tutorials
```

Now run the following command to install the npm packages:

```
npm install
```

This will install the required npm packages and dependencies to build and run the client-side project.


Once the npm packages are installed, run the following command to preview your web parts in SharePoint Workbench:

```
gulp serve
```

## Contributions

These samples are direct from the feature teams, SharePoint PnP core team (http://aka.ms/SharePointPnP) or shared by the community. We welcome your input on issues and suggestions for new samples. We do also welcome community contributions around the client-side web parts. If there's any questions around that, just let us know.

Please have a look on our [Contribution Guidance](./.github/CONTRIBUTING.md) before submitting your pull requests, so that we can get your contribution processed as fast as possible. Thx. 

> Sharing is caring!