### Factory I/O
## 프로젝트 제출물

0. 조별 계획서
1.보고서 + 사진
2. 발표자료 ppt
3. 동영상 ( plc , hmi , scada 연동 )

트윈은 자산을 시각화 하는 것보다, AI 최적화 루프에 데이터를 공급할 수 있는지.

AI로 트윈 분석 -> 변경안 실험 -> 검증 적용

# 설정

1. num : 탐지된 비트에 따라 해당 하는 값을 돌려줌.
2. digital : 비트
3. analog : 아날로그 전압 값 0 ~ 10 V

# 서버 연결
1. MX OPC
2. New MX Devie
3. GX Simulator2
4. factory I/o Files
5. drivers
6. browse

# 물체 값

블루 : 1 , bool 0
그린 : 4 , bool 2
메탈 : 7 , bool 0 , 1 , 2

# 시뮬레이션 수정

mx opc 정지 - > 시뮬 정지 - > 수정 -> 시뮬 시작 -> mx opc 재시작 ( factory i/o 는 수정 필요 x )

# 참고

비전 검사 트리거 값은 바로 초기화됨 !
