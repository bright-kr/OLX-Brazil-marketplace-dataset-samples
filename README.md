# OLX Brazil Marketplace Ads Dataset Sample

<h2>1,000개 레코드의 샘플 dataset</h2>

<a href="https://brightdata.co.kr">
    <img src="https://github.com/bright-kr/OLX-Brazil-marketplace-dataset-samples/blob/main/datasets-image.png" alt="Bright Data datasets" />
</a>

이 **OLX Brazil Marketplace Ads Dataset Sample**에는 **1,000개 레코드**가 포함되어 있으며, **Bright Data API**를 사용해 추출되었습니다.

## 데이터 포인트

| Field Name | 설명 |
|------------|-------------|
| `body` | 광고의 주요 콘텐츠 또는 설명입니다. |
| `subject` | 광고의 제목 또는 헤드라인입니다. |
| `Currency` | 가격이 표시되는 통화로, 일반적으로 BRL(브라질 헤알)입니다. |
| `priceValue` | 광고 중인 상품의 금액 또는 가격입니다. |
| `ProfessionalAnnouncement` | 광고가 전문가에 의해 게시되었는지 여부를 나타냅니다(true/false). |
| `category` | 광고의 특정 카테고리를 나타내는 숫자 ID입니다. |
| `parentCategoryName` | 광고가 등록된 상위 카테고리입니다. 예: 'Autos e peças'. |
| `categoryName` | 광고의 구체적인 카테고리명입니다. 예: 'Carros, vans e utilitários'. |
| `PublicationDate` | 광고가 게시된 날짜와 시간입니다. |
| `adReply` | 광고가 받은 답변 또는 응답 수입니다. |
| `friendlyUrl` | 온라인에서 광고를 확인할 수 있는 URL 링크입니다. |
| `Sellername` | 광고를 게시한 판매자 또는 엔티티의 이름입니다. |
| `Destaques` | 광고의 하이라이트 또는 주요 특징입니다. |
| `phone` | 판매자가 제공한 연락처 전화번호입니다. |
| `images` | 광고와 관련된 이미지의 URL 또는 링크입니다. |
| `NumberOfImages` | 광고에 포함된 이미지 수입니다. |
| `neighbourhood` | 상품이 제공되거나 등록된 동네 위치입니다. |
| `municipality` | 광고가 게시된 지방자치단체 또는 도시입니다. |
| `zipcode` | 광고 위치와 연결된 우편번호입니다. |
| `zone` | 지방자치단체 내 구역 또는 지역 분류입니다. |
| `region` | 광고가 등록된 더 넓은 지역 또는 주입니다. |
| `vehicleSpecificData` | 해당하는 경우 차량 관련 추가 사양입니다. |
| `pubSpecificData` | 광고와 관련된 게시물별 데이터 또는 메타데이터입니다. |
| `trackingSpecificData` | 광고 성과 및 참여 지표 추적에 사용되는 데이터입니다. |
| `searchboxes` | 적용된 검색 필터 또는 기준에 대한 정보입니다. |
| `breadcrumbUrls` | 사이트 내에서 광고 위치를 찾기 위한 breadcrumb URL입니다. |
| `tags` | 광고와 관련된 키워드 또는 태그입니다. |
| `featured` | 광고가 추천 또는 강조 표시되었는지 여부를 나타냅니다(true/false). |
| `vehicleTags` | 차량 광고에 특화된 태그입니다. |
| `description` | 광고에 첨부된 상세 설명 또는 서술입니다. |
| `listTime` | 광고가 처음 등록된 시점의 timestamp입니다. |
| `isFeatured` | 광고가 현재 플랫폼에서 추천 상태인지 나타내는 Boolean 값입니다. |
| `Marca` | 해당하는 경우 차량의 브랜드 또는 제조사입니다. |
| `TipoDeVeiculo` | 광고 중인 차량의 유형 또는 카테고리입니다. |
| `Quilometragem` | 차량에 해당하는 주행거리 또는 주행 킬로미터입니다. |
| `PotenciaDoMotor` | 차량의 엔진 출력 사양입니다. |
| `Combustível` | 차량이 사용하는 연료 유형입니다. |
| `ManufactureYear` | 차량 또는 상품의 제조 연도입니다. |
| `properties` | 광고와 관련된 추가 부동산 데이터입니다. |
| `locations` | 광고와 관련된 지리적 위치 데이터입니다. |
| `url` | 온라인에서 광고에 직접 접근할 수 있는 URL 링크입니다. |
| `adId` | 각 광고에 할당된 고유 식별자입니다. |
| `listId` | 광고 항목과 연결된 listing ID입니다. |
| `seller_id` | 판매자 또는 광고주의 고유 식별자입니다. |
| `destaque` | 광고의 주요 하이라이트 또는 특징입니다. |
| `tipo_anunciante` | 개인 또는 회사와 같은 광고주 유형입니다. |


## 활용 사례

### 1. 시장 트렌드 분석
광고 데이터를 분석하여 브라질 온라인 마켓플레이스의 새로운 시장 트렌드를 파악하고, 전략적 비즈니스 의사결정을 지원합니다.

### 2. 경쟁 인텔리전스
이 dataset을 활용해 경쟁사의 가격 책정 및 광고 전략을 모니터링하고, 시장 포지셔닝에 대한 인사이트를 확보할 수 있습니다.

### 3. 소비자 행동 인사이트
소비자 참여 지표와 광고 응답을 분석하여 선호도를 이해하고 마케팅 전략을 최적화합니다.



## 파일 형식

이 dataset은 여러 형식으로 제공됩니다:
- **CSV** (이 샘플에 포함됨)
- **JSON**
- **NDJSON**
- **JSON Lines**
- **Parquet**
- **Compressed (.gz)**

## 제공 옵션

- **Email**
- **API Download**
- **Webhook**
- **Amazon S3**
- **Google Cloud Storage**
- **Microsoft Azure**
- **Snowflake**
- **SFTP**

## 업데이트 주기

dataset은 다양한 일정으로 업데이트될 수 있습니다:
- **Once** (일회성 제공)
- **Daily**
- **Weekly**
- **Monthly**
- **Quarterly**
- **Custom schedules**

## 데이터 보강

특정 요구사항에 따라 추가 데이터 포인트로 dataset을 강화할 수 있습니다. 맞춤형 enrichment 옵션에 대해서는 문의해 주세요.

**[전체 OLX Brazil Marketplace Ads dataset 받기](https://brightdata.co.kr/products/datasets/olx)**

---

## 연구자 및 NGO를 위한 무료 액세스

Bright Initiative는 환경 및 사회적 이슈를 다루는 학술 연구자, NGO 및 NPO를 위해 **[Web Scraper APIs](https://brightdata.co.kr/products/web-scraper)** 및 **[바로 사용할 수 있는 datasets](https://brightdata.co.kr/products/datasets)**에 대한 무료 액세스를 제공합니다. 

무료 액세스는 [brightinitiative.com](https://brightinitiative.com)에서 신청하세요.