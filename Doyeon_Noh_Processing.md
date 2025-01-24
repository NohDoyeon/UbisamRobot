# Doyeon 자동차 진행 사항 Readme.md 파일

### 작성자
- 노도연 최초작성 25.01.24

### 작업 목록 (날짜별)
####  25.01.22 
- 2월중순까지의 작업 일정 회의

####  25.01.23~24
- 라즈베리파이5 -우분투 데스크탑 24.04.01 os 설치 및 부팅 완료 
    - sd카드 포맷 이슈 발생
    - 128GB - > 32 GB ISO쓰고 부팅함.
    - VNC 및 SSH 설정 필요 (도움요청)

- 터미널 리눅스 명령어 연습 
    - 사용자명@ubisamrobot:~$ 
    - ~$ : 경로
```terminal
# 터미널 실행 단축키 
Ctrl + Alt + T

# 업데이트 & 업그레이드 
sudo apt update
sudo apt upgrade

# 터미널에서 현재 경로의 파일이나 폴더 목록 나타내기 
ls

# 현재 경로 나타내기
pwd

# 터미널 창 초기화 
clear

# 폴더 생성 명령어
mkdir '폴더명'      // 작은따옴표 안쳐도 됨됨

# 삭제하는 명령어
rm
sudo rm -r '폴더명'
[sudo] password for pw : 7777 (엔터)

# 폴더간 이동 명령 
cd
cd ' ' 


```

- 필요한 소프트웨어 설치 
    
    - Chrome 설치
        ```
        1. Update Package
            sudo apt update (레파지토리 최신 업데이트)
        2. Check wget Utility
            wget --version (버전 확인하여 wget의 설치 유무 확인하기)
            2-1. [설치 X] 에러뜰 경우 Install wget Utility(If not installed)
                    sudo apt install wget
            2-2. [설치 O] ~~버전이라고 나옴
        3. Download .dev Package for Chrome Installation
            wget https://dl.google.com/linux/direct/google-chrome-stable-current-amd64.deb
            (크롬 설치를 위한 .dev Package를 다운로드 한다.)
        4. Install Google Chrome
            sudo dpkh-i google-chrome-stable_current_amd64.deb
            (다음 명령을 사용하여 크롬을 설치한다.)
            ++ 추가 명령어
            sudo apt install chromium-browser
        5. 설치 확인하기
            show application - Chrome
        6. Add to Favorites 
            즐겨찾기에 추가하면 이후 사용이 편해진다. ( 사용하지 않는 앱은 즐겨찾기에서 삭제 )
        7. 설정 > Default [Chrome] 세팅 
        ``` 
    - Python pip3 파이썬 가상 환경 만들기
        ```
        1. 
        ```
    - Ros2 jazzy 

```
ROS2를 위한 환경 설정 
```
####  추후 계획 
