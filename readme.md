# NodeJS 課堂心得   
講師: 小賴老師 ｜ 授課時間: 2021/12/25 ~ 12/26

## 12/25 課堂重點 (詳閱小賴老師共筆)
- 終端機指令: `cd`, `pwd`, `ls`, `mkdir`, `touch`, `cat`...etc
- Git & GitHub: `git init`, `git add [filename]`, `git commit -m "messages"`...etc
- Git flow: 建立分支與合併 `git switch [要合併別人的branch]` --> `git merge [要被合併的branch]`
    - 通常不會在開發或正式分支上做commit或push
    - 正式專案會常用pull request
- markdown語法
- 軟體開發流程: Scrum vs. 瀑布式開發(硬體開發流程):

Scrum:
![](https://www.visual-paradigm.com/servlet/editor-content/scrum/what-are-scrum-time-boxed-events/sites/7/2018/12/five-scrum-events.png "Scrum")

> 通常一個sprint(衝刺)約2~4周，專案成員會事先將每個功能設定難易度點數、每個sprint設定需達成的總點數，再開始從較優先要開發的功能進入sprint。
> (不過台商較多假scrum，大多還是硬體開發思維)

瀑布式(Waterfall model):

![](https://i.imgur.com/5BlHgUT.jpg "瀑布式")

> 屬硬體開發思維，容易導致工程師專案後期都在加班QAQ


## 12/26 課堂重點 (詳閱小賴老師共筆)
- 資訊相關科系五大必修: 
    - 資料結構 (DS)
    - 演算法 (Algo)
    - 資料庫 (DB): 正規化 --> 後端需要了解如何設計table schema
        但正規化不是一定要遵守的法律，有時會因為商業邏輯的特殊設定而違反
    - 網路 Networking
    - 作業系統 (OS)
- NodeJS 簡介 & 特色
    - 版本: 偶數版通常是正式長期維護版(LTS)
        ![](https://raw.githubusercontent.com/nodejs/Release/master/schedule.svg?sanitize=true "NodeJS version")

---
## 轉職 & 面試相關
**一些後端面試必考題:**
- PHP & SQL 基礎 (可再複習)
- 箭頭函式
- this
- reduce
```javascript
const array1 = [1, 2, 3, 4];
// 一般寫法
const reducer = function(previousValue, currentValue){
    previousValue + currentValue;
}
// 箭頭函式寫法
const reducer = (previousValue, currentValue) => previousValue + currentValue;

```
附上一張網路上找到感覺能更理解reduce的圖:
![](https://i.redd.it/9dm5u0f5mrr41.jpg "map filter reduce")


**一些面試時可以先問公司的:**
- Commit message style?
- Coding-style? (不同語言style不同)
- git-flow都怎麼跑?
- 有沒有跑scrum?
- code review 的規範?

**修行在個人的部分:**
> Keep learning! <br> 現在會的東西只是起點，未來有更多東西要靠自己學
- 想走後端的建議可學PHP的框架: Laravel
- 可去天瓏書店挖寶，小賴老師推薦的:
    - 《重構》 by M.Fowler(1999) 主旨為程式碼開發原則
    - 《JavaScript the good part》 好書，若要精進JS可看
- 資工系五大必修，建議可找時間補足

## 一點個人心得
因為年紀比較大的關係(咳)，從決定轉職到現在，經歷了很多自我懷疑和低谷。
不過也在過程中認知到自己是真的喜歡寫程式，從無名小站年代開始會研究一點點標籤語言、自訂喜歡的樣式，到轉職前在W3school自學HTML和JavaScript，到現在...開始可以寫出一個簡單的動態網頁，而且(意外地XD)對資料庫和後端比較有興趣、可以熬夜寫個不停...原來人真的會在學習的過程中，更認識自己。

很認同小賴老師說的，
> 我們都是大人了，要對自己的人生負責。

雖然常會後悔當初怎麼沒選資工系、或為什麼不早點跨進來，但相信過往的人生也不是沒有成長或累積，要帶上過去的自己一起放眼未來XD

給自己未來的代辦事項:
1. GitHub 經營 & 更新 (作品集導向)
2. 個人網頁規劃 & 建置
3. 學習 PHP 框架 (Laravel)
4. 資工系五大必修惡補
    - 資源: [哈佛CS50](https://cs50.harvard.edu/college/2022/spring/) 
5. 讀《重構》
6. 嘗試在 LeetCode 刷題
7. 每日(盡量)一篇英文新聞
9. 其他: 想到再更新



