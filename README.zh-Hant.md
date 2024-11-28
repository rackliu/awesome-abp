[English](README.md) | 繁體中文 | [简体中文](README.zh-Hans.md) | [Türkçe](README.tr.md)

# Awesome ABP!

[ABP Framework](https://github.com/abpframework/abp) 相關資源的分類清單.

## 目錄
- [Awesome ABP!](#awesome-abp)
  - [目錄](#目錄)
  - [一、官方連結](#一官方連結)
    - [1、官方站點](#1官方站點)
    - [2、其他官方連結](#2其他官方連結)
  - [二、其他清單](#二其他清單)
  - [三、教學/文章](#三教學文章)
    - [1、官方教學](#1官方教學)
    - [2、社群文章](#2社群文章)
    - [3、其他教學](#3其他教學)
  - [四、UI主題](#四ui主題)
    - [1、官方主題](#1官方主題)
    - [2、社群開源主題](#2社群開源主題)
  - [五、應用模組](#五應用模組)
    - [1、開源/免費模組](#1開源免費模組)
      - [1.1、官方開源/免費模組](#11官方開源免費模組)
      - [1.2、社群開源模組](#12社群開源模組)
    - [2、商業化模組](#2商業化模組)
      - [2.1、官方商業化模組](#21官方商業化模組)
  - [六、工具](#六工具)
  - [七、NuGet / NPM 軟體包](#七nuget--npm-軟體包)
  - [八、影片教學](#八影片教學)
    - [1、英文版](#1英文版)
    - [2、其他語言](#2其他語言)
      - [2.1、Türkçe (土耳其語)](#21türkçe-土耳其語)


## 一、官方連結

### 1、官方站點

* **[abp.io](https://abp.io/)** (主頁)
* **[abp.io/docs](https://abp.io/docs/latest/)** (開發文件)
* **[abp.io/community](https://abp.io/community/)** (ABP社群)
* **[abp.io/blog](https://abp.io/blog/)** (官方部落格)

### 2、其他官方連結

* [**twitter**.com/abpframework](https://twitter.com/abpframework)
* [**discord**.gg/abp](https://discord.gg/abp)
* [**stackoverflow**.com/questions/tagged/abp](https://stackoverflow.com/questions/tagged/abp)
* [**github**.com/abpframework](https://github.com/abpframework)

## 二、其他清單

* [Awesome ABP](https://github.com/EasyAbp/awesome-abp) (EasyAbp社群)

## 三、教學/文章

### 1、官方教學

* [Getting Started](https://abp.io/docs/latest/get-started/layered-web-application): 使用ABP框架建立一個腳手架應用以快速開始開發.
* [Quick Start](https://abp.io/docs/latest/tutorials/todo): 開始使用ABP框架並建立一個簡單的TODO應用程式.
* [Web Application Development](https://abp.io/docs/latest/tutorials/book-store/part-01): 10步教你快速建立一個全功能的web應用程式.

### 2、社群文章

​	關注 [abp.io/articles](https://abp.io/community/articles)瞭解更多關於ABP框架核心團隊和社群釋出的最新文章.

### 3、其他教學

​	TODO...

## 四、UI主題

### 1、官方主題

* [Basic Theme](https://abp.io/docs/latest/framework/ui/mvc-razor-pages/basic-theme): 基於Bootstrap框架構建的一個簡約主題，並且未新增任何新的樣式。你可以把它作為基礎主題，並且在此基礎上構建自己的主題或樣式.
* [Lepton Theme](https://abp.io/docs/latest/ui-themes/lepton): 一個專業的UI主題，有多種顏色和風格選項.
* [LeptonX Theme](https://x.leptontheme.com/): 一個現代的、響應式的、靈活的UI主題，新的應用程式推薦使用這個主題。它有兩個版本：
  * [LeptonX Lite](https://abp.io/docs/latest/ui-themes/lepton-x-lite/asp-net-core): 免費版缺少一些高階功能和配置選項
  * [LeptonX](https://abp.io/docs/latest/ui-themes/lepton-x/asp-net-core): 具有所有功能和配置選項的完整版本

### 2、社群開源主題

​	TODO...

## 五、應用模組

​	一個應用模組提供一個完整的、獨立實現的應用且包含業務功能，它們通常有自己的實體、服務、API和UI元件.

### 1、開源/免費模組

#### 1.1、官方開源/免費模組

​	以下這些應用模組都是由ABP核心團隊建立和維護的.

* [Account](https://abp.io/docs/latest/Modules/Account): 為帳號管理提供使用者介面，允許使用者登入/註冊應用程式.
* [Audit Logging](https://abp.io/docs/latest/Modules/Audit-Logging): 將稽核日誌持久化到資料庫中.
* [Background Jobs](https://abp.io/docs/latest/Modules/Background-Jobs): 一個在後臺持久執行的任務管理模組.
* [Blogging](https://abp.io/modules/Volo.Blogging): 建立和管理你自己的部落格站點 (不再維護，請使用 [CMS Kit](https://abp.io/docs/latest/Modules/Cms-Kit/Index)或者[blogging feature](https://abp.io/docs/latest/Modules/Cms-Kit/Blogging) 作為替代品).
* [CMS Kit](https://abp.io/docs/latest/Modules/Cms-Kit/Index): 一套可複用的內容管理系統套件模組.
* [Docs](https://abp.io/docs/latest/Modules/Docs): 用於建立一個管理技術文件的站點. ABP框架[官方文件](https://abp.io/docs) 已經在使用這個模組.
* [Feature Management](https://abp.io/docs/latest/Modules/Feature-Management): 系統功能管理模組[檢視詳情](https://abp.io/docs/latest/framework/infrastructure/features).
* [Identity](https://abp.io/docs/latest/Modules/Identity): 基於微軟官方身份認證庫，用以管理組織、角色、使用者和他們的許可權.
* [IdentityServer](https://abp.io/docs/latest/Modules/IdentityServer): 整合IdentityServer4.
* [Permission Management](https://abp.io/docs/latest/Modules/Permission-Management): 用於許可權管理以及持久化.
* [Setting Management](https://abp.io/docs/latest/Modules/Setting-Management): 用於管理和持久化系統設定資訊 [檢視詳情](https://abp.io/docs/latest/framework/infrastructure/settings).
* [Tenant Management](https://abp.io/docs/latest/Modules/Tenant-Management): 租戶系統[多租戶](https://abp.io/docs/latest/framework/architecture/multi-tenancy)管理模組.

#### 1.2、社群開源模組

​	TODO...

### 2、商業化模組

#### 2.1、官方商業化模組

* [Account](https://abp.io/modules/Volo.Account.Pro): 整合登入、註冊、忘記密碼、電子郵件啟用、社交登入和其他帳號相關功能.
* [Audit Logging](https://abp.io/modules/Volo.AuditLogging.Ui): 使用者稽核日誌以及實體變更歷史報表.
* [Chat](https://abp.io/modules/Volo.Chat): 線上即時通訊系統.
* [CMS Kit](https://abp.io/modules/Volo.CmsKit.Pro): 構建定製化的內容管理系統.
* [File Management](https://abp.io/modules/Volo.FileManagement): 檔案管理系統（檔案上傳、下載、分層管理）.
* [Forms](https://abp.io/modules/Volo.Forms): 問卷調查系統.
* [GDPR](https://abp.io/modules/Volo.Gdpr): 允許使用者下載和刪除應用程式收集的個人數據.
* [Identity](https://abp.io/modules/Volo.Identity.Pro): 使用者、角色、組織和許可權管理.
* [Identity Server UI](https://abp.io/modules/Volo.Identityserver.Ui): 使用者身份認證管理服務，如客戶端、API資源、身份資源、秘密、應用程式URL、claims等.
* [Language Management](https://abp.io/modules/Volo.LanguageManagement): 系統UI本地化資源管理.
* [Payment](https://abp.io/modules/Volo.Payment): 整合各種支付閘道器.
* [SaaS](https://abp.io/modules/Volo.Saas): 管理租戶、版本和功能，建立你的多租戶或者SaaS應用程式.
* [Text Template Management](https://abp.io/modules/Volo.TextTemplateManagement): 提供一個用於管理文字或郵件模版的管理系統.
* [Twilio SMS](https://abp.io/modules/Volo.Abp.Sms.Twilio): 透過Twilio雲服務傳送簡訊.

## 六、工具

* [ABP CLI](https://abp.io/docs/latest/CLI): ABP框架的官方CLI.
* [ABP Suite](https://abp.io/suite): 自動生成基於分層結構的CRUD頁面工具，並且安裝和下載應用模組的原始碼. 這個工具屬於 [ABP商業版](https://abp.io/) 的一部分.
* [ABP Studio](https://abp.io/studio): ABP Studio 是一個跨平臺桌面應用程式，旨在透過自動化為您提供舒適的開發環境，提供有關您的解決方案的見解，使開發、執行和部署您的解決方案變得更加容易。
* [AbpDevTools](https://github.com/enisn/AbpDevTools): 非官方的 CLI 應用程式，包含一組使 ABP 開發變得更容易的工具。

## 七、NuGet / NPM 軟體包

* [所有官方NuGet和NMP軟體包](https://abp.io/packages)

## 八、影片教學

​	請檢視 **[abp.io/community](https://abp.io/community)** 網站，瞭解我們在這裡或者其他平臺發表的ABP框架和.NET相關的最新影片帖子，以下羅列了部分影片資源：

### 1、英文版

* [基於ABP框架構建.NET微服務 - 全系列](https://abp.io/community/videos/.net-microservice-with-abp-full-series-m6opqjb1)

### 2、其他語言

#### 2.1、Türkçe (土耳其語)

* [ABP & Blazor ile kapsamlı bir eğitim seti](https://www.udemy.com/course/web-tabanli-on-muhasebe-1-5/) (Udemy, toplam 100 saat)
* [ABP Framework Eğitim Serisi](https://www.youtube.com/watch?v=JvwPpSTEAvg&list=PLBEMB-Eql15s3kaMvQ6pIobVk492a7s9j&index=1)  (YouTube, ücretsiz)
