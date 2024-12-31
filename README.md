# 치안분야 자연어처리 벤치마크 개발

## 최종보고서 보안등급
일반[√], 보안[ ]

## 사업명
- 사업명: 인재활용확산지원
- 내역사업명: 해외우수과학자유치사업(Brain Pool)
- 전문기관명: 한국연구재단
- 연구개발과제번호: RS-2023-00304286


## 연구개발과제명
- 국문: 치안분야 자연어처리 벤치마크 개발
- 영문: Development of Natural Language Processing Benchmark for Policing

## 주관연구개발기관
- 기관명: 경찰대학 산학협력단
- 사업자등록번호: 142-82-01333
- 기관유형: 국공립(연)
- 주소: (31539)충청남도 아산시 신창면 황산길 100-50 경찰대학

- ## 연구책임자
- 성명: 윤철희
- 직위: 과학기술부 연구관
- 연락처
-  - 전자우편: bertter@police.ac.kr

## 해외우수과학자(BP Fellow)
- 성명: 김미영
- 국적: 한국
- 연락처
  - 직장전화: +1-780-679-1104
  - 전자우편: miyoung2@ualberta.ca
  - 국가연구자번호: 13024744

## 총 연구개발기간
- 2023.12.06.~2024.09.05.(9개월)

## 연구개발비(단위: 천원)


### 내역사업명
해외우수과학자유치사업(Brain Pool)

### 연구개발과제명
치안분야 자연어처리 벤치마크 개발

### 전체 연구개발기간
2023.12.06.~2024.09.05.(9개월)

### 연구개발 목표 및 내용
#### 최종 목표
치안분야 언어모델 성능평가를 위한 치안분야 벤치마크 데이터셋 개발

#### 전체 내용
1. 언어모델이 치안분야에 적용되었을 때 성능평가를 위한 치안분야 벤치마크데이터셋 개발
   - 자연언어처리 기술을 활용한 다양한 치안분야 연구기술개발이 추진되고 있지만, 핵심요소 기술인 언어모델이 치안분야에 적용되었을 때 제대로 성능평가를 할 수 있는 치안분야 벤치마크 데이터셋이 없어 문제점 발생. 관련, 치안분야 전용 벤치마크데이터셋 개발이 필요
   - 급격하게 발전하고 있는 언어모델들이 치안분야에 적용되었을 때의 성능 편차가 매우 커서 신뢰성 있는 성능 평가를 위한 치안분야 전용 벤치마크 데이터셋 개발이 필수적

2. 벤치마크 데이터셋 개발과 함께, 치안분야 언어모델 개발
   - 바이오, 의료, 법령, 특허 등의 분야에 특화된 언어모델들이 개발되었듯이, 수사, 교통, 생활안전 등 치안 데이터 학습을 기반으로 치안분야에 특화된 언어모델을 개발이 필요

#### 목표
치안분야 언어모델 성능평가를 위한 치안분야 벤치마크 데이터셋 개발

#### 내용
1. 언어모델이 치안분야에 적용되었을 때 성능평가를 위한 치안분야 벤치마크데이터셋 개발
   - 보이스피싱, 치안 질의 등 전용 벤치마크 데이터셋 9종
   - 치안데이터 비식별화, 의도분류 비식별화

2. 벤치마크 데이터셋 개발과 함께, 치안분야 언어모델 개발
   - 치안 분야 데이터셋 개발 진행 후 치안 언어모델 빌드
     ➀ Poli-ELECTRA
     ➁ Poli-Mamba
     ➂ Poli-llama
     ➃ Poli-Gemma
     ➄ Poli-llama-70B

     ## 수행 과정 및 수행 내용(Major research topics and outcome)

### 1) 주요내용(Major Topic)

| 연구내용                              | 연구결과                                                                                     |
|---------------------------------------|---------------------------------------------------------------------------------------------|
| 데이터 비식별화 수행 치안벤치 마크 셋 구성 | - 치안벤치 마크 셋을 위한 데이터셋 비식별화 제작<br> - 치안분야에 활용 가능 데이터셋 제작 (9종) : 비식별화 수행<br> - 치안분야에 활용 가능 데이터셋 활용 : 의도분석 레이블 수행 |
| 치안벤치 마크 셋 적용 치안언어 모델 빌드 | - 치안벤치 마크 셋을 위한 치안언어 모델 빌드<br> - 치안분야 언어모델 빌드 : 최신 5종 이상 언어LLM 빌드 수행                |


### 데이터 비식별화 및 치안 벤치 마크 셋 구성 

#### ➀ 데이터 비식별화 수행

■ 최근 인공지능(AI) 기술, 특히 대규모 언어 모델(Large Language Models, LLMs)과 같은 생성형 AI 기술의 급속한 발전으로 다양한 산업 분야에서 AI의 활용이 증가하고 있음. 치안 분야에서도 AI 기술을 활용한 범죄 예방, 수사 지원, 긴급 대응 등의 필요성이 대두되고 있으나, 데이터의 개인정보의 문제가 대두되어 비식별화를 수행함

■ 기존의 일반적인 AI 모델들은 치안 분야의 특수성이 담긴 데이터를 반영하지 못하여, 최신 범죄 동향이나 법률 정보 등을 즉각적으로 반영하기 어려운 한계가 있어 치안 언어용 데이터 학습이 필요

- 데이터의 특수성 적용: 치안 관련 데이터는 민감하고 기밀성이 높아 일반 AI 모델의 학습에 사용하기 어려움
- 실시간 업데이트의 필요성: 범죄 수법이나 법률은 지속적으로 변화하므로, 이를 실시간으로 반영할 수 있는 유연한 시스템 필요
- 높은 정확도 요구: 치안 분야의 의사결정은 직접적으로 시민의 안전과 권리에 영향을 미치므로 매우 높은 수준의 정확도 필요
- 범죄 패턴의 복잡화 및 다양화에 따른 데이터 적용: 사이버 범죄, 국제적 범죄 조직 등 새로운 유형의 범죄에 대응하기 위한 고도화된 분석 능력 필요
- 대규모 민감 데이터 처리의 필요성: CCTV 영상, 통신 기록, SNS 데이터 등 방대한 양의 정보를 신속하고 정확하게 분석할 수 있는 기술 요구
- 인력 및 자원의 효율적 데이터 활용: 반복적이고 시간 소모적인 업무를 AI가 대체함으로써 인적 자원을 중요 업무에 집중 배치 가능

### 1) 치안 특화 AI 시스템 개발을 위한 치안 데이터 셋 수집

- 할루시네이션의 한계극복을 위한 치안 전용 언어 모델의 데이터 셋 수집
: 기술적 문제점을 극복하고자 BELUGA(Benchmark for Empowering Law enforcement Using Generative 데이터셋: 가칭) 프로젝트 수행

### 가. 치안 AI 벤치마크 데이터셋 수집
- 범죄 예방, 긴급 신고 대응, 범죄 수사 등 각 단계별 데이터 구축
- 실제 경찰 업무 데이터를 기반으로 구축하여 현장 적용성 극대화

### 나. 개인정보 보호를 위한 철저한 비식별화 처리
- 개인정보 보호를 통한 지속적인 업데이트 체계를 통해 최신 범죄 동향 반영
- 현장 데이터를 수집하여 비식별화 처리

### 2) 치안 벤치마크 데이터 셋 구현을 위한 전용 데이터 DB구현
- 인공지능 기반 수사기법 검색·추천시스템 개발에 필요한 언어 모델을 학습하기 위해, 매뉴얼·사건·법률 데이터셋 구축과 이에 따른 파인튜닝용 데이터셋 수집 처리용 DB처리

