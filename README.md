# Literary-Therapy-lab-chatLLM
문학치료 기반 LLM챗봇 실험 연구를 위해 만들어진 챗봇


<img width="770" height="534" alt="로그인" src="https://github.com/user-attachments/assets/3f480076-cb3d-4711-9a7e-6b02c63ad69b" />

<img width="545" height="323" alt="로그인2" src="https://github.com/user-attachments/assets/338302f6-e2c7-45e1-8600-3eda69fff05b" />

앱종료 등 통제불가능한 상황에서 프롬프트 등을 노출시키기 않기 위해 실험 운영자 로그인 기능 적용

노트북 환경 등 외부 컴퓨터에서 활용하기 위해 API키를 저장하지 않고 수동입력하여 어플리케이션 시작


<img width="1050" height="903" alt="메인 1" src="https://github.com/user-attachments/assets/2b05e3b6-6304-44cc-b49d-5b4f1d6a2ff9" />


문학치료 및 이야기치료에서 이용자가 상시 읽을 수 있는 텍스트 입력 가능
시스템 프롬프트 외 준수해야 할 긍정적 프롬프트와 부정적 프롬프트 입력 가능
(상담 절차, 주요 개념, 주의점, 특정 이론이나 상담 기술 활용 등 지시)
우측 패널을 통해 이용자의 대답에 대한 공감 정도, 상담 결과 해석 안내 수준 (상담사용), 상담 시 리스크 발견 및 조치 민감성, 상담 시 적극적 질문 및 문제 탐색 성향 등을 프리셋으로 지정

<img width="1032" height="894" alt="메인2" src="https://github.com/user-attachments/assets/a2d52db1-4331-4e04-ac8c-1dc33f688d4d" />

실험자가 보게 될 메인 화면
우측에 상시로 살펴봐야 할 이야기 반복 감상 가능. 
이용자의 명시적 동의 후 채팅을 통해 이야기에 관한 채팅 상담
상담종료 시 운영자용 비밀번호 입력 후 JSON 파일로 내보내기 후 해석자 화면으로 이용
(실험환경에서 통제없이 임의로 상담종료를 눌러 피험자가 자신의 증상에 대한 내용을 열람하는 것을 차단)

<img width="1065" height="894" alt="메인3" src="https://github.com/user-attachments/assets/1a5f022c-a707-4c2e-8f1f-7ccc6044e866" />

JSON 파일 카드 내보내기 기능으로 의료전문 LLM 및 정밀 문제 탐색 편의성 지원
우측에 LLM 기반 문제 해설 제시 (gemini는 gemini 2.5 flesh가 기본값)
문제 해설을 기반한 상담사와의 치료 전략 논의 채팅 지원



* 본 어플리케이션이 의료적 임상 진단을 보장하지 않으며 오로지 원활한 이야기 기반 상담챗봇 개발 실험 진행을 위한 목적으로 개발됨
* 부주의, 오남용, 실험윤리 위반 및 허가되지 않은 방식의 오남용에 따른 책임은 전적으로 이용자에게 있음
* 파이썬 3.13 버전 이상, 필요 패키지 설치 목록과 자동 설치 버튼을 지원하나 다른 환경에서 테스트되지 않음


