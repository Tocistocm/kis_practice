# kis_practice

입력값
SRS = input("종목 코드를 입력하세요(ex. 6AZ23): ") MNQM24 \
EXCH = input("거래소 코드를 입력하세요(ex. CME): ") CME \
STRT_DT = input("조회 시작일을 입력하세요 (YYYYMMDD 형식): ") 20240522 \
END_DT = input("조회 종료일을 입력하세요 (YYYYMMDD 형식): ") 20240524 \
GAP = input("조회 간격(분)을 입력하세요 (ex. 1) : ") 1 

안녕하세요, 5월 24일에 '해외선물분봉조회 시 시간' 으로 질문 달았던 사람입니다.

답변 주신 대로 샘플코드 활용하여 시도해보았으나 21:40~06:00 사이의 분봉값만 나오는 오류가 지속되어 재차 질문 올립니다.
아래는 시도한 코드 파일 및 결과 excel 파일올려둔 github이고,
토큰 발급시 유효기간 내 토큰 있으면 재발급 하지 않기위해 토큰 발급 부분은
샘플코드(해외선물분봉조회) 말고 답변주신 github 다른 파일에 있는 kis_auth 이용하였습니다.
kis_api01.py에서 ACCESS_TOKEN은 kis_auth.read_token()으로 가져왔습니다.
또, appkey 와 appsecret은 질문 업로드 위해 비워두었고 토큰은 정상적으로 발급 되었으며 토큰 파일은 제외하고 올립니다

번거로우시겠지만 검토해 주신다면 많은 도움 될 것 같습니다.

감사합니다.