### ■ Vishing detection 데이터 제작을 위한 전사 및 비식별화 태그 수정
- 발주처에서 제공한 데이터에 대한 초벌전사 후 비식별화 태그 수정작업을 진행 
- 총14,030건의 결과물을 정리함

### ■ Vishing next utterance prediction 데이터 제작을 위한 전사 및 의도 분류 레이블링
- 치안 데이터에 대한 초벌전사 및 전사보정 후 발화 의도 분류 레이블링 작업을 진행하여 총 48,229건의 결과물을 정리함

### ■ 지식 문서 전처리
- 치안 범죄 수사 지식 관련 raw 데이터에 대하여 발주처에서 요청한 규격에 맞게 지식 문서 가공을 진행하여, 총 57건 10,235페이지 분량에 대한 결과물을 정리함
- 비식별화 태깅 작업은 1차적으로 진행한 BIO 태그 전처리 결과물을 바탕으로 태그 오류 및 내용 오류 등을 수정 및 보완하는 작업을 진행함

### 가. 전처리 가이드라인 제작
- 비식별화 태깅 작업은 BIO 태그 전처리 결과물을 바탕으로 태그 오류 및 내용 오류 등을 수정 및 보완하는 작업을 진행함
- B(Begin)와 I(Inside)를 모두 표현하기 위하여 총 18개 태그 기호가 존재

### [비식별화 태그 분류표]
| 번호 | 태그 형식-태그명      | 설명                                   |
|------|-----------------------|----------------------------------------|
| 1    | `[B/I-name]`          | 이름(홍길동, 홍 김자 등자)              |
| 2    | `[B/I-age]`           | 나이(47세, 40대, 스물여덟살)            |
| 3    | `[B/I-birth]`         | 생년월일(83년생, 10월 30일생)           |
| 4    | `[B/I-bank]`          | 은행(농협은행, 하나은행, 카카오 뱅크)    |
| 5    | `[B/I-organization]`  | 기관/상호명(킹 엔마방, 강남 경찰서)      |
| 6    | `[B/I-address]`       | 주소(경기도 시흥시, OO로 OO번지, 동/호수) |
| 7    | `[B/I-account]`       | 계좌 번호                              |
| 8    | `[B/I-phone]`         | 핸드폰 번호                            |
| 9    | `[B/I-id]`            | 주민 등록 번호/사업자 등록 번호         |

### 예시) 구현 처리 사례
명의도 사건으로 연락드렸습니다. → 명의도용 사건으로 연락드렸습니다.
전주 농협원의 직원이었고 → 전직 농협원의 직원이었고
내경제은행[B-bank] 맞으시죠 ? → 내 국내 은행 맞으시죠?
국민[B-organization], 사회[B-organization]면[B-organization], 위메프[B-organization] → 쇼핑

2022년 3월 16일 일대[B-address]당[B-address] 기초[I-address]몰[I-address]시[I-address] 영등포구[I-address] 물패동 지점에서 우리 은행 통장을 개설한 사실이 있습니까? 어니요 → 이매 당시

월단 대전[B-address] 중, 대전광역시, 중국[B-bank]은행[B-bank]점[B-bank]점 혹은 건 적은 없다라고 하시는 거죠 ? → 중구 은행동지점

### 나. 내용 수정 및 저장
- 비식별 태그는 제작된 작업 툴을 통해 저장, 수정할 내용이 자주 출현하는 내용으로 판단될 경우 태그 뱅크에 추가하여 앞으로 작업할 문서에서 해당 내용을 자동으로 변환하여 보여주었음 
- BIO 태깅 방법은 코퍼스(corpus)로부터 개체명을 인식하기 위한 가장 보편적인 방법으로 공백(띄어쓰기)을 기준으로 B(Begin)와 I(Inside)를 구분하여 마킹하는 기준을 선정하였으며, 예를 들어 주소 정보인 "경기도 시흥시 독산동"을 태깅 한다면 아래와 같은 결과물로 태깅하였음.

### Ⓐ account
- 계좌 번호의 경우, 번호를 3~4자리씩 묻고 답하면서 말을 따라하는 경우가 많기 때문에 발화자 유추나 띄어쓰기, 작업의 일관성 관련 표기함.

### Ⓑ name
- 한사건에 등장하는 동일 인물의 이름이 텍스트 인식의 오류로 인해 다르게 나타나는 경우가 매우 자주 발생함
- 기준의 일관성을 위해 이름 태그의 경우, 자주, 그리고 많이 출현되는 이름을 기준으로 진행함
- 피해자의 이름을 물어보는 과정에서 한 글자씩 물어보는 경우와 묻고 답하면서 따라하는 경우, 발화자 유추나 띄어쓰기, B/I 태그 등 식별이 어려운 문제가 있었음
- 따라서, 위 1)번의 예시처럼 의미있는 억양구 단위마다 B/I 태그를 진행하였고, 이름이 전체적으로 불러지지 않고 성만 사용된 경우(예: 김 부장님, 박선생님, 고사장님, 김대포님 등등) name 태그를 삭제 처리

### Ⓒ bank, organization
- 은행과 기관명, 상호명 태그는 작업 기준의 일관성을 위해 아래와 같이 표기하기로 논의함

### Ⓓ birth
- 년생, 년도생, 일생, 생 등 출생과 관련된 어미 단어도 태그에 포함

예시: 
1984[B-birth]년[B-birth] 2[I-birth]월[I-birth] 6[I-birth]일[I-birth]생입니다.
↓
1984년[B-birth] 2월[I-birth] 6일[I-birth]생입니다.

1984[B-birth]년[B-birth]생 맞습니까?
↓
1984년생[B-birth] 맞습니까?

### Ⓔ age
- 세, 대, 살 등 나이와 관련된 어미 단어도 태그에 포함

예시:
40[B-age]대 남성 → 40대[B-age] 남성
39[B-age]세 → 39세[B-age]
스물여덟[B-age]살 → 스물여덟살[B-age]

### 다. 작업 툴 제작
- 비식별화 태깅 작업을 수월하게 진행하기 위하여 별도의 전용 GUI 툴을 제작하였으며 총 18건의 BIO 레이블을 쉽게 등록 및 수정, 삭제가 가능함

### 라. 후처리

#### Ⓐ 태그 미수정 및 미 작업 오류 확인 및 검증
- 비식별화 작업자가 미처 작업하지 못한 파일에서 아래와 같은 형태의 오류가 나타나는지 확인하는 과정
- 검출 방식은 비식별화 태그 기호인 "]" 과 "[" 사이에 텍스트가 존재하는지, 공백이 있는지로 판단

#### Ⓑ 태그 기호 검증
- 태그 기호에는 "-", "[", "]" 과 같은 특수 기호들이 사용

#### Ⓒ 태그 미수정 및 미 작업 오류 확인 및 검증
- 비식별화 태그에는 항상 "B" 혹은 "I"가 등장하므로 해당 내용이 유효한지 검증하는 코드를 작성
- "B"와 "I" 태그간의 혼동으로 인해 발생되는 오류를 발견하기 위해서 별도의 알고리즘을 제작
- B/I 태그들 간에 태그의 종류가 동일한 종류인지도 검증
- 예를 들어, 앞에 태그 내용은 "홍길동[B-name]" 이었는데, 뒤의 태그 내용은 "94년생[I-birth]"인 경우, B/I 태그의 종류가 다르므로 이를 검수자에게 알려줄 수 있도록 제작함

