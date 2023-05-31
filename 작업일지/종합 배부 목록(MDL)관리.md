### 수신 관리대장(EX)

- 함 - 메뉴 추가
    - 자료관리 – 교신문서관리 – 교신문서 관리대장(EX) – 수신 관리대장(EX)
    - sendListEx.jsp 복사하여, receiveListEx.jsp 생성
- 함 - 그리드 더블클릭하여 상세보기 시, corrPopup.jsp에서 모든 버튼 노출안함
- 함 - sendListEx.jsp 조회조건 수정
    - INST_TYPE_CD = ‘RECEIVE’ 로 변경
    - USER_SEQ 주석처리
- 함 - 상태(RECEP_STATUS_CD)
    - STANDBY: 수신대기
    - COMPLETE: 수신완료
    

### 종합 배부 목록(MDL)관리

- [x]  버튼으로 RAI 들어가는 부분 팝업으로 선택해서 값 들어가도록 변경
- [x]  RAI 그리드 생성
- [x]  rai  마다 버튼 돋보기 생성 후 팝업 생성
- [x]  1E의 경우 배부 수는 비활성화 되어야 함.
- [x]  그리드의 값은 하드코딩으로 함.
