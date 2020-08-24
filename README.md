# CCCR

Markdown 사용법
----

# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

단락
--------------------
안녕하세요.  
저는 당주현입니다.  
만나서 반갑습니다.  

  저도 반갑습니다.  
    Hi  



기울임(Italic)
-----
안녕하세요.  
*저는 당주현입니다.*  
_저는 당주현입니다._  



볼드(Bold)
------
안녕하세요.  
**저는 당주현입니다.**  
__저는 당주현입니다.__  



기울임+볼드
-------
안녕하세요.  
***저는 당주현입니다.***  
___저는 당주현입니다.___  
_**저는 당주현입니다.**_  
__*저는 당주현입니다.*__  



인용문
-------
> 안녕하세요.  
>> 저는 당주현입니다.
>>> hello world

> ### 제목3
> 안녕하세요. 저는 **당주현** 입니다.



목록
-------
- 목록1
- 목록2
- 목록3
  - 목록3-1
  - 목록3-2
    - 목록3-2-1
      - 목록3-2-1-1
- 목록4

1. 목록1
2. 목록2
3. 목록3
  - 목록3-1
  - 목록3-2
4. 목록4

1) 목록1
2) 목록2
3) 목록3

- 목록1
- 목록2
- 목록3
  + 목록3-1
  + 목록3-2
    * 목록3-2-1
      - 목록3-2-1-1


- hello
- markdown
  world
  korea
- > South Korea


코드블록
-------
Ansible AWX에서 ```login```을 하세요.  

```
print("hello world")
```

```python
print("hello world")
```

```shell
ls -l
```



링크
------
http://www.google.com
<http://www.google.com>

[Google](http://www.google.com)
[Google](http://www.google.com "구글")

<wildsniper07@naver.com>



이미지
------
![kube1](./kube.png)
![kube2](https://miro.medium.com/max/700/1*WCsqMt85nMP0DvYv0JnkOA.png)
![kube3](./kube.png "쿠버네티스")



탈출문자
-----
hello **world** korea  
hello *\*\world*\*\ korea

- hello  
\- hello



----
확장문법
----

테이블
-----
|A|B|
|-|-|
|X|Y|
|S|T|

| syntax | description | summary |
| :- | :-: | --: |
| header | title | abc |
| paragragh | text | xyz |


각주
----

위 내용은 [^1] 다음을 참조하세요.  
아래 내용은 [^kubespray] 다음을 참조하세요.  

[^1]: http://www.google.com  
[^kubespray]: 쿠베스프레이는 프로덕션 레디~



정의
-----
kubespray
: abc

ansible
: xyz



취소선
------
안녕하세요. ~~저는 당주현입니다.~~



작업목록
------
- [X] 테스트
- [X] 개발
- [ ] 릴리즈



링크 비활성화
-----
http://www.google.com
`http://www.google.com`


