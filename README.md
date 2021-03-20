# GFM_Syntax

<style>
    *{
        font-family : ariel, 'sans-serif';
        margin-bottom :20px;
        margin-top :20px;
    }
    #BGC{
        background-color : #addb40;
        color:white;
        font-size : 64px;
        padding:20px;
        }
    .lime{color : #addb40;}
    .orange{color : #cf6d1d;}
    #px32{font-size:32px;}
    
    table{
        border:1px solid lightgray;
        width: 100%;
        table-layout :fixed;
        border-collapse: collapse;
    }
    th{
        background-color : #addb40;
        font-weight : bold;
        color : white;
    }
    th, td
    {
        border:1px solid lightgray;
        padding : 5px;
    }
</style>

<div id="BGC"><strong>Basic Syntax</strong></div>

# <span class="lime"><strong>비주얼 스튜디오 코드사용법</strong> </span>
* 에디터 뷰 : Ctrl+Shift+V 
<!-- 마크다운으로 주석 처리 가능 -->
# <span class="lime"><strong>제목(header)</strong></span>

### 1.제목을 표현할 때, (#)을 심볼을 단어, 또는 문장앞에 사용할 수있다. 
* h1 부터 h6 까지 # 의 개수로 표현할 수있다.

| Markdown | Output |
|:---|:---|
| # 제목 1 | <h1>제목 1</h1> |
| ## 제목 2 | <h2>제목 2</h2> | 
| ### 제목 3 | <h3>제목 3</h3> | 
| #### 제목 4 | <h4>제목 4</h4> | 
| ##### 제목 5 | <h5>제목 5</h5> | 
| ###### 제목 6 | <h6>제목 6</h6> | 
* (#) 심볼을 사용할때는 공백이 한칸 있어야 적용된다.

### 2.또 다른방법으로는 (==) (--) 심볼을 사용할 수있다.
* 단, h1 태그와 h2 태그만 표현가능하다.

| Markdown | Output |
|:---|:---|
| 제목 1<br>====| <h1>제목 1</h1>|
| 제목 2<br>-----| <h2>제목 2</h2>|

<!-- 마크다운으로 주석 처리 가능 -->

# <span class="lime"><strong>단락 나누기(Paragraphs)
</strong></span>
### 엔터키를 이용해 공백으로 단락을 나눌수 있다.
<!-- 마크다운으로 주석 처리 가능 -->

# <span class="lime"><strong>줄바꿈(Line Breaks)
</strong></span>

### br 태그를 이용해서 줄을 바꿀수 있다.
<!-- 마크다운으로 주석 처리 가능 -->

# <span class="lime"><strong>텍스트 강조</strong></span>
### 1.볼드(Bold)
* 볼드체를 적용시키고 싶은 부분부터, 종료점까지
아래와 같은 방식을 사용하면 된다

| Markdown | Output |
|:---|:---|
| I just love ** bold text** | I just love <strong>bold text</strong> |
| I just love __ bold text__ |  I just love <strong>bold text</strong> | 
| Love** is**bold | Love<strong>is</strong>bold</td> | 

* 단, 문장 중간을 볼드할때 (__)를 사용하면 안된다.

### 2.이텔릭체(Italic)
* 이텔릭체를 적용시키고 싶은 부분부터 종료점 까지 아래와 같은 방식을 사용하면 된다.

| Markdown | Output |
|:---|:---|
| Italicized text is the * cat's meow*</span> | Italicized text is the <em>cat's meow</em>. |
| Italicized text is the _ cat's meow_ |  Italicized text is the <em>cat's meow</em>. | 
| A* cat*meow | A<em>cat</em>meow</td> | 

* 단, 문장 중간을 이텔릭 할때 (_)를 사용하면 안된다.

### 3.볼드와 이텔릭을 섞어서 사용할 수도 있다.
<br>
<!-- 마크다운으로 주석 처리 가능 -->

# **<span class="lime">인용구(Blockquotes)</span>**

### 1.인용구를 사용 하기 
* 위해서는 적용하고 싶은 문장, 글 앞에 > 를 사용하면 적용된다.

```markdown
> Dorothy followed her through many of thebeautiful rooms in her castle.
```

> Dorothy followed her through many of the beautiful rooms in her castle.

### 2.여러 인용구 적용하기
* 인용구를 여러번 적용하고 싶다면 두 문장, 글 사이제 공백줄에 > 를 추가시킨다.

```markdown
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### 3.중첩된 인용구 적용하기
* 중첩 하고 싶은 위치에 >> 를 사용하면 된다.

```markdown
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### 4.인용구 내부에 다른 원소 추가시키기.

* 인용구 내부에 여태 배운 "제목" "볼드" "이텔릭체" 등등, 특정 마크다운 요소를 사용할 수 있다. 

```markdown
> ## **The quarterly results look great!**
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```

> ## **The quarterly results look great!**
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
The rendered output looks like this:
<!-- 마크다운으로 주석 처리 가능 -->

# <span class="lime"><strong>리스트(Lists)</strong></span>
### 리스트에는 순서리스트와 비순서리스트가 있다.

* 인용구(Blockquotes)와 단락 나누기(Paragraphs)를 적용시킬 수 있다.

1. **순서리스트**
    * 순서리스트는 리스트에 번호가 매겨지는 리스트 이다.
    * 적용 시키려면 (번호). 를 적고 한칸 띄고난뒤 내용을 적으면 된다.
        * 단, 어떤 숫자를 적든 마크다운 화면에는 1,2,3... 순서로 차례대로 표시된다.
        * 순서 리스트 내부에 충첩으로 리스트를 적용 할 수있다.
    * ')'를 사용하면 안된다.

| Markdown | Output |
|:---|:---|
| 1. First item<br>2. Second item<br>3. Third item<br>4. Fourth item| 1. First item<br>2. Second item<br>3. Third item<br>4. Fourth item|
|1. First item<br>2. Second item<br>3. Third item <br> (공백) 1. Indented item<br>(공백) 2. Indented item <br>4. Fourth item|<ol><li>First item</li><li>Second item</li><li>Third item<ol><li>Indented item</li><li>Indented item</li></ol></li><li>Fourth item</li></ol>|

2. **비순서 리스트**
* 비순서 리스트는 리스트에 ○,●,■ 심볼로 매겨지는 리스트이다.
    * 적용 시키려면 *, +, - 를 적고 한칸 띄고난뒤 내용을 적으면 된다.
        * 비순서 리스트 내부에 충첩으로 리스트를 적용 할 수있다.
    * *, +, -를 일관성 있게 사용해야 한다.

| Markdown | Output |
|:---|:---|
|:- First item<br>- Second item<br>- Third item<br>- Fourth item|<ul><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ul>|
|+ First item<br>+ Second item<br>+ Third item<br>+ Fourth item|<ul><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ul>|
|* First item<br>* Second item<br>* Third item<br>* Fourth item|<ul><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ul>|
|:- First item<br>- Second item<br>- Third item<br>(공백) - Indented item<br>(공백) - Indented item<br>- Fourth item|<ul><li>First item</li><li>Second item</li><li>Third item<ul><li>Indented item</li><li>Indented item</li></ul></li><li>Fourth item</li></ul>|
<!-- 마크다운으로 주석 처리 가능 -->

# <span class="lime"><strong>코드블럭</strong></span>

### 하나의 탭, 또는 4번의 공백으로 코드블럭을 적용 시킬수 있다.

**예시**

```markdown
    1.  Open the file.
    2.  Find the following code block on line
        <html>
          <head>
            <title>Test</title>
          </head>
    3.  Update the title to match the name of your website.
```

아래는 적용된 모습이다.

---
1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.
---
<!-- 마크다운으로 주석 처리 가능 -->

# <span class="lime"><strong>경계선(Horizontal Rules)</strong></span>

*** 또는 --- 또는 ___ 으로 경계선을 적용 시킬수 있다.
<!-- 마크다운으로 주석 처리 가능 -->

# <span class="lime"><strong>이미지 적용 & 링크 적용</strong></span>


### <span>1. 링크 적용 : "!\[]\();"</span>

 ```markdown
 ![표시](상대경로 혹은 절대경로) /// 이미지 적용
 -> ![lime](https://techcrunch.com/wp-content/uploads/2015/05/limes-e1431965418433.jpg?w=1390&crop=1)
```

### <span>2. 링크 적용 : "\[]\();"</span> 

```markdown
 [표시](웹주소, 상대경로 혹은 절대경로)/// 링크적용
 -> My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
```

---
아래는 적용된 모습이다.

---
![lime](https://techcrunch.com/wp-content/uploads/2015/05/limes-e1431965418433.jpg?w=1390&crop=1)

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

---
<!-- 마크다운으로 주석 처리 가능 -->

# <span class="lime"><strong>URLs & Email Addresses</strong></span>
### <>를 감싼뒤에 그 안에 ULR, Email 주소를 작성한다.

```markdown
<https://felipuss.tistory.com/>
<fake@example.com>
```

아래는 적용된 모습이다.

---
<https://felipuss.tistory.com/> <br>
<fake@example.com>

---
<!-- 마크다운으로 주석 처리 가능 -->

# <span class="lime"><strong>Escape문</strong></span>

### backslash to escape the following characters

* 평소에 그냥 사용할 수 없는 특수문자를 \ (백슬래쉬)를 이용해 특문표현이 가능하다.
<!-- 마크다운으로 주석 처리 가능 -->

# <span class="lime"><strong>HTML 문법 사용</strong></span>
### 1.마크다운 언어는 HTML또한 사용 가능하다.
### 2. < style> 태그로 글자의 색,크기, 등등 CSS문법을 사용할 수있다.
![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/240px-HTML5_logo_and_wordmark.svg.png)

<div id="BGC"><strong>GFM Syntax</strong></div>


# <span class="lime"><strong>표만들기</strong></span>

### 1. '|' 로 일단 표를 나눈다.
* | 으로 나눈것만큼 열을 생성할 수가 있다
### 2. '---' 로 머리글 행을 표시한다.
* |:---| 는 왼쪽정렬
* |---:| 는 오른쪽 정렬
* |:---:| 는 가운데 정렬

```markdown
| Markdown | Output |
|:---|:---|
```

### 3. 이제 한줄 한줄 행을 설정할 수 있다. 

```markdown
| # 제목 1 | <h1>제목 1</h1> |
| ## 제목 2 | <h2>제목 2</h2> | 
```

아래는 적용된 모습이다.

---

| Markdown | Output |
|:---|:---|
| ## 제목 2 | <h2>제목 2</h2> |
| ### 제목 3 | <h3>제목 3</h3> | 

---


# <span class="lime"><strong>체크바(Task lists)
</strong></span>

### 1.체크바를 생성하기 위해선 '-' 으로 리스트를 생성하고 대괄호를 작성한다.
 * [x] : 체크 표시
 * [] : 체크 안됨

```markdown
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request

### 2.괄호를 작성하기 위해 이스케이프문 '\\'를 사용한뒤 괄호를 적용하면 된다.

```markdown
- [ ] \(Optional) Open a followup issue
```

<!-- 마크다운으로 주석 처리 가능 -->

# <span class="lime"><strong>언급기능(Mentioning people & teams)
</strong></span>

### 1. You can mention a person or team on GitHub  
* typing @ plus their username or team name.


```markdown
@github/support What do you think about these updates?
```
# <span class="lime"><strong>Autolinked references and URLs
### 1.URLs
* GitHub automatically creates links from standard URLs.

```markdown
Visit https://github.com
```

Visit https://github.com

### 2. Issues and pull requests
* Within conversations on GitHub, references to issues and pull requests are automatically converted to shortened links.

|Reference type	 |Raw reference	 |Short link |
|:---|:---|:---|
|Issue or pull request URL|	https://github.com/jlord/sheetsee.js/issues/26|	#26|
| # and issue or pull request number| #26	| #26 |
|GH- and issue or pull request number| GH-26| GH-26|

#1
mojombo#1
mojombo/github-flavored-markdown#1

### 3.Commit SHAs
* References to a commit's SHA hash are automatically converted into shortened links to the commit on GitHub.

|Reference type	|Raw reference	|Short link|
|:---|:---|:---|
|Commit URL	|https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e	|a5c3785|
|SHA|	a5c3785ed8d6a35868bc169f07e40e889087fd2e|	a5c3785|
|User@SHA|	jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e|jlord@a5c3785|

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

# <span class="lime"><strong>취소선(Strikethrough)
### 1. '~~' 을 취소선을 적용할 범위마다 앞뒤로 적어주면 적용된다.

    ~~안녕하세요~~

~~안녕하세요~~
    
