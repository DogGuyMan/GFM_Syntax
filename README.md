<style>
    *{
        font-family : ariel, 'sans-serif';
        margin-bottom :20px;
        margin-top :20px;
    }
    #BGC{
        background-color :red;
        color:black;
        font-size : 64px;
        padding:20px;
        }
    .lime{color : red;}
    .orange{color : #cf6d1d;}
    #px32{font-size:32px;}
    
    table{
        border:1px solid lightgray;
        width: 100%;
        table-layout :fixed;
        border-collapse: collapse;
    }
    th{
        background-color : red;
        font-weight : bold;
        color : black;
    }
    th, td
    {
        border:1px solid lightgray;
        padding : 5px;
    }
</style>

<div id="BGC"><strong>Basic Syntax</strong></div>

# <span class="lime"><strong>���־� ��Ʃ��� �ڵ����</strong> </span>
* ������ �� : Ctrl+Shift+V 
<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->
# <span class="lime"><strong>����(header)</strong></span>

### 1.������ ǥ���� ��, (#)�� �ɺ��� �ܾ�, �Ǵ� ����տ� ����� ���ִ�. 
* h1 ���� h6 ���� # �� ������ ǥ���� ���ִ�.

| Markdown | Output |
|:---|:---|
| # ���� 1 | <h1>���� 1</h1> |
| ## ���� 2 | <h2>���� 2</h2> | 
| ### ���� 3 | <h3>���� 3</h3> | 
| #### ���� 4 | <h4>���� 4</h4> | 
| ##### ���� 5 | <h5>���� 5</h5> | 
| ###### ���� 6 | <h6>���� 6</h6> | 
* (#) �ɺ��� ����Ҷ��� ������ ��ĭ �־�� ����ȴ�.

### 2.�� �ٸ�������δ� (==) (--) �ɺ��� ����� ���ִ�.
* ��, h1 �±׿� h2 �±׸� ǥ�������ϴ�.

| Markdown | Output |
|:---|:---|
| ���� 1<br>====| <h1>���� 1</h1>|
| ���� 2<br>-----| <h2>���� 2</h2>|

<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# <span class="lime"><strong>�ܶ� ������(Paragraphs)
</strong></span>
### ����Ű�� �̿��� �������� �ܶ��� ������ �ִ�.
<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# <span class="lime"><strong>�ٹٲ�(Line Breaks)
</strong></span>

### br �±׸� �̿��ؼ� ���� �ٲܼ� �ִ�.
<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# <span class="lime"><strong>�ؽ�Ʈ ����</strong></span>
### 1.����(Bold)
* ����ü�� �����Ű�� ���� �κк���, ����������
�Ʒ��� ���� ����� ����ϸ� �ȴ�

| Markdown | Output |
|:---|:---|
| I just love ** bold text** | I just love <strong>bold text</strong> |
| I just love __ bold text__ |  I just love <strong>bold text</strong> | 
| Love** is**bold | Love<strong>is</strong>bold</td> | 

* ��, ���� �߰��� �����Ҷ� (__)�� ����ϸ� �ȵȴ�.

### 2.���ڸ�ü(Italic)
* ���ڸ�ü�� �����Ű�� ���� �κк��� ������ ���� �Ʒ��� ���� ����� ����ϸ� �ȴ�.

| Markdown | Output |
|:---|:---|
| Italicized text is the * cat's meow*</span> | Italicized text is the <em>cat's meow</em>. |
| Italicized text is the _ cat's meow_ |  Italicized text is the <em>cat's meow</em>. | 
| A* cat*meow | A<em>cat</em>meow</td> | 

* ��, ���� �߰��� ���ڸ� �Ҷ� (_)�� ����ϸ� �ȵȴ�.

### 3.����� ���ڸ��� ��� ����� ���� �ִ�.
<br>
<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# **<span class="lime">�ο뱸(Blockquotes)</span>**

### 1.�ο뱸�� ��� �ϱ� 
* ���ؼ��� �����ϰ� ���� ����, �� �տ� > �� ����ϸ� ����ȴ�.

```markdown
> Dorothy followed her through many of thebeautiful rooms in her castle.
```

> Dorothy followed her through many of the beautiful rooms in her castle.

### 2.���� �ο뱸 �����ϱ�
* �ο뱸�� ������ �����ϰ� �ʹٸ� �� ����, �� ������ �����ٿ� > �� �߰���Ų��.

```markdown
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### 3.��ø�� �ο뱸 �����ϱ�
* ��ø �ϰ� ���� ��ġ�� >> �� ����ϸ� �ȴ�.

```markdown
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### 4.�ο뱸 ���ο� �ٸ� ���� �߰���Ű��.

* �ο뱸 ���ο� ���� ��� "����" "����" "���ڸ�ü" ���, Ư�� ��ũ�ٿ� ��Ҹ� ����� �� �ִ�. 

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
<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# <span class="lime"><strong>����Ʈ(Lists)</strong></span>
### ����Ʈ���� ��������Ʈ�� ���������Ʈ�� �ִ�.

* �ο뱸(Blockquotes)�� �ܶ� ������(Paragraphs)�� �����ų �� �ִ�.

1. **��������Ʈ**
    * ��������Ʈ�� ����Ʈ�� ��ȣ�� �Ű����� ����Ʈ �̴�.
    * ���� ��Ű���� (��ȣ). �� ���� ��ĭ ����� ������ ������ �ȴ�.
        * ��, � ���ڸ� ���� ��ũ�ٿ� ȭ�鿡�� 1,2,3... ������ ���ʴ�� ǥ�õȴ�.
        * ���� ����Ʈ ���ο� ��ø���� ����Ʈ�� ���� �� ���ִ�.
    * ')'�� ����ϸ� �ȵȴ�.

| Markdown | Output |
|:---|:---|
| 1. First item<br>2. Second item<br>3. Third item<br>4. Fourth item| 1. First item<br>2. Second item<br>3. Third item<br>4. Fourth item|
|1. First item<br>2. Second item<br>3. Third item <br> (����) 1. Indented item<br>(����) 2. Indented item <br>4. Fourth item|<ol><li>First item</li><li>Second item</li><li>Third item<ol><li>Indented item</li><li>Indented item</li></ol></li><li>Fourth item</li></ol>|

2. **����� ����Ʈ**
* ����� ����Ʈ�� ����Ʈ�� ��,��,�� �ɺ��� �Ű����� ����Ʈ�̴�.
    * ���� ��Ű���� *, +, - �� ���� ��ĭ ����� ������ ������ �ȴ�.
        * ����� ����Ʈ ���ο� ��ø���� ����Ʈ�� ���� �� ���ִ�.
    * *, +, -�� �ϰ��� �ְ� ����ؾ� �Ѵ�.

| Markdown | Output |
|:---|:---|
|:- First item<br>- Second item<br>- Third item<br>- Fourth item|<ul><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ul>|
|+ First item<br>+ Second item<br>+ Third item<br>+ Fourth item|<ul><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ul>|
|* First item<br>* Second item<br>* Third item<br>* Fourth item|<ul><li>First item</li><li>Second item</li><li>Third item</li><li>Fourth item</li></ul>|
|:- First item<br>- Second item<br>- Third item<br>(����) - Indented item<br>(����) - Indented item<br>- Fourth item|<ul><li>First item</li><li>Second item</li><li>Third item<ul><li>Indented item</li><li>Indented item</li></ul></li><li>Fourth item</li></ul>|
<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# <span class="lime"><strong>�ڵ��</strong></span>

### �ϳ��� ��, �Ǵ� 4���� �������� �ڵ���� ���� ��ų�� �ִ�.

**����**

```markdown
    1.  Open the file.
    2.  Find the following code block on line
        <html>
          <head>
            <title>Test</title>
          </head>
    3.  Update the title to match the name of your website.
```

�Ʒ��� ����� ����̴�.

---
1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.
---
<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# <span class="lime"><strong>��輱(Horizontal Rules)</strong></span>

*** �Ǵ� --- �Ǵ� ___ ���� ��輱�� ���� ��ų�� �ִ�.
<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# <span class="lime"><strong>�̹��� ���� & ��ũ ����</strong></span>


### <span>1. ��ũ ���� : "!\[]\();"</span>

 ```markdown
 ![ǥ��](����� Ȥ�� ������) /// �̹��� ����
 -> ![lime](https://techcrunch.com/wp-content/uploads/2015/05/limes-e1431965418433.jpg?w=1390&crop=1)
```

### <span>2. ��ũ ���� : "\[]\();"</span> 

```markdown
 [ǥ��](���ּ�, ����� Ȥ�� ������)/// ��ũ����
 -> My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
```

---
�Ʒ��� ����� ����̴�.

---
![lime](https://techcrunch.com/wp-content/uploads/2015/05/limes-e1431965418433.jpg?w=1390&crop=1)

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

---
<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# <span class="lime"><strong>URLs & Email Addresses</strong></span>
### <>�� ���ѵڿ� �� �ȿ� ULR, Email �ּҸ� �ۼ��Ѵ�.

```markdown
<https://felipuss.tistory.com/>
<fake@example.com>
```

�Ʒ��� ����� ����̴�.

---
<https://felipuss.tistory.com/> <br>
<fake@example.com>

---
<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# <span class="lime"><strong>Escape��</strong></span>

### backslash to escape the following characters

* ��ҿ� �׳� ����� �� ���� Ư�����ڸ� \ (�齽����)�� �̿��� Ư��ǥ���� �����ϴ�.
<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# <span class="lime"><strong>HTML ���� ���</strong></span>
### 1.��ũ�ٿ� ���� HTML���� ��� �����ϴ�.
### 2. < style> �±׷� ������ ��,ũ��, ��� CSS������ ����� ���ִ�.
![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/240px-HTML5_logo_and_wordmark.svg.png)

<div id="BGC"><strong>GFM Syntax</strong></div>


# <span class="lime"><strong>�ڵ��(Code Block)</strong></span>
```markdown
    ```(language)
    ```

    ```ruby
    require 'redcarpet'
    markdown = Redcarpet.new("Hello World!")
    puts markdown.to_html
    ```
```

____________________________
 
 ```ruby
    require 'redcarpet'
    markdown = Redcarpet.new("Hello World!")
    puts markdown.to_html
```
____________________________

# <span class="lime"><strong>ǥ�����</strong></span>

### 1. '|' �� �ϴ� ǥ�� ������.
* | ���� �����͸�ŭ ���� ������ ���� �ִ�
### 2. '---' �� �Ӹ��� ���� ǥ���Ѵ�.
* |:---| �� ��������
* |---:| �� ������ ����
* |:---:| �� ��� ����

```markdown
| Markdown | Output |
|:---|:---|
```

### 3. ���� ���� ���� ���� ������ �� �ִ�. 

```markdown
| # ���� 1 | <h1>���� 1</h1> |
| ## ���� 2 | <h2>���� 2</h2> | 
```

�Ʒ��� ����� ����̴�.

---

| Markdown | Output |
|:---|:---|
| ## ���� 2 | <h2>���� 2</h2> |
| ### ���� 3 | <h3>���� 3</h3> | 

---


# <span class="lime"><strong>üũ��(Task lists)
</strong></span>

### 1.üũ�ٸ� �����ϱ� ���ؼ� '-' ���� ����Ʈ�� �����ϰ� ���ȣ�� �ۼ��Ѵ�.
 * [x] : üũ ǥ��
 * [] : üũ �ȵ�

```markdown
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request

### 2.��ȣ�� �ۼ��ϱ� ���� �̽��������� '\\'�� ����ѵ� ��ȣ�� �����ϸ� �ȴ�.

```markdown
- [ ] \(Optional) Open a followup issue
```

<!-- ��ũ�ٿ����� �ּ� ó�� ���� -->

# <span class="lime"><strong>��ޱ��(Mentioning people & teams)
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

|Reference type  |Raw reference  |Short link |
|:---|:---|:---|
|Issue or pull request URL| https://github.com/jlord/sheetsee.js/issues/26| #26|
| # and issue or pull request number| #26   | #26 |
|GH- and issue or pull request number| GH-26| GH-26|

#1
mojombo#1
mojombo/github-flavored-markdown#1

### 3.Commit SHAs
* References to a commit's SHA hash are automatically converted into shortened links to the commit on GitHub.

|Reference type |Raw reference  |Short link|
|:---|:---|:---|
|Commit URL |https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e   |a5c3785|
|SHA|   a5c3785ed8d6a35868bc169f07e40e889087fd2e|   a5c3785|
|User@SHA|  jlord@a5c3785ed8d6a35868bc169f07e40e889087fd2e|jlord@a5c3785|

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

# <span class="lime"><strong>��Ҽ�(Strikethrough)<strong></span>
### 1. '~~' �� ��Ҽ��� ������ �������� �յڷ� �����ָ� ����ȴ�.

    ~~�ȳ��ϼ���~~

~~�ȳ��ϼ���~~

# <span class="lime"><strong>�̸�Ƽ�� ���(Emoji)<strong></span>

### ���� ���̿� ����ϰ� ���� �̸�Ƽ���� [Emojicode](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) �� :�� ���θ鼭 ����Ѵ�.


```markdown
:EMOJICODE:

@octocat :+1: This PR looks great - it's ready to merge! :shipit:

```

@octocat :+1: This PR looks great - it's ready to merge! :shipit:

# <span class="lime"><strong>GITHUB URL<strong></span>
https://github.com/DogGuyMan/GFM_Syntax/blob/main/README.md