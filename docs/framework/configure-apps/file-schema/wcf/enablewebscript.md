---
title: "<enableWebScript>"
ms.date: "03/30/2017"
ms.assetid: 9c7e96e1-af70-4e6e-ac5c-d67929dddbaa
---
# \<enableWebScript>
This element enables the endpoint behavior that makes it possible to consume the service from ASP.NET AJAX web pages.  
  
 \<system.ServiceModel>  
\<behaviors>  
\<endpointBehaviors>  
\<behavior>  
\<enableWebScript>  
  
## Syntax  
  
```xml  
<enableWebScript />
```  
  
## Attributes and Elements  
 The following sections describe attributes, child elements, and parent elements.  
  
### Attributes  
 None.  
  
### Child Elements  
 None.  
  
### Parent Elements  
  
|Element|Description|  
|-------------|-----------------|  
|[\<behavior>](behavior-of-endpointbehaviors.md)|Specifies the set of endpoint behaviors.|  
  
## Remarks  
 This behavior should only be used in conjunction with either the [\<webHttpBinding>](webhttpbinding.md) standard binding, or the [\<webMessageEncoding>](webmessageencoding.md) binding element.  For more information on this behavior, see <xref:System.ServiceModel.Description.WebScriptEnablingBehavior>.  
  
## See also

- <xref:System.ServiceModel.Configuration.WebScriptEnablingElement>
- <xref:System.ServiceModel.Description.WebScriptEnablingBehavior>
- [AJAX Integration and JSON Support](../../../wcf/feature-details/ajax-integration-and-json-support.md)
- [\<webHttp>](webhttp.md)
