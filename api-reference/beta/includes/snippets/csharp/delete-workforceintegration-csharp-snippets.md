---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Teamwork.WorkforceIntegrations["{workforceIntegrationId}"]
	.Request()
	.DeleteAsync();

```