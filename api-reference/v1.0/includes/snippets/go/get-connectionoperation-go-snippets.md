---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

externalConnectionId := "externalConnection-id"
connectionOperationId := "connectionOperation-id"
result, err := graphClient.External().ConnectionsById(&externalConnectionId).OperationsById(&connectionOperationId).Get()


```