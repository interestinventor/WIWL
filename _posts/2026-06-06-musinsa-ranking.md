# 데이터 입력 필요

현재 `{{rankcrawler.products}}` 변수에 실제 상품 데이터가 제공되지 않았습니다. 

Jekyll 포스트를 생성하려면 다음 형식의 데이터가 필요합니다:

```json
{
  "products": [
    {
      "rank": 1,
      "brand": "브랜드명",
      "product_name": "상품명",
      "price": 89000,
      "discount": 15,
      "imageUrl": "https://...",
      "link": "https://..."
    },
    ...
  ]
}
```

---

**100개 상품의 크롤링 데이터를 제공해주시면, 즉시 WIWL 매거진 스타일의 완성된 마크다운 포스트를 생성해드리겠습니다.**