---
title: DataRecordsets.DataRecordsetAdded event (Visio)
keywords: vis_sdr.chm16362035
f1_keywords:
- vis_sdr.chm16362035
ms.prod: visio
api_name:
- Visio.DataRecordsets.DataRecordsetAdded
ms.assetid: ff3dae8e-3a49-7432-fc52-261a603d7bc3
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# DataRecordsets.DataRecordsetAdded event (Visio)

Occurs when a **DataRecordset** object is added to a **DataRecordsets** collection.


> [!NOTE] 
> This Visio object or member is available only to licensed users of Visio Professional 2013.


## Syntax

_expression_.**DataRecordsetAdded** (_DataRecordset_)

_expression_ An expression that returns a **[DataRecordsets](Visio.DataRecordsets.md)** object.


## Parameters

|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _DataRecordset_|Required| **[IVDATARECORDSET]**|The data recordset that was added.|

## Remarks

If you are using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own **Event** objects, use the **[Add](visio.eventlist.add.md)** or **[AddAdvise](visio.eventlist.addadvise.md)** method. 

To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. 

To create an **Event** object that receives notification, use the **AddAdvise** method. 

To find an event code for the event that you want to create, see [Event codes](../visio/Concepts/event-codesvisio.md).

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]