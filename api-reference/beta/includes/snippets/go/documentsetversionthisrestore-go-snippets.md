---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

siteId := "site-id"
listId := "list-id"
listItemId := "listItem-id"
documentSetVersionId := "documentSetVersion-id"
graphClient.SitesById(&siteId).ListsById(&listId).ItemsById(&listItemId).DocumentSetVersionsById(&documentSetVersionId).Restore(site-id, list-id, listItem-id, documentSetVersion-id).Post()


```