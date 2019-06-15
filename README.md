D card algorithm implementation
1, the structure of the number of citizenship numbers is a feature combination code,

It consists of a 17-digit digital ontology code and a checksum code.

The order of arrangement from left to right is: six digit address code, eight digit birth date code three digit sequence code and one digit check code.

2. The address code (the first six digits) indicates the administrative division code of the county (city, flag, district) where the permanent residence of the coded object is located, and is executed in accordance with the provisions of GB/T2260.

3. The date of birth (7th to 14th digits) indicates that the year, month and day of the coded object are executed according to the provisions of GB/T7408. There is no separator between the year, month and day code.

4, the sequence code (fifteenth to seventeenth)
Indicates the sequence number programmed by the person born in the same year, the same month, and the same day within the area identified by the same address code. The odd number of the order code is assigned to the male and the even number is assigned to the female.
5, check code (eighteenth digit)
(1) Seven-digit digital ontology code weighted summation formula S = Sum(Ai * Wi), i = 0,...,16
First, the right to seek the first 17 digits
Ai: Indicates the digital value of the ID number in my position.
Wi: indicates the weighting factor Wi at the i-th position: 7 9 10 5 8 4 2 1 6 3 7 9 10 5 8 4 2
(2) Calculation modulo Y = mod(S, 11)
(3) Obtain the corresponding check code Y through the mode: 0 1 2 3 4 5 6 7 8 9 10
Check code: 1 0 X 9 8 7 6 5 4 3 2


51018219960865412
Li Qihui
Can be derived:
People in Tianpeng Town or Lichun Town, Pengzhou City, Sichuan Province




Chinese translation:
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


51018219960865412
李奇徽
可以得出：
四川省彭州市天彭鎮或者麗春鎮人士
