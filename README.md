# MNIST Inference Project 🧠

TensorFlow 기반으로 학습된 모델을 불러와 MNIST 손글씨 이미지를 추론하는 코드입니다.

## 구성
- `saved_model/`: 학습된 모델
- `dataset_test/`: 테스트용 이미지 (`1.png ~ 10.png`)와 정답 라벨
- `mnist_inference_tf2.x.py`: 실행 코드 (TensorFlow 최신 버전 호환)
- `.gitignore`: 가상환경 및 캐시 무시

## 실행 방법
```bash
python mnist_inference_tf2.x.py
