---
title: 合作伙伴安全要求 | 合作伙伴中心
ms.topic: article
ms.date: 10/11/2019
description: 了解对参与云解决方案提供商计划的顾问和合作伙伴的安全要求。
author: isaiahwilliams
ms.author: iswillia
keywords: Azure Active Directory, 云解决方案提供商, 云解决方案提供商计划, CSP, 控制面板供应商, CPV, 多重身份验证, MFA, 安全应用程序模型, 安全应用模型, 安全性
ms.localizationpriority: high
ms.openlocfilehash: b09588387d3b4f0f3f726a700245999c89755199
ms.sourcegitcommit: 9dd6f1ee0ebc132442126340c9df8cf7e3e1d3ad
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/16/2019
ms.locfileid: "72425201"
---
# <a name="partner-security-requirements"></a>合作伙伴安全要求

**适用于**

- 云解决方案提供商计划中的所有合作伙伴
  - 直接计费
  - 间接提供商
  - 间接经销商
- 所有控制面板供应商
- 所有顾问

增强隐私保护和安全性是我们优先关注的事项。 我们知道，最好的防御措施是防患于未然，链条的强度取决于其最弱的一环。 因此，我们需要生态系统中的所有人都行动起来，确保将安全保护措施实施到位。 为了保护合作伙伴和客户，我们引入了一系列强制性安全要求，针对那些参与云解决方案提供商计划的顾问、控制面板供应商和合作伙伴。

## <a name="overview"></a>概述

