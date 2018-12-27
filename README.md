# Markdown 가이드
> 개인적으로 참고할 목적으로 작성한 페이지입니다. 아래 주소의 블로그를 참고하여 작성하였고, 훨씬 자세하게 잘 정리되어 있으니, 해당 블로그를 참고하시는 것을 권장드립니다.
- <http://sergeswin.com/1013>

> 주의사항
- 아래 내용은 Visual Studio Code의 Markdown Preview 기능을 기준으로 작성되었습니다.
- 적용되는 내용은 동일할 것이나, 글자와 문법 사이에 공백이 있어야 한다는 점 등, 에디터의 프리뷰 기능이 에디터마다 약간씩 다를 수 있습니다.

-------------------------------------------------------

## 제목
    해시태그(#) 뒤에 글자를 붙이면 제목이 됩니다. 해시태그를 여러개(##, ###, ...)를 붙이면 차차로 글자 크기가 줄어듭니다.
    ex) # 제목1
        ## 제목2
        ### 제목3
- Visual Studio Code의 Markdown Preview 기준으로 확인할 때 최대 6개의 해시태그(#)를 붙이는 것이 가능합니다.
- 제목 수준으로 크기를 키우고 싶은 글자의 다음 라인에 '='을 넣으면 글자가 제목 수준으로 지정됩니다. ('='를 여러개 넣어도 무방)

## 진하게(Bold)
    혹은 언더스코어 두개(__), 별표 두 개(**)를 글자의 양 끝에 붙이면 글자를 진하게 지정 가능합니다.
    ex) **진하게**
        __진하게__
- **실제로 Bold가 적용된 모습입니다.**
- __언더스코어로 적용한 모습__

## 기울이기(Italic)
    언더스코어 한 개, 혹은 별표 한 개(_, *)를 글자의 양 끝에 붙이면 글자에 기울이기를 적용 가능합니다.
    ex) _기울이기_
        *기울이기*
- _언더스코어로 적용한 기울이기_
- *별표로 적용한 기울이기*

## 숫자 목록
    숫자 목록은 항목으로 지정하고 싶은 내용의 앞에 숫자와 닷(.)을 붙이면 적용됩니다.
    따로 들여쓰기를 하지 않더라도 적절히 들여쓰기가 지정됩니다.
    ex) 1. 일
        2. 이
        3. 삼
1. 이렇게 지정됩니다.
2. 이렇게 지정됩니다.

## 글 머리 기호
    숫자가 아닌 기호로 항목 지정을 할 경우에는 항목으로 지정하고 싶은 항목 앞에 별표(*) 혹은 하이픈(-), 또는 더하기(+) 기호를 붙입니다.
    해당 에디터 기준으로는 별표(*)와 하이픈(-) 더하기(+) 뒤에 공백이 필요합니다. 그러나 기호들을 혼용하면 문단이 구분되어 간격이 생기므로 통일하는 편이 좋습니다.
    ex) * 첫 번째
        * 두 번째
        * 세 번째
* 별표로 지정한 첫번째 항목
* 별표로 지정한 두번째 항목
- 하이픈으로 지정한 첫번째 항목
- 하이픈으로 지정한 두번째 항목
* 별표로지정한 항목
+ 더하기로 지정한 항목

## 인용문
    인용문의 경우에는 오른쪽 꺾쇠(>)를 이용합니다.
    ex) > 인용문구
> 인용문은 이렇게 지정됩니다.

## 이메일 링크
    이메일 링크는 양쪽을 꺾쇠 괄호(<>)로 묶어 사용합니다.
    ex) <test@test.com>
- <test@test.com>

