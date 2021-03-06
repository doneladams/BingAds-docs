---
title: Paging Data Object - Campaign Management
ms.service: bing-ads-campaign-management-service
ms.topic: article
author: eric-urban
ms.author: eur
description: Defines a paging object that you can use to request objects in batches.
---
# Paging Data Object - Campaign Management
Defines a paging object that you can use to request objects in batches.

## Syntax
```xml
<xs:complexType name="Paging" xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:sequence>
    <xs:element name="Index" type="xs:int" />
    <xs:element name="Size" type="xs:int" />
  </xs:sequence>
</xs:complexType>
```

## <a name="elements"></a>Elements

|Element|Description|Data Type|
|-----------|---------------|-------------|
|<a name="index"></a>Index|The zero-based results page index. For example to request the first page of results, set this value to 0 (zero).|**int**|
|<a name="size"></a>Size|The page size and the number of results to return in the specified page. The maximum size is 1,000.|**int**|

## Requirements
Service: [CampaignManagementService.svc v12](https://campaign.api.bingads.microsoft.com/Api/Advertiser/CampaignManagement/v12/CampaignManagementService.svc)  
Namespace: https\://bingads.microsoft.com/CampaignManagement/v12  

## Used By
[GetLabelAssociationsByLabelIds](getlabelassociationsbylabelids.md)  
[GetLabelsByIds](getlabelsbyids.md)  
[GetMediaMetaDataByAccountId](getmediametadatabyaccountid.md)  
