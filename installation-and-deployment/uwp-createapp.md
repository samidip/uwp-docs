---
title: Start Using Telerik UI for UWP
page_title: Start Using Telerik UI for UWP
description: Start Using Telerik UI for UWP
slug: createapp-uwp
tags: UWP,windows,universal,platform
published: True
position: 3
---

# Start Using Telerik UI for UWP

The following example describes what steps you should perform in order to add Telerik UI for UWP in your application.

## Requirements
Before walking through this example, you must have installed **Telerik UI for UWP** and **Visual Studio 2015/17** on your machine.

## Create New Application

Once the extensions are installed, developers are ready to create their UWP application. Visual Studio 2015/17 provides a *Blank App* template which can be used for easier start. It can be created using the New Project wizard.

![Blank App project Template](images/newprojectblankapp.png)

### Add required references

Once the wizard finishes creating the Blank App, developers are ready to reference the already installed packages. 

![Open Reference Manager](images/openreferencemanager.png)

In the Reference Manager, all extensions should be visible. Developers can reference the necessary one(s).

![Open Reference Manager](images/addreferences.png)

Referencing all three packages equals to referencing all binaries in the suite. This means developers will be allowed to utilize every single component from the suite. However, if this is not convenient and optimization is required customers are capable of manually referencing only the binaries they need. In the cases when only one or two of the available controls are used this optimization may be considered. The required binaries are described in each control's **Getting Started** article. It may turn out that the application needs only two of the available assemblies. In this case instead of referencing everything the better approach would be to include only the needed ones.

## For Existing Applications

Developers who have already started an UWP application project, do have the option of bringing in Telerik UI for UWP as a reference within their existing project. Bits for Telerik UI for UWP are available free of cost as a public NuGet package. Simply search on *NuGet.org* and pull Telerik UI for UWP as a reference within your application project, as below:

![Nuget Package Reference](images/nugetpackagereference.png)