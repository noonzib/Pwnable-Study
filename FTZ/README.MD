# FTZ

>trainer1

password : trainer1

* ls -al : 파일,디렉토리 보기

>trainer2

password : linuxer

* pwd => 현재 디렉토리
* cd => change directory,
* cd .. => 상위 디렉토리 이동
* / => 최상위 디렉토리
* mkdir => 디렉토리 생성
* rmdir => 디렉토리 삭제
* cp file1 file2 => file1을 file2에 복사
* rm => 파일 삭제
* mv => 파일 이동, 파일 이름 변경 할 때 사용

>trainer3

password : computer

* w => 현재 접속 정보
* finger -l => 사용자 정보 보기
* tty => 자신의 터미널 확인
* ifconfig => 현재 접속한 서버의 ip보기
* write guest /dev/pts/번호 => guest한테 메세지 보내기
* wall => 모든 사용자에게 메세지 보내기

>trainer4

password : mungguta

1. 디렉토리 설명
    * **bin** => 필수적인 리눅스 실행 파일
    * boot => 리눅스 부팅 관련 파일, 커널
    * dev => 하드웨어 정보들이 파일로 존재
    * **etc** => 리눅스의 설정 파일 ex) 패스워드 파일, 쉐도우 파일, 리눅스 설정 파일등..
    * **home** => 일반 사용자 디렉토리, 사용자의 아이디, 작업공간
    * lib => 라이브러리 파일
    * mnt => mount 명령을 사용, 플로피 디스크, 마운트 시킨 CD-ROM가 들어있다
    * proc => 프로세스들이 파일 형태로 저장
    * root => 루트의 홈 디렉토리
    * sbin => 기본 명령을 제외한 시스템 관리용 실행 파일
    * **tmp** => 누구나 임시 파일을 저장할 수 있는 공간
    * usr => 응용프로그램들이 설치된 곳
    * var => 시스템 운영 중에 생성되는 임시파일, 외부 접속에 대한 로그
2. 중요한 파일 설명
    * /etc/passwd => 사용자들에 대한 간단한 정보
    * /etc/shadow => 사용자들의 패스워드가 들어있음, 아무나 보지 못함
    * /etc/services => 서버가 어떤 서비스를 하는중 인지 보여줌
    * /etc/issue.net => 처음 접속될때 나오는 화면
    * /etc/motd => 로그인 후에 나오는 메세지
    * ~/public_html => 사용자들의 홈페이지 파일, 해킹 성공시 파일을 수정할 수 있음

>trainer5

password : goodluck

1.정보수집
    * whoami => 자신의 누구인지
    * id => 자신의 좀 더 자세한 정보
    * uname -a => 커널 버전 확인
    * cat /etc/\*release => OS 버전 확인 
    * rpm -da => 패키지의 정보
    * cat /proc/cpuinfo => cpu 정보 

>trainer6

password : coffee

* cat => 파일내용 확인

root : x : 0 : 0 : Admin : /root : /bin/bash
    * root => 사용자 아이디
    * x => 패스워드
    * 0 => 사용자 아이디, 컴퓨터가 보기 쉽게 숫자로...
    * 0 => 사용자가 속해있는 그룹
    * Admin => 사용자의 이름
    * /root => 로그인 했을 떄 기본으로 위치한게 되는 디렉토리
    * /bin/bash => 로그인 했을 때 실행되게 할 프로그램, 쉘 실행

>trainer7

password : to the top

tar cvf file file1 file2 => 파일 합치기
tar xvf file => 파일 해체하기
    * 옵션
        * c - Create : 새로운 파일을 만드는 옵션
        * x - eXtract : 압축 해제

        * v - View : 압축,해체 과정출력
        * f - File : 파일로 백업
* tar => 백업용
//-- 2019-07-25 --//