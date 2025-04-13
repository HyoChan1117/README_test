# TEAM-NOSIE-AI-PROJECT

**Noise classification project for classroom AI system**  
AI를 활용해 교실 소음을 실시간으로 분석하고, 학습을 방해하는 소리와 방해하지 않는 소리를 구분하여 시각적으로 표시하는 프로젝트입니다.

---

## 📂 REPOSITORY 구조도

![Project Structure](https://github.com/HyoChan1117/HyoChan1117/raw/master/team_project-structure.drawio.png)

---

## 📁 디렉토리 설명

| 폴더명         | 설명 |
|----------------|------|
| `src/`         | 팀 공통 코드 (학습, 예측, 모델 등) |
| `dev/`         | 각자 실험 공간 (브랜치별 관리) |
| `models/`      | 최종 모델 저장 (.pth 등) |
| `outputs/`     | 시각화 그래프, 로그, 평가 결과 등 |
| `data/`        | 공통 오디오 데이터셋 (예: loud, quiet 등) |
| `scripts/`     | 구조 재배치 등 유틸 스크립트 |
| `test/`        | 테스트용 샘플 오디오 |
| `docker/`      | PyTorch Docker 실행 환경 구성 |
| `.gitignore`   | Git 추적 제외 항목 |
| `README.md`    | 실행 가이드 및 프로젝트 설명 문서 |

---

## 주요 기술 스택

- Python, PyTorch
- Docker, Shell Script
- Librosa, OpenCV, Matplotlib
- GitHub, GitHub Actions (자동화 및 협업)

---

## 목표

- 교실 내 소음을 분석하여 **조용한 소리** / **시끄러운 소리**를 분류
- 3가지 모드 (도서관 / 회의 / 쉬는 시간)에 따라 허용 소음 기준 다르게 적용
- 분석 결과를 **웹 UI**를 통해 실시간 시각화

---

## 팀 협업 규칙 요약

- `main` 브랜치는 보호됨 → PR을 통해 병합
- 팀원별 실험은 `dev/이름/` 디렉토리에서 작업
- 코드 리뷰 후 `src/`로 병합
- `models/`에는 검증된 모델만 업로드

---

프로젝트에 대한 자세한 내용은 곧 `docs/` 폴더에 정리될 예정입니다.  
문의사항이나 제안은 PR 또는 이슈로 자유롭게 올려주세요!

