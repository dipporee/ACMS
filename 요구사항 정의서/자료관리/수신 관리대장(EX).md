**작업현황**

2023.05.31. ~ 2023.05.31

### 요구사항

- 메뉴 추가
    - 자료관리 – 교신문서관리 – 교신문서 관리대장(EX) – 수신 관리대장(EX)
    - sendListEx.jsp 복사하여, receiveListEx.jsp 생성
- 그리드 더블클릭하여 상세보기 시, corrPopup.jsp에서 모든 버튼 노출안함
- sendListEx.jsp 조회조건 수정
    - INST_TYPE_CD = ‘RECEIVE’ 로 변경
    - USER_SEQ 주석처리
- 상태(RECEP_STATUS_CD)
    - STANDBY: 수신대기
    - COMPLETE: 수신완료

- 그리드
    - RECEP_STATUS_CD = 'COMPLETE' 일 경우에만, RECEP_DT를 수신일 또는 접수일에 표기
    - **조회 조건**
        
        INST.BIZ_CD_SEQ = 76455
        AND INST.INST_TYPE_CD = 'RECEIVE'
        AND INST.DEL_YN = 'N'
