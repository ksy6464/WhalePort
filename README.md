
 1. 주 체

  -  공항 직원
     [공통]
       1) 로그인 (사번 / 비밀번호 찾기, SMS를 통한 임시비밀번호 발송)
       2) 마이페이지 (회원 정보 수정, 근태 현황 / 본인의 차량 등록 / 온라인 출입증 조회)
       3) 메신저 (내부 커뮤니케이션 / 알림 시스템)
       4) 웹 메일 (메일 검색 및 작성)
       5) 캘린더 (개인/부서 스케줄 일정)


     [부서별]
       1) 인사관리 (직원 관리 / 사원등록)
       2) 전산관리 (관리자)
       3) 협력업체 관리(항공사 / 보안업체 / 입접업체 / 시설업체)
       4) 공항서비스 관리 (실시간 항공 API / 시설 예약 관리 / 고객 서비스)

  -  협력업체
       1) 입점업체 계정 신청
       2) 문의 및 FAQ / 도움말 관리
       3) 보안 긴급 알림
       4) 보안 점검 및 보고서 관리
       5) 물류창고 관리
       6) 입점업체 이벤트 관리
       7) 긴급 시설 상태 점검 및 보고
       8) 정기 점검 및 유지보수 및 보고
       9) 청소 및 유지보수 요청 및 보고
       10) 항공권 가격 결정

  -  고객
       1) 회원가입
       2) 로그인(아이디 / 비밀번호 찾기, SMS를 통한 임시비밀번호 발송)
       3) 항공권 예매 / 결제 / 조회
       4) 여객, 화물 출발 / 도착시간 조회
       5) 입/출국 절차 안내 확인
       6) 고객센터 이용 가능
       7) 시설(라운지, 캡슐 호텔, 주차장, 회의실) 예약, 조회
       8) 실시간 항공편 추적 지도 확인 가능
       9) 맞춤형 알림 서비스
       10) 위치별 최단거리 동선 시스템 제공
       11) 마이페이지(회원정보수정, 예약 내역 확인)
       12) 안내 및 서비스 확인
     　　
 2. 주요 기능

 □ 공항 직원 
   - 마이페이지를 통해 근태 현황, 차량 등록 관리, 메신저, 웹메일, 캘린더를 통한 일정 관리 할 수 있다. 
   - 인사관리에서 직원 정보 등록 및 근무 일정관리 할 수 있다.
   - 협력업체 관리자는 계정 승인 및 권한 부여, 문의 관리, 항공편 스케줄 관리 및 보안 업체 일정 등을 총괄하고 전체적인 운영을 감독 할 수 있다.
   - 공항 서비스 관리는 항공편 스케줄 안내, 고객 서비스 수집, 공항 내 시설 예약 관리를 할 수 있다.
       [공통]
       1. 로그인, 로그아웃
           - 로그인 시 사번과 비밀번호가 일치하면 로그인 가능
           - 로그인 3회 실패시 Simple Captcha API를 적용하여 사번, 비밀번호, 보여주는 글자의 정보를 받아 일치해야 로그인 가능
           - 사번찾기 시 이름과 핸드폰 번호가 일치 할 때, 팝업창으로 사번 제공
           - 비밀번호 찾기 시 이름, 사번, 핸드폰 번호가 일치 할 때, SMS로 임시
             비밀번호 제공 
       2. 마이페이지
           - 회원정보 수정시 현재 비밀번호가 일치해야 수정 가능하며, 사번 및 부서를 제외한 정보들만 수정 가능 
           - 비밀번호 수정 시 대소문자, 숫자, 특수문자를 포함한 8자 이상으로 입력 가능
           - 온라인 출입증 조회 가능
           - 근태 현황
              ▷ 연간 : 총 근무시간, 결근, 조기퇴근, 지각 내역 조회 가능
              ▷ 주간 : 한 주의 연장 / 야간 근무 시간 조회 가능(주 최대 근무 시간 확인)
              ▷ 금일 : 출 퇴근 시간 기록 가능 (출/퇴근 버튼)
           - 차량 등록 : 사내 주차장 이용을 위해 차량 등록 신청 
       3. 메신저
           - 내부 커뮤니케이션 : 공항 직원 간의 원활한 소통을 위한 메시징 시스템 (1:1, N:N)
           - 알림 시스템 : 실시간 알림 및 나에게 도착한 알림(메일, 채팅) 현황 확인(읽음과 안 읽음 구분 가능)
       4. 캘린더
           - 개인용 / 업무용으로 카테고리를 나눠 일정 관리 가능

       [부서별]
       1. 인사관리
           - 직원의 정보를 등록/조회/수정/삭제 가능
           - 사원 등록 시 이름, 사번, 비밀번호(주민번호 앞자리로 설정), 이메일, 근로형태, 입사일, 소속조직, 직위, 직무, 사내전화, 휴대전화, 주소, 생년월일, 기타 정보, 첨부파일 작성
           - 직원 출입증 신청 가능
           - 직원 근무 일정 편성 후 캘린더에 배포
           - 직원 출퇴근 시간, 결근 등 근태 내역 조회
           - 조직도 조회/등록/수정/삭제 가능
       2. 전산관리
           - 업무별 접근권한 부서별 부여
           - 직원 정보 등록 내역 조회/승인/반려(이유) 가능
           - 출입증 신청 내역 조회/승인/반려(이유) 가능
       3. 협력업체 관리 (항공사 / 입점업체 / 외주업체(보안 및 시설))
           [공통]
             - 관리자(공항직원)는 협력업체의 계정 신청 확인 후 승인 또는 반려(이유) 결정가능
             - 협력업체 사업자등록번호 조회(조회 API)로 실제 업체인지 검증 가능
             - 협력업체의 문의 및 FAQ에 등록된 문의 사항 확인 후 답변 등록 가능
           [업체별]
             - 항공사
                ▷ 항공사 전체 목록 조회 가능
                ▷ 항공사 예매 정보 입력 : 
                   항공사별 스케줄 실시간 데이터 API(항공사, 이용공항(우리 공항만 사용한다고 가정하고 하나의 공항 정하기), 편명, 도착지, 수화물 찾는 곳, 도착지, 출발지, 출발 예정 시간 등) 받아서 좌석 타입, 잔여석, 수화물 정보 등 입력
             - 입점업체 
                ▷ 물류 창고 배정, 각 업체별 대여중인 물류 창고 관리(도식화)
                ▷ 입점업체의 프로모션, 이벤트 등의 정보의 게시 승인/반려(이유) 가능
             - 외주업체
                ▷ (보안) 보안 점검 등록 가능
                         보안업체 출입 허가(QR코드 발급)
                         보안 일정 캘리더에 등록(담당 관리 공항직원과 보안업체 모두 캘린더에서 일정 조회 가능)
                         보안업체 점검 결과를 확인, 피드백 가능
                         업로드된 보안 점검 보고서 PDF 형식으로 다운로드 가능
                ▷ (시설) 시설 점검(정기/청소/긴급 작업 요청) 등록 가능
                         점검 일정 캘리더에 등록(담당 관리 공항직원과 시설업체 모두 캘린더에서 일정 조회 가능)
                         시설업체 점검 결과 확인, 피드백 가능 
                         업로드된 시설 점검 보고서 PDF 형식으로 다운로드 가능  
       4. 공항서비스 관리
           - 고객 관리 : 회원가입된 고객 정보 조회 가능
           - 항공편 스케줄 안내 : 공항 내 항공편의 출발 및 도착 시간(체크인 카운터), 게이트정보, 항공 지연 및 결항 정보 등 안내 가능(항공편 / 공공 데이터 API로 실시간 데이터 활용)
           - 고객 서비스 : 문의 사항 접수 및 피드백 수집 가능
                          이벤트 정보(입점업체 포함)나 프로모션 기간 정보 팝업으로 제공
           - 시설 예약 관리 : 회의실, 라운지, 캡슐 호텔, 주차장 등 공항 내 시설의 예약 및 
                             사용 현황 관리, 공항 시설 도식화

 □ 협력업체
   - 공항 시스템에 접근할 수 있는 계정을 신청 할 수 있다.
   - 승인 된 협력업체는 실시간 알람을 받거나 작업 상태를 보고 할 수 있다.

       1. 입점업체 계정 신청
           - 계정 신청 페이지에서 필수 정보(업체명, 담당자 이름, 이메일, 연락처, 사업자 등록 번호, 제공 서비스 유형 등) 입력 후 계정 신청
           - 계정 신청 후 공항직원의 승인 대기 상태 표시
           - 계정 승인 완료 후 신청했던 아이디, 비밀번호로 시스템 내 기능 접근 가능
       2. 문의 및 FAQ / 도움말 관리
           - 승인된 협력업체는 FAQ 페이지를 통해 자주 묻는 질문을 확인 후 추가 문의 사항 등록
           - 공항직원이 등록한 답변 알람(또는 댓글)으로 받기 가능
       3. 보안 긴급 알림
           - 보안등급 중 긴급 상황에 대해서 공항 내 직원 전체에게 긴급 알림 SMS 전송 가능
       4. 보안 점검 및 보고서 관리
           - 공항직원이 등록한 보안 점검(점검일, 인원수, 점검 장소, 점검 목적 등 포함) 확인 가능
           - 보안구역 출입을 위한 QR코드로 승인된 시간 내에 보안구역 출입 가능
           - 보안 점검 후 점검 내용, 점검 직원 정보, 특이 사항 등 보고서 입력 가능
       5. 물류창고 관리
           - 입점업체별 승인된 물류창고(도식화)에 대해서만 접근 가능     
       6. 입점업체 이벤트 관리
           - 입점업체의 이벤트 정보 정보 등록(업체명, 제공 서비스, 이벤트 정보, 프로모션 
             기간 등), 수정, 삭제 신청 가능
       7. 긴급 시설 상태 점검 및 보고
           - 공항직원이 제공되는 도식에 이상 여부가 발생한 장소에 대해 긴급 작업 요청 한 것을 시설업체가 정보 확인 가능
           - 이상이 발생한 곳에 대한 점검 및 수리 후 보고 (진행 중, 수리완료 등) 실시간 가능
           - 점검 및 수리 내용을 시스템에 등록, 이 정보를 바탕으로 보고서 자동으로 시스템 업로드
       8. 정기 점검 및 유지보수 및 보고
           - 공항직원이 등록한 정기 점검 시설업체 확인 가능
           - 정기 점검 및 유지보수 완료 후 시스템에 등록, 이 정보를 바탕으로 보고서 자동으로 시스템 업로드
       9. 청소 및 유지보수 요청 및 보고
           - 공항직원이 입력한 청소 요청을 시스템에서 확인 가능
           - 작업 형태를 실시간으로 보고, 작업 완료 후 시스템에 등록, 이 정보를 바탕으로                 보고서 자동으로 시스템 업로드
       10. 항공권 가격 결정
           - 비행거리, 기종 등등 고려하여 항공권 가격 측정 가능
 
 □ 고객
   - 항공권을 예매하고 취소 할 수 있다.
   - 공항내 캡슐 호텔, 회의실, 주차장 등 시설 이용 예약, 취소, 조회가 가능하다.
   - 다양한 고객 맞춤 서비스를 제공 받을 수 있다.

       1. 회원가입
           - 아이디 : 5~20자의 영문 소문자, 숫자와 특수기호(_),(-)만 사용 가능, 중복확인 필수
           - 비밀번호 : 대소문자, 숫자, 특수문자를 포함한 8자 이상, 비밀번호 확인 필수
           - 이름 : 한글로 입력
           - 이메일 : 이메일 형식 사용, 중복 확인
           - 핸드폰 번호 : 본인 인증을 위한 SMS 확인
           - 성별, 생년월일, 주소, 개인정보처리 방침, 약관 및 마케팅 수신 동의 여부 입력
       2. 로그인
           - 로그인 시 아이디와 비밀번호 일치 할 경우 로그인 가능
           - 로그인 3회 실패시 Simple Captcha API를 적용하여 아이디, 비밀번호, 보여주는 글자 정보를 받아 일치해야 로그인 가능
           - 아이디 찾기 : 이름과 핸드폰 번호 일치 시, 팝업창으로 아이디 제공
           - 비밀번호 찾기 : 이름, 아이디, 핸드폰 번호 일치 할 때, SMS로 임시 비밀번호 제공 
       3. 항공권 예매
           - 원하는 항공편의 자세한 정보(수화물 kg, 잔여석 등등) 확인 가능
           - 선택한 항공편에 대한 예매 가능
       4. 여객, 화물 출발 / 도착시간 조회
           - 카테고리별로 출발시간, 목적지, 항공사, 터미널 출발 현황(지연, 출발, 마감 예정, 탑승 중, 탑승구 변경, 입장, 수속 중 등) 조회 가능
           - 비행 정보, 최장 이동 경로, 날씨 시차 확인 가능
       5. 입/출국 절차 안내 확인
           - 입국 경로, 검역 안내, 세관 신고, 자동 출입국 심사, 수화물 찾기 등 확인 가능
           - 공항 혼잡도(소요 시간) 실시간 확인 가능
           - ‘위험 물품 검색 시스템’ 검색 사용 가능
       6. 고객센터 이용 가능
           - 공지사항 및 FAQ 검색 및 조회 가능
           - ‘고객의 소리’를 통해 불편 사항 또는 칭찬 등록 및 삭제 가능
           - 챗봇 API 사용 가능
       7. 시설(라운지, 캡슐 호텔, 주차장, 회의실) 예약, 조회
           - 라운지
             ▷ 라운지 선택(위치, 영업시간, 이용시간, 좌석 수, 가격, 이용 가능 시설 등)
             ▷ 결제 방법 선택(예약 후 현장 결제, 공항라운지 무료 이용 가능한 카드 사용)
           - 캡슐 호텔
             ▷ 비어 있는 객실 캘린더로 확인 가능(Room type 별)
             ▷ 원하는 객실 결제 가능
           - 주차장 
             ▷ 주차장(예약 가능한 주차장 구역만 조회 가능), 입차일시, 출차일시, 차량 선택 후 예약 가능 조회
             ▷ 예약 가능할 경우 차량번호, 차종 입력, 예약 보증금 결제, 예약취소 또는 예약 부도시 예약 취소수수료 확인 후 예약 완료
            - 회의실
             ▷ 원하는 날짜, 원하는 시간대, 원하는 공간 예약 신청
             ▷ 결제는 선입금 또는 당일 결제 가능, 선입금 선택 시 입금 여부 확인 후 공항직원의 승인을 거쳐 예약 최종 확정
       8. 실시간 항공편 추적 지도 확인 가능
       9. 맞춤형 알림 서비스
       10. 위치별 최단거리 동선 시스템 제공
       11. 마이페이지
           - 현재 비밀번호 확인 후 회원정보 수정(아이디 제외한 정보) 가능
           - 항공권 예매, 시설 예약 조회/취소 가능
       12. 안내 및 서비스 확인
           - 장애인 안심 여행 서비스 이용 가능
           - 임시 여권 발급, 워킹 홀리데이, 국제 운전 면허 신청, 병역 관련 사항 홈페이지들의 링크 연결
           - 도식화된 쇼핑 및 식당 정보 조회 가능
  
3. 특이기술
     1. 항공편 조회 API
     2. WebSocket을 활용한 1:1, N:N 채팅
     3. 사업자 등록 번호 조회 API
     4. 최단 거리 알고리즘 사용
     5. 위험 물품 검사는 위한 AI 활용

4. 데이터
     1. 공공데이터 개방플랫폼에서 제공하는 인천공항 API를 통해 실시간 항공 데이터를 받을 수 있다.
     2. 공공데이터 개방플랫폼에서 제공하는 실시간 공항 혼잡도 데이터를 받을 수 있다.

