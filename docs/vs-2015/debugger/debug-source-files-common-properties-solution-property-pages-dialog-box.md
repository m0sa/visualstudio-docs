---
title: "Debug Source Files, Common Properties, Solution Property Pages Dialog Box | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "vs.debug.options.FindSource"
dev_langs: 
  - "FSharp"
  - "VB"
  - "CSharp"
  - "C++"
  - "JScript"
  - "SQL"
  - "VB"
  - "CSharp"
  - "C++"
helpviewer_keywords: 
  - "Debug Source Files property page"
  - "debugging [Visual Studio], specifying source and symbol files"
  - "source files, specifying in debugger"
  - "debugger, source files"
ms.assetid: 0af11464-eeb1-4d0b-87a6-0cc96779afb1
caps.latest.revision: 13
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# Debug Source Files, Common Properties, Solution Property Pages Dialog Box
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

The latest version of this topic can be found at [Debug Source Files, Common Properties, Solution Property Pages Dialog Box](https://docs.microsoft.com/visualstudio/debugger/debug-source-files-common-properties-solution-property-pages-dialog-box).  
  
This property page specifies where the debugger will look for source files when debugging the solution.  
  
 To access the **Debug Source Files** property page, right-click on your Solution in **Solution Explorer** and select **Properties** from the shortcut menu. Expand the **Common Properties** folder, and click the **Debug Source Files** page.  
  
 **Directories containing source code**  
 Contains a list of directories in which the debugger searches for source files when debugging the solution. Subdirectories of the specified directories are also searched.  
  
 **Do not look for these source files**  
 Enter the names of any files that you do not want the debugger to read. If the debugger finds one of these files in one of the directories specified above, it will ignore it. If the **Find Source** dialog box comes up while you are debugging and , you click **Cancel**, the file you were searching for gets added to this list so that the debugger will not continue searching for that file.  
  
## See Also  
 [Debugger Security](../debugger/debugger-security.md)   
 [Debugger Settings and Preparation](../debugger/debugger-settings-and-preparation.md)



