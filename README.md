# PHP 程式設計師養成班
## 課程大綱
### 第零章 課前說明 [內容](ch0/README.md)
#### 課程教材使用方式
+ 申請 Github 帳號
+ 課堂下載檔案
#### 專案製作
+ 專案構思與製作
+ 程式碼放置於 GitHub 站台
#### 證照考試
+ 國外證照考試
  + Zend PHP
  + Oracle MySQL  
#### 課程後該學會的事
+ 了解網站應用系統架構
+ 了解開發環境需求與應用
+ 了解版控需求與應用
+ 了解佈署流程與方法
  
### 第一章 環境建置 [內容](ch1/README.md)
#### 開發環境建置
+ 安裝開發工具 VSCode 
+ 安裝 Docker 容器(Only For Windows 10)
+ 安裝 Podman 容器(Only For CentOS 8 Linux)
+ 安裝 Git 工具
#### 參考文獻

### 第二章 Docker 基本操作 [內容](ch2/README.md)
#### Docker 基礎操作
+ Docker 容器概念
+ Docker 三大基礎元件
+ Docker 常用指令
+ Docker 組織結構概論
#### Docker 容器管理
#### Docker 映像檔管理
#### Docker 倉庫管理
#### Docker 網路與儲存管理
#### Docker 維護工作
#### 參考文獻

### 第三章 MySQL 資料庫操作與 SQL 基本語法 [內容](ch3/README.md)
#### 使用 Docker 安裝 MySQL
+ 使用 Docker 指令安裝 MySQL Server
+ 安裝 MySQL Workbench
#### 資料收集與整理
+ 資料收集與整理
+ 資料表正規化
#### MySQL 基本操作
+ SQL 語法認知
+ 資料庫內可接受的資料類型
+ 操作資料庫與資料表
+ 操作資料內容
+ 操作資料庫系統
#### 參考文獻

### 第四章 Git 版控與 GitHub 操作 [內容](ch4/README.md)
#### 版控的觀念與使用
+ 關於版本控制
+ 本地端版本控制
+ 集中式版本控制系統
+ 分散式版本控制系統
+ Git 基礎要點
#### 使用 Git 指令
+ 初次設定 Git
+ 取得一個 Git 倉儲
+ 紀錄變更到版本庫中
#### 使用 GitHub 站台儲放程式碼
+ 與遠端協同工作
+ 顯示遠端
+ 新增遠端版本庫
+ 從遠端獲取或拉取
+ 推送到遠端
+ 檢視遠端
+ 移除或重新命名遠端
#### 使用 MarkDown 語法
+ 概述
+ 區塊元素
+ 區段元素
#### 參考文獻

### 第五章 HTML 與 CSS 基本語法 [內容](ch5/README.md)
#### HTML5 基本語法
+ 概要
+ HTML語法
+ HTML主要結構
+ HTML5 新增標籤
#### CSS3 基本語法
+ CSS 概述
+ CSS 語法格式定義
#### Bootstrap 4 框架基本語法
+ Bootstrap 概要
+ 開始使用 Bootstrap 的方式
+ Bootstrap 網格的概念
#### VS Code Extensions 安裝提示
+ 由 Extensions 安裝 VS Code 外掛軟體
+ HTML ＆ CSS 推薦外掛套件
#### 參考文獻

### 第六章 PHP 基本語法 [內容](ch6/README.md)
#### PHP 基本觀念
+ 站台的運作方式
+ PHP 的運作方式
+ PHP 包含 HTML 標籤
#### 變數
+ 變數
+ 變數的存活範圍
+ 常數
#### 資料型態
+ 標準資料型態
+ 資料型態轉換
#### 運算子
+ 運算式與運算子
+ 運算子的優先順序
+ 太空船運算子
#### 陣列
+ 宣告方式
#### 控制結構
+ 決策控制
+ 迴圈控制
+ 巢狀迴圈
+ break 與 continue
#### 參考文獻

