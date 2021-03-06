---
title: Application.NewWorkbook property (Excel)
keywords: vbaxl10.chm133283
f1_keywords:
- vbaxl10.chm133283
ms.prod: excel
api_name:
- Excel.Application.NewWorkbook
ms.assetid: 3a50a338-53be-3ac9-d398-c58084e19e6d
ms.date: 06/08/2017
localization_priority: Normal
---


# Application.NewWorkbook property (Excel)

Returns a  **[NewFile](Office.NewFile.md)** object.


## Syntax

_expression_. `NewWorkbook`

 _expression_ An expression that returns an **[Application](Excel.Application(object).md)** object.


## Return value

NewFile


## Example

In this example, Microsoft Excel sets the variable wkbOne to a  **NewFile** object.


```vb
 
Sub SetStartWorking() 
 
    Dim wkbOne As NewFile 
 
    ' Create a reference to an instance of the NewFile object. 
    Set wkbOne = Application.NewWorkbook 
 
End Sub
```


## See also


[Application Object](Excel.Application(object).md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]