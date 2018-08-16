# Handsome-U
OpenCV를 활용한 리듬 게임

프로젝트 소개
- 프로젝트 주제 : 
	OpenCV 게임 제작
- 프로젝트 목표 : 
	사용자의 표정과 감정을 인식하여 화면에 표시되는 감정에 대한 알맞은 표정을 지어  점수를 낸다.
  
  Main : 게임 진행 클래스
 - Score : 점수
 - Top Score : 최고 점수 
 - Top Score Time :  최고 점수 기록 시간
 - Mode : 게임 모드
 
Face Recognition : 표정인식 클래스
 - Anger : 화남 
 - Happy : 기쁨
 - Sad : 슬픔
 - Fear : 두려움
 - Surprise : 놀람
 - 
Easy Mode : 이지 모드 게임진행 모드 클래스
 - Score : 점수
 - Life : 생명
 - Left Time : 남은 시간
 - Face Recognition : 얼굴 인식
 - Result Recognition : 표정 결과
 - Frame : 출력되는 화면

Hard Mode : 하드 모드 게임진행 모드 클래스
 - Score : 점수
 - Life : 생명
 - Left Time : 남은 시간
 - Face Recognition : 얼굴 인식
 - Result Recognition : 표정 결과
 - Frame : 출력되는 화면


3. 테스트 시나리오

3-1. 시나리오
표정 인식을 통해 화면에 표시되는 감정키워드에 따른 표정을 지어서 점수를 얻는 게임을 
구성하였습니다.

게임의 플레이과정은 다음과 같습니다.
1. 모드 인식(이지모드,하드모드)
2. 해당 모드 플레이
3. 감정 키워드 전달 
4. 플레이어가 감정인식API에서 인식되는 알맞은 표정을 지으면 스코어 획득 or 알맞지 않은 	표정을 지으면 라이프 감소
5. 목숨을 다 잃으면 게임 오버
6. 초기화면
