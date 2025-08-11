# 柯南國際 - 後台系統

使用 React 開發的內部後台系統, 用於管理複雜表單與串接後端資料。

## Tech Stack
- React
- React Router
- MobX
- Ant Design

## Highlights
- 以表單為主的 UI, 並透過 computed properties 進行效能優化
- 能處理大量資料的介面設計
- 僅供內部使用的專案

## Demo GIFs

### Login
- 系統登入介面, 支援帳號密碼靜態驗證與伺服器驗證
- 登入後自動跳轉至主控台首頁

![Login](./assets/gifs/conan_login.gif)

### Menu
- 主選單導航功能, 提供系統各功能模組的快速入口
- 側邊欄選單設計, 支援多層級功能分類
- 檢查用戶身份, 顯示不同的導航

![Menu](./assets/gifs/conan_menu.gif)

### Visitors
- 訪客管理系統, 記錄和追蹤來訪人員資訊
- 支援訪客資料的新增、編輯、查詢功能
- 可查看訪客歷史記錄和訪問狀態

![Visitors](./assets/gifs/consn_visitor.gif)

### Format Item
- 格式項目管理功能, 用於設定和維護系統表單格式
- 支援動態表單欄位配置
- 可自訂欄位類型、驗證規則和顯示樣式

![Format Item](./assets/gifs/conan_format_item.gif)

### Check List
- 檢查表管理系統, 用於建立和管理各種檢核項目
- 支援檢查項目的分類和狀態追蹤
- 提供檢核進度統計和完成率分析

![Sidebar](./assets/gifs/conan_check_list.gif)

### Budget
- 預算管理功能（第一部分）：預算項目建立和基本資訊設定
- 支援預算分類、金額設定和期間管理

![Budget01](./assets/gifs/conan_budget_01.gif)

- 預算管理功能（第二部分）：預算明細編輯和統計分析
- 提供預算執行進度追蹤和差異分析功能

![Budget02](./assets/gifs/conan_budget_02.gif)
