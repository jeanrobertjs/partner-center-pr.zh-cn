---
title: 常见计费方案 | 合作伙伴中心
ms.topic: article
ms.date: 03/15/2019
description: 本主题介绍了在添加新订阅、调整订阅中的许可证数或取消订阅后，你应该会在帐单上看到的内容。 基于使用情况和基于许可证的订阅受到的影响有所不同。
ms.assetid: E4BBD3E7-AFE2-4998-950D-0D27D1178160
author: MaggiePucciEvans
ms.author: evansma
Keywords: 计费、 付款、 订单、 使用情况、 基于许可证的计费、 周年日、 术语、 取消、 续订、 价格公式、 对帐文件、 侦测文件
ms.localizationpriority: medium
ms.openlocfilehash: 2a619356577345923cd78499d2ae5a1f3c6c1614
ms.sourcegitcommit: b1ab80345b4e4af649fb8cc51d96d798e0791ade
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/23/2019
ms.locfileid: "62135317"
---
# <a name="common-billing-scenarios"></a>常见计费方案

**适用于**

-   云解决方案提供商计划帐单

本主题介绍了在添加新订阅、按订阅调整许可证数或取消订阅后，你应该会在帐单上看到的内容。 基于使用情况和基于许可证的订阅受到的影响有所不同。

## <a name="in-this-section"></a>本节内容

