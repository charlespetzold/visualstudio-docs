---
title: "Refactor rename in Visual Studio | Microsoft Docs"
ms.custom: ""
ms.date: 01/26/2018
ms.reviewer: ""
ms.suite: ""
ms.technology: vs-ide-general
ms.topic: reference
author: "gewarren"
ms.author: "gewarren"
manager: ghogen
f1_keywords: 
  - "vs.csharp.refactoring.rename"
dev_langs: 
  - CSharp
  - VB
ms.workload: 
  - "dotnet"
---
# Rename a code symbol refactoring

This refactoring applies to:

- C#

- Visual Basic

**What:** Lets you rename identifiers for code symbols, such as fields, local variables, methods, namespaces, properties and types.

**When:** You want to safely rename something without having to find all instances, and copy/paste the new name.

**Why:** Copy and pasting the new name across an entire project would likely result in errors. This refactoring tool will accurately perform the renaming action.

## How-to

1. Highlight or place the text cursor inside the item to be renamed:

   - C#:

    ![Highlighted code - C#](media/rename-highlight-cs.png)

   - Visual Basic:

    ![Highlighted code - Visual Basic](media/rename-highlight-vb.png)

1. Next, do one of the following:

   - **Keyboard**
     - Press **Ctrl+R**, then **Ctrl+R**. (Note that your keyboard shortcut may be different based on which profile you've selected.)
   - **Mouse**
     - Select **Edit > Refactor > Rename**.
     - Right-click the code and select **Rename**.

1. Rename the item simply by typing the new name.

   - C#:

    ![Rename animation - C#](media/rename-animated-cs.gif)

   - Visual Basic:

    ![Rename - VB](media/rename-rename-vb.png)

   > [!TIP]
   > You can also update comments and other strings to use this new name, as well as [preview the changes](../../ide/preview-changes.md) before saving, using the checkboxes in the **Rename** box which appears at the top right of your editor.

1. When you're happy with the change, choose the **Apply** button or press **Enter** and the changes will be committed.

> [!NOTE]
> If you use a name that already exists which would cause a conflict, the **Rename** box will warn you.
>
> ![Rename Conflict](media/rename-conflict-cs.png)

## See also

[Refactoring](../refactoring-in-visual-studio.md)  
[Preview Changes](../../ide/preview-changes.md)
