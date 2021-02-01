[**HOME**](https://github.com/ct-report/summary) | [Europe](https://github.com/ct-report/summary/blob/master/Europe.md) | [USA](https://github.com/ct-report/summary/blob/master/USA.md) | [Rest of the World](https://github.com/ct-report/summary/blob/master/ROTW.md)
-----|-----|------|-----

-------------------------------------

# CY
Contact Tracing - Cyprus

![](apkicon_CY.png)

Until February 1st 2021 the Ministry of Health of Cyprus was still providing 2 different official contact-tracing apps, which were incompatible with each other.

The older one (COVTRACER) is a GPS/Wi-Fi location tracker, while the other official app (COVTRACER EN) is based on BLE proximity tracing through Apple+Google Exposure Notifications API.

**Since February 1st 2021, COVTRACER EN is the only official app of Cyprus** . Former COVTRACER app has been subsequently removed from the Google Play Store.

This app has been developed by RISE CoE & KIOS CoE joint-venture on behalf of the Ministry of Health. It relies on BLE proximity tracing through a decentralized model, that relies on Apple+Google Exposure Notifications API.

Play Store | https://play.google.com/store/apps/details?id=cy.gov.dmrid.covtracer
-----------|---------------------------------------------------------------------
Sources | Unreleased - based on PathCheck EN https://github.com/Path-Check/gaen-mobile
Website | https://covtracer.dmrid.gov.cy/
PathCheck EN | https://www.pathcheck.org/en/covid-19-exposure-notification-app

Versions | Release Date
---------|-------------
1.3.2 | Jan 12, 2021
1.3.1 | Dec 16, 2020
1.2.0 | Dec 1, 2020
2020.11.25 | Nov 25, 2020
2020.11.24 | Nov 24, 2020
2020.11.13 | Nov 13, 2020
2020.11.11 | Nov 11, 2020
2020.11.05 | Nov 5, 2020
2020.11.03 | Nov 3, 2020
2020.10.28 | Oct 28, 2020

- APKLAB Analysis

Build | Link
------|-----
1.3.2 #43 | https://apklab.io/apk.html?hash=b85cd4548caa236c37b47dcfabdef35635d913911ddbefa837b3f7b4a2c9470d

- JoeSandbox Report

Build | Link
------|-----
1.3.2 #43 | https://www.joesandbox.com/analysis/346889/0/html

----------------------------------

As written before, Cyprus had a former official contact-tracing app = **COVTRACER** developed by RISE joint venture - based on MIT PrivateKit:SafePaths solution. It doesn't rely on Bluetooth/BLE to check crossed paths / proximity, but it uses only location tracing.

Indeed, since Coronavirus lockdown has been extended in Cyprus until April 30, such app has been released for those people, whose movements are not currently limited (doctors, nurses, police officers, fire fighters, security forces, people working in important utilities).

The app logs device’s location (GPS+Wi-Fi) every five minutes. Besides, it can import previous location trails through Google Takeout service.

The location log could be exported only by sharing it to a trusted contact (such as a health official). 

Play Store | https://play.google.com/store/apps/details?id=edu.rise.ihnilatis
-----------|-----------------------------------------------------------------
Status | **Removed from the Google Play Store on Feb 1, 2021**
Sources | Unreleased - Based on MIT PrivateKit/SafePaths https://github.com/ct-report/MIT
Website | https://covid-19.rise.org.cy/en

Versions | Release Date
---------|-------------
2.0.2 | Jun 11, 2020
2.0.1 | May 21, 2020
2.0.0 | May 13, 2020
1.0.1 | Apr 12, 2020

- APKLAB Analysis

Build | Link
------|-----
2.0.2 #42 | https://apklab.io/apk.html?hash=92477777361b02d6d480d5b844191f2d93ebf21dae6913189826d8f5032bd699
2.0.1 #34 | https://apklab.io/apk.html?hash=bee53b7a4514cb196e8aea284a00400de3b0141f347293eac6ef0824ecce8e0f
1.0.1 #13 | https://apklab.io/apk.html?hash=2a13b864c84f684f6007dd2f11e96068a2a6ab8d829c332ac7f0d3669681cc2d

- JoeSandbox Report

Build | Link
------|-----
2.0.1 #34 | https://www.joesandbox.com/analysis/234832/0/html
1.0.1 #13 | https://www.joesandbox.com/analysis/225339/0/html
