---
description: "Used to describe a machine."
title: MACHINE_INFO_FLAGS
ms.date: 11/04/2016
ms.topic: reference
f1_keywords:
- MACHINE_INFO_FLAGS
helpviewer_keywords:
- MACHINE_INFO_FLAGS enumeration
author: maiak
ms.author: maiak
manager: jmartens
ms.technology: vs-ide-debug
dev_langs:
- CPP
- CSharp
---
# MACHINE_INFO_FLAGS

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Used to describe a machine.

## Syntax

### [C#](#tab/csharp)
```csharp
public enum enum_MACHINE_INFO_FLAGS { 
   MCIFLAG_TERMINAL_SERVICES_AVAILABLE = 0x00000001
};
```
### [C++](#tab/cpp)
```cpp
enum enum_MACHINE_INFO_FLAGS { 
   MCIFLAG_TERMINAL_SERVICES_AVAILABLE = 0x00000001
};
typedef DWORD MACHINE_INFO_FLAGS;
```
---

## Fields
 `MCIFLAG_TERMINAL_SERVICES_AVAILABLE`\
 Indicates that terminal services are available.

## Remarks
 Used as the `Flags` member of the [MACHINE_INFO](../../../extensibility/debugger/reference/machine-info.md) structure.

## Requirements
 Header: msdbg.h

 Namespace: Microsoft.VisualStudio.Debugger.Interop

 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll

## See also
- [Enumerations](../../../extensibility/debugger/reference/enumerations-visual-studio-debugging.md)
- [MACHINE_INFO_FIELDS](../../../extensibility/debugger/reference/machine-info-fields.md)
