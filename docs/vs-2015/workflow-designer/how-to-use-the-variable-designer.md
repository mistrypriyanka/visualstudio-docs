---
title: "How to: Use the Variable Designer | Microsoft Docs"
ms.custom: ""
ms.date: 11/15/2016
ms.prod: ".net-framework-4.6"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "reference"
f1_keywords: 
  - "System.Activities.Presentation.View.DesignTimeVariable.UI"
ms.assetid: 0318dfb0-bf8f-4f92-9b86-ae4c1b2161ad
caps.latest.revision: 14
author: gewarren
ms.author: gewarren
manager: "erikre"
---
# How to: Use the Variable Designer
The variable designer is used to create variables for use in data-binding scenarios and conditional statements. The designer is accessed by clicking the **Variables** button in the lower-left corner of the design canvas. The designer contains a list of variables that appear in a tabular form and can be sorted by each of the column headers, except for the **Default** column. Each variable contains a name, variable type, scope, and default value (if any). The name and default value are editable text fields, and the type and scope are drop-downs. The scope is the activity that was selected when the variable designer was invoked. If a variable cannot be created within the scope of the selection, then the scope will default to the nearest ancestor activity of the selection that allows for variables to be created in its scope. [!INCLUDE[crabout](../includes/crabout-md.md)] variables, see [Variables and Arguments](http://msdn.microsoft.com/library/d03dbe34-5b2e-4f21-8b57-693ee49611b8).  
  
 The sort order is not applied until the user explicitly uses one of the sorting controls, closes and reopens the variable designer, or creates another variable.  
  
### To create a new variable  
  
1.  Open a workflow or activity solution in [!INCLUDE[vs_current_short](../includes/vs-current-short-md.md)].  
  
2.  On the design canvas, select an activity in your workflow.  
  
3.  Open the variable designer by clicking the **Variables** button in the lower-left corner of the design canvas. The variable designer appears.  
  
4.  Click the empty row labeled **Create Variable**. This will add a new row with a new variable using the following default values: variablex for the **Name** where x is an integer with an initial value of 1 that is automatically incremented to create unique variable names, **String** for the **Variable type**, and **Sequence** for the **Scope**. No value is added for **Default**. You can change these values at any time during the workflow design process.  
  
    > [!NOTE]
    >  To delete a variable, select the variable by clicking it and then press the **Delete** key.  
  
## See Also  
 [Using the Workflow Designer](../workflow-designer/using-the-workflow-designer.md)   
 [Variables and Arguments](http://msdn.microsoft.com/library/d03dbe34-5b2e-4f21-8b57-693ee49611b8)   
 [How to: Use the Argument Designer](../workflow-designer/how-to-use-the-argument-designer.md)