# Deep Learning-based Semantic Document Decomposition
Academic Conference

  - 2024 한국정보기술학회 하계종합학술대회(2023.11.20), 우수논문상
  - 특허 출원(2024.03.19)
  - ICCDA-24(2024.08.05)

## Purpose
여러 주제들로 이루어진 문서를 여러 하위 문서 집합으로 분할할 수 있는 문서 분할 방법론을 제안

## Methodology
인코딩 기반의 언어모델을 활용하여 임베딩을 수행, 이들의 유사도를 각각 비교하여 특정 임계값 이하로 떨어지는 지점을 하위 문서 분할 지점으로 설정. 이후 클러스터링을 통해 비슷한 주제의 하위 문서 집합을 구성
	
  - Model : SBert
  - Dataset : 임의로 생성한 다양한 주제로 이루어진 신문 Data

## Result
1. 사전학습 언어모델을 활용한 시스템으로, 문맥을 고려한 문서 분할 가능
2. 높은 의미적 동질성을 갖는 문서들의 집합을 제공하여 다양한 텍스트 분석 기법의 성능을 향상시킬 수 있을 것으로 기대
3. 대량의 문서를 관리하고 분석하는 작업에서 효과적으로 활용할 수 있을 것으로 기대 