从 2019 年 8 月 1 日开始，所有合作伙伴都必须对其合作伙伴租户中的所有用户帐户强制实施多重身份验证。 与合作伙伴安全要求相关的条款已添加到[云解决方案提供商计划指南](https://go.microsoft.com/fwlink/p/?LinkId=617100)中。 由于与顾问相关，因此会实施相同的合同要求。

> [!NOTE]
> 强烈建议所有通过主权云（世纪互联、Microsoft Cloud for US Government、德国 Microsoft 云）进行事务处理的合作伙伴立即行动起来，履行这些安全要求。 但是，这些合作伙伴不是必须满足这些在 2019 年 8 月 1 日生效的安全要求。 Microsoft 会在以后更详细地说明如何强制实施这些针对主权云的安全要求。

一旦我们强制实施这些安全要求，不实施这些强制性要求的合作伙伴将不能在云解决方案提供商计划中进行事务处理，也不能利用委托管理权限来管理客户租户。

## <a name="actions-that-you-need-to-take"></a>需要采取的措施

若要符合合作伙伴安全要求，你必须为合作伙伴租户中的每个用户帐户强制实施多重身份验证。 可以通过下述方式之一来实现这一点

- 实现 Azure Active Directory 提供的[对管理员要求 MFA](/azure/active-directory/conditional-access/howto-baseline-protect-administrators) 和[最终用户保护](/azure/active-directory/conditional-access/howto-baseline-protect-end-users)基线保护策略功能，不需额外付费
- 为每个用户帐户购买 Azure Active Directory Premium。 有关详细信息，请参阅[规划基于云的 Azure 多重身份验证部署](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-getstarted)。
- 使用第三方解决方案为合作伙伴租户中的每个用户帐户强制实施多重身份验证。 请参阅[如何强制实施安全要求](#how-the-requirements-will-be-enforced)，更详细地了解如何确保解决方案会提供预期的信息。

### <a name="consideration"></a>注意事项

由于这些要求适用于合作伙伴租户中的所有用户帐户，因此需要遵守一些注意事项，确保顺利进行部署。 这些注意事项包括确定 Azure Active Directory 中不能执行多重身份验证的用户帐户，以及组织所使用的不支持新式身份验证的应用程序和设备。

建议在执行任何操作之前确定以下事项：

#### <a name="do-you-have-an-application-or-device-that-does-not-support-the-use-of-modern-authentication"></a>你是否有不支持使用新式身份验证的应用程序或设备？

强制实施多重身份验证时，系统会阻止旧版身份验证协议（例如 IMAP、POP3、SMTP 等）的使用，因为这些协议不支持多重身份验证。 为了解决此限制问题，可以使用名为[应用密码](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#app-passwords)的功能，确保应用程序或设备仍然能够进行身份验证。 你应该查看[此处](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#considerations-about-app-passwords)记录的应用密码使用注意事项，确定应用密码是否可以在你的环境中使用。

#### <a name="do-you-have-users-using-office-365-provided-by-licenses-associated-with-your-partner-tenant"></a>你是否有用户使用通过与合作伙伴租户相关联的许可证获得的 Office 365？

在实现任何解决方案之前，建议你确定合作伙伴租户中的用户所使用的 Microsoft Office 版本。 在采取任何行动之前，请参阅 [Office 365 部署的多重身份验证计划](https://docs.microsoft.com/office365/admin/security-and-compliance/multi-factor-authentication-plan#enable-mfa)。 用户可能会在使用 Outlook 之类的应用程序时遇到连接问题。 在强制实施多重身份验证之前，必须确保使用的是 Outlook 2013 SP1 或更高版本，且组织已启用新式身份验证。 有关详细信息，请参阅[在 Exchange Online 中启用新式身份验证](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online)。

若要为任何运行 Windows 且已安装 Microsoft Office 2013 的设备启用新式身份验证，需创建两个注册表项。 请参阅[在 Windows 设备上启用适用于 Office 2013 的新式身份验证](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication)。

#### <a name="is-there-a-policy-preventing-any-of-your-users-from-using-their-mobile-devices-while-working"></a>是否有策略阻止用户在工作时使用其移动设备？

必须确定任何阻止员工在工作时使用移动设备的公司策略，因为它会影响你实现的具体的多重身份验证解决方案。 有的解决方案（例如通过实施[基线保护策略](/azure/active-directory/conditional-access/concept-baseline-protection)提供的解决方案）仅允许使用 Authenticator 应用进行验证。 如果组织的某项策略阻止使用移动设备，则应考虑以下选项之一：

- 部署可以在安全系统上运行的基于时间的一次性密码 (TOTP) 应用程序
- 实现第三方解决方案，为合作伙伴租户中的每个用户帐户强制实施多重身份验证，以便提供最适当的验证选项
- 为受影响的用户购买 [Azure Active Directory Premium](https://azure.microsoft.com/pricing/details/active-directory/) 许可证

#### <a name="what-automation-or-integration-do-you-have-that-leverages-user-credentials-for-authentication"></a>你有什么样的利用用户凭据进行身份验证的自动化或集成？

由于此要求是对合作伙伴目录中的每位用户（包括服务帐户）强制实施 MFA，因此任何利用用户凭据进行身份验证的自动化或集成都会受影响。 因此，必须确定在这些情况下使用的是什么帐户。 下面是一个列表，其中包含应该考虑的应用程序或服务的示例：

- 控制面板，用于代表客户预配资源
- 与任何用于客户发票（由于与 CSP 计划相关）和支持的平台的集成
- 利用 Az、AzureRM、Azure AD、MS Online 等模块的 PowerShell 脚本

以上列表并不完整。 因此，必须对环境中利用用户凭据进行身份验证的任何应用程序或服务进行完整的评估。 在可能情况下，应该按[安全应用程序模型框架](https://docs.microsoft.com/partner-center/develop/enable-secure-app-model)中的指南（不同于多重身份验证的要求）进行操作。

## <a name="accessing-your-environment"></a>访问环境

若要更好地了解哪个帐户或用户在进行身份验证时没有受到多重身份验证质询，建议查询 Azure Active Directory 审核日志。 为此，可以使用 [Azure PowerShell](https://docs.microsoft.com/powershell/azure/overview) 模块和下面的脚本。 这样会生成一个报表，该报表详细说明了过去一天内发生的哪些身份验证尝试没有受到多重身份验证质询。

```powershell
Login-AzAccount
$context = Get-AzContext

function Get-SignInEvents
{
    param([string]$userId)

    $content = '{"startDateTime":"' + (Get-Date).AddDays(-1).ToUniversalTime().ToString("yyyy-MM-ddT05:00:00.000Z") + '","endDateTime":"' + (Get-Date).ToUniversalTime().ToString("yyyy-MM-ddTHH:mm:ss.fffZ")  + '","userId":"' + $userId +'","riskState":[],"totalRisk":[],"realtimeRisk":[],"tokenIssuerType":[],"isAdfsEnabled":false}'

    $token = [Microsoft.Azure.Commands.Common.Authentication.AzureSession]::Instance.AuthenticationFactory.Authenticate($context.Account, $context.Environment, $context.Tenant.Id, $null, "Never", $null, "74658136-14ec-4630-ad9b-26e160ff0fc6")

    $headers = @{
    'Authorization' = 'Bearer ' + $token.AccessToken
    'Content-Type' = 'application/json'
        'X-Requested-With'= 'XMLHttpRequest'
        'x-ms-client-request-id'= [guid]::NewGuid()
        'x-ms-correlation-id' = [guid]::NewGuid()
    }

    Invoke-RestMethod -Body $content -Header $headers -Method POST -Uri "https://main.iam.ad.ext.azure.com/api/Reports/SignInEventsV3"
}

$report = $()

Get-AzADUser | foreach {
    $events = Get-SignInEvents $_.Id
    $report += $events.Items
}

$report | Where-Object {$_.mfaRequired -eq $false -and $_.loginSucceeded -eq $true} | Select-Object userPrincipalName, userDisplayName, createdDateTime, resourceDisplayName, loginSucceeded, failureReason, mfaRequired, mfaAuthMethod, mfaAuthDetail, mfaResult, @{Name='policies'; Expression={[string]::join(',', $($_.conditionalAccessPolicies | Select-Object displayName).displayName )}}, conditionalAccessStatus | Export-Csv report.csv
```

运行以上脚本以后，即可在 report.csv 文件中获取详细信息。 该文件将包含一个列表，列表中的身份验证尝试是过去一天内发生的，相关用户没有受到 MFA 质询。 你需要查看每个条目，确定其是否为预期的行为，必要时采取行动。

![评估报表](images/security/assessment-report.png)

## <a name="how-the-requirements-will-be-enforced"></a>将如何强制实施这些要求

合作伙伴安全要求将先后由 Azure Active Directory 和合作伙伴中心强制实施，方法是：检查是否存在 MFA 声明，以便确定是否进行了多重身份验证。 如果使用 Azure 多重身份验证或基线保护策略，则不需执行任何其他操作。

使用第三方多重身份验证解决方案时，可能会出现 MFA 声明未发出的情况。 如果缺少该声明，则 Azure Active Directory 无法确定身份验证请求是否受到了多重身份验证的质询。 若要了解如何验证解决方案是否发出了预期的声明，请参阅[测试合作伙伴安全要求](https://docs.microsoft.com/powershell/partnercenter/test-partner-security-requirements)。

> [!IMPORTANT]
> 如果第三方解决方案未发出预期的声明，则需咨询开发该解决方案的供应商，以确定应该采取哪些措施。

## <a name="resources-and-support"></a>资源和支持

下面是提供支持和示例代码的资源

- [合作伙伴中心安全指南组社区](https://www.microsoftpartnercommunity.com/t5/Partner-Center-Security-Guidance/ct-p/partner-center-security-guidance) - 这是一个在线社区，你可以在其中了解即将发生的事件并提问任何问题。
- [Partner Center .NET Samples](https://github.com/microsoft/partner-center-dotnet-samples)（合作伙伴中心 .NET 示例） - 此 GitHub 存储库包含使用 .NET 开发的示例，用于演示如何实现安全应用程序模型框架。
- [合作伙伴中心 Java 示例](https://github.com/microsoft/partner-center-java-samples) - 此 GitHub 存储库包含使用 Java 开发的示例，用于演示如何实现安全应用程序模型框架。
- [合作伙伴中心 PowerShell - 多重身份验证](https://docs.microsoft.com/powershell/partnercenter/multi-factor-auth) - 这是一篇详述如何使用 PowerShell 实现安全应用程序模型框架的文章。