#### Ⓓ 개인 정보 내용 검출 및 태그 부착
- 태그가 달려 있지 않아도 개인정보로 판단 될 경우 발주처와 논의 하여 "[B-id]" 태그를 작성, 검출 키워드는 "주민등록, 주민번호, 민번, 앞자리, 뒷자리, 앞번호, 뒷번호, 6자리, 7자리"등

#### Ⓔ 각 태그별 내용 검증
- B/I 태그의 내용을 모두 모아서 태그 형태별로 정렬을 진행한 다음 육안으로 태그의 내용을 확인하는 검증 과정을 진행
- 아래 그림에서는 "[B-bank]"(은행명)으로 조회한 각 태그의 내용을 보여줌

### 수정 전/후 예시:

| 수정 전                                     | 수정 후                                   |
|---------------------------------------------|-------------------------------------------|
| 정희[B-name]외[B-name]                      | 정희외[B-name]                            |
| 정희[B-name]연[B-name]                      | 정희연[B-name]                            |
| 정희[B-name]린[B-name]                      | 정희린[B-name]                            |
| 정희[B-name]룬[B-name]                      | 정희룬[B-name]                            |
| 제1[B-bank]운행[B-bank]                     | 제일은행[B-bank]                          |
| 제[B-bank]은행[B-bank]                      | 제일은행[B-bank]                          |
| 저[B-bank]죽은행[B-bank]                    | 저축은행[B-bank]                          |
| 제[B-organization]1[B-organization]캐피털[B-organization] | 제일캐피털[B-organization]               |
| 제니[B-organization]스                     | 제니스[B-organization]                    |
| 제이[B-bank]티[B-bank]                      | 제이티[B-bank]                            |
| 제이[B-organization]비[B-organization]      | 제이비[B-organization]                    |
| 제이[B-organization]비[B-organization]우리[B-organization] 캐피탈 | 제이비우리캐피털[B-organization]          |
| 제이[B-organization]스핀[B-organization]   | 제이스핀[B-organization]                  |
| 제이[B-organization]유[B-organization]     | 제이유[B-organization]                    |
| 제이[B-bank] 저축은행[I-bank]               | 제이저축은행[B-bank]                      |
| 제이티[B-bank] 저축은행[I-bank]             | 제이티저축은행[B-bank]                    |
| 제이티[B-bank]진해[B-bank]저축은행[I-bank]  | 제이티진해저축은행[B-bank]                |
| 제이티[B-bank]친[B-organization]           | 제이티친[B-bank]                          |


## 2. 수행 과정 및 수행 내용(Major research topics and outcome)

### ① 치안벤치 마크 대규모언어모델(LLM) 기술 활용도 파악
- 치안코퍼스를 활용하여 치안언어 모델 빌드 타당성 조사

### ChatGPT 이후, 대규모 언어모델(LLM)을 경쟁적으로 출시

- 언어 생성 모델 생성형 AI 기술 중 하나인 대규모 언어모델(Large Language Model, LLM)은 일반적으로 수백억 개 이상의 파라미터를 포함하는 인공지능 모델을 의미하며 복잡한 언어 패턴과 의미를 학습하고 다양한 추론 작업에 대해 우수한 성능을 보유

- 특징:
 - 초거대 언어 모델은 미리 입력된 답변을 제공하는 데서 벗어나, 스스로 생각하고 학습, 판단할 수 있도록 설계
 - AI가 맥락을 파악해 능동적으로 대화 가능
 - GPT3 이후 개발된 대표적인 초거대 AI 언어 모델로는 구글의 PaLM, LaMDA, FLAN, 메타의 opt, 엔비디아의 Megatron, 네이버의 HyperCLOVA, 빅사이언스의 BLOOM, 화웨이의 Pan-Gu 등이 있음

### 주요 모델:
- ChatGPT-4 (오픈AI)
- Gemini Pro 1.5 (구글)
- ChatGPT-3.5 (오픈AI)
- Llama 3 (메타)
- Claude 3 (앤트로픽)

3LLM의 크기가 지속적으로 증가하고 있으며, GPT-3의 1,750억 개 파라미터에서 시작해 더 큰 규모의 모델들이 등장했으며, BERT(Poli-ELECTRA)와 같은 초기 모델들(3억 개 파라미터)에 비해 현대 LLM들의 규모가 훨씬 크다는 것을 보여 주고 있으며, AI 언어모델 기술의 빠른 발전 속도와 주요 기업들 간의 치열한 경쟁 상황을 잘 보여주고 있음

### [그림] 언어모델 유형
출처 "Attention Is All You Need" (2017) 논문에서 제안된 원래의 Transformer 구조

- Encoder-only 모델들: BERT, RoBERTa, ELECTRA 등
- Encoder-Decoder 모델들: T5, BART 등
- Decoder-only 모델들: GPT 시리즈, OPT, BLOOM 등

### ② 치안벤치 마크 LLM 모델 빌드
- 치안벤치마크 대규모언어모델(LLM) 언어모델 빌드

#### ⓐ Poli-ELECTRA
- Google의 ELECTRA 구조를 기반으로 한 모델로, 1.1억 및 3.3억 파라미터 버전 개발
- Transformer 아키텍처를 사용하며, Horovod를 통한 멀티-GPU 학습을 구현함

#### ⓑ Poli-Mamba
- 카네기 멜론 대학의 Mamba 구조를 채택한 7.9억 파라미터 규모의 모델
- State Space Model (SSM)을 기반으로 하며, DeepSpeed를 활용한 분산 학습을 수행함

#### ⓒ Poli-llama
- Meta의 Llama 3를 기반으로 한 80억 파라미터 규모의 모델
- Transformer 구조를 사용하며, DeepSpeed를 통한 효율적인 학습을 구현
- 기존 모델을 기반으로 추가 학습을 진행함

#### ⓓ Poli-Gemma
- Google의 Gemma 모델을 기반으로 한 90억 파라미터 규모의 모델
- Transformer 구조를 사용하며, DeepSpeed를 활용하여 학습을 진행함

#### ⓔ Poli-llama-70B
- Meta의 Llama 3.1을 기반으로 한 대규모 모델로, 700억 파라미터를 보유
- 단일 GPU와 경량화 기법을 활용하여 효율적인 학습 및 추론을 구현함

모든 모델은 NVIDIA의 고성능 GPU (A100 또는 H100)를 사용하여 학습되었으며, 치안 분야의 특수성을 반영하기 위해 관련 데이터로 추가 학습을 진행함

### 가. 폴리 일렉트라 (1.1억/3.3억 파라미터)

#### Poli-ELECTRA 성능 검증 (민간 벤치마크)
| 모델               | 크기  | 평균   | NSMC  | Naver NER | PAWS  | KorNLI | KorSTS | Question Pair | KorQuaD | Hate Speech |
|--------------------|-------|--------|-------|-----------|-------|--------|--------|----------------|---------|-------------|
| KoBERT-Base        | 1.1억 | 79.10  | 89.59 | 87.92     | 81.25 | 79.62  | 81.59  | 94.85         | 51.75   | 66.21       |
| XLM-RoBERTa-Base   | 1.1억 | 79.97  | 89.03 | 86.65     | 82.80 | 82.23  | 78.45  | 93.80         | 64.70   | 64.06       |
| KoELECTRA-Base     | 1.1억 | 84.83  | 90.63 | 88.11     | 84.45 | 82.24  | 85.53  | 95.25         | 84.83   | 67.61       |
| PoliELECTRA-Base   | 1.1억 | 85.62  | 91.99 | 90.83     | 81.45 | 83.67  | 85.67  | 95.25         | 85.26   | 70.83       |
| PoliELECTRA-Large  | 3.3억 | 85.52  | 92.37 | 91.30     | 83.30 | 83.93  | 85.95  | 95.79         | 86.54   | 72.96       |

