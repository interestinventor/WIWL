# 데이터 입력 필요

현재 `{{rankcrawler.products}}` 변수에 무신사 랭킹 데이터가 제공되지 않았습니다.

**100개 상품 데이터를 다음 형식으로 제공해주세요:**
```json
[
  {
    "rank": 1,
    "brand": "브랜드명",
    "name": "상품명",
    "price": 원가,
    "discount": 할인율,
    "final_price": 최종가격,
    "imageUrl": "이미지 URL",
    "link": "상품 링크"
  },
  ...
]
```

데이터가 입력되면 즉시 Jekyll 블로그 포스팅 마크다운을 생성해드리겠습니다.