---
title: Create a new project
ms.date: 03/19/2019
ms.topic: conceptual
f1_keywords:
  - "vs.newproject"
helpviewer_keywords:
  - "projects [Visual Studio], creating"
author: gewarren
ms.author: gewarren
manager: jillfra
ms.workload:
  - "multiple"
---
# Create a new project in Visual Studio

::: moniker range="vs-2017"

## Open the New Project dialog

There are multiple ways to create a new project in Visual Studio 2017. On the Start page, you can type in the name of a project template in the **Search project templates** box or choose the **Create new project** link to open the **New Project** dialog box. Aside from the Start page, you can also choose **File** > **New** > **Project** on the menu bar or click the **New Project** button on the toolbar.

![Start page and File > New > Project](./media/vside-newproject1.png)

## Select a template type

In the **New Project** dialog box, available project templates appear in a list under the **Templates** category. Templates are organized by programming language and project type, such as Visual C#, JavaScript, and Azure Data Lake.

![New project dialog box](./media/vside-newproject-templates-list.png)

> [!NOTE]
> The list of available languages and project templates that appears depends on the version of Visual Studio you are running and the workloads that are installed. To learn about how to install additional workloads, see [Modify Visual Studio by adding or removing workloads and components](../install/modify-visual-studio.md).

Show the list of templates for the programming language you want to use by clicking the triangle next to the language name and then choosing a project category (such as Windows Desktop).

The following image shows the project templates available for Visual C# .NET Core projects:

![Project templates](./media/new-project-dialog-net-core.png)

## Configure your project

Enter a name for the new project in the **Name** box. You can save the project in the default location on your computer or click the **Browse** button to find another location. You can also choose a solution name or add the new project to a Git repository (by choosing **Add to Source Control**).

Click **OK** to create the solution and project.

::: moniker-end

::: moniker range=">=vs-2019"

## Open the Create a new project page

There are multiple ways to create a new project in Visual Studio 2019. When you first open Visual Studio, the start window appears, and from there, you can choose **Create a new project**.

![Create a new project from the start window in VS 2019](media/vs-2019/start-window-create-new-project.png)

If the Visual Studio development environment is already open, you can create a new project by choosing **File** > **New** > **Project** on the menu bar or by clicking the **New Project** button on the toolbar.

![New Project button in Visual Studio 2019](media/vs-2019/new-project-button.png)

## Select a template type

On the **Create a new project** page, you can filter the available project templates by **Language** (for example, C# or C++), **Platform** (for example, Windows or Azure), and **Project type** (for example, Desktop or Web). You can also enter search text into the search box to further filter the templates, for example, **asp.net**.

![Project template filters in Visual Studio 2019](media/vs-2019/create-new-project-filters.png)

Select a template and then click **Next**.

## Configure your project

The **Configure your new project** page has options to name your project (and solution), choose a location where to save it, and select a Framework version (if applicable to the template you chose).

![Configure your new project page in VS 2019](media/vs-2019/configure-new-project.png)

Click **Create** to create the new project.

::: moniker-end

## Add additional projects to a solution

If you want to add an additional project to a solution, select the solution node in **Solution Explorer**, and then on the menu bar, choose **Project** > **Add New Item**.

## See also

- [Create solutions and projects](creating-solutions-and-projects.md)
