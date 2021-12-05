# [오픈소스 과제 02]


김정현 3학년 20152993 컴퓨터공학과
---
#### 목차
1. [문제1](#문제1)
2. [문제2](#문제2)
3. [문제3](#문제3)
4. [문제4](#문제4)
5. [문제5](#문제5)

---


### 문제1


![과제1](https://user-images.githubusercontent.com/93643813/144736162-f3bba1ad-06e3-4e6a-8255-60be99004ec8.gif)


* 최고 스코어 __8 points__ 

* 사용한 명령어 : GWi"<End>"<Esc>ZZ

| 명령어 | 사용이유 |
|:---|:---|
| G |파일의 마지막 줄로 이동 하는 것 입니다.  |
| W | 문자단위 이동하는 것입니다.( 소문자w는 다음단어의 처음으로 이동할수 있습니다.) |
| i | 현위치에서 입력모드를 시작할수 있습니다. |
| ZZ | 저장하고 나가기 키를 써서 나갔습니다.(:wq와 같은 기능입니다.) |


* 설명

1.처음에는 G를 입력해서 파일의 마지막으로 이동합니다.

2.W를 둘러 문자단위로 이동합니다.

3.i로 현위치에서 입력모드를 하여서 __"__ 를 입력하고 End키를 누르고 다시한번더 __"__ 를 입력합니다.

4.완료가 되면 Ese키를 눌러서 일반모드로 돌아오게 합니다. 

5.마지막으로 종료키 ZZ를 눌러 종료를 해줍니다.

---


### 문제2


![과제2](https://user-images.githubusercontent.com/93643813/144736721-c55a8829-4f44-4ec2-9ed8-cc8287f1652b.gif)


* 최고 스코어 __27 points__ 

* 사용한 명령어 : %s/sublime\|emacs/vim/g<CR>ZZ

| 명령어 | 사용이유 |
|:---|:---|
| %s/<현재문자>/<바꿀문자>/g |현재 문자를 입력하고 바꿀문자를 입력하면 현재문자가 바꿀문자가 됩니다. 여기서g는 글로벌로 전체를 의미합니다.  |
| ㅣ | 파이프를 써서 한번에 처리하도록 하였습니다. |
| ZZ | 저장하고 나가기 키를 써서 나갔습니다.(:wq와 같은 기능입니다.) |


* 설명
  
 sublime,emacs를 vim으로 바꾸기 위해서는 __%s/현재문자/바꿀문자/g__ 하나식 써서 가능하지만, 
  
 더 짧게 하기 위해서 | 기능을 을 써서 sublime,emacs을 한번에 vim으로 변경하였습니다.
  
 마지막으로는 ZZ를 눌러서 종료하였습니다.
  
  ---


### 문제3


![과제3](https://user-images.githubusercontent.com/93643813/144740066-d2ca0c9a-7e7e-4633-a8fe-c207bbd42c69.gif)


* 최고 스코어 __35 points__ 

* 사용한 명령어 : 5<CR>yyPWCTODO<Home><Right>// <Esc>yykPWcwVersion<Esc>ZZ

| 명령어 | 사용이유 |
|:---|:---|
| :<number> | 5번째 줄로 이동하게 하는 것입니다.  |
| yy | 현재 커서가 위치하는 줄을 복사합니다. |
| shif+p | 현재 커서가 위치한 바로 윗 줄에 붙혀넣기를 합니다. |
| W | 문자단위 이동하는 것입니다.( 소문자w는 다음단어의 처음으로 이동할수 있습니다.) |
| cw | 커서가 위치한 단어를 잘라내고 insert를 합니다. |
| C | 커서가 위치한 곳부터 단어의 마지막까지 잘라내고 insert를 합니다. |
| k | 위로 올리기 기능입니다. |
| ZZ | 저장하고 나가기 키를 써서 나갔습니다.(:wq와 같은 기능입니다.) |



* 설명

1.처음에는 :5를 입력해서 그 해당 줄로 이동합니다.

2.yy를 눌러 그 줄을 복사합니다.

3.복사가 완료 되었으면, shift+p를 눌러서 위에 줄에 붙혀넣기를 합니다.

4.W를 눌러서 Bool의 위치에 있게 합니다.
 
5.커서가 Bool의 위치에 있으면 C를 눌러서 그 단어를 잘라내고 insert를 "TODO"로 합니다.

6.HOME키를 누르고 다시 오른쪽 버튼을 누른후 "// "룰 눌러주고 esc키를 일반모드로 돌아오게 합니다.
  
7.다시 yy를 눌러서 복사를 합니다.
  
8.k를 눌러 위로 올라간다음에, shift+p를 눌러 위에 줄에 붙혀넣기를 합니다.

9.W로 Debug의 위치에 가게 한다음 cw를 누른후 , "Version"을 입력하고 다시 esc키를 눌러 일반모드로 돌아오게 합니다.
  
10.ZZ를 눌러서 종료합니다.

11.마지막으로 종료키 ZZ를 눌러 종료를 해줍니다.


