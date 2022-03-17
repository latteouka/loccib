## user.txt
這個檔案寫你的帳號，注意不要有任何空格或是換行。

## ChromeDriver放在C
在C底下放chromedriver。(路徑會長這樣 C:\chromedriver.exe)

## 確認現在的Chrome版本為何
[Google Chrome 如何確認程式版本並檢查更新](https://helpcenter.trendmicro.com/zh-tw/article/tmka-08277/)
ChromeDriver的版本要跟上網用的Chrome版本一致，但Chrome會被機關派送更新，所以每過一段時間就會出現錯誤不能用，因為Chrome的版本大於你之前下載的ChromeDriver，這時就要重新去下載ChromeDriver。

## 下載ChromeDriver
[Chrome Driver](https://chromedriver.chromium.org)  
上一個步驟你看到版本是多少就要下載相對應的。
通常一堆裡面你要選的是Latest stable release的chromedriver_win32.zip，然後記得要解壓縮出來才是.exe檔，將其放在C底下。

## Changelog
[3.2.0]2021.05.17 緯度問題。
[3.2.1]2022.03.17 解決有的機關擋https。