-   [基于使用情况的计费](#usagebased)

-   [基于许可证的计费](#licensebased)

## <a href="" id="usagebased"></a>基于使用情况的计费

在订阅周年日期会对基于使用情况的订阅进行每月拖欠计费。 例如，如果订阅周年日期为 15 日，则将在 1 月 15 日收取 12 月 15 日至 1 月 14 日服务期间的费用。 再次在年 2 月 15 日年 1 月 15 日-年 2 月 14 日，服务期间将计费等。生成订阅周年日费用将显示在下面的发票和对帐文件。

有时可能会注意到，有些使用费是缺少发票，或从上个月使用情况付费在当月的发票中。 这不是错误;它指的是，该服务在服务发生之后就加盖时间戳。 使用情况的计费周期结束时的 24 小时内报告将显示在下个月的帐单上。 

在任何时候，可能会挂起基于使用情况的订阅。 

Azure CSP 价目表每月发布一次，可以在合作伙伴中心的“销售”->“定价和产品/服务”页面上找到。 请注意，价格每天都可能会变动，并且会反映在价目表的“更改历史记录”选项卡上。

使用费按每日价格计算。 如果价格在服务期间内发生变化，你将看到每个按比例计算的服务期间和适用价格的计费行。

## <a href="" id="licensebased"></a>基于许可证的计费

**计费：** 基于许可证的订阅上订阅周年纪念日提前计费。

**周年日：** 周年日是你购买订阅的每月天数。 例如，如果你在 1 月 15 日购买了订阅，那么周年日期将是每个月的第 15 天。

**一术语：** 所有基于许可证的订阅都具有 12 个月付费的术语，它在购买日期开始。

**取消：** 在第 1 个月的订阅将为贷记的 100%。 如果在第 2-12 个月暂停订阅，则将按比例进行退款。

**续订：** 基于许可证的所有订阅自动都续订 12 个月付费的术语开始后。

## <a href="" id="licensebasedmonthly"></a>每月计费方案

**方案 1:新的订阅**

你的计费日期是每个月的 15 日。 1 月 13 日，你以一个许可证每月 4 美元的价格购买了新订阅，并选择按月计费。 1 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|1/13/2018         |2/12/2018    |周期费用   |4.00       |1        |4.00    

2 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|2/13/2018         |3/12/2018    |周期费用   |4.00       |1        |4.00    

**方案 2:更改许可证数量**

你的计费日期是每个月的 15 日。 1 月 13 日，你以一个许可证每月 4 美元的价格购买了新订阅，并选择按月计费。 1 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|1/13/2018         |2/12/2018    |周期费用   |4.00       |1        |4.00    

2 月 1 日，你将许可证数量从一个增加到了两个。 2 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
| 1/13/2018        |2/12/2018    |周期实例按比例计算   |-4.00       |1        |-4.00    
|1/13/2018         |2018/1/31    | 周期实例按比例计算   |2.45       |1        |2.45    
|2/1/2018         |2/12/2018    | 周期实例按比例计算   |1.55       |2        |3.10    
|2/13/2018         |3/12/2018    | 周期实例按比例计算   |4.00       |2        |8.00    

**单位价格公式：**

每月价格为 4.00 并且服务期 1/13/2018 – 2/12/2018 共 31 天。 这相当于每日价格为 0.129 (4/31)。

按比例计算的服务期 1/13/2018 – 1/31/2018 共 19 天。

按比例计算的单价 = 2.451 = 19 x 0.129

按比例计算的服务期 2/1/2018 – 2/12/2018 共 12 天。

按比例计算的单价 = 1.54 = 12 x 0.129

**方案 3:挂起前 30 天**

你的计费日期是每个月的 15 日。 1 月 13 日，你以一个许可证每月 4 美元的价格购买了新订阅，并选择按月计费。 1 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
|1/13/2018         |2/12/2018    |周期费用   |4.00       |1        |4.00    

2 月 1 您挂起某一订阅。 2 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|2/12/2018|取消费用|-4.00|1|-4.00

**方案 4:在 30 天后挂起**

你的计费日期是每个月的 15 日。 1 月 13 日，你以一个许可证每月 4 美元的价格购买了新订阅，并选择按月计费。 1 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|2/12/2018|周期费用|4.00|1|4.00

2 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
2/13/2018|3/12/2018|周期费用|4.00|1|4.00

3 月 1 日，你暂停了订阅。 3 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
3/1/2018|3/12/2018|取消费用|-1.72|1|-1.72

**单位价格公式：**

每月价格为 4.00 并且服务期 2/13/2018 – 3/12/2018 共 28 天。 这相当于每日价格为 0.143 (4/28)。

单价 = 服务期中的天数 x 每日价格 x 许可证数。

取消期间 3/1/2018 – 3/12/2018 共 12 天。 

因此的单位价格 =-1.716 (12 x 0.143 x (-1))。

## <a name="annual-billing-scenarios"></a>按年计费方案

**方案 1:新的订阅**

你的计费日期是每个月的 15 日。 1 月 13 日，你以一个许可证每月 4 美元的价格购买了新订阅，并选择按年计费。 1 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|按比例计算购买时的费用|48.00|1|48.00

**方案 2:订阅周年日之后计费日期之前添加许可证**

你于 2017 年 2 月 11 日以每年 211.20 美元的价格购买了具有一个许可证的新订阅。 你的订阅周年日期设置为每个月的 11 号。 Microsoft 计费系统会创建以下计费行： 

-   2017 年 2 月 11 日至 2018 年 2 月 10 日期间的费用为 211.20 美元。 

你于 2017 年 2 月 12 日购买了第二个许可证。 你的计费日期为 2017 年 2 月 14 日。 系统生成了发票和对帐文件。 对帐文件将包含以下计费行： 

|费用开始日期  |费用结束日期  |费用类型  |单价 |数量 | 金额 |
|      :---:   |      :---:   |      :---:   |      :---:   |:---:   |:---:   |
|2017 年 2 月 11 日 |2018 年 2 月 10 日 |按比例计算购买时的费用 |211.20 |1 | 211.20 |

在你的订阅周年日期（2017 年 3 月 11 日），Microsoft 计费系统会为 2017 年 2 月 12 日增加的许可证创建以下计费行： 
-   2017 年 2 月 11 日至 2018 年 2 月 10 日期间的退款为 -211.20 美元。 
-   2017 年 2 月 11 日当天，对于 1 个许可证，每许可证按比例计算的费用为 0.58 美元。 
-   2017 年 2 月 12 日至 2017 年 3 月 10 日期间，对于 2 个许可证，每许可证按比例计算的费用为 15.62 美元。 
-   2017 年 3 月 11 日至 2018 年 2 月 10 日期间，对于 2 个许可证，每许可证按比例计算的费用为 195.00 美元。 

你于 2017 年 2 月 11 日购买订阅。 你于 2017 年 2 月 12 日添加许可证。 你的计费日期为 2017 年 2 月 14 日。 你的订阅将于 2018 年 2 月 11 日续订。

你的下一个计费日期为 2017 年 3 月 14 日，而且系统生成了发票和对帐文件。 对帐文件将包含以下计费行： 

|费用开始日期  |费用结束日期  |费用类型  |单价 |数量 | 金额 |
|      :---:   |      :---:   |      :---:   |      :---:   |:---:   |:---:   |
|2017 年 2 月 11 日 |2018 年 2 月 10 日 |周期实例按比例计算 |-211.20 |1 |-211.20 |
|2017 年 2 月 11 日 |2017 年 2 月 11 日 |周期实例按比例计算 |0.58 |1 |0.58 |
|2017 年 2 月 12 日 |2017 年 3 月 10 日 |周期实例按比例计算 |15.62 |2 |31.25 |
|2017 年 3 月 11 日 |2018 年 2 月 10 日 |周期实例按比例计算 |195.00 |2 |390.00 |

在 2018 年 2 月 11 日，订阅又续订了 12 个月。


**方案 3:更改许可证数量**

你的计费日期是每个月的 15 日。 1 月 13 日，你以一个许可证每月 4 美元的价格购买了新订阅，并选择按年计费。 1 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|按比例计算购买时的费用|48.00|1|48.00

2 月 1 日，你将许可证数量从一个增加到了两个。 2 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  | 
1/13/2018|1/12/2019|周期实例按比例计算|-48.00|1|-48.00
1/13/2018|2018/1/31|周期实例按比例计算|2.47|1|2.47
2/1/2018|1/12/2019|周期实例按比例计算|44.98|2|89.96

**单位价格公式：**

每年价格为 48.00，这相当于每日价格为 0.13 (48.00/365)。

单价 = 服务期中的天数 x 每日价格 x 许可证数。

服务期 1/13/2018 – 1/31/2018 共 19 天。 

因此，单价 = 2.47 (19x0.13x1)

服务期 2/1/2018 – 1/12/2019 共 346 天。 

因此，单价 = 44.98 (346x0.13x2)

**方案 4:挂起前 30 天**

你的计费日期是每个月的 15 日。 1 月 13 日，你以一个许可证每月 4 美元的价格购买了新订阅，并选择按年计费。 1 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|按比例计算购买时的费用|48.00|1|48.00

2 月 1 日，你暂停了订阅。 2 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|取消费用|-48.00|1|-48.00

**方案 5:在 30 天后挂起**

你的计费日期是每个月的 15 日。 1 月 13 日，你以一个许可证每月 4 美元的价格购买了新订阅，并选择按年计费。 1 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|按比例计算购买时的费用|48.00|1|48.00

2 月 15 日的基于许可证的对帐文件将不包含此订阅的任何计费行。
3 月 1 日，你暂停了订阅。 3 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
3/1/2018|1/12/2019|取消费用|-41.34|1|-41.34

**单位价格公式：**

每年价格为 48.00，这相当于每日价格为 0.13 (48.00/365)。

单价 = 服务期中的天数 x 每日价格 x 许可证数。

服务期 3/1/2018 – 1/12/2019 共 318 天。 

因此，单价 = 41.34 (318x0.13x1)。 因为这是退款，所以单价是 -41.34。

**方案 6:暂停和重新激活**

你的计费日期是每个月的 15 日。 1 月 13 日，你以一个许可证每月 4 美元的价格购买了新订阅，并选择按年计费。 1 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|按比例计算购买时的费用|48.00|1|48.00

2 月 1 日，你暂停了订阅。 2 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
1/13/2018|1/12/2019|取消费用|-48.00|1|-48.00

3 月 1 日，你重新激活了订阅。 3 月 15 日的基于许可证的对帐文件将包含以下计费行：

|费用开始日期 |费用结束日期 |费用类型 |单价 |数量 |金额 |
|       :---:      |    :---:       | :---:      |:---:      |:---:    |:---:  |
3/1/2018|1/12/2019|按比例计算购买时的费用|41.34|1|41.34

**单位价格公式：**

每年价格为 48.00，这相当于每日价格为 0.13 (48.00/365)。

单价 = 服务期中的天数 x 每日价格 x 许可证数。

服务期 3/1/2018 – 1/12/2019 共 318 天。 

因此，单价 = 41.34 (318x0.13x1)。
