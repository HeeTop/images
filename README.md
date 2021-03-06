# images### **Oh-My-Zsh로 쉘 꾸미고 플러그인 사용하기!**
------

#####**Oh My Zsh를 설치해서 터미널을 보다 깔끔하고 편하게 사용**

 일반적으로 맥이나 우분투를 사용하는 경우 터미널로 bash 쉘을 사용하는데 **개발자**스럽게 디자인이 정말 딱딱하다...
그래서 요즘 쓰게된 [zsh](http://www.zsh.org/) + [Oh My Zsh](http://ohmyz.sh/) + [iTerm2](http://www.iterm2.com/)를 소개하고자 한다.

--------------
### Oh My Zsh

[Oh My Zsh](http://ohmyz.sh/)는 zsh의 환경설정을 다루는 프레임 워크로 쉘의 테마뿐만 아니라 유용한 플러그인들을 사용할수 있다.
먼저 현재 쓰고있는 정말 투박한 bash 쉘을 zsh 쉘로 바꿔보자!
```
$ zsh --version        # zsh 버전 확인
zsh 5.2
```
만약에 zsh가 다운되어 있지 않다면 먼저 이 명령어를 실행한다.
```
$ brew install zsh     # zsh 다운로드
```
이제 zsh를 기본 쉘로 바꿔보자.
```
$ which zsh            # zsh 위치확인
/bin/zsh

$ chsh -s `which zsh`  # 현재 쉘을 zsh 쉘로 바꿈
$ chsh -s /bin/zsh     # 위의 명령어와 같음

```
이후에 터미널을 종료한 후 다시 실행하면 zsh 쉘로 바뀐 것을 알수있다.
이제 드디어 Oh My Zsh를 다운받자
```
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"  # oh my zsh 다운로드
$ brew cask install iterm2     # iterm2 다운로드
```
다시 현재 터미널을 종료하고  iTerm로 실행하면 이 터미널이 나올것이다. 

![enter image description here](https://raw.githubusercontent.com/HeeTop/images/master/myblog/iterm3.png)

----------------
####본격적으로 세팅을 해보자






