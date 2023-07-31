# Wi-Fi7_AFC_test_authentication
Wi-Fi 7 與 AFC 法規認證研討

# WIFI 7 802.11 be
- wifi 7已經要採用320mhz原本2.4已經不行，要用6ghZ頻段
- 2020 FCC開放各國開始使用(韓國日本因為法規所以還不能用320MHZ)
- multiple resource unit提高使用效率通過率頻寬增加，增加頻譜效益
- OFDMA ,non-OFDMA transmissions
- 每一個punching 至少20 mega hz
- punching只支援80,160,320mhz ppdu bandwidth (支援20,40,80等punching)

## FCC法規要求
- Full testing:
- similar modulation : be,ax,ac,n
- single R :RU 26,52,106
- partial testing:
- legacy moulation: a,b,g

## AFC/CBP
博通高通才有拿到AFC使用執照，政府國家監管單位資料庫連結
- 測試點藉由API來去看供應營運商與我們生產公司去測試
- standard power need AFC DUT test plan
- 
| # | horizental-coordination | vertical-coordination |
|---| ----- | -------- |
|---| xy | z |
|case 1 | CNSS | Barometer|
|case 2 | CNSS | CNSS|
|case 3	| WiFI based | Barometer|
|case4 | WiFI based | Building data|

- bureau veritas必維國際檢驗集團HANK:

- 1. AFC這些東西都掌握在晶片商手中，到時候商品還是需要連接到他們的雲服務
- 2. 還沒有開放認證，現在只是在討論階段
- 3. 如果我們有API TOOL那就可以支援自動測試
- 4. 營運商自己也要測SUT TEST PLAN


