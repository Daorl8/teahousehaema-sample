# STRUCTURE · teahousehaema-sample

```
teahousehaema-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인)
├─ wrangler.toml              name = teahousehaema-sample → teahousehaema-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ hm-songmyung.woff2         제목 · 세로쓰기 (송명 400, 쓰는 글자만)
├─ hm-pretendard.woff2        본문 (Pretendard 400–600, 쓰는 글자만)
├─ hm-seahorse-c.webp         해마 로고 크림색 (헤더 · 푸터)
├─ hm-sign.webp               히어로 세로 간판
├─ hm-hero / tea1 / tea2 / tea3 .webp     하동의 차 정물 4
├─ hm-leaves / shelf / cards / set .webp  클래스 (상단 · 단계 하나 · 둘 · 셋)
├─ hm-jars / counter / space .webp        작가의 다구
├─ hm-dasik / drink1~3 .webp              찻집
├─ hm-movie.webp              모임
├─ hm-table.webp              오시는 길
├─ favicon.png · og-haema.jpg
├─ img/                       다올 제공 원본 58장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로(어두움) → `#hadong`(어두움) → `#class`(밝음) → `#dagu`(밝음) → `#teahouse`(어두움) → `#gather`(밝음) → `#visit`(어두움) → 푸터 + 모바일 `.quick`.

## 링크
- 클래스 예약 `m.place.naver.com/restaurant/2029868397/booking` (헤더 · 히어로 · 클래스 · 하단 바 4곳)
- 길찾기 `map.naver.com/p/entry/place/2029868397` · 전화 `0507-1341-2816` · 인스타 `@teahouse_haema`

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 송명은 400 단일 → 제목에 font-weight 지정 금지(가짜 볼드).
