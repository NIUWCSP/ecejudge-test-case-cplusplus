# ecejudge.tk測資自動化產生工具，此程式由JF主要開發
此為用於基於QDUOJ的測資產生軟體，基於python開發  
目前解答程式僅提供C++撰寫檔案
主要用於解決之前SPJ產生的問題，沒有.out檔案  

# 未來新增功能

 - 新增自動產生測資功能
 - 支援解答程式使用C++
 - 支援指定不同.exe檔
 - 支援.cpp自動編譯成.exe
 - 支援自動壓縮成.zip
 - 支援自動上傳到ecejudge

# 如何使用

 1. 將編譯好的C++程式放到main.py同目錄下(名稱為Q1.exe)
 2. 將測資(僅含.in的檔案)資料夾(名稱為problem_[題目編號]_test_cases)放到跟目錄中
 3. 執行main.py
 4. 輸入題目編號
 5. 在測資資料夾內會自動產生.out的對應檔案
 6. 請自行到資料夾內將.in與.out打包並上傳到ecejudge中