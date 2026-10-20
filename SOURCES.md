# 지능의 시간 — 근거와 연출

45초 · 1920×1080 · 24fps · 한국어 타이포그래피 · 오리지널 스테레오 전자음악.
기준 시점: 2026-10-20. 2036년과 2046년은 이 기준에서 10년, 20년 뒤입니다.

## 사실과 전망의 경계

영상의 ‘최근 2년’은 2024.10–2026.10이라는 편집상의 관찰 기간입니다.
직접 확인한 공개 근거는 2024–2025년 자료가 중심입니다. 이 영상은 2026년 최신 모델이나 제품의 전수 조사, 순위표 또는 실시간 현황을 주장하지 않습니다.
화면에도 자료의 범위를 표시했습니다. 미래 장면은 아래 근거에 대한 제작자의 조건부 추론이며, 연구기관의 예측 수치가 아닙니다.

## 장면별 근거

### 00:00–00:10 / 역사

1956년 Dartmouth 연구 프로젝트를 AI 연구의 제도적 출발점으로 요약했습니다.
2012년 AlexNet의 이미지 분류 성과, 2017년 Transformer, 2022년 ChatGPT를 ‘규칙에서 학습으로, 대화형 AI의 대중화로’라는 압축된 연혁으로 배치했습니다.

관련 원전:
- McCarthy, Minsky, Rochester & Shannon, *A Proposal for the Dartmouth Summer Research Project on Artificial Intelligence* (1955; 연구 행사 1956).
- Krizhevsky, Sutskever & Hinton, *ImageNet Classification with Deep Convolutional Neural Networks* (2012).
- Vaswani et al., *Attention Is All You Need* (2017), https://arxiv.org/abs/1706.03762
- OpenAI, *Introducing ChatGPT* (2022-11-30), https://openai.com/index/chatgpt/

위 역사 원전은 서지 안내이며 이번 작업에서 본문을 새로 내려받아 검증하지 않았습니다. 아래 공개 저장소 자료는 이번 제작 중 직접 읽었습니다.

### 00:10–00:15 / 추론·코드·과학으로의 확장

- DeepSeek-AI, *DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning* (2025).
  https://github.com/deepseek-ai/DeepSeek-R1
  공식 README의 추론 학습·증류 설명과 자체 평가 결과를 참고했습니다. 제조사의 성능 주장은 독립 검증과 구분합니다.
- SWE-bench, 공식 평가 저장소.
  https://github.com/SWE-bench/SWE-bench
  실제 저장소 이슈 기반 소프트웨어 작업 평가라는 성격을 참고했습니다. 코드 생성 또는 벤치마크 해결을 현실의 모든 업무 자율 수행으로 확대 해석하지 않았습니다.
- Abramson et al., *Accurate structure prediction of biomolecular interactions with AlphaFold 3*, Nature (2024).
  https://doi.org/10.1038/s41586-024-07487-w
  공식 프로젝트 설명: https://github.com/google-deepmind/alphafold3
  생체분자 상호작용 구조 예측을 과학 도구의 예로 참고했습니다. 구조 예측을 임상적 효능·신약 완성으로 표현하지 않았습니다.

### 00:15–00:21 / 화면에 제시한 정량 근거

출처: OpenAI `simple-evals` README, Benchmark Results 표의 GPQA 열.
https://github.com/openai/simple-evals

| 모델 식별자 | GPQA |
|---|---:|
| gpt-4o-2024-11-20 | 46.0% |
| gpt-4.1-2025-04-14 | 66.3% |

이는 두 특정 모델의 공개 평가표 비교입니다. 사람의 지능, 일반적 신뢰성, 생산성, 또는 업계 전체의 평균 개선율이 아닙니다.
프롬프트·평가 설정에 따라 결과가 달라질 수 있습니다. 이 표만으로 장기적인 지수 성장을 추정하지 않았습니다.
이 저장소는 2025년 7월부터 새 모델 결과 업데이트를 중단했다고 명시합니다. 2026년 최신 평가 결과로 표시하지 않았습니다.

### 00:21–00:25 / 확산의 제약

평가 점수가 개선돼도 오류 검증, 보안, 비용, 전력, 규제와 조직 통합이 남는다는 분석입니다.
‘성능 ≠ 신뢰’는 벤치마크와 현실의 배치 가능성을 구분하기 위한 편집적 요약입니다.
단일한 확률·경제 효과·전력 수요 전망은 제시하지 않았습니다.

### 00:25–00:32 / 2036년 조건부 시나리오

추론·도구 사용이 더 안정되고 비용이 낮아질 경우, AI 에이전트가 여러 단계의 업무를 연결할 수 있다고 가정했습니다.
사람의 목표 설정·검증·승인을 유지합니다. ‘일자리 전면 대체’나 ‘완전 자율화’를 예고하지 않았습니다.
규제, 조직의 도입 속도, 취약한 장기 실행의 신뢰성이 이 시나리오를 늦추거나 바꿀 수 있습니다.

### 00:32–00:39 / 2046년 장기 시나리오

맞춤 교육·과학 도구·일부 현장 자동화가 인프라처럼 확산될 가능성을 표현했습니다.
물리적 세계의 안전, 하드웨어 교체, 전력망, 자본, 접근성과 제도 때문에 확산은 불균등할 수 있습니다.
범용 지능의 달성 연도, 완전 자율 로봇 사회, 인간의 대체는 확정하지 않았습니다.

### 00:39–00:45 / 결론

‘무엇을 맡기고, 무엇을 지킬 것인가’는 사실 예측이 아닌 가치 판단을 위한 질문입니다.

## 제작과 재현

모든 장면은 EffectCraft 네이티브 텍스트·벡터 레이어, 키프레임으로 제작했습니다.
EffectCraft CLI가 H.264 영상과 AAC 오디오를 직접 렌더링했습니다. 외부 영상 인코더로 대체하지 않았습니다.
`make_film.py`는 원본 JSX를 생성하고, `build.jsx`가 EffectCraft 프로젝트를 생성합니다.
`score.py`는 외부 샘플을 사용하지 않고 파형으로 오리지널 음악·효과음을 합성합니다. 내레이션은 없습니다.
FFmpeg/ffprobe는 재생 파일의 메타데이터·디코딩·음량 확인용으로만 사용했습니다.

사용 글꼴: NanumGothic (SIL OFL 1.1), Inter (SIL OFL 1.1), JetBrains Mono (SIL OFL 1.1).
별도 인물·브랜드·상용 영상·Adobe 에셋은 사용하지 않았습니다.
