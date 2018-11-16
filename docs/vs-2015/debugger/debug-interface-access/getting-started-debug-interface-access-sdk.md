---
title: "Getting Started (Debug Interface Access SDK) | Microsoft Docs"
ms.custom: ""
ms.date: 11/15/2016
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - ".dbg files"
  - "DBG files"
ms.assetid: cb3d040a-2846-40d7-bdbc-8a5beb5dd2f6
caps.latest.revision: 18
author: MikeJo5000
ms.author: mikejo
manager: "ghogen"
---
# Getting Started (Debug Interface Access SDK)
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

The Debug Interface Access (DIA) SDK supplies you with instructional documentation and a sample that illustrates how to use the DIA API. Use the interfaces and methods in the DIA SDK to develop custom applications that open the .pdb and .dbg files and search their content for symbols, values, attributes, addresses, and other debugging information. This SDK also provides reference tables for the properties associated with symbols found in C++ applications.  
  
 To best use the DIA SDK, you should be familiar with the following:  
  
- C++ programming language  
  
- COM programming  
  
- Visual Studio integrated development environment (IDE) for compiling the samples  
  
  The DIA SDK is normally installed with Visual Studio and its default location is *[drive]*\Program Files\Microsoft Visual Studio 9.0\DIA SDK. As part of the installation, the msdia90.dll, which implements the DIA SDK, is automatically registered so all that you need to do to use it is to include `dia2.h` in your program and link to `diaguids.lib`.  
  
  Header: include\dia2.h  
  
  Library: lib\diaguids.lib  
  
  DLL: bin\msdia80.dll  
  
  IDL: idl\dia2.idl  
  
## In This Section  
 [Overview](../../debugger/debug-interface-access/overview-debug-interface-access-sdk.md)  
 Reviews the basic architecture of DIA.  
  
 [Querying the .Pdb File](../../debugger/debug-interface-access/querying-the-dot-pdb-file.md)  
 Provides step-by-step instructions on how to use the DIA API to query a .pdb file.  
  
## See Also  
 [Debug Interface Access SDK](../../debugger/debug-interface-access/debug-interface-access-sdk.md)


