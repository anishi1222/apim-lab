---
title: 前提条件
has_children: false
nav_order: 1
---


## Workshopを始める前に

開始前に、以下の前提条件がすべて揃っていることを確認してください。

- Azure
  - [Azure Portal](https://www.portal.azure.com) にアクセスできること。
  - 利用可能な [Azure サブスクリプション](https://portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) にアクセスできること。
  - API Managementインスタンスのデプロイのため、リソースグループのContributorロール (共同作成者ロール) を持っていること。
- Part 3では、既存のAPIをAPI Managementインスタンスに追加するため、 以下のAPIやWebサイトが利用できること。
  - [Colors API](https://colors-api.azurewebsites.net/swagger/v1/swagger.json) このWebサイトが停止している場合は、 [この手順](../10-additionalTopics/apimanagement-10-2-containerinstance.md) でAPIをデプロイできます。
  - [Colors website](https://colors-web.azurewebsites.net) このWebサイトが停止している場合は、 [この手順](../10-additionalTopics/apimanagement-10-2-containerinstance.md) でWebサイトをデプロイできます。
  - [Star Wars API](https://swapi.dev/)
  - [Calculator API](http://calcapi.cloudapp.net/calcapi.json)
- Part 8では、 [Azure DevOps](https://dev.azure.com) 組織にアクセスできる必要があります。

**API Managementインスタンスの生成には時間がかかります。** Workshop実施に先立ち、API Managementの作成手順に従ってインスタンスを生成してください。
