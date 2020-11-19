---
title: "accessPackageLocalizedText resource type"
description: "A complex type used to represent a string in a specific language."
author: "markwahl-msft"
localization_priority: Normal
ms.prod: "microsoft-identity-platform"
doc_type: resourcePageType
---

# accessPackageLocalizedText resource type

Namespace: microsoft.graph

A complex type which would be used to represent a string in a specific language.

## Properties
|Property|Type|Description|Required|Read-only|
|:---|:---|:---|:---|:---|
|languageCode|String|The ISO code for the intended language.|Yes|No|
|text|String|The text in the specific language|Yes|No|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.accessPackageLocalizedText"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.accessPackageLocalizedText",
  "text": "String",
  "languageCode": "String"
}
```
