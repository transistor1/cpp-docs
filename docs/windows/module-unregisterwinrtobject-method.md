---
title: "Module::UnregisterWinRTObject Method | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "reference"
f1_keywords: ["module/Microsoft::WRL::Module::UnregisterWinRTObject"]
dev_langs: ["C++"]
helpviewer_keywords: ["UnregisterWinRTObject method"]
ms.assetid: 32334aa7-2293-40d2-9a89-4b02e2e31f3c
caps.latest.revision: 6
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
ms.workload: ["cplusplus", "uwp"]
---
# Module::UnregisterWinRTObject Method
Unregisters one or more Windows Runtime objects so that other applications cannot connect to them.  
  
## Syntax  
  
```  
virtual HRESULT UnregisterWinRTObject(  
   unsigned int,  
   _Inout_ WINRT_REGISTRATION_COOKIE* cookie  
);  
  
```  
  
#### Parameters  
 `cookie`  
 A pointer to a value that identifies the class object whose registration is to be revoked.  
  
## Return Value  
  
## Requirements  
 **Header:** module.h  
  
 **Namespace:** Microsoft::WRL
 
 ## See Also
 [Module Class](../windows/module-class.md)