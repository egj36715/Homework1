# Homework1

請依照Microsoft Malware Challenges
2015 Dataset，並參考
https://github.com/ManSoSec/Microsoft-M
alware-Challenge所產生的Dataset，其中
有1800+屬性，請回答以下問題：

### (1) 哪些屬性對於惡意程式分類有效？

Useful features:
1. feature 306 (0.013411)
2. feature 117 (0.011097)
3. feature 265 (0.008002)
4. feature 228 (0.007035)
5. feature 1638 (0.006078)
6. feature 95 (0.006050)
7. feature 1497 (0.005857)
8. feature 740 (0.005746)
9. feature 877 (0.005639)
10. feature 314 (0.005220)
11. feature 1667 (0.005106)

### (2) 哪些屬性對於惡意程式分類無效？

Useless features:

1786. feature 1112 (0.000000)
1787. feature 349 (0.000000)
1788. feature 1110 (0.000000)
1789. feature 350 (0.000000)
1790. feature 382 (0.000000)
1791. feature 1093 (0.000000)
1792. feature 868 (0.000000)
1793. feature 1066 (0.000000)
1794. feature 1001 (0.000000)
1795. feature 981 (0.000000)
1796. feature 335 (0.000000)
1797. feature 1475 (0.000000)
1798. feature 1049 (0.000000)
1799. feature 412 (0.000000)
1800. feature 449 (0.000000)
1801. feature 70 (0.000000)
1802. feature 78 (0.000000)
1803. feature 458 (0.000000)
1804. feature 345 (0.000000)

### (3) 用什麼方法可以幫助你決定上述的結論？

用random forest評估每個特徵的重要性，由重要性可得出哪些特徵有效及無效

### (4) 透過Python哪些套件以及方法可以幫助你完成上面的工作？


pandas 匯入csv檔

sklearn 使用sklearn中的random forest演算法

numpy 計算標準差與排序

### (5) 課程迄今有無建議？

希望老師上課中可以多介紹些好用或常用到的套件