## URL 링크
    URL 링크의 경우도 양쪽을 꺾쇠 괄호(<>)로 묶어 사용합니다. 만일 URL 대신 다른 내용을 링크 내용으로 사용하고 싶다면 링크 앞에 대괄호([]) 안에 사용하고자 하는 내용을, 뒤쪽에 소괄호(()) 안에 링크 주소를 입력합니다.
    ex) <https://github.com>
        [깃헙](https://github.com)
- <https://github.com>
- [깃헙](https://github.com)

## 이미지 넣기
    이미지의 경우 소괄호(()) 안에 이미지의 URL을 넣으면 적용됩니다.
    캡션을 넣으시고 싶은 경우에는 파일 링크 앞에 느낌표와 대괄호를 이용하여 적습니다(![])
    ex) ![테스트이미지](https://github.com/cliche90/markdown_tutorial/blob/master/github_logo.png?raw=true)
![깃헙 이미지](https://github.com/cliche90/markdown_tutorial/blob/master/github_logo.png?raw=true)



## 가로선 넣기
    가로선의 경우 하이픈(-), 별(*), 언더스코어(_) 중 아무 것이나 연달아 세 개 이상 입력하면 적용됩니다.
    ex) ------------------
        ***
        _______
---
- 위와 같이 적용됩니다.

## 강제 개행
    해당 Editor의 경우 그냥 줄을 바꾸어 줄 경우 적용됩니다.
    일반적으로 Markdown에서는 HTML 문법도 사용 가능하므로 <br></br>을 이용해서도 개행이 가능합니다.
    ex) 1행<br></br>2행
- 아래 내용은 위의 예시대로 작성했을 경우 적용되는 내용입니다.<br> 
1행<br></br>2행

## 코드 블럭(Code Block)
    제가 지금 작성한 내용을 감싸고 있는 이 블럭은 코드 작성시에 이용됩니다.
    문법 내용이 적용되지 않고 그대로 보이기 때문에 코드로 볼 수가 있습니다.
    사용 방법은 공백 4개를 라인의 앞에 입력해 두면 됩니다.

````
혹은 아래와 같이 backtick 3개(```) 로 감싸도 코드 블럭으로 지정이 가능합니다. 또한 시작 부분의 ```에 ```js 와 같이 언어를 지정하여 syntax highlighting을 할 수도 있습니다. 저는 이 방법을 좀 더 권장합니다.
ex)
```java
int a = 10;
```
````

## 코드(Code)
    보통은 코드 블럭을 이용하겠지만 라인 안에 코드를 작성하고 싶은 경우에는 어포스트로피 기호(`)로 코드를 감싸서 처리합니다.
    ex) `<br>`
- 따옴표(') 기호가 아니라 키보드의 ESC 바로 아래쪽에 있는 어포스트로피 기호(`)입니다.
- `<strong>진하게</strong>`

## 이스케이프(Escape)
    마크다운을 작성하다보면 마크다운에서 사용하는 문법 기호를 사용하고 싶을 때가 있습니다. 이럴 경우에는 백슬래쉬(\) 기호를 이용하여 원하는 문자를 이스케이프 시켜줍니다.
    ex) \+
        \*
- 이런식으로 \*별표 이스케이프\* 이스케이프를 이용하면 문법을 적용시키지 않고 문자를 보여줄 수 있습니다.

<br></br>

-------------------------------------------------------

# 멀티 마크다운
>- 멀티 마크다운은 기본 마크다운 문법에 몇 가지 기능이 추가된 문법을 말합니다. 취소선/주석 등입니다.
> - 아래쪽부터는 멀티 마크다운 문법입니다.


## 취소선
    취소선은 물결 기호 두개(~~)로 글자를 감싸면 적용됩니다.
    HTML 문법으로는 <del> 태그를 이용하면 됩니다.
    ex) ~~취소선~~
- ~~취소선은 이런식으로 적용됩니다.~~

## 주석(각주)
    주석은 대괄호 안에 캐럿 기호와 숫자를 더하여 작성합니다.([^1])
    주석을 적용할 문장의 뒤에 [^숫자]를 넣고, 해당 부분에 작성할 주석 내용은 동일한 기호([^숫자])에 콜론(:)을 쓰고 그 뒤에 내용을 작성합니다.
    ex) 주석을 적용할 문장[^1]
        [^1]: 주석에 작성할 내용
- Visual Studio Code의 마크다운 Preview 기능 기준으로는 적용이 안 됩니다.

## 표 그리기
    표를 그리는 경우에는 이전의 가로선 기호인 하이픈(-) 세개 이상과 파이프(|) 기호를 이용합니다. 하이픈으로 행을 구분하고 파이프로 열을 구분하는 식입니다.
    ex) 제목1 | 제목2 | 제목3
        ------|------|-----
        1행1열|1행2열|1행3열
        2행1열|2행2열|3행3열
- 위와 같은 예시대로 작성할 경우 아래와 같이 표가 작성됩니다.

    제목1 | 제목2 | 제목3
    ------|------|-----
    1행1열|1행2열|1행3열
    2행1열|2행2열|3행3열

