# Team 안구건조
## ★ 실시간 판정이 가능한 눈싸움 VAR ★

---

## ✅ 수정 예정 리스트
1. 실눈 상태를 '눈 감음'으로 오인 인식함
2. 눈 이외의 얼굴 영역이 가려질 경우, 얼굴 인식 실패 발생

## ✅ 진행 리스트
1. 데이터셋 https://github.com/kairess/eye_blink_detector/tree/master/dataset (2,586개)
2. keras 모델 학습
3. 소량의 이미지를 MediaPipe에서 눈 추출하여 0/1(closed/open) 인식하는지 확인

## ✅ 진행 예정 리스트
1. 대량의 이미지 파일 돌려볼 예정
2. 웹캠 연동해서 [수정 예정 리스트] 해결됐는지 확인
3. 두 사람만 인식되도록.. 

## ✅ 도구 및 라이브러리
1. Python 3.10 (MediaPipe는 Python 3.7 ~ 3.10 지원)
2. VS Code → 개발 환경
3. MediaPipe → 얼굴 및 눈 랜드마크 탐지
4. OpenCV → 웹캠 영상 처리 및 출력
5. Numpy → 수치 계산(MediaPipe 내부에서 사용)
