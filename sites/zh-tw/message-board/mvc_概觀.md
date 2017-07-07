## 解釋 MVC 與 Record

![MVC 概覽](/intro-to-rails/img/mvc.png)

Rails 實做了非常具體的**模型/視圖/控制器（Model/View/Controller）**設計模式，它指引你如何架構化自己的 web 程式。

<h3 id="model">模型</h3>
  
* 把資料存到資料庫
* 訪問資料庫的資料
* 橋接資料庫與物件
  
<h3 id="view">視圖</h3>

* 顯示給人類（或機器）使用的資料
* 網頁是視圖

<h3 id="controller">控制器</h3>

* 作為模型與視圖的連接
* 整合幾個模型的資料
* 總結和過濾資料

在 MVC，模組、視圖、控制器都有很特定的工作。像這樣把歸責處（responsibilities）分離，能讓 rails 程式易於維護與擴展。把歸責處混在一起的話，除錯與增加新功能都會變得很困難。
