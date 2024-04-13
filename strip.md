



Strip Handler
2015-07-01 ~ 2016-07-01
* 메인 프로그래머로 장비 개발 진행.
  - 장비 제어 Framework 개발. ( 장비 제어에 공통적인 부분을 Framework로 제작하여 다른 프로젝트에서도 사용 가능하도록 개발 함. )

1.  Machine Vision 이용한 Strip Align 기능 개발.
  - 자재 Test를 위해서는 +- 20um 이내의 Contact 정밀도가 필요 함.
  - Strip의 Fiducial Mark 이용하여 현재 Strip 위치와 Contact 위치 오차 계산 후 정확히 Contact 될 수 있도록 제어.

2. 기구 충돌 방지 기능 개발.
  - 이동하는 기구물의 치수와 해당 모터의 진행 방향을 가지고 장비의 원점 기준 가상 3차원 좌표 생성.
  - 모션 동작 시 실시간으로 현재 위치 및 이동 경로 파악 후 Collision Check 진행 할 수 있도록 기능 개발.
