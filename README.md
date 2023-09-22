# 歡迎使用Google Sheet資料查詢輔助工具
## 使用前須知:
> 1.您需要有一個想查詢的Google Sheet文件。
>> 範例：````https://docs.google.com/spreadsheets/d/1cdBNqeGPVt_oZJQ4piooftSuPvhpRvsBFGjpjnvX9-c/edit#gid=0````
>
> 2.APP中共需要填入三個欄位 API憑證、試算表ID、工作表名稱，以下依序介紹:
>> **API憑證**：
>>> (步驟1).於Google Sheet文件中開啟共用功能並將**檢視存取權 給予 所有知道連結的人**。
>>>
>>> (步驟2).若尚未啟用Google Sheet API功能，請先[啟用](https://console.cloud.google.com/marketplace/product/google/sheets.googleapis.com)。  
>>>
>>> (步驟3).若尚未建立Google服務專案，請先[建立](https://console.cloud.google.com/projectcreate)。
>>>
>>> (步驟4).於[憑證頁籤](https://console.cloud.google.com/projectselector2/apis/credentials)中點擊 建立憑證 >> API金鑰，來獲取API金鑰。  
>>> 另外若您想限制金鑰來確保安全性，可自行編輯API金鑰來做相關的使用限制。  
>>>> 範例(使用我的是無法成功的 __因為我有加密過了xd，也請注意金鑰不要外流__)：````KSjkCiM3UUTunNDbQw9XRJYmEePw-18sGrqgKtg````  
>>>> 
>> **試算表ID**：從Google Sheet URL中取得，````https://docs.google.com/spreadsheets/d/{試算表ID}/edit#gid=0````  
>>> 範例：````1cdBNqeGPVt_oZJQ4piooftSuPvhpRvsBFGjpjnvX9-c````
>>
>> **工作表名稱**：Google Sheet中選擇欲查詢之工作表的名稱。
>>> 範例：````溫度量測````
>>
