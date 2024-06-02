# OSS

리눅스 명령어_20203161 컴퓨터공학과 선주연

·top : 시스템의 프로세스/메모리 사용 상태를 5초의 간격으로 업데이트하여 출력
 -b : 배치모드로 정보를 출력한다. 실시간 상화 대화형모드로 정보를 화면에 일렬로 출력
 -d delay : 지정한 시간(delay 초)의 간격으로 정보를 업데이트하여 출력
 -i idle : 토글값이 off일 때, idle 프로세스나 좀비 프로세스 정보를 출력하지 않음
 -n num : 지정한 시간(num)만큼 업데이트 정보를 출력
 -p pid : 지정한 프로세스 ID(pid)의 정보만을 출력
 -q : 시간의 간격 없이 계속하여 업데이트 정보를 출력
 -s : 몇 개의 대화식 명령을 비활성화(시큐어 모드).
 -S : 누적된 정보를 출력

 ·ps : 프로세스의 현재 상태를 출력
 -A : 모든 프로세스를 출력
 -N : -A 옵션과 비슷하나 ps 프로세스를 제외하고 출력
 -a : 세션 리더 및 터미널에 속하지 않는 프로세스를 제외하고 출력
 -d : 세션 리더를 제외한 모든 프로세스를 출력
 -e : 커널 프로세스를 제외한 모든 프로세스를 출력

 T : 현재 터미널에서의 모든 프로세스를 출력
 a : 현재 터미널의 사용자 고유 프로세스를 출력
 r : 현재 실행 중인 프로세스를 출력
 x : 터미널이 없는 프로세스를 출력
 --deselect : -N 옵션과 같음

·jobs
 -l : 프로세스 그룹 ID를 state 필드 앞에 출력
 -n : 프로세스 그룹 중에 대표 프로세스 ID를 출력
 -p : 각 프로세스 ID에 대해 한 행씩 출력
 command : 지정한 명령어를 실행

·kill
 pid ··· : 종료시킬 프로세스 ID나 프로세스 이름을 지정
 -s : 전달할 시그널의 종류를 지정
 -l : 시그널로 사용할 수 있는 시그널 이름 표시
 -1, : -HUP 프로세스를 재활성화
 -9 : 프로세스를 강제로 종료



[자료]
top : https://terms.naver.com/entry.naver?docId=4125861&cid=59321&categoryId=59321
ps : https://terms.naver.com/entry.naver?docId=4125773&cid=59321&categoryId=59321
jobs : https://terms.naver.com/entry.naver?docId=4125682&cid=59321&categoryId=59321
kill : https://terms.naver.com/entry.naver?docId=4125687&cid=59321&categoryId=59321
