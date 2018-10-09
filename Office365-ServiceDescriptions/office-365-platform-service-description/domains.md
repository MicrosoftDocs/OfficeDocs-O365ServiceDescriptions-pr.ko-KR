---
title: 도메인
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/10/2017
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: 도메인을 추가 하는 경우 단계별 마법사를 사용 하 사용자를 추가 하 고 Office 365 전자 메일 주소 및 기타 서비스 비즈니스 이름으로 변환할 수 있습니다. 마법사를 완료 하는 경우 현재 전자 메일 공급자에 이동 하는 대신 Office 365 될 예정인 비즈니스 전자 메일 시작 합니다. 자세한 내용은 참조 Office 365에 사용자 및 도메인을 추가 합니다. 21Vianet에서 운영 하는 Office 365를 사용 하는 경우 도메인을 확인 합니다.를 참조 하십시오.
ms.openlocfilehash: 47c378482b8a8d09e2f2516968af99af9472c641
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036485"
---
# <a name="domains"></a>도메인

도메인을 추가 하는 경우 단계별 마법사를 사용 하 사용자를 추가 하 고 Office 365 전자 메일 주소 및 기타 서비스 비즈니스 이름으로 변환할 수 있습니다. 마법사를 완료 하는 경우 현재 전자 메일 공급자에 이동 하는 대신 Office 365 될 예정인 비즈니스 전자 메일 시작 합니다. 자세한 내용은, [사용자 및 Office 365에 도메인 추가](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611)참조 합니다. 21Vianet에서 운영 하는 Office 365를 사용 하는 경우 [도메인을 확인 합니다.](http://go.microsoft.com/fwlink/?LinkID=733344&amp;clcid=0x409)를 참조 하십시오.
  
## <a name="custom-domains"></a>사용자 지정 도메인
<a name="BKMK_CustomDomains"> </a>

Office 365 구독에 도메인 최대 900 개까지 추가할 수 있습니다. 그러나 다른 Microsoft 클라우드 서비스에서 이미 사용 중인 Office 365에 도메인을 추가할 수 없습니다. 즉, 여러 Office 365 구독을 동일한 도메인을 추가할 수 없습니다. 자세한 내용은 [도메인 FAQ](https://support.office.com/en-us/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a)를 참조 하십시오.
  
### <a name="second-and-third-level-domains"></a>2차 및 3차 수준 도메인
<a name="BKMK_SecondAndThirdLevelDomains"> </a>

Office 365 Enterprise 및 Office 365 Business를 사용하여 marketing.contoso.com 등의 3차 수준 도메인을 비롯한 모든 수준의 도메인을 추가할 수 있습니다. [Office 365에 사용자 지정 하위 도메인 또는 여러 도메인 추가](http://go.microsoft.com/fwlink/?LinkID=733345&amp;clcid=0x409)를 참조하세요. 21Vianet에서 운영하는 Office 365를 사용하는 경우 [21Vianet에서 운영하는 Office 365에서 사용자 지정 하위 도메인 또는 여러 도메인 추가](http://go.microsoft.com/fwlink/?LinkID=733346&amp;clcid=0x409)를 참조하세요.
  
## <a name="domain-verification-and-managing-dns-records"></a>도메인 확인 및 DNS 레코드 관리
<a name="BKMK_ManagingDNSRecords"> </a>

Office 365를 사용하여 DNS 호스팅 공급자에서 모든 DNS 레코드를 관리하거나 Office 365에서 도메인의 DNS 레코드를 설정 및 관리하도록 할 수 있습니다. 레코드를 계속 관리하는 경우 필요에 따라 Office 365 서비스를 가리키도록 특정 레코드를 변경합니다. 각 레코드에 사용할 특정 값을 포함하여 레코드 추가에 대한 단계별 지침을 제공하는 도메인 등록 기관 목록은 [Office 365용 DNS 레코드 만들기](https://go.microsoft.com/fwlink/p/?LinkID=270173)를 참조하고, 21Vianet에서 운영하는 Office 365를 사용하는 경우에는 21Vianet에서 운영하는 Office 365용 공급자에서 DNS 레코드 만들기를 참조하세요. 
  
Office 365에서 도메인의 DNS 레코드를 관리하는 경우 먼저 Office 365를 가리키도록 도메인의 이름 서버 레코드를 전환해야 합니다. 그러면 Office 365에서 Office 365 서비스를 설정하고 도메인의 DNS 레코드가 Office 365에서 관리됩니다.
  
도메인이 GoDaddy에 등록되어 있는 경우 Office 365는 GoDaddy에 필요한 레코드를 만들 수 있습니다. 
  
DNS 레코드가 호스트되는 위치에 관계없이 Office 365 또는 다른 호스팅 공급자에서 호스트되는 공개 웹 사이트를 사용하도록 DNS 레코드를 설정할 수 있습니다. 
  
Office 365는 DNS 레코드를 사진에 확인하여 DNS 문제를 찾고 해결하는 데 도움을 줍니다. DNS 레코드가 예상과 다르면 Office 365 관리 센터에서 알림이 수신되고 확인된 가능한 문제의 해결 방법을 알려주는 정보가 표시됩니다.
  
자세한 내용은 [Office 365에서 DNS 레코드를 관리하는 방법](https://go.microsoft.com/fwlink/p/?LinkID=270144)을 참조하세요. 21Vianet에서 운영하는 Office 365의 경우 [DNS 레코드를 관리할 때 Office 365용 DNS 레코드 만들기](http://go.microsoft.com/fwlink/?LinkID=817326&amp;clcid=0x409)를 참조하세요.
  
## <a name="sharing-a-domain"></a>도메인 공유
<a name="BKMK_ManagingDNSRecords"> </a>

Office 365에서 도메인에 대 한 일부 전자 메일 주소 및 일부 이전 전자 메일 공급자에서 사용 하 여 Office 365를 시험 수 있습니다. 것이 좋습니다에 사용 하는 동안 Office 365의 파일럿 추가 설치 단계를 수행 해야 하 고 Office 365 서비스에 대 한 일부 제한이 있기 때문에 합니다. 자세한 내용은 다음을 참조 합니다.
  
- [중소기업용 Office 365 파일럿](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [대기업용 Office 365 파일럿(FastTrack 사용)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>기능 가용성
<a name="BKMK_ManagingDNSRecords"> </a>

Office 365 계획, 독립 실행형 옵션 및 온-프레미스 솔루션 간의 기능 가용성을 확인하려면 [Office 365 플랫폼 서비스 설명](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)을 참조하세요.
  
