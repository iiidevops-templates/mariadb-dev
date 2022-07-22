# mariadb
:warning: 此範本為開發用資料庫，不包含master、slave以及headless svc，請勿作為Production使用
:information_source: 資料庫資料不提供儲存功能， 因此若本專案有任何commit更動都會導致原本的資料庫資料遺失，請commit前一定要注意(這資料庫並無掛載volume，因此無法救回)。

## 取出及管理資料庫資料
若在開發過程中想要將目前的資料庫資料取出可以透過UI上的介面，選擇資料庫管理系統後即可以網頁的形式去對資料庫進行各項操作, 也可請使用支援 MySQL/MariaDB 的工具程式處理 Exp. [HeidiSQL](https://www.heidisql.com/)
