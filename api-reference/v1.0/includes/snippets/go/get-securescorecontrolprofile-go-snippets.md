---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

secureScoreControlProfileId := "secureScoreControlProfile-id"
result, err := graphClient.Security().SecureScoreControlProfilesById(&secureScoreControlProfileId).Get()


```