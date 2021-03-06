---
title: "IDiaSymbol::get_oemId | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
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
  - "IDiaSymbol::get_oemId method"
ms.assetid: c472830f-c3eb-46ab-9498-cd637763d241
caps.latest.revision: 11
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# IDiaSymbol::get_oemId
[!INCLUDE[vs2017banner](../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDiaSymbol::get_oemId](https://docs.microsoft.com/visualstudio/debugger/debug-interface-access/idiasymbol-get-oemid).  
  
Retrieves the symbol's original equipment manufacturer (OEM) ID value.  
  
## Syntax  
  
```cpp#  
HRESULT get_oemId (   
   DWORD* pRetVal  
);  
```  
  
#### Parameters  
 `pRetVal`  
 [out] Returns a unique value that identifies an OEM.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns `S_FALSE` or an error code.  
  
> [!NOTE]
>  A return value of `S_FALSE` means that the property is not available for the symbol.  
  
## Remarks  
 This property applies only to symbols with a [SymTagEnum Enumeration](../../debugger/debug-interface-access/symtagenum.md) type of `SymTagCustomType`.  
  
## See Also  
 [IDiaSymbol](../../debugger/debug-interface-access/idiasymbol.md)   
 [SymTagEnum Enumeration](../../debugger/debug-interface-access/symtagenum.md)



