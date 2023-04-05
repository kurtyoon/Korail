# Korail
내가 쓰려고 만드는 코레일 크롤링

# 사용방법

```
pip install selenium
brew install --cask chromedriver
```

실행 후 input창에 멤버십 아이디, 비밀번호, 출발지, 도착지, 날자, 시간 입력

KTX or SRT 외 다른 기차도 찾고 싶으면 SRT / KTX 버튼 클릭 부분 코드 삭제 후 진행

현재 예약 완료 후 오류가 뜨는 버그 있음

특실 / 우등실: td[5], 일반실: td[6], 유아: td[7], 자유석 / 입석: td[8]로 수정 후 사용하면 편함