#### Poli-ELECTRA 성능 검증 (112 코드 분류) - KoELECTRA 대비 오류율 13% 개선
| 모델                  | 예측 정확도 |
|-----------------------|-------------|
| Poli-ELECTRA-Base-112 | 87.72%      |
| KoELECTRA-Base        | 85.89%      |
| ETRI KorBERT-Base     | 85.40%      |

Poli-ELECTRA 모델의 성능을 다양한 한국어 자연어 처리 태스크에서 평가하였다. 주요 결과는 다음과 같다.

#### ➀ 일반 벤치마크 성능
- NSMC(감성분석) 태스크에서 92.37%의 정확도를 달성하여 기존 모델들을 상회하는 성능을 보였다.
- KorNLI(자연어 추론) 태스크에서 85.95%의 정확도로 우수한 성능을 나타냈다.
- KorQuaD(기계독해) 태스크에서는 EM 스코어 86.54, F1 스코어 95.79를 기록하여 높은 수준의 독해 능력을 입증하였다.

#### ➁ 치안 특화 태스크 성능
- 112 신고 코드 분류 태스크에서 Poli-ELECTRA-Base-112 모델은 87.72%의 정확도를 달성하였다.
- 이는 기존 KoELECTRA-Base 모델(85.89%)과 ETRI KorBERT-Base 모델(85.40%) 대비 각각 1.83%p, 2.32%p 향상된 결과이다.

이러한 결과는 Poli-ELECTRA 모델이 일반적인 한국어 처리 능력뿐만 아니라 치안 분야의 특수한 태스크에서도 우수한 성능을 보임을 입증한다. 특히 112 신고 코드 분류에서의 성능 향상은 실제 치안 업무에서의 활용 가능성을 높이는 중요한 성과로 볼 수있음.

### 나. 폴리 맘바 (7.9억 파라미터)

#### Poli-Mamba 성능 검증 (분류형 테스크)
| 모델 | KorNLI | NSMC | 112 코드 분류 | 112 코드 분포 |
| Poli-mamba (7.9억개) | 75.00 | 91.27 | 85.53 | 78.06 |
| 한글 Llama2 (70억개)(리더보드) | 59.71* | N/A | N/A | N/A |

