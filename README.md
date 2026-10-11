
## 이동녕 | DongNyoung Lee
Backend Engineer

## Skills

Java · Spring Boot · PostgreSQL · Redis · OpenSearch · AWS · Docker

## Open Source

### FasterXML / Jackson

Java 기반 JSON 처리 라이브러리 Jackson의 **파싱 정확성, 캐시 일관성, 리소스 관리 및 데이터 바인딩 안정성** 개선에 기여하고 있습니다.

[View all FasterXML contributions →](https://github.com/search?q=org%3AFasterXML+author%3ADongnyoung+is%3Apr&type=pullrequests)

#### jackson-core
- [Fix UTF-8 surrogate validation in String skip path #1727](https://github.com/FasterXML/jackson-core/pull/1727)
- [Prevent stale symbol table children from replacing newer root tables #1655](https://github.com/FasterXML/jackson-core/pull/1655)
- [Fix ByteBuffer-backed async releaseBuffered() output #1647](https://github.com/FasterXML/jackson-core/pull/1647)

#### jackson-databind
- [Fix read-only serializer cache invalidation for typed replacements #6143](https://github.com/FasterXML/jackson-databind/pull/6143)
- [Apply default null handling to @JsonAnySetter #6171](https://github.com/FasterXML/jackson-databind/pull/6171)
- [Fix DefaultCacheProvider.Builder default cache sizes #6138](https://github.com/FasterXML/jackson-databind/pull/6138)

#### jackson-dataformats-binary
- [Fix unsupported isEnd() call for Apache DirectBinaryDecoder #808](https://github.com/FasterXML/jackson-dataformats-binary/pull/808)



### Other Open Source Contributions

- **Spring Framework** — [PR #34856](https://github.com/spring-projects/spring-framework/pull/34856), [PR #35444](https://github.com/spring-projects/spring-framework/pull/35444)
- **Node.js** — [PR #7868](https://github.com/nodejs/nodejs.org/pull/7868)
- **Pinpoint APM** — [PR #13281](https://github.com/pinpoint-apm/pinpoint/pull/13281)
- **Lombok** — [PR #3998](https://github.com/projectlombok/lombok/pull/3998)
- **Spring Guides** — [PR #82](https://github.com/spring-guides/gs-accessing-data-jpa/pull/82)

## Projects

### Dealit

실시간 경매 기반 중고거래 플랫폼 | 팀장 · Backend · Infrastructure

**Tech Stack:** Java, Spring Boot, PostgreSQL, Redis, OpenSearch, AWS, Docker

[GitHub](https://github.com/Dealit-2026) · [시연 영상](https://www.youtube.com/watch?v=CkGmaPMyGKs)

- **Concurrency:** Redis + Lua Script로 동시 입찰 시 조회·비교·갱신을 원자적으로 처리
- **Performance:** Pinpoint APM으로 OpenSearch 동기 인덱싱 병목을 분석하고 비동기화하여 API 응답 지연시간 **p95 5.37s → 59.6ms (98.9% 단축)**
- **Data Integrity:** 멱등키, Wallet-Ledger 및 비관적 락을 활용한 결제 정합성 보장

## Stats

[![Solved.ac Profile](http://mazassumnida.wtf/api/mini/generate_badge?boj=leedo7182)](https://solved.ac/leedo7182)

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=leedo7182)](https://solved.ac/leedo7182/)
