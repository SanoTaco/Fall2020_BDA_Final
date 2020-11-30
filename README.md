# Fall2020_BDA_Final
## 動機：
學業成績對於一個學生來說是非常重要的，但我們並不知道什麼是影響成績最大的因素。我們會通過對資料集的分析，建立模型來預測學生成績。

## 計畫摘要：
我們利用資料中的受教育程度，班級，選擇課程，成績，出勤特徵，以及家長參與等信息，來進行資料分析及視覺化，通過分析資料並建立模型預測學生成績。

## 研究步驟：
資料预处理->資料視覺化->模型建立分析->参数调优->预测效果

## 環境：
Python 3.7 + Jupyter Notebook

## Python 所需套件：
pandas、sklearn、seaborn、matplotlib、numpy

## 參考資料：
Students' Academic Performance Dataset (xAPI-Edu-Data) https://www.kaggle.com/brianvancil/xapi-edu-data1
Seaborn API Website
https://seaborn.pydata.org/api.html

## 資料集栏位介紹：
1.	gender-学生性别(“M”或“FM”)
2.	National-學生國籍(’ Kuwait’,’ Lebanon’,’ Egypt’,’ SaudiArabia’,’ USA’,’ Jordan’,’ Venezuela’,’ Iran’,’ Tunis’,’ Morocco’,’ Syria’,’ Palestine’,’ Iraq’,’ Lybia)
3.	PlaceofBirth-學生出生地(“KuwaIT”、“Jordan”、“Iraq ”  、“lebanon”、“SaudiArabia ”、“USA ”、“Palestine”、“Egypt”、“Tunis”、“Iran”、“Lybia ”、“Syria ”、“Morocco”、“venzuela”)
4.	StageID-學生所屬教育級別(“lowerlevel”、“MiddleSchool ”、“HighSchool”)
5.	GradeID-年級(“G-01”、“G-02”、“G-03”、“G-04”、“G-05”、“G-06”、“G-07”、“G-08”、“G-09”、“G-10”、“G-11”、“G-12”)
6.	SectionID-學生所屬教室(‘A’，‘B’，‘C’)
7.	Topic—課程('IT'、 'Math'、 'Arabic' 、'Science'、'English'、 'Quran' 、'Spanish' 、'French' 、'History'、 'Biology' 'Chemistry' 、'Geology')
8.	Semester-學年(“F”、“S”)
9.	Relation-家長與學生之關係(’mom’,’father’)
10.	raisedhands-學生在課堂上有舉手的次數(数字：0-100)
11.	VisITedResources-學生訪問課程內容的次數(数字：0-100)
12.	AnnouncementsView-學生檢查新公告的次數(数字：0-100)
13.	Discussion-學生參與討論小組的次數(数字：0-100)
14.	ParentAnsweringSurvey-家長是否回答學校提供的調查(’Yes’,’No’)
15.	ParentschoolSatisfaction-家長對學校的滿意度(’Yes’,’No’)
16.	StudentAbsenceDays-每名學生缺席天數(above-7, under-7)
17.	Class-學生成績分類(L、M、H)
