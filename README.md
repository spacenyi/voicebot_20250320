# 한기대 OpenAI API를 활용한 AI 서비스 개발 II

https://voicebot2025-aomsvhas68bppfyy5bxjsn.streamlit.app과 같은 봇 만들기 할 예정

1. pip install streamlit streamlit-audiorecorder

2. https://www.gyan.dev/ffmpeg/builds/에서 ffmpeg-git-essentials.7z다운로드받아 압축풀어 bin만 c:/ffpeg/bin복사(user 환경변수 path에 추가) 후 cmd에서 ffmpeg -version이 실행되면 성공

3. conda 환경에서 requirements.txt 파일 생성 
pip list --format=freeze > requirements.txt

4. requirements 파일에서 pywin32, pywinpty 윈도우 전용 패키지 항목 제거

5. packages.txt 파일 생성
파일 내용으로 ffmpeg 을 기술

6. packages.txt생성
packages.txt : 리눅스패키지
requirements.txt : 파이썬 패키지

7. git에 packages.txt와 requirements.txt 올림

8.https://streamlit.io/cloud free계정 생성(지금 구글 계정으로 가입함)

9. Workspaces -> setting -> github로그인 클릭 -> Authorize streamlit 클릭
