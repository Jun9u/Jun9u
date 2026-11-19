# 지준구

세종대학교 지능기전공학부 무인이동체공학전공 · AI 응용 개발과 데이터 분석

## 프로젝트

### [MLB 구종·투구 위치 추천](https://github.com/Jun9u/2026-DeepLearningLab-Pitch-Recommender)

**2026년 1학기 · 딥러닝실습 개인 프로젝트**  
같은 타석에서 앞선 공을 보고 다음 구종 후보를 예측. MLB Statcast 기록에서 구종과 코스별 기대득점 변화를 구해, 경기 상황을 넣으면 추천 코스를 스트라이크존에 표시하는 웹 데모 구현.

`Python` `PyTorch` `FastAPI` · [발표 자료](https://github.com/Jun9u/2026-DeepLearningLab-Pitch-Recommender/blob/main/docs/final_presentation.pdf)

<details>
<summary>⚾ 한 타석에서 볼카운트가 바뀌면?</summary>

2025년 6월 2일, 8회 무사 주자 없는 상황. 같은 타석에서 볼카운트가 바뀔 때마다 모델이 추천한 다음 공.

| 볼카운트 | 1순위 추천 | 스트라이크존 위치 |
| --- | --- | --- |
| 2볼 0스트라이크 | 싱커 | 오른쪽 가운데 · 6번 |
| 2볼 1스트라이크 | 싱커 | 오른쪽 위 · 3번 |
| 3볼 1스트라이크 | 싱커 | 가운데 위 · 2번 |

[해당 타석의 실제 투구와 추천 결과 비교](https://github.com/Jun9u/2026-DeepLearningLab-Pitch-Recommender/blob/main/outputs/outcome_recommendation_sample.csv)

</details>

### [저출생 대응 예산 × 출생환경지표 분석](https://github.com/Yumocha/yumocha)

**유모차 팀 · 공공데이터 분석**  
17개 시도의 저출생 대응 예산과 지역 여건을 연도별로 비교. 고용·주거 등 구조환경지표 28개를 지역·연도별로 정리하고, 결측 처리부터 표준화·가중지수 산출까지 담당.

[지표 통합 PR](https://github.com/Yumocha/yumocha/pull/84) · [가중지수 산출 PR](https://github.com/Yumocha/yumocha/pull/87)

## 진행 중

**[바르미](https://github.com/Jun9u/Barumi)** · 한국어 발음 연습 서비스 / 팀장·AI 담당  
Azure 발음 평가에서 단어별 점수와 오류 유형을 추출하는 코드 작성. 녹음 인식 실패와 발음 점수 0점을 구분하는 처리 및 테스트를 검토 중. [실험 PR](https://github.com/Jun9u/Barumi/pull/3)

## 활동

- 2025 세종대 SW·AI 해커톤 장려상 2회 · AI Challenge 동상
- AI 멘토 · 고급프로그래밍활용 수업 조교
- 밴드 ZIZZY에서 키보드 연주. 합주할 곡에 맞춰 신스 톤과 건반 스플릿을 직접 구성.
