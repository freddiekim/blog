---

layout: post
title: "hellow github blog!"
categories: Diary
tags: [documentation,sample]
image:
 feature: bag.jpg
 teaser: bag-teaser.jpg
 credit:
 creditlink:

---

### github blog 입문

github 블로그를 입문하다.!!!  <br>
참 힘들었다. 우선 윈도우 환경에 익숙한 나에게 mac으로 github 블로그를 만든다는 것은 참 힘든일이었다.<br>
<br>
내가 블로그를 해야겠다라고 마음 먹은것은 [SanghyukChun](http://sanghyukchun.github.io/)님의  <br>
블로그를 보고이다. 나도 내가 공부한것을 정래해서 적어놓으면 다른사람에게 도움되면 좋고 내 생각도 정리되니 좋을것 같다는 막연한 생각에서부터 시작했다.<br>
<br>
그러나 너무 힘들었다. 하나도 모르는 상태에서 하려니 너무 힘들었다. 위 SanghyukChun님은 경험이 많아 보였다.  <br>
실제 업무로 Ruby같은 툴을 사용하고 있었고...그러나 나는 하나도 모르는 상태에서 했다. 그래서 무지 힘들었다. -.-;;<br>
<br>
우선 여러 사이트를 벤치마킹해서 만들어 봤다. 시간나는데로 내가 했던 것을 정리해서 적어놔야겠다.<br>
<br>
#### 기본적인 jekyll 사용법
`-` 서버에서 내가 작성한 내용 확인하기<br>
 _config.yml파일 안의 baseurl이 ""이면 jekyll serve -w 만 적으면 되지만<br>
나의 블로그는 baseurl "blog" 이므로 경로를 무시해줘야한다.<br>
즉 : jekyll serve -w --baseurl '' (baseurl앞 데쉬가 2개이다.)<br>
`-` *.md파일 작성하기<br>
해당 파일을 작성할때 양식이 있다. 이 양식은 지켜줘야한다. 2017-MM-DD-title.md<br>
titled은 숫자로 시작하면 안된다.<br>
`-` atom에서 preview 보기<br>
shift+ctrl M을 누르면 토글로 preview가 왔다갔다한다.<br>
`-` 웹사이트에서 확인하기<br>
website에서 localhost:4000을 친다. 그럼 확인할 수 있다.<br>
