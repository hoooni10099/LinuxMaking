# LinuxMaking

Dell Power Edge 2900에 우분투 설치

USB(용량 좀 넉넉한) 컴퓨터에 연결하고 우분투와 Rufus 다운받는다
Rufus 실행 후 USB에 이미지 파일 넣는다.(좀만 구글링하면 과정 자세하게 나옴.)
Dell Power Edge 2900 포트에 USB 넣고 실행
DELL 화면 뜨자마자 F11 연타해서 Boot menu 모드로 들어감
거기서 Boot Suquence에서  USB(Embedded NIC 1 MBA v2.6.7 slot 0500)가 제일 위로 오게 설정
Boot Sequence Retry - Enabled
Embedded Server Management - Front-panel LCD Options - Deault