### 第七章 PHP 進階語法 I [內容](ch7/README.md)
#### 函數
+ 函數的作用
+ 使用方式
+ 可變長度引數
+ 遞迴函數
+ 參數與回傳值宣告
#### 物件導向
+ 物件導向的目的
+ 類別與物件 (Class & Object)
+ 封裝 (Encapsulation)
+ 建構子(constructor)與解建構子(destructor)
+ 繼承(extends)
+ 覆寫(override)
+ 介面(interface)
+ 抽象類別 (Abstract)
+ 靜態屬性(static)
+ 多型(Polymorphism)
+ 多載(overloading)
+ 匿名類別
#### 參考文獻

### 第八章 PHP 進階語法II [內容](ch8/README.md)
#### 類別的應用與處理
+ 自動載入
+ 命名空間(Namespace)
+ 特徵(Trait)
#### 例外處理
+ 掌握錯誤與例外
+ 錯誤的情況處理分類
+ 錯誤與例外的不同
+ 例外的情況處理分類
+ try...catch 敘述
+ 抛出例外與接收
+ Exception 類別的繼承
+ 多層次的例外處理
#### 參考文獻

### 第九章 套件、框架、Composer [內容](ch9/README.md)
#### 套件
+ PHP 套件庫
+ 自製套件
#### Composer
+ Composer 工具
+ Composer 運作方式
#### 框架
+ 框架思維
+ Laravel 框架特色
+ 安裝與設定 Laravel
+ Laravel 目錄結構
+ Artisan 工具
+ Laravel 運作流程
#### 參考文獻

### 第十章 Laravel 的ＭＶＣ I [內容](ch10/README.md)
#### HTTP 相關基本知識
+ HTTP 資料傳遞
+ HTTP 標頭與回應
#### MVC 概念
+ MVC (Model-View-Controller)概念
#### Laravel 的 Router 模組
+ Laravel Routing簡介
+ Laravel Routing 語法
+ 路由參數傳遞
+ 使用路由群組
+ 路由命名
+ 路由表的查詢
#### 參考文獻

