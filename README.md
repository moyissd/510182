身份證算法實現
1，號碼的結構公民身份號碼是特徵組合碼，
由十七位數字本體碼和一位校驗碼組成。
排列順序從左至右依次為：六位數字地址碼，八位數字出生日期碼三位數字順序碼和一位數字校驗碼。
2，地址碼（前六位數）表示編碼對象常住戶口所在縣（市，旗，區）的行政區劃代碼，按GB / T2260的規定執行。
3，出生日期碼（第七位至十四位）表示編碼對像出生的年，月，日，按GB / T7408的規定執行，年，月，日代碼之間不用分隔符。
4，順序碼（第十五位至十七位）
表示在同一地址碼所標識的區域範圍內，對同年，同月，同日出生的人編定的順序號，順序碼的奇數分配給男性，偶數分配給女性。
5，校驗碼（第十八位數）
（1）十七位數字本體碼加權求和公式S = Sum（Ai * Wi），i = 0，...，16
，先對前17位數字的權求和
艾：表示第我位置上的身份證號碼數字值
Wi：表示第i位置上的加權因子Wi：7 9 10 5 8 4 2 1 6 3 7 9 10 5 8 4 2
（2）計算模Y = mod（S，11）
（3）通過模得到對應的校驗碼Y：0 1 2 3 4 5 6 7 8 9 10
校驗碼：1 0 X 9 8 7 6 5 4 3 2

如：51018219960865412
可以得出：
四川省彭州市天彭鎮或者麗春鎮人士
