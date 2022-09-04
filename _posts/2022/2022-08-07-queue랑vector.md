---
layout: post
title:	"queue랑 vector"
date:	2022-08-14 03:00:00
categories:
    - blog
tags:
    - C언어
    - C++
---

쉽게 말하자면 배열이다.
일단 사용하려면 헤더파일처럼 일단 선언해야 한다.

```c
#include<queue>
#include<vector>
```

선언하는방법은 queue또는 vector을 쓰고 <>를 쓰고 저거 안에다가 int나 그런걸 쓰고 그 밖에 뒤에 변수이름을 쓰면 된다.

```c
ex)
#include<queue>
#include<vector>
queue<int> q;
vector<int> v;
```

<h2>queue</h2>
queue는 앞에서 값들을 삽입하고 뒤에서 삭제한다.  
queue는 변수이름뒤에 .를 적으면 뭔가 쫘라락 나오는데 6개만 알아볼꺼다.  
push()는 변수 제일 앞에다가 괄호안에 있는 값을 삽입한다.  
pop()은 변수 제일 뒤에있는 값을 삭제시킨다.  
size()는 변수의 크기를 알려준다.  
empty()는 변수가 비어있으면 1, 비어있지않으면 0이된다.  
front()는 변수의 제일 앞에 있는 값이다.  
back()은 변수의 제일 뒤에 있는 값이다.  


<h2>vector</h2>
vector은 뒤에서 값들을 삽입하고 뒤에서 삭제한다.  
vector도 .을 치면 뭔가 많이 나오는데 7개만 알아볼꺼다.
push_back()은 push와 동일하다.  
pop_back()은 pop와 동일하다.
size()도 동일하다.  
empty()도 동일하다.  
front()도 동일하다.  
back()도 동일하다.  
at()은 변수의 `괄호안에 있는 값`번째 값을 알려준다.  


...사실 둘이 거의 똑같다.