### 第十一章 Laravel 的ＭＶＣ II [內容](ch11/README.md)
#### Controller 的使用
+ Controller 的用途
+ 建立 Controller
+ 由 Route 轉發要求給 Controller
+ 路由可以指定 Controller 處理七種不同要求
+ Controller 命名空間
#### View 與 Blade 的使用
+ Laravel 的網頁根目錄
+ Laravel 的 View 目錄
+ 基本使用 View 的方式
+ Blade 樣板引擎
+ Blade 語法
+ Blade 樣板實作
#### 參考文獻
+ [Bootstrap for laravel](https://www.positronx.io/how-to-properly-install-and-use-bootstrap-in-laravel/)

### 第十二章 Laravel 與資料庫的結合 I [內容](ch12/README.md)
#### 基本資料庫連線與操作
+ 連接資料庫的設定方式
+ 利用 MVC 連接資料庫
+ 其他的 SQL 語法使用方式
#### 使用 Migration 操作資料庫物件
+ Migration 用途
+ Migration 初始化
+ 建立 Migration
+ 操作 Migration 指令
+ Schema 類別
+ Blueprint 操作資料表方法
#### 使用 Eloguent 查詢資料庫內容
+ Eloguent 概述
+ Eloguent 建立過程
+ Eloquent 中 Model 的常見屬性值列表
+ Eloquent 中常見的查詢類方法
+ Eloquent 資料取出的方法
+ Collection 物件的方法
#### 參考文獻

### 第十三章 Laravel 與資料庫的結合 II [內容](ch13/README.md)
#### Eloquent 管理資料庫內容
+ 新增資料
+ 更新資料
+ 大量新增
+ 大量更新
+ 保護欄位
+ 刪除資料
+ 大量刪除資料
+ 軟刪除
#### Eloquent 關聯與限制
+ 關聯的使用
+ 關聯的類型與使用方式
#### 參考文獻

### 第十四章 請求、回傳、資料驗證 [內容](ch14/README.md)
#### 請求與回應
+ 概述
+ 請求的方法
+ 回應的方法
+ 方法欺騙
#### 資料驗證
+ 資料驗證
+ 表單驗證
#### 參考文獻

### 第十五章 使用中介層 [內容](ch15/README.md)
#### Laravel 的中介層
+ 中介層概述
+ 建立中介層
+ 註冊中介層
#### Laravel 內建 Auth 機制
+ 建立 Laravel 內建的 Auth 機制
+ 註冊路由
+ 資料庫內容
+ Auth 控制器
+ View 的使用
#### 自建 Auth 認證登入
+ 註冊路由
+ 編寫控制器
+ 修改 View 內容
#### 參考文獻

### 第十六章 自訂 Artisan 指令 [內容](ch16/README.md)
#### 自訂 Artisan 的 Commands
+ 簡介說明
+ 建立自訂指令
+ 註冊自訂指令
#### 新增 Repository 建立的 Commands
#### 新增 Service 建立的 Commands
#### 參考文獻

### 第十七章 使用依賴注入(Dependency injection) [內容](ch17/README.md)
#### 前言
+ 簡介說明
#### 使用 Repository
+ Repository Pattern
+ 範例實作
#### 使用 Service
+ Service Layer
+ 範例實作
#### 參考文獻

### 第十八章 測試程式撰寫 [內容](ch18/README.md)
#### 整合測試
#### 單元測試
#### 瀏覽器測試
#### 參考文獻

### 第十九章 使用 NoSQL [內容](ch19/README.md)
#### Redis
#### MongoDB
#### RebbitMQ
#### Websocket
#### 參考文獻

### 第二十章 Web API 開發 [內容](ch20/README.md)
#### RESTful Web API 開發
#### Client Web API 開發
#### 參考文獻

### Append A. 正式環境佈署篇 [內容](appa/README.md)
#### 正式環境建置
+ 安裝與使用虚擬機軟體
  + 下載 VirtualBox，官網：https://www.virtualbox.org 
  + 安裝 VirtualBox
  + 新增虚擬機與調整設定
+ 安裝與設定 Linux 作業系統
  + 安裝 CentOS 8 Linux 作業系統
  + 設定網路組態與遠端控制
#### 參考文獻

### Append B. Linux 作業系統基本操作 [內容](appb/README.md)
#### 檔案與目錄管理
+ Linux 檔案與目錄架構
+ 檔案與目錄管理指令
#### 使用者與群組管理
+ 使用者與群組概念
+ 使用者與群組管理指令
#### 基本權限管理
+ Linux 權限概念
+ 權限管理指令
#### 軟體安裝與管理
+ Linux 軟體安裝概念
+ YUM 軟體安裝與管理
#### Web 站台架設
+ Nginx 套件安裝與啟用
+ PHP 套件安裝與啟用
#### 基本安全設定
+ 基本防火牆應用
+ SELinux 的基本應用
#### 參考文獻

#### 課後綜合練習(一) [內容](exercise1/README.md)
#### 課後綜合練習(二) [內容](exercise2/README.md)
#### 課後綜合練習(三) [內容](exercise3/README.md)
#### 課後綜合練習(四) [內容](exercise4/README.md)
#### 課後綜合練習(五) [內容](exercise5/README.md)
#### 課後綜合練習(六) [內容](exercise6/README.md)
#### 課後綜合練習(七) [內容](exercise7/README.md)
#### 課後綜合練習(八) [內容](exercise8/README.md)

#### 參考書籍
#### 參考網站

+ [MarkDown 文件](https://markdown.tw/)
+ [GitFlow 觀念](https://medium.com/kuma%E8%80%81%E5%B8%AB%E7%9A%84%E8%BB%9F%E9%AB%94%E5%B7%A5%E7%A8%8B%E6%95%99%E5%AE%A4/%E5%9F%BA%E7%A4%8E-git-flow-%E5%B7%A5%E4%BD%9C%E6%B3%95-fa50b1dddc4f)
+ [什麼是 CI/CD](https://medium.com/@william456821/%E4%BB%80%E9%BA%BC%E6%98%AF-ci-cd-72bd5ae571f1)
+ [Git達人教你搞懂GitHub基礎觀念](https://www.ithome.com.tw/news/95283)
+ [git 教學文件](https://zlargon.gitbooks.io/git-tutorial/content/)