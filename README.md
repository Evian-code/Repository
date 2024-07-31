## 常用脚本
1.提取文件夹中所有文件名称并保存到xlsx文件（作者：AcePlay https://www.bilibili.com/read/cv25175725/ 出处：bilibili）
dir %cd%/b|for %%i in (*) do @echo %%~ni|find /v "test"|find /v "GetFileName">>test.xlsx
