# ChatGPT API Tutorial
`진짜 챗GPT API 활용법` 교재의 깃허브입니다.  

진짜 실무에서 사용하는 ChatGPT API 사용법들을 눌러담았습니다.
![chatgpt책](https://github.com/chatgpt-kr/chatgpt-api-tutorial/assets/79401093/1716e11f-5e6a-4fb0-bf37-7ec4781166ef)

## 문의사항 (Inquiries)

궁금한 사항이 있으면 이슈 또는 이메일 부탁드립니다.

## 저자 (Authors)

김준성 / (wnstlddl@gmail.com)  : 자율주행 개발자  
브라이스유 / (nlp.consulting777@gmail.com) :  딥 러닝 자연어 처리 연구원  
안상준 / (dailybugle@naver.com) : AI 분야 강사 및 겸임 교수


## 실습 코드 수정 내용
### 음성비서 프로그램 실습 코드 추가(23.09.09)
streamlit-audiorecorder 패키지 변경으로 인한 신규버전 음성비서 프로그램 실습파일 추가하였습니다.

책의 설명을 따라 실습을 진행하시려면 아래 2가지 방법 중 "1) 기존 실습코드 활용" 시 설명에 따라 실습을 진행합니다.
1) 기존 실습코드를 활용 시 
   - 실습 코드 : ch03/ch03_voicebot.py
   - `pip install streamlit-audiorecorder==0.0.2` 명령어로 설치(책 P.88)
  
2) 신규 실습코드를 활용 시 (ch03/ch03_voicebot_ver2.py)
   - 실습 코드 : ch03/ch03_voicebot_ver2.py
   - `pip install streamlit-audiorecorder` 명령어로 설치(책 P.88) 

### openAI 패키지 설치 명령어 변경(23.11.08)
23년 11월 7일 부로 openAI 가 대대적인 업데이트를 하면서 API 코드 문법이 변경되었습니다. 
책의 내용 및 예제코드와 동일한 실습을 위해선 아래의 명령어로 openai 패키지 설치를 진행합니다.
   - `pip install openai==0.28.1`

만약 이미 신규버전(1.1.1) 설치를 하셨다면 먼저 아래 명령어로 패키지 삭제 후 다시 설치를 진행합니다.
   - `pip uninstall openai`
