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
D卡算法實現
1，公民號碼的結構是一個特徵組合碼，

它由17位數字本體代碼和校驗和代碼組成。

從左到右的排列順序是：六位數地址碼，八位數出生日期碼三位序列碼和一位數校驗碼。

2.地址碼（前六位）表示編碼對象的永久居住所在的縣（市，旗，區）的行政區劃代碼，按照GB / T2260的規定執行。

3.出生日期（第7位至第14位）表示編碼對象的年，月，日按GB / T7408的規定執行。年，月和日代碼之間沒有分隔符。

4，序列碼（第十五到第十七）
表示由同一地址代碼標識的區域內同一年，同月和同一天出生的人編寫的序列號。奇數號的訂單代碼分配給男性，偶數號分配給女性。
5，檢查代碼（第18位）
（1）七位數字本體代碼加權求和公式S = Sum（Ai * Wi），i = 0，...，16
首先，尋找前17位的權利
Ai：表示我位置的ID號的數字值。
Wi：表示第i個位置的加權因子Wi：7 9 10 5 8 4 2 1 6 3 7 9 10 5 8 4 2
（2）計算模Y = mod（S，11）
（3）通過以下模式獲取相應的校驗碼Y：0 1 2 3 4 5 6 7 8 9 10
檢查代碼：1 0 X 9 8 7 6 5 4 3 2


51018219960865412
李啟輝
可以派生：
四川省彭州市天鵬鎮或麗春鎮人