#### Poli-Mamba 성능 검증 (ko-lm-harness: 생성형 AI 언어모델의 성능을 평가할 수 있는 벤치마크)
![image](https://github.com/user-attachments/assets/71e0392b-e229-44a4-8b1a-5aca8270e51c)


Poli-Mamba 모델의 성능을 다양한 벤치마크와 Few-shot 학습 시나리오에서 평가하였다. 주요 결과는 다음과 같다.

#### ➀ 기본 성능 지표
- KorNLI 태스크에서 78.80점을 기록하였다.
- NSMC 태스크에서는 91.27점의 높은 성능을 보였다.
- 112 코드 분류에서 86.73%의 정확도를 달성하였다.

#### ➁ Few-shot 학습 성능
- 0-shot, 5-shot, 10-shot 학습 시나리오에서 다양한 태스크에 대한 성능을 평가하였다.
- kobest_copa 태스크에서 0-shot 64.400, 5-shot 63.400, 10-shot 63.300으로 비교적 안정적인 성능을 보였다.
- kohatespeech_apeach 태스크에서는 0-shot 51.353, 5-shot 52.175, 10-shot 52.308로 shot 수 증가에 따른 성능 향상을 보였다.

#### ➂ 한글 Llama2 모델과의 비교
- 대부분의 태스크에서 Poli-Mamba가 한글 Llama2 모델보다 낮은 성능을 보였으나, 일부 태스크(예: kobest_hellaswag)에서는 경쟁력 있는 결과를 나타냈다.

Poli-Mamba 모델은 State Space Model 기반의 새로운 아키텍처를 채택함으로써, 특정 태스크에서 기존 Transformer 기반 모델과 차별화된 성능을 보여주었다. 특히 Few-shot 학습 능력에서 일부 태스크의 안정적인 성능은 주목할 만하다. 그러나 전반적으로 한글 Llama2 모델에 비해 성능이 낮은 점은 추가적인 최적화와 학습이 필요함을 시사한다.

### 다. 폴리라마 (80억 파라미터)

#### Poli-llama 성능 검증 (ko-lm-harness 벤치마크)
| Task              | 0-shot | 5-shot | 10-shot | Poli-llama-8B (5-shot) | 한글 Llama-3-8B (5-shot) | Llama-3-8B (5-shot) |
|-------------------|--------|--------|---------|-------------------------|--------------------------|---------------------|
| kobest_boolq      | 50.142 | 71.225 | 76.638  | 71.225                 | 80.556                  | 83.832             |
| kobest_copa       | 74.500 | 84.300 | 84.200  | 84.300                 | 80.000                  | 69.000             |
| kobest_hellaswag  | 51.200 | 65.800 | 55.200  | 65.800                 | 48.400                  | 44.800             |

#### ➀ Few-shot 학습 성능
- kobest_boolq 태스크에서 0-shot 50.142, 5-shot 71.225, 10-shot 76.638로 shot 수 증가에 따른 뚜렷한 성능 향상을 보였다.
- kobest_copa 태스크에서는 0-shot 74.500, 5-shot 84.300, 10-shot 84.200으로 5-shot에서 최고 성능을 달성하였다.
- nsmc 태스크의 경우 0-shot 51.588, 5-shot 86.656, 10-shot 89.224로 감성 분석 능력의 큰 향상을 보였다.

#### ➁ 기존 Llama 모델과의 비교 (5-shot 기준)
- kobest_boolq: Poli-llama-8B (71.225) < 한글 Llama-3-8B (80.556) < Llama-3-8B (83.832)
- kobest_copa: Llama-3-8B (69.000) < 한글 Llama-3-8B (80.000) < Poli-llama-8B (84.300)
- nsmc: 한글 Llama-3-8B (84.952) < Llama-3-8B (85.116) < Poli-llama-8B (86.656)

#### ➂ 종합 분석
- Poli-llama-8B 모델은 대부분의 태스크에서 0-shot에서 10-shot으로 갈수록 성능이 향상되는 경향을 보였다.
- 10개의 평가 벤치마크 중 8개에서 Poli-llama-8B 모델이 가장 좋은 점수를 획득하였다.
- 특히 kobest_copa, kohatespeech_apeach, nsmc 등의 태스크에서 기존 Llama 모델들을 큰 폭으로 앞서는 성능을 보였다.

이러한 결과는 Poli-llama-8B 모델이 한국어 처리에 특화되어 미세조정되었음을 보여준다. 특히 Few-shot 학습 능력의 향상은 실제 치안 업무에서 제한된 예시만으로도 효과적인 학습과 적용이 가능함을 시사함.

### 라. 폴리 젬마 (90억 파라미터)

#### Poli-Gemma 학습 효과 테스트 (ko-lm-harness 벤치마크)
| Task              | Poli-gemma-9B (90억) 0-shot | Poli-gemma-9B (90억) 5-shot | Poli-gemma-9B (90억) 10-shot | Gemma-9B (90억) 0-shot | Gemma-9B (90억) 5-shot | Gemma-9B (90억) 10-shot |
|-------------------|----------------------------|----------------------------|-----------------------------|-----------------------|-----------------------|-----------------------|
| kobest_boolq      | 60.897                     | 50.214                     | 50.499                      | 50.214                | 50.214                | 50.214                |
| kobest_copa       | 70.600                     | 79.100                     | 80.000                      | 46.900                | 47.400                | 46.900                |
| kobest_hellaswag  | 42.800                     | 44.400                     | 46.400                      | 26.800                | 29.400                | 26.800                |

Poli-Gemma 모델과 원본 Gemma 모델의 성능을 비교 분석하였다. 주요 결과는 다음과 같다.

#### ➀ Few-shot 학습 성능 비교
- kobest_boolq 태스크에서 Poli-gemma-9B는 0-shot 60.897, 5-shot 50.214, 10-shot 50.499를 기록한 반면, 원본 Gemma-9B는 모든 shot에서 50.214로 일정한 성능을 보였다.
- kobest_copa 태스크에서 Poli-gemma-9B는 0-shot 70.600, 5-shot 79.100, 10-shot 80.000으로 지속적인 성능 향상을 보였다.
- nsmc 태스크에서 Poli-gemma-9B는 0-shot 46.080, 5-shot 83.470, 10-shot 86.358로 큰 폭의 성능 향상을 달성하였다.

#### ➁ 모델 간 성능 차이 분석
- Poli-gemma-9B 모델은 대부분의 태스크에서 원본 Gemma-9B 모델보다 우수한 성능을 보였다.
- 특히 5-shot과 10-shot 학습에서 Poli-gemma-9B의 성능 향상이 두드러졌다.
- kohatespeech_gen_bias 태스크에서 Poli-gemma-9B는 0-shot 15.074에서 10-shot 72.399로 큰 폭의 성능 향상을 보였다.

#### ➂ 학습 효과 분석
- Gemma는 2024년 6월 구글에서 공개한 오픈소스 언어모델로, 한국어 데이터로 단기간 학습(12,000 step)을 통해 성능이 크게 향상되었다.
- Poli-gemma-9B 모델은 원본 Gemma 모델에 비해 한국어 처리 능력이 크게 개선되었음을 확인할 수 있다.
- 그러나 1차 학습을 완료한 Poli-llama에 비해서는 아직 전반적으로 낮은 성능을 보이고 있다.

이러한 결과는 Gemma 모델이 비교적 짧은 기간의 추가 학습으로도 한국어 태스크에 대한 적응력이 높다는 것을 보여준다. Poli-gemma-9B 모델의 성능 향상은 치안 분야 특화 데이터를 활용한 미세조정의 효과를 입증하며, 향후 추가적인 학습을 통해 더 높은 성능 개선의 여지가 있음을 시사함.

### ③ 치안벤치 마크 셋 적용 치안언어 모델 검증

#### - 언어모델 검증

##### 치안벤치 마크 셋을 위한 치안언어 모델의 데이터 셋 개발 진행 후 치안 언어모델 빌드

1. 언어모델이 치안분야에 적용되었을 때 성능평가를 위한 치안분야 벤치마크데이터셋 개발
  - 자연언어처리 기술을 활용한 다양한 치안분야 연구기술개발이 추진되고 있지만, 핵심요소 기술인 언어모델이 치안분야에 적용되었을 때 제대로 성능평가를 할 수 있는 치안분야 벤치마크 데이터셋이 없어 문제점 발생. 관련, 치안분야 전용 벤치마크데이터셋 개발이 필요
  - 급격하게 발전하고 있는 언어모델들이 치안분야에 적용되었을 때의 성능 편차가 매우 커서 신뢰성 있는 성능 평가를 위한 치안분야 전용 벤치마크 데이터셋 개발이 필수적

2. 벤치마크 데이터셋 개발과 함께, 치안분야 언어모델 개발
  - 바이오, 의료, 법령, 특허 등의 분야에 특화된 언어모델들이 개발되었듯이, 수사, 교통, 생활안전 등 치안 데이터 학습을 기반으로 치안분야에 특화된 언어모델을 개발이 필요

### ② 비식별화 이후 치안 AI 벤치마크 데이터셋 구축 및 서비스

#### - 범죄 대응 단계별 벤치마크용 데이터 셋 제작 (총9종)

1. 범죄 예방 활동용 데이터 셋 (3종):
  - 보이스피싱 대화 데이터: 실제 보이스피싱 사례를 기반으로 한 대화 시나리오 10,000건 이상 구축
  - 수사관 출석 요구 데이터: 다양한 범죄 유형별 출석 요구서 템플릿 및 예시 5,000건 구축
  - 미끼문자 데이터: 통한 최신 사기 수법이 반영된 미끼문자 50,000건 수집 및 분류

2. 긴급 신고 대응용 데이터 셋(2종):
  - 112 신고 매뉴얼: 다양한 긴급 상황별 대응 매뉴얼 1,000건 이상 디지털화
  - 긴급 신고 음성 데이터 100,000건 이상 수집 및 텍스트 변환 범죄 수사

    3. 형사 법률 조항 데이터 셋(3종):
  - 최신 개정 사항이 반영된 형법 및 특별법 조항 전수 데이터베이스화
  - 형사 판결문 데이터를 통해 최근 10년간의 주요 형사 판결문 50,000건 이상 수집 및 분석
  - 범죄 수사학 교과서 및 수사 매뉴얼 활용 수행 (디지털 포렌식, 프로파일링 등 최신 수사 기법 포함 교재 100권 이상 디지털화)

4. 범죄 분석 개체명 데이터 셋(1종):
  - 범죄 관련 특수 용어, 은어 등 200,000개 이상의 개체명 사전 구축

![image](https://github.com/user-attachments/assets/bb1c1a5d-aed8-4f4f-916e-fe334b1efc39)

### 가. 치안 데이터셋 구축 결과와 의미 설명 과정을 표현한 웹페이지 제작

- 치안 벤치마크 데이터셋을 그 자체로 언어모델의 학습용 인스트럭션 데이터셋으로 사용될 수 있으며, 해당 데이터를 파인튜닝 과정을 통해 학습한 언어모델은 치안 분야 태스크에 최적화되어, 다양한 치안 분야 서비스에 활용될 수 있음
- 본 과제를 통해 생성된 치안 분야 벤치마크 데이터셋을 다양한 치안 분야 서비스에 활용하기 위해, 치안 벤치마크 데이터셋을 설명하고 홍보하는 웹 페이지를 제작, 배포

![image](https://github.com/user-attachments/assets/3ab86fc8-5081-4b8d-baea-cf1ad3cd0f0b)


### 나. 치안 데이터를 활용해 학습한 언어모델의 벤치마크 시범서비스

- 치안 데이터 언어모델 기반 채팅 시스템라는 통합 치안 AI 연구 개발 체계를 구축
- 채팅형 시스템을 통해 범죄 차단 및 법집행을 위한 생성형 언어모델 활용이라는 의미를 담고 있으며, 다양한 생성형 AI 모델들을 경찰 활동에 적용할 수 있도록 통합하고자 함
- 향후 벤치마크 데이터셋 개발을 지속적으로 확장해 나가며, 이를 통해 경찰 활동 전반에 걸쳐 AI 기술을 보다 효과적으로 적용할 수 있는 기반을 마련할 계획

### - 범죄 수사의 3단계중 '범죄의 예방' 단계에서 필요한 자연어 처리 태스크의 설명과, 이를 통해 제작된 4개 Task에 대한 설명

### - 범죄 수사의 3단계중 '범죄 신고에 대한 긴급 대응' 단계에서 필요한 자연어 처리 태스크의 설명과, 이를 통해 제작된 2개 Task에 대한 설명

### - 범죄 수사의 3단계중 '범죄의 수사' 단계에서 필요한 자연어 처리 태스크의 설명과, 이를 통해 제작된 4개 Task에 대한 설명

### 다. 치안 데이터셋 구축 결과로 개발된 채팅형 치안 언어모델 시범 서비스 수행

- 8종의 Task 데이터는 모두 생성형 거대 언어모델(LLM)을 활용해 학습할 수 있는 형태로 제작되었으며, 범죄 수사의 큰 단계에서 모두 각각의 자연어 처리 역할을 담당
- 따라서, 해당 데이터를 학습한 언어모델은 채팅형 시스템 내에서 경찰관의 질의 응답, 범죄 수사에 대한 상황 판단 등을 할 수 있는 기본적인 능력을 갖추게 되며, 해당 학습 모델을 실제 채팅형 시스템을 시작품화하여 활용성을 증명함
- 로컬 서버에 체크포인트로 저장시킨 8종의 Task를 파인튜닝 학습한 언어모델을 사용하는 구조이며, 해당 모델의 사용 방법에 관한 소스코드는 다음과 같음
- 또한, 효율적으로 사용하기 위해, 각 태스크에 대한 사용 방법을 모델에 적절히 설명하는 인풋 프롬프트를 개발

### [기본 태스크별 인풋 프롬프트, 보이스피싱 및 112 신고 요약]

![image](https://github.com/user-attachments/assets/f8451b87-7d60-4d33-aefd-373252f948a9)
![image](https://github.com/user-attachments/assets/53e40cc3-eaf0-4fdb-a487-5d35b63940ea)


### [기본 태스크별 인풋 프롬프트, 상황요약 및 범죄 개체명 예측]

![image](https://github.com/user-attachments/assets/b61e722a-a7fe-4af3-8ffd-be8a9a554d19)
![image](https://github.com/user-attachments/assets/7282d4a4-1512-40ac-8370-04780fba1d2b)


### [기본 태스크별 인풋 프롬프트, 미끼문자 및 범죄수사 질의응답]

![image](https://github.com/user-attachments/assets/bc7b3e45-49c9-4638-8978-b3ccd4cd1102)

![image](https://github.com/user-attachments/assets/ff124b41-2826-43d4-ac77-0d63a56782ff)


### [기본 태스크별 인풋 프롬프트, 범죄수사 가설추론]

![image](https://github.com/user-attachments/assets/0e4d8ba8-c121-4a2e-b0ca-05b7ca31998d)
![image](https://github.com/user-attachments/assets/22440748-6094-473f-afe6-20a8db6d7ce1)


### ■ 치안 벤치마크 셋 데이터 활용

#### 1) 데이터 셋 필요성
- 치안 전용 언어 모델은 치안안전을 위한 자연어를 처리하고 이해하는 것을 목적으로 설계함, 이러한 모델은 방대한 치안 전용 코퍼스를 통해 텍스트 데이터로 훈련되어, 다양한 질문과 프롬프트에 대한 일관된 응답을 생성하며, 맥락에 부합
- 패턴을 분석하여 의미를 추출하며, 인간과 유사한 텍스트를 생성 
- 언어번역, 전체 텍스트 생성 및 요약, 감정분석, 질문-답변 시스템에 활용

#### 2) 데이터 셋 준비 과정
- 데이터 수집: 데이터 요구 사항을 신중하게 정의하고 신뢰할 수 있는 웹사이트, 서적, 논문에서 데이터를 수집하여 법적 준수와 개인 정보를 보장

- 데이터 필터링: 모델 기반 휴리스틱 방법을 사용하여 유해한 자료를 포함하여 품질이 낮거나 관련 없는 컨텐츠를 걸러내고 전반적인 데이터 품질을 향상

- 데이터 중복 제거: TF-IDF, MinHash, SimHash와 같은 기술을 이용하여 중복되거나 매우 유사한 텍스트를 제거하여 데이터 세트의 고유성을 보장

- 데이터 표준화: 문장 분할, 인코딩 교정, 언어 감지, 불용어 제거 및 철자 교정을 포함하여 텍스트를 통일된 형식으로 변환

- 데이터 검토: 전처리 단계를 문서화하고 수동 검토를 수행하여 데이터가 품질 표준을 충족하는지 확인하고 추가 개선을 위한 피드백을 제공

### ■ Fine Tuning Model Evaluation 사전 점검

#### 1) Lm-evaluation-harness
- EleutherAI의 Open Source Benchmark library 
- 6가지 분야에 대한 성능을 평가하여 순위 결정
- 참고: 영어를 기준으로 평가

| 평가 항목 | 설명 |
| ARC(AI2 Reasoning Challenge) | 초등학교 수준의 객관식 과학문제로 평가 |
| HellaSwag | 주어진 시나리오에서 가장 적합한 문장 선택 |
| MMLU | 상식적인 지식 평가 |
| TruthfulQA | 38개 범주에 대한 질문에 대해 LLM 답변 진실성 평가 |
| Winogrande | 주어진 문장을 완성하여 상식적 추론 테스트 |
| GSM8k | 다단계 수학적 추론 테스트 |

#### 2) Open-ko-llm-leaderboard 확인
- 한국어 리더보드이며, Open LLM LeaderBoard에서 사용하는 평가 데이터셋
- 한국어 task는 다른 언어에 비해 상대적으로 어려운 작업
- Test 데이터셋을 학습시키면 점수 상승 효과 (데이터셋 모두 공개)

#### 3) Horangi-leaderboard Neo
- Q&A 형식의 언어이해 llm-kr-eval : 일본어 버전인 llm-jp-eval 기반에서 한국어 버전으로 개발
- Multi-turn 대화를 통해 생성 능력 평가 MT-Bench
- Weight & Biases 테이블 기능을 활용 a 평가 결과를 다양한 시각에서 쉽게 분석

#### 4) LogicKor 확인
- 한국어 언어모델 다분야 사고력 벤치마크
- 벤치마크의 추론 및 평가 코드, 데이터셋 포함
- https://github.com/instructkr/LogicKor

#### 5) Poli-llama fine-tunning
Parameter 효율화 기법을 통한 성능 고도화

##### 가) 환경 세팅
- Cuda12.1 + cuDNN8 + tensorrt 8 for cuda12.1
- Cuda 12.X 와 호환되는 TensorFlow 버전
 - CUDA 12.x를 사용할 경우, TensorFlow 2.14.0 이상의 버전을 설치
- Python9
 - TensorFlow 2.14.0 의 호환되는 python 버전
- numpy 1.23.5
 - Tensorflow 2.14.0은 numpy 1.23.5 와 호환 및 안정적인 모듈
- numpy 1.23.5 아래에서 모듈 버전 호환:
  spacy==3.5.3
tensorboard==2.13.0
thinc==8.1.8
torchvision==0.15.2
blis==0.7.9

##### 나) 방식의 채택
- LoRA (Low-Rank Adaptation)
 - Poli-llama의 초기 fine-tunning시 사용했던 부분
 - QLoRA (Quantized LoRA) 학습대비 성능의 부족으로 fade-out 진행
- QLoRA (Quantized LoRA)
 - 대형모델에 적합한 fine-tunning기법으로 LoRA대비 좋은결과 도출로 채택
 - LoRA의 Rank(r) 및 Alpha 값을 높게 설정하고 양자화를 결합하여 학습

##### 다) Parameter 세팅을 통한 전이 학습

```python
# 모델의 로드
model = AutoModelForCausalLM.from_pretrained(
   model_name,
   device_map="auto",
   quantization_config=BitsAndBytesConfig(
       load_in_4bit=False,
       bnb_4bit_quant_type="nf4",
       bnb_4bit_compute_dtype=torch.float32,
       bnb_4bit_use_double_quant=True
   )
)
load_in_4bit=False

더 높은 정밀도를 위해 4비트 대신 기본 부동소수점 사용


bnb_4bit_quant_type="nf4"

nf4는 좋은 양자화 타입 옵션


bnb_4bit_compute_dtype=torch.float32

연산을 32비트 부동소수점으로 처리


bnb_4bit_use_double_quant=True

이중 양자화 활성화하여 정밀도 증가

# QLoRA 설정
peft_config = QLoRAConfig(
    r=64,
    lora_alpha=32,
    lora_dropout=0.05,
    bias="all",
    task_type="CAUSAL_LM"
)
- r=64
 - 높은 Rank로 설정으로 학습 정확도를 증가
- lora_alpha=32
 - LoRA의 alpha 값을 증가해 표현력 증가
- lora_dropout=0.05
 - 낮은 dropout으로 안정성 보장
- bias="all"
 - 원래 모델과 LoRA 모두에서 편향 항을 사용
- task_type="CAUSAL_LM"
 - Causal Language Modeling 최적화

```python
training_params = TrainingArguments(
   output_dir="./results",
   num_train_epochs=5,
   per_device_train_batch_size=32,
   gradient_accumulation_steps=1,
   optim="adamw_torch",
   save_steps=50,
   logging_steps=10,
   learning_rate=3e-5,
   weight_decay=0.01,
   fp16=True,
   bf16=False,
   max_grad_norm=0.5,
   max_steps=-1,
   warmup_ratio=0.1,
   group_by_length=True,
   lr_scheduler_type="cosine",
   report_to="tensorboard"
)

per_device_train_batch_size=32

큰 배치 크기 설정으로 정확도 증가 (GPU 메모리가 충분할 경우)


gradient_accumulation_steps=1

적은 누적 스텝으로 더 빠르게 학습


optim="adamw_torch"

AdamW 옵티마이저로 변경하여 최신 패러다임 적용


learning_rate=3e-5

최적의 학습 rate 적용
fastai 모듈을 사용하여 최적의 learning_rate 값 도출 및 적용

### ■ Prompt engineering 적용 부분 확인

#### 1) Special Token
- LLM이 텍스트 데이터를 처리할 때 사용되는 특수 토큰
- 더 이상 나눠지지 않는 하나의 토큰이며, LLM이 올바른 지시를 이해할 수 있도록 도와줌

#### 2) Multi Turn Prompt Engineering
- 여러 차례의 대화 턴을 통해 LLM에 정보 제공
- 이를 바탕으로 더욱 정교한 응답을 생성하도록 하는 Prompt Engineering 기법
- 자연스러운 대화 생성 가능, 문맥 이해 강화

#### 3) Zero-Shot Prompt Engineering
- LLM에 예제를 제공하지 않고 응답을 생성하게 하는 기법
- LLM 성능 평가 시, 보통 사용되는 기법

#### 4) Few-Shot Prompt Engineering
- LLM에 몇 가지(Few) 예제를 제공하여 응답을 생성하게 하는 기법
- Zero-Shot보다 더 나은 성능을 보임
- 예제 개수에 따라, 1-Shot, 3-Shot... 등으로 불릴 수 있음
- 일정 크기 이상의 LLM에 적용 가능
- 답변의 형식을 지정할 때도 사용 가능

#### 5) Chain-of-Thought(CoT) Prompt Engineering
- LLM이 답변을 생성할 때, 단순히 최종 답만 생성하는 것이 아닌 그 과정을 단계별로 나누어서 생각하도록 하는 기법
- 추론 과정의 투명성, 복잡한 문제 해결 능력, 학습 효율성 향상

#### 6) Generated Knowledge Prompting Engineering
- LLM으로부터 먼저 지식을 생성하게 하도록 지시하고, 생성된 지식을 Prompt에 포함하여 답변을 생성하도록 하는 기법을 고민함

#### 7) Self-Ask Prompt Engineering
- LLM이 스스로 질문을 던지며 문제 해결을 하면서, 최종적으로 답변을 생성을 하게 하는 기법

### 라. SLM을 통한 언어 모델구현 수행

#### ■ 치안 벤치마크 셋 데이터 활용
##### 1) 데이터 셋 필요성 
- 치안 전용 언어 모델은 치안안전을 위한 자연어를 처리하고 이해하는 것을 목적으로 설계함. 이러한 모델은 방대한 치안 전용 코퍼스를 통해 텍스트 데이터로 훈련되어, 다양한 질문과 프롬프트에 대한 일관된 응답을 생성하며, 맥락에 부합하는 결과를 도출함
- 패턴을 분석하여 의미를 추출하며, 인간과 유사한 텍스트를 생성
- 언어번역, 전체 텍스트 생성 및 요약, 감정분석, 질문-답변 시스템에 활용

##### 2) 데이터 셋 준비 과정
- 데이터 수집
 - 데이터 요구 사항을 신중하게 정의하고 신뢰할 수 있는 웹사이트, 서적, 논문에서 데이터를 수집하여 법적 준수와 개인 정보를 보장

- 데이터 필터링
 - 모델 기반 휴리스틱 방법을 사용하여 유해한 자료를 포함하여 품질이 낮거나 관련 없는 컨텐츠를 걸러내고 전반적인 데이터 품질을 향상

- 데이터 중복 제거
 - TF-IDF, MinHash, SimHash와 같은 기술을 이용하여 중복되거나 매우 유사한 텍스트를 제거하여 데이터 세트의 고유성을 보장

- 데이터 표준화
 - 문장 분할, 인코딩 교정, 언어 감지, 불용어 제거 및 철자 교정을 포함하여 텍스트를 통일된 형식으로 변환

- 데이터 검토
 - 전처리 단계를 문서화하고 수동 검토를 수행하여 데이터가 품질 표준을 충족하는지 확인하고 추가 개선을 위한 피드백을 제공

#### ■ Vector Database 적용 여부 확인

##### 1) Vector Database 
- Vector DB는 정보를 벡터로 저장하는 데이터베이스
- 벡터 데이터: 다차원 벡터 공간에 표현되는 데이터를 의미
 - 일반적으로 기계 학습에 사용되는 임베딩 알고리즘에서 파생

#### 2) 벡터 데이터베이스의 장점:
- 효율적인 데이터 관리: 벡터 데이터베이스는 텍스트, 이미지, 오디오 파일과 같은 대규모 비정형 데이터를 효과적으로 처리하는 데 탁월하여, 대규모 데이터셋을 다루는 비즈니스에 이상적임
- 강화된 검색 기능: 이 데이터베이스는 특히 유사성 검색과 같은 고급 검색 기능으로 유명하며, 추천 시스템이나 자연어 처리(NLP) 애플리케이션에 필수적임
- 확장성: 벡터 데이터베이스는 데이터와 컴퓨팅 요구 사항이 증가함에 따라 확장 가능하도록 설계되어, 동적 비즈니스 환경에 적응할 수 있음
- AI 및 머신러닝과의 호환성: 벡터 데이터베이스는 AI와 머신러닝 모델과의 통합을 통해 데이터 분석 및 의사결정 과정을 향상시키며, 더 정교한 애플리케이션을 제공

#### ■ Fine Tuning 수행 적용
##### 1) Transformer
- Sequence to Sequence Learning이 목표
- RNN + Attention 에 기반한 인코더 + 디코더 구조
- Self-Supervised Learning에 기반한 Pretraning+Fine-tuning 패턴 적용
- Downstream task를 위한 방법 적용
- 기계,시스템 등의 미세 조정을 의미(미세한 조정 과정을 통해 더 잘 작동되게 한다의 의미)
- 모델의 특정 레이블이 저장된 예제를 제공한 다음 역전파라는 프로세스를 통해 가중치를 업데이트
- 특정 작업이나 도메인에 높은 적합성을 확보하기 위해 미리 훈련된 모델에 특정 데이터 셋을 사용하여 추가 학습을 수행하는 것을 뜻함

##### 1-1) 활용 가능한 pipeline
| pipeline | description |
|----------|-------------|
| feature-extraction | 기계 학습 및 데이터 분석 과정으로 원시 데이터에서 관련 특징을 식별하고 추출하는 과정 |
| fill-mask | 문장의 일부 단어를 가리고 해당 마스크를 대체해야 하는 단어를 예측하는 작업 |
| ner(named entity recognition) | 엔티티를 식별하고 분류하는데 중점을 둔 NLP 기술 |
| question-answering | 자연어로 인간이 제기하는 질문에 자동으로 답변하는 시스템 |
| sentiment-analysis | 디지털 텍스트를 분석하여 메시지의 감정 톤이 긍정인지, 부정적인지, 중립적인지를 결정하는 과정 |
| summarization | 요약은 텍스트에서 참조되는 대부분 중요한 측면을 유지 |
| text-generation | 텍스트를 생성하는 것은 프롬프트를 제공하면 나머지 텍스트를 생성하여 자동으로 완성 |
| translation | 텍스트 번역 |
| zero-shot-classification | 모델이 레이블이 지정된 예제 세트에 대해 학습된 다음 이전에 볼 수 없었던 클래스에서 새로운 예제를 분류할 수 있는 작업 |

#### 2) Fine-tuning 방법 제시
##### 2-1) Full Fine-tuning
- Full Fine-tuning은 모든 모델 변수를 포함하여 사전 학습된 모델 전체를 fine-tuning 하는 작업을 의미
- 이 방법에서는 사전 학습된 모델의 모든 레이어와 매개 변수가 업데이트되고 최적화되어 대상 작업의 요구 사항에 맞게 조정
- 일반적으로 작업과 사전 학습된 모델 사이에 큰 차이가 있거나 작업에서 모델의 유연성과 적응성이 높아야 하는 경우에 적합
- Full Fine-tuning 에는 상당한 리소스와 시간이 필요하지만 그만큼 더 나은 성능을 얻을 수 있음

##### 2-2) Feature extraction(Repurposing)
- 사전 학습된 모델의 하위 레이어를 그대로 유지하면서 모델의 상위 레이어 또는 선택된 몇개의 레이어를 Fine-tuning 을 의미
- 사전 학습된 모델에 대한 일반적인 지식을 유지하면서 최상위 레이어를 특정 작업에 적용
- 대상 작업과 사전 학습된 모델 사이에 특정 유사성이 있거나 작업 데이터셋이 작은 경우에 적합
- 몇 개의 레이어만 업데이트되므로 Full fine-tuning에 비해 필요한 리소스와 시간이 적지만 경우에 따라 약간의 성능 저하가 발생

#### 3) Fine-tuning 유형
- Supervised Fine-tuning : 미세 조정 단계에서 레이블이 지정된 학습 데이터셋을 사용하는 프로세스
- Unsupervised Fine-tuning : 레이블이 지정되지 않는 학습 데이터셋을 사용하는 것을 포함

#### 4) Fine-tuning 절차

![image](https://github.com/user-attachments/assets/c429130e-11cd-4b98-ad63-4f458daaaec2)


#### 5) LLM Fine-tuning 수행
- 데이터셋 준비 → 사전학습 및 파운데이션 모델 선택 → 파인튜닝 전략 정의 → 하이퍼파라미터 설정 -> 모델 매개변수 초기화 → 파인튜닝 학습 → 모델 평가 및 튜닝 → 성능 테스트 및 배포

#### ■ Inference 체크
##### 1) Inference
- Training을 통해 만들어진 모델에 데이터를 적용하여 결과를 얻는 과정
- Inference의 속도가 빨라질수록,
 1. 사용자가 원하는 정보를 신속하게 제공 가능
 2. 동일한 시간 동안 더 많은 요청 처리 가능
 3. 전력 소모 및 하드웨어 리소스 사용 감소

#### 2) Quantization 
- 모델의 Parameter Weight(Bias) 및 Activation을 Lower bit로 표현하는 기법
- Inference 속도 상승, 모델 사이즈 축소, 모델 정확도 감소

#### 3) BetterTransformer
- Encoder, EncoderLayer, MultiHeadAttention에 ① Kernel Fusion과 ② Nested tensor을 활용한 Transformer 구조
- 독립적인 계산들을 하나로 통합하여 메모리 이동 최소화
- 입력의 희소성을 활용하여 패딩 토큰에 불필요한 작업을 하지 않도록 함

#### ■ Prompt engineering 적용 부분 확인
##### 1) Special Token
- LLM이 텍스트 데이터를 처리할 때 사용되는 특수 토큰
- 더 이상 나눠지지 않는 하나의 토큰이며, LLM이 올바른 지시를 이해할 수 있도록 도와줌

##### 2) Multi Turn Prompt Engineering
- 여러 차례의 대화 턴을 통해 LLM에 정보 제공
- 이를 바탕으로 더욱 정교한 응답을 생성하도록 하는 Prompt Engineering 기법
- 자연스러운 대화 생성 가능, 문맥 이해 강화

##### 3) Zero-Shot Prompt Engineering
- LLM에 예제를 제공하지 않고 응답을 생성하게 하는 기법
- LLM 성능 평가 시, 보통 사용되는 기법

##### 4) Few-Shot Prompt Engineering
- LLM에 몇 가지(Few) 예제를 제공하여 응답을 생성하게 하는 기법
- Zero-Shot보다 더 나은 성능을 보임
- 예제 개수에 따라, 1-Shot, 3-Shot... 등으로 불릴 수 있음
- 일정 크기 이상의 LLM에 적용 가능
- 답변의 형식을 지정할 때도 사용 가능

##### 5) Chain-of-Thought(CoT) Prompt Engineering
- LLM이 답변을 생성할 때, 단순히 최종 답만 생성하는 것이 아닌 그 과정을 단계별로 나누어서 생각하도록 하는 기법
- 추론 과정의 투명성, 복잡한 문제 해결 능력, 학습 효율성 향상

##### 6) Generated Knowledge Prompting Engineering
- LLM으로부터 먼저 지식을 생성하게 하도록 지시하고, 생성된 지식을 Prompt에 포함하여 답변을 생성하도록 하는 기법을 고민함

##### 7) Self-Ask Prompt Engineering
- LLM이 스스로 질문을 던지며 문제 해결을 하면서, 최종적으로 답변을 생성을 하게 하는 기법

#### 라. SLM을 통한 언어 모델구현 수행

#### ■ 치안 벤치마크 셋 데이터 활용
##### 1) 데이터 셋 필요성
- 치안 전용 언어 모델은 치안안전을 위한 자연어를 처리하고 이해하는 것을 목적으로 설계함, 이러한 모델은 방대한 치안 전용 코퍼스를 통해 텍스트 데이터로 훈련되어, 다양한 질문과 프롬프트에 대한 일관된 응답을 생성하며, 맥락에 부합
- 패턴을 분석하여 의미를 추출하며, 인간과 유사한 텍스트를 생성
- 언어번역, 전체 텍스트 생성 및 요약, 감정분석, 질문-답변 시스템에 활용
