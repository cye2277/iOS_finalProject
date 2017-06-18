# iOS_finalProject
整體流程： 首頁（ＭＡＰ）-> 店家資訊 -> 訂購 ->登入->店家確認->訂購完成 -> 取餐通知 -> 取餐  

>頁面規劃
>>```
>>1.首頁（店家位置標記，是否要做店家分類項目？）
>>奕：覺得先不用，有時間再新增欄位和fillter
>>2.店家資訊頁面（店家名稱，營業時間，地址，菜單，訂購Button，是否要做評價？）
>>奕：覺得可以做評價，在取餐完後使用者回App確認可給
>>3.訂購頁面（菜單選擇->訂單確認 -> 填選個人資料-> 訂單送出）
>>4.個人頁面（大頭照，名稱，目前預定的訂單）
>>奕：應該要再加上歷史訂單？
>>5.登入頁面（FB登入）
>>6.店家收取訂單頁面（要給店家自己的權限）




>功能
>>User
>>> ```
>>>登入（第三方登入）-layout/ＦＢ會員功能
>>>google map(首頁) 
>>>店家資訊 - layout/連後端資料庫
>>>點餐功能： 菜單（連資料庫顯示）/ 訂單確認 / 確認後上傳（到資料庫）
>>>個人頁面： 顯示訂單狀態（是否成功）/ 



>>Backend
>>>```
>>>店家編輯功能 - firebase資料庫建立店家資訊
>>>店家動態資訊編輯功能(等候時間、餐點購買有無)

>>Backend by admin
>>>```
>>>店家新增功能- 先從資料庫新增
>>奕：應該不需要做出介面，直接在資料庫新增即可
