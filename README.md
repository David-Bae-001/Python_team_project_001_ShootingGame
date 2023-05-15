# 2023.python.P1
◎ 2023년 파이썬 프로젝트1\
◎ 프로젝트 이름 : Save Earth\
◎ 프로젝트 설명 : 슈팅게임 예제를 활용하여 팀 프로젝트 개발과정 < 계획 – 역할분담 – 진행 – 과정기록 – merge – test > 경험해보기\
◎ 프로젝트 기간 : 4.10. ~ 25.( 교육과 병행, 쉬는시간과 점심시간 등 최대한 활용 )\
◎ 팀원 : 팀장 배성민, 팀원 김기덕, 박수범, 조일운, 정동진\
◎ 추진방향 : \
 1. 예제로 주어진 소스코드를 기반으로 최대한 완성도를 높인다. ( 움직임, 키패드 입력, 각종 오류 개선 등 )
 2. 필수 요구사항인 움직이는 배경과 필살기를 포함시킨다.
 3. 다른 조와의 차별점을 발전시킨다.
 4. 개발은 단계별 계발로 진행한다.
◎ 개발일지 / 버전관리( 통합 )\
  - 예제코드 제대로 작동되도록 구현 : ShootingGameEx.py
  - 상하이동 구현 : ShootingGame_v0412.py
  - 대각선방향 이동 추가 : ShootingGame_v0412_2.py
  - 운석 이미지 추가 : ShootingGame_v0413.py
  - 흐르는 배경 구현 : ShootingGame_v0417.py
   => 김기덕님 설명
  - 운석회전 + 스킬게이지 구현 : ShootingGame_v0417_2.py
   => 정동진님 설명
  - 필살기( Q키 ) 구현 : ShootingGame_v0417_3.py
   => 조일운님 설명
  - 랭킹 시스템( 마리아DB 연동 )구현 : ShootingGame_v0418.py
   => 김기덕님 설명
  - 시놉시스, 처음/마지막 화면, 흐르는 배경 3종 구현 : ShootingGame_v0418_2.py
   => 배성민님 설명
  - 전반적인 소스코드 정리 : ShootingGame_v0419.py
  - 운석 여러개 떨어지도록 구현 : ShootingGame_v0420.py
   => 정동진님 설명
  - 마우스 / 키보드 모드 구현 : ShootingGame_v0420_2.py
   => 정동진님 설명
  - 전역변수, 필살기등 소스코드 개선 : ShootingGame_v0421.py
   => 배성민님 설명
  - 보스 구현 : ShootingGame_v0424.py
   => 박수범님 설명
  - 필살기 개선 : ShootingGame_v0425_2.py
    => 조일운님 설명
 ◎ 최종 비교시현 : \
  - 최초버전 : ShootingGameEx.py  // 231 lines
  - 최종버전 : ShootingGame_v0424.py  // 1054 lines
 ◎ 프로그램 강약점 : \
  1. 프로그램 강점
   - 프로그램 추가 성능개발의 가능성이 있음
    => 흐르는 배경 + 보스를 통한 게임 단계 구현 가능
   - 데이터베이스를 연동하여 랭킹 시스템을 구현
    => 게임을 종료하고 다시 켜도 랭킹이 유지됨
   - 1, 2단계 100% 구현
  2. 프로그램 약점
   - 흐르는 배경 바뀌도록 적용 시 프로그램 자체가 느려지는 현상이 있어 비활성화
   - 전역변수가 과도하게 많은 문제 : 파이썬 클래스를 사용하면 해결될 수 있으나 클래스를 아직 제대로 배우지 않아 소스코드를 클래스로 구현하지 못했음( 일부는 구현 )
   - 해결하지 못한 버그 아직 남아있음 : 운석에 직진하면 통과하는 문제, 좌우 방향키 전환시 잠깐 멈추는 문제 등
 ◎ 개발간 어려웠던 점 / 느낀 점\
  - 김기덕님 : 
   => 어려운 점 : 파이썬을 배운지 얼마안된 상태에서 게임에 도전해서 어떻게 프로그램해야 할지에 대한 어려움과 기존 소스를 클래스로 만들때 어려움이 있었습니다.
  - 정동진님 : 
   => 힘들었던 점 :  협업하는 프로젝트는 처음이기에 파일 최신화가 각자 되다 보니 어려움이 있었다.
  - 조일운님 : 
   => 어려웠던 점 : 코드에 대한 이해가 힘들어서 제가 구상한 아이디어를 코드로 구현하는게 쉽지 않았습니다.
   => 느낀 점 : python에 대한 이해도가 낮아서 아직 배울게 많다는 점을 느꼈습니다.
  - 박수범님 : 
   => 어려웠던 점 : 파이썬에 대해 잘 모르는 상태에서 진행해서 적용시키기 어려습니다. 예제소스를 가지고 진행을 했지만, 아직까지도 구조에 대해 어렵습니다.
   => 느낀 점 : python 과  다른 언어도 마찬가지로 부족한게 많다고 느꼈습니다.
  - 배성민님 : 
   => 어려웠던 점 : 개발도 개발이지만 중간에 행정적인 소요가 생각보다 상당했고 파이썬 클래스 부분에 어려움을 느꼈습니다.
   => 느낀 점 : 팀장 겸 PM 역할을 간접적으로 경험해보는 기회였는데 단순히 일을 나누는게 문제가 아니라 팀원들에 대한 전반적인 관리가 필요하다는 것을 느꼈습니다. 
 ◎ 산물정리\
  1. 프로젝트 기획서 / 보고서( .hwp )
  2. ShootingGame 폴더
   - 파이썬 버전별 .py 파일 21개( 0412 ~ 0425_2 )
   - font, images 폴더
  3. 버전관리 폴더
   - 파이썬 버전별 .txt 파일 21개( 0412 ~ 0425_2 )
  4. 개발일지 폴더
   - 일자별 개발일지 .txt 파일 13개( 0410 ~ 0425 )
