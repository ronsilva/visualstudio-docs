---
title: "Tutorial: Open a project from a repo"
description: "Learn how to open a project in a Git or Azure DevOps repository by using Visual Studio."
ms.custom: "get-started"
ms.date: 03/13/2019
ms.technology: vs-ide-general
ms.prod: visual-studio-windows
ms.topic: tutorial
author: TerryGLee
ms.author: tglee
manager: jillfra
dev_langs:
  - CSharp
ms.workload:
  - "dotnet"
  - "dotnetcore"
---
# Tutorial: Open a project from a repo

In this tutorial, you'll use Visual Studio to connect to a repository for the first time and then open a project from it.

::: moniker range="vs-2017"

If you haven't already installed Visual Studio, go to the [Visual Studio downloads](https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=inline+link&utm_content=download+vs2017) page to install it for free.

::: moniker-end

::: moniker range="vs-2019"

If you haven't already installed Visual Studio, go to the [Visual Studio downloads](https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=inline+link&utm_content=download+vs2019+rc) page to install it for free.

::: moniker-end

## Open a project from a GitHub repo

1. Open Visual Studio 2017.

1. From the top menu bar, choose **File** > **Open** > **Open from Source Control**.

   The **Team Explorer - Connect** pane opens.

    ![The Team Explorer window within the Visual Studio IDE](./media/open-proj-repo-team-explorer.png)

1. In the **Local Git Repositories** section, choose **Clone**.

    ![Choose Clone from the Local Git Repositories section](./media/open-proj-repo-local-git-repo-clone.png)

1. In the box that says ***Enter the URL of a Git repo to clone***, type or paste the URL for your repo, and then press **Enter**. (You might receive a prompt to sign in to GitHub; if so, do so.)

   After Visual Studio clones your repo, Team Explorer closes and Solution Explorer opens. A message appears that says *Click on Solutions and Folders above to view a list of Solutions*. Choose **Solutions and Folders**.

   ![Choose "Solutions and Folders" from the Solution Explorer](./media/open-proj-repo-github-solutions-folders.png)

1. If you have a solution file available, it will appear in the "Solutions and Folders" fly-out menu. Choose it, and Visual Studio opens your solution.

   ![Choose what you want to open from the Solution Explorer drop-down list](./media/open-proj-repo-github-solutions-folders-picker.png)

   If you do not have a solution file (specifically, a .sln file) in your repo, the fly-out menu will say "No Solutions Found." However, you can double-click any file from the folder menu to open it in the Visual Studio code editor.

### Review your work

View the following animation to check the work that you completed in the previous section.

   ![Animation of opening a project in a GitHub repo by using Visual Studio](./media/open-project-from-github.gif)

## Open a project from an Azure DevOps repo

1. Open Visual Studio 2017.

1. From the top menu bar, choose **File** > **Open** > **Open from Source Control**.

   The **Team Explorer - Connect** pane opens.

    ![The Team Explorer window within the Visual Studio IDE](./media/open-proj-repo-team-explorer.png)

1. Here are two ways to connect to your Azure DevOps repo:

      - In the **Hosted Service Providers** section, choose **Connect...**.

        ![The Hosted Service Providers section of the Team Explorer window within the Visual Studio IDE](./media/open-proj-repo-azure-devops.png)

      - In the **Manage Connections** drop-down list, choose **Connect to a Project...**.

        ![The Manage Connections section of the Team Explorer window within the Visual Studio IDE](./media/open-proj-repo-azuredevops-manage-connections.png)

1. In the **Connect to a Project** dialog box, choose the repo that you want to connect to, and then choose **Clone**.

      ![The "Connect to a Project" dialog box that's generated from Visual Studio](./media/open-proj-azure-devops-connect-cloud-clone.png)

    > [!NOTE]
    > What you see in the list box depends on the Azure DevOps repositories that you have access to.

1. After Visual Studio clones your repo, Team Explorer closes and Solution Explorer opens. A message appears that says *Click on Solutions and Folders above to view a list of Solutions*. Choose **Solutions and Folders**.

      ![The "Solutions and Folders" notification from Team Explorer in Visual Studio](./media/open-proj-repo-solutions-folders.png)

   A solution file (specifically, a .sln file), will appear in the "Solutions and Folders" fly-out menu. Choose it, and Visual Studio opens your solution.

   If you do not have a solution file in your repo, the fly-out menu will say "No Solutions Found". However, you can double-click any file from the folder menu to open it in the Visual Studio code editor.
  
## Next steps

If you're ready to code with Visual Studio, dive into any of the following language-specific tutorials:

- [Visual Studio tutorials | **C#**](./csharp/index.yml)
- [Visual Studio tutorials | **Visual Basic**](./visual-basic/index.yml)
- [Visual Studio tutorials | **C++**](/cpp/get-started/)
- [Visual Studio tutorials | **Python**](/visualstudio/python/)
- [Visual Studio tutorials | **JavaScript**, **TypeScript**, and **Node.js**](/visualstudio/javascript/)

## See also

- [Azure DevOps Services: Get started with Azure Repos and Visual Studio](/azure/devops/repos/git/gitquickstart/)
- [Microsoft Learn: Get started with Azure DevOps](/learn/modules/get-started-with-devops/)