---
title: Azure 计划价目表 | 合作伙伴中心
ms.topic: article
ms.date: 10/15/2019
description: 如何查看 Azure 计划中的订阅价目表
author: LauraBrenner
ms.author: labrenne
Keywords: ''
robots: ''
ms.localizationpriority: high
ms.openlocfilehash: 64f7b6930f31afc63397ae3ed0e0dba2357b0f1e
ms.sourcegitcommit: cd90a59ff0ea81197b603abcb7bf462c4fb1edbe
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/09/2019
ms.locfileid: "72171279"
---
# <a name="price-list-for-the-new-commerce-experience-in-csp-for-azure"></a>Azure 的 CSP 新商务体验价目表 

CSP 中的新 Azure 商务体验的价目表将在合作伙伴中心发布。 价目表在实时准确的文件中动态传送，仅以美元显示价格。 但是，计费是按客户所在国家/地区支持的货币进行的。 有关客户所在国家/地区的货币计费的详细信息，请阅读 [Azure 计划 - 计费](azure-plan-billing.md)。

## <a name="see-pricing-for-subscriptions-under-the-azure-plan-pricing"></a>参阅 Azure 计划定价中的订阅定价

1. 在左侧的“合作伙伴中心”菜单中选择“销售”，然后选择“市场”。  

2. 在“导出类型”旁边，选择“Azure 计划消耗定价”。  

3. 在“定价日期”旁边选择所需的日期，例如“当前”。   注意：还可以选择“外汇汇率”导出当前的外汇汇率。 

![Azure 定价 2](images/azure/pricelist2.jpg)

4. 在“市场”下，选择产品的“类型”和“类别”，或搜索产品。    将根据搜索显示可用的产品。

![pricing](images/azure/Azurepricelist1.jpg)

5. 然后选择“导出 Azure 计划价目表”来下载所选产品的 Azure 计划价格。 


![导出价目表](images/azure/pricelist1.png)



## <a name="azure-price-list-specifics"></a>Azure 价目表具体信息

- Azure 计划定价将在合作伙伴中心的“市场”页中的“销售”下提供。 

- 可以导出 Azure 计划消耗服务、Azure 预留项和外汇汇率的内容。

- 导出选项包括：

    - **当日定价**：包括当月 1 号到当前日期的所有计量项目和定价。 这包括新价格、更改的价格或已删除的价格。 所有价格具有生效开始日期和结束日期，以解释这些价格是新价格还是已删除的价格。

    - **上个月的定价**：按月下载每种类型的资源。 对于定价文件，这包括该月可用的所有计量项目。 如果在该月中途显示了新的计量项目，将显示一个具有生效日期的计量项目，该日期反映该计量项目的可用性。 与停用的价格相似，将显示一个结束日期用于描述该计量项目何时不再可用。

    - **外汇汇率**：外汇汇率在每月 1 号的前一天下午 6 点 (PST) 可供下载。 例如，如果你想要 11 月份的汇率，请在 10 月 31 日下载。 还会提供上个月的外汇汇率。

    - **符合条件的服务**：合作伙伴赚取的返点适用于 **Azure 计划消费定价**（合作伙伴可从 Azure 计划定价页将其导出）中列出的服务。 请注意存在一些例外情况，包括但不限于第三方和 Azure 预留项。

- 价目表中的价格是直接价格。 某些合作伙伴可能符合赚取返点的条件。 有关如何计算合作伙伴赚取的返点的信息，请阅读[如何计算和支付合作伙伴赚取的返点](partner-earned-credit-explanation.md)。


## <a name="price-list-data"></a>价目表数据

|**字段**   |**描述**   |
|--------------------------|:---------------------------|
|ProductTitle  |产品的标题或名称|
|ProductID   |产品的 ID|
|SKuId|SKU 的 ID|
|SkuTitle|SKU 的标题或名称|
|发布者|第一方始终是 Microsoft|
|SkuDescription|SKU 的说明|
|UnitOfMeasure|收费或计费单位|
|TermDuration|适用于基于期限的产品（包括预留项），表示期限的长短|
|市场|定价适用的市场|
|货币|定价使用的货币|
|UnitPrice|每个单位的价格|
|PricingTierRangeMin|分层定价中应用的最低价格|
|PricingTierRangeMax|分层定价中应用的最高价格|
|EffectiveStartDate|定价开始日期|
|EffectiveEndDate|定价结束日期|
|MeterIds|产品 SKU 的计量 ID|
|MeterType|计量类型|
|标记|项的属性，对于 Azure 计划定价，此字段为 Azure，或 Azure 和预留项（具体而言，是预留项）|

详细的[价目表信息](https://partner.microsoft.com/commerce/sales?type=Any&category=Any)  
