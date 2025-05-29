---
title: Android용 푸시 알림 시작 - 소개
description: 이 튜토리얼에서는 Adobe Campaign에서 푸시 알림을 전송하고 Android 앱에서 이러한 알림을 받는 단계를 설명합니다.
feature: Push
jira: KT-5951
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noDisplay
exl-id: 291c2e3a-c126-439d-9753-06a4091bbda0
source-git-commit: b56c0af81ed73fa06fe4846d0794167d35a26305
workflow-type: tm+mt
source-wordcount: '355'
ht-degree: 100%

---

# Android용 푸시 알림 시작 - 소개

Adobe Campaign을 통해 개인화 및 세그먼트화한 [!DNL push] 알림을 [!DNL iOS] 및 [!DNL Android] 모바일 디바이스로 전송할 수 있습니다. 이 튜토리얼에서는 Adobe Campaign에서 [!DNL Android] 앱으로 [!DNL push] 알림을 전송하는 단계를 설명합니다.

## 사전 요구 사항

시작하려면 먼저 다음을 수행해야 합니다.

1) **Android 모바일 애플리케이션**

   이 튜토리얼에서는 모바일 애플리케이션을 설정하는 데 필요한 세부 단계를 다루지 않습니다. **[!DNL Android]모바일 애플리케이션을 [!DNL Campaign SDK]와 통합해야 합니다**.

   제품 설명서에서 필요한 단계에 대한 자세한 설명을 확인할 수 있습니다.

   [모바일 애플리케이션에 Campaign SDK 통합](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=ko)

   Experience Platform Mobile SDK를 사용할 수도 있습니다. 자세한 내용은 튜토리얼 비디오를 참조하십시오.

   [Experience Platform Mobile SDK를 사용하여 푸시 채널 구성](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html?lang=ko)

2) **[!DNL Mobile App channel]패키지 설치**

   [!DNL Mobile App channel] 패키지는 [!DNL Campaign] 인스턴스에 설치해야 합니다. 다음 비디오에서는 [!DNL Mobile App channel]이 인스턴스에 설치되어 있는지 확인하는 방법과 설치되어 있지 않은 경우 설치하는 방법을 설명합니다.

>[!VIDEO](https://video.tv.adobe.com/v/340425?quality=12&learn=on&captions=kor){transcript=true}

## 튜토리얼 개요

[!DNL Neotrip] [!DNL Android] 모바일 앱 가입자에게 개인화된 홍보용 [!DNL push] 알림을 보내려고 합니다. [!DNL Neotrip] 앱은 [!DNL Campaign SDK]로 구성되었으며 [!DNL Mobile App channel]이 [!DNL Campaign] 인스턴스에서 활성화되었는지 확인했습니다.

다음 구성 단계가 필요합니다.

### 1단계: 앱 구독 스키마를 확장하여 [!DNL push] 알림 개인화

[!DNL push] 알림을 개인화하려는 경우, 먼저 [앱 구독 스키마를 확장하여](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) 사용자가 서비스에 가입하면 앱에서 받은 개인 설정 값을 저장할 수 있습니다.

### 2단계: Android 서비스를 구성하고 Campaign에서 모바일 애플리케이션 만들기

다음으로 [Android 서비스를 구성하고 Campaign에서 모바일 애플리케이션을 만들어야](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md) 합니다. 이 단계에서는 푸시 알림의 대상으로 [!DNL Neotrip] 앱을 정의합니다.

### 3단계: 푸시 알림 구성 및 전송

그러면 [푸시 알림을 구성하고 전송할](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md) 준비가 되었습니다.

## 튜토리얼 시작

1단계: [앱 구독 스키마 확장](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
