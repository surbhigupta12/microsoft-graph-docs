---
title: "deviceManagementConfigurationIntegerSettingValue resource type"
description: "Simple setting value"
author: "dougeby"
localization_priority: Normal
ms.prod: "intune"
doc_type: resourcePageType
---

# deviceManagementConfigurationIntegerSettingValue resource type

Namespace: microsoft.graph

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Simple setting value


Inherits from [deviceManagementConfigurationSimpleSettingValue](../resources/intune-deviceconfigv2-devicemanagementconfigurationsimplesettingvalue.md)

## Properties
|Property|Type|Description|
|:---|:---|:---|
|value|Int32|Value of the integer setting.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.deviceManagementConfigurationIntegerSettingValue"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceManagementConfigurationIntegerSettingValue",
  "value": 1024
}
```




