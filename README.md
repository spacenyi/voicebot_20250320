# 한기대 OpenAI API를 활용한 AI 서비스 개발 II

pip install streamlit streamlit-audiorecorder

[ Streamlit Cloud 배포 ]

1. https://github.com/ 계정 생성
2. https://streamlit.io/cloud 계정 생성
3. github와 streamlit cloud 계정 연동

4. conda 환경에서 requirements.txt 파일 생성 
pip list --format=freeze > requirements.txt

6. requirements 파일에서 pywin32, pywinpty 윈도우 전용 패키지 항목 제거

7. packages.txt 파일 생성
파일 내용으로 ffmpeg 을 기술
