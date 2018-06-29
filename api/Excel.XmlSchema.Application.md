---
title: XmlSchema.Application Property (Excel)
keywords: vbaxl10.chm749073
f1_keywords:
- vbaxl10.chm749073
ms.prod: excel
api_name:
- Excel.XmlSchema.Application
ms.assetid: c9a4dd13-acb4-b841-3099-70872547156e
ms.date: 06/08/2017
---


# XmlSchema.Application Property (Excel)

When used without an object qualifier, this property returns an  **[Application](Excel.Application(objec).md)** object that represents the Microsoft Excel application. When used with an object qualifier, this property returns an **Application** object that represents the creator of the specified object (you can use this property with an OLE Automation object to return the application of that object). Read-only.


## Syntax

 _expression_. `Application`

 _expression_ A variable that represents a [XmlSchema](./Excel.XmlSchema.md) object.


## Example

This example displays a message about the application that created  `myObject`.


```vb
Set myObject = ActiveWorkbook 
If myObject.Application.Value = "Microsoft Excel" Then 
 MsgBox "This is an Excel Application object." 
Else 
 MsgBox "This is not an Excel Application object." 
End If
```


## See also


[XmlSchema Object](Excel.XmlSchema.md)
