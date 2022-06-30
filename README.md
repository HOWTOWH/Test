소속 : 국립안동대학교, 컴퓨터공학과
========================

학번, 이름 : 20181125 이우협

--------------------------------
# 1. Header
# 1.1. 집
## 2.1 가
### 3.1 고
#### 4.1 싶
##### 5.1 다
###### 6.1 ㅠ

# 2. BlockQue

* ">" 블록 인용 문자 사용

> One
>	> Two
>	>	>Three

# 3. List
1. First
* First-First
	+ First-Second
		- First-Third
2. Second
3. Third

# 4. Code

* 띄우지 않고 들여쓰기 했을 때

각각각각각각각각각각
	각각각각각각각각각각
각각각각각각각각각각

* 띄우고 들여쓰기 했을 때

꺆꺆꺆꺆꺆꺆꺆꺆꺆꺆
	
	꺆꺆꺆꺆꺆꺆꺆꺆꺆꺆

꺆꺆꺆꺆꺆꺆꺆꺆꺆꺆

## Source Code

* "```언어" 적으면 그 언어의 문법 강조 가능


<pre>
<code>
```java
class Computer{
	private String Name;
	private String Number;
	
	Computer(String Name, String Number){
		this.Name = Name;
		this.Number = Number;
	}
		
}
```
</code>
</pre>


# 5. Draw Line

* 페이지 나누기 용도로 사용

"* * *"
* * *
"***"
***
"*****"
*****
"- - -"
- - -
"------------"
------------

# 6. Link

* 참조 링크

Link: [Naver][Naverlink]

[Naverlink]: https://www.naver.co.kr

* 외부 링크

[naver](https://www.naver.com "네이버 드가자~")

* 자동 링크

Naver Homepage: <https://www.naver.com>

# 7. Emphasis

* 텍스트를 강조할 때 사용하는 문법

>"*이텔릭체* 혹은 _이텔릭체_"

*이텔릭체*
_이텔릭체_

>"**두껍게** 혹은 __두껍게__"

**두껍게**
__두껍게__

>"~~취소선~~"

~~취소선~~

# 8. 이미지

![Street](sangsu.jpg "sangsu")

* 크기 조절

<img src="sangsu.jpg" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>
<img src="sangsu.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>

# 9. Footnotes

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.
This allows you to have a footnote with multiple lines.
[^note]:
Named footnotes will still render with numbers instead of the text but allow easier identification and linking.
This footnote also has been made with a different syntax using 4 spaces for new lines.