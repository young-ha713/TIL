# git 

> 분산 버전 관리 시스템(DVCS) 맨 왼쪽 바 만드는법 부등호 띄어쓰기

## 준비 사항

* git bash (윈도우 사용 경우 필요)

## 기본문법

###  0.git 저장소 생성

```bash
$git init
#비어있는 깃 저장소 초기화 함
Initialized empty Git repository in C:/Users/gkdud/OneDrive/바탕 화면/test/.git/

```

* 폴더에  git 저장소 초기화 하면
  * .git 폴더 생ㅅ성되고
  * bash 에는 (master)라고 표기
* 주의사항
  * 깃 저장소 내에 깃 저장소를 만들지 말아라
    * git init 입력시  `(master)`가 보이면절대 입력하지 말것
    * 상위폴더가 깃 저장소면 하위폴더는 자동으로 깃 저장소



## 1.`add`

```bash
$ git add {디렉토리}
$ git add . # 현재 디렉토리 
$ git add a.txt #특정 파일
$ git add myfolder/ #특정폴더
```

* working directoty 상태 파일을 staging area 상태로 변경(첫번째 통)->(두번째통)
* 커밋을 위한 파일들을 추가하는 명령어

## 예시

```bash
$ touch a.txt #파일을 만든다 =>코드 작업을 했다
$ git status
```





## 3. log

```bash
$ git log
$ git log --oneline # 한줄로
$ git log -2 #두개
$ git log --oneline -1 #1개를 한줄로
```



### 4. status

* working directory ,staging area 공간의 파일 상태를 확인 할 수 있다

```bash
$ git status

```

