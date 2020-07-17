---
title: 서버 용량 모니터링, IP 주소 나열 허용 및 SSH 키 추가
description: Campaign 컨트롤 패널을 사용하면 인스턴스 및 허용 목록 IP 주소별로 SFTP 저장소를 모니터링하고 관리할 수 있습니다.
feature: SFTP Server allow listing
topics: Control Panel
kt: 3266
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 1%

---


# 서버 용량, [!UICONTROL allow listing] IP 주소 모니터링 및 SSH 키 추가

Campaign 컨트롤 패널을 사용하면 SFTP 저장소를 인스턴스별로 모니터링 및 관리하고 [!UICONTROL allow listing]IP 주소를 추가할 수 있습니다.

## 하위 도메인 [!UICONTROL Control Panel] 관리 액세스

하위 도메인 관리에 액세스하려면 다음 [!UICONTROL Control Panel]으로 이동합니다.

* [Experience Cloud 홈](https://experience.adobe.com/#/home) > [!UICONTROL Solution picker]: **[!DNL Campaign]** > **[!UICONTROL Control Panel]** 카드 > **[!UICONTROL Subdomains & Certificates]** 카드

   또는
* URL에서 바로 [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## 서버 용량, [!UICONTROL allow list] IP 주소 모니터링 및 SSH 키 추가

이 비디오에서는 SFTP 서버 저장소 [!UICONTROL Adobe Campaign Control Panel]를 액세스하고, IP 주소를 모니터링하며, SSH 키를 추가하는 방법을 설명합니다 [!UICONTROL allow list] .

>[!VIDEO](https://video.tv.adobe.com/v/27270?quality=12)

### 인터페이스 설명

**인스턴스:** 관리자 권한이 있는 인스턴스만 나열됩니다.

**작업 로그:** 에서 실행된 작업만 [!UICONTROL Control Panel] 나열됩니다. 외부에서 실행된 작업은 [!UICONTROL Control Panel] 포함되지 않습니다(예: 실행 중인 워크플로우 등).

로그에는 조직 관리자가 실행하는 작업만 포함됩니다. 여러 개의 조직이 있는 경우 작업 로그에 다른 조직의 로그가 표시되지 않습니다

**저장소 탭:** 헤더에는 가장 많이 사용되는 상위 3개의 서버가 표시됩니다. 3개 이상의 서버가 있는 경우 나머지 서버는 [!UICONTROL Storage] 탭에 표시됩니다.

**경고 메시지:**

* 주황색 - 서버가 80% 활용됨
* 빨간색 - 서버 사용 중 90%

## 추가 자료

* [SSH 키 생성](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)