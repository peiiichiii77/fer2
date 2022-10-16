# Linux背景知識-Linux是什麼?!
 Linux是一種自由開放原始碼的類似Unix 的作業系統，其廣泛運用於伺服器和嵌入式系統中。具有可移植性的Open Source的作業系統，它的程式碼可以被修改適合在各種機器上。運行目前主流的 Linux 發佈版本包括：Debian、Fedora、CentOS、Ubuntu 等。
 ![image](https://user-images.githubusercontent.com/113227666/196044548-fcfeb022-c99b-4d90-9598-16e265df937d.png)


## Linux背景知識-檔案系統目錄結構
![image](https://user-images.githubusercontent.com/113227666/196044516-29e55f7c-6e18-4406-8ba5-79f30f5c1904.png)

## Linux各個目錄存放的內容
**/**：根目錄，所有檔案皆從根目錄開始，只有root使用者具該目錄的許可權 </br>
**/root**：該目錄為系統管理員，也稱作超級許可權者的使用者主目錄 </br>
**/bin**：存放著經常使用的命令 </br>
**/boot**：系統啟動時必須讀取的檔案, 包括系統核心 </br>
**/home**：存放普通使用者的家目錄，每個使用者都有自己的家目錄 </br>
**/etc**：放置與系統設定、管理相關的檔案 </br>
**/usr**：這是一個非常重要的目錄，使用者的應用程式和檔案都放在這個目錄下，類似與windows下的program files目錄 </br>
**/tmp**：供全部使用者暫時放置檔案的目錄 </br>
**/var**：系統執行時, 內容經常變動的資料或暫存檔(log file), 都會放置在這個目錄裡 </br>

## Linux指令-查看檔案目錄資訊
**ls -l**：顯示目錄下的所有檔案詳細資訊 </br>
**ls -al**：顯示目錄下的所有檔案(包含隱藏檔)詳細資訊 </br>

![image](https://user-images.githubusercontent.com/113227666/196044956-7adee5d9-75ed-4b28-ad7c-72d052cb2e41.png)

## Linux指令-更改檔案或目錄權限

**chown** 可修改檔案或目錄的擁有者及群組
![image](https://user-images.githubusercontent.com/113227666/196044999-b7a07b54-004b-419f-a5e2-d97fcbb9e5a9.png)
