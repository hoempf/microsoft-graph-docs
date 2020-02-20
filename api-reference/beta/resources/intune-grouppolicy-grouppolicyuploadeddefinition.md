---
title: "groupPolicyUploadedDefinition resource type"
description: "The entity describes all of the information about a single group policy."
author: "rolyon"
localization_priority: Normal
ms.prod: "Intune"
doc_type: resourcePageType
---

# groupPolicyUploadedDefinition resource type

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

The entity describes all of the information about a single group policy.


Inherits from [groupPolicyDefinition](../resources/intune-grouppolicy-grouppolicydefinition.md)

## Methods
|Method|Return Type|Description|
|:---|:---|:---|
|[List groupPolicyUploadedDefinitions](../api/intune-grouppolicy-grouppolicyuploadeddefinition-list.md)|[groupPolicyUploadedDefinition](../resources/intune-grouppolicy-grouppolicyuploadeddefinition.md) collection|List properties and relationships of the [groupPolicyUploadedDefinition](../resources/intune-grouppolicy-grouppolicyuploadeddefinition.md) objects.|
|[Get groupPolicyUploadedDefinition](../api/intune-grouppolicy-grouppolicyuploadeddefinition-get.md)|[groupPolicyUploadedDefinition](../resources/intune-grouppolicy-grouppolicyuploadeddefinition.md)|Read properties and relationships of the [groupPolicyUploadedDefinition](../resources/intune-grouppolicy-grouppolicyuploadeddefinition.md) object.|
|[Create groupPolicyUploadedDefinition](../api/intune-grouppolicy-grouppolicyuploadeddefinition-create.md)|[groupPolicyUploadedDefinition](../resources/intune-grouppolicy-grouppolicyuploadeddefinition.md)|Create a new [groupPolicyUploadedDefinition](../resources/intune-grouppolicy-grouppolicyuploadeddefinition.md) object.|
|[Delete groupPolicyUploadedDefinition](../api/intune-grouppolicy-grouppolicyuploadeddefinition-delete.md)|None|Deletes a [groupPolicyUploadedDefinition](../resources/intune-grouppolicy-grouppolicyuploadeddefinition.md).|
|[Update groupPolicyUploadedDefinition](../api/intune-grouppolicy-grouppolicyuploadeddefinition-update.md)|[groupPolicyUploadedDefinition](../resources/intune-grouppolicy-grouppolicyuploadeddefinition.md)|Update the properties of a [groupPolicyUploadedDefinition](../resources/intune-grouppolicy-grouppolicyuploadeddefinition.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|classType|[groupPolicyDefinitionClassType](../resources/intune-grouppolicy-grouppolicydefinitionclasstype.md)|Identifies the type of groups the policy can be applied to. Inherited from [groupPolicyDefinition](../resources/intune-grouppolicy-grouppolicydefinition.md). Possible values are: `user`, `machine`.|
|displayName|String|The localized policy name. Inherited from [groupPolicyDefinition](../resources/intune-grouppolicy-grouppolicydefinition.md)|
|explainText|String|The localized explanation or help text associated with the policy. The default value is empty. Inherited from [groupPolicyDefinition](../resources/intune-grouppolicy-grouppolicydefinition.md)|
|categoryPath|String|The localized full category path for the policy. Inherited from [groupPolicyDefinition](../resources/intune-grouppolicy-grouppolicydefinition.md)|
|supportedOn|String|Localized string used to specify what operating system or application version is affected by the policy. Inherited from [groupPolicyDefinition](../resources/intune-grouppolicy-grouppolicydefinition.md)|
|policyType|[groupPolicyType](../resources/intune-grouppolicy-grouppolicytype.md)|Specifies the type of group policy. Inherited from [groupPolicyDefinition](../resources/intune-grouppolicy-grouppolicydefinition.md). Possible values are: `admxBacked`, `admxIngested`.|
|id|String|Key of the entity. Inherited from [groupPolicyDefinition](../resources/intune-grouppolicy-grouppolicydefinition.md)|
|lastModifiedDateTime|DateTimeOffset|The date and time the entity was last modified. Inherited from [groupPolicyDefinition](../resources/intune-grouppolicy-grouppolicydefinition.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|definitionFile|[groupPolicyDefinitionFile](../resources/intune-grouppolicy-grouppolicydefinitionfile.md)|The group policy file associated with the definition. Inherited from [groupPolicyDefinition](../resources/intune-grouppolicy-grouppolicydefinition.md)|
|presentations|[groupPolicyPresentation](../resources/intune-grouppolicy-grouppolicypresentation.md) collection|The group policy presentations associated with the definition. Inherited from [groupPolicyDefinition](../resources/intune-grouppolicy-grouppolicydefinition.md)|

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.groupPolicyUploadedDefinition"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.groupPolicyUploadedDefinition",
  "classType": "String",
  "displayName": "String",
  "explainText": "String",
  "categoryPath": "String",
  "supportedOn": "String",
  "policyType": "String",
  "id": "String (identifier)",
  "lastModifiedDateTime": "String (timestamp)"
}
```


