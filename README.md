# functional-javascript

유인동 강사의 "함수형 프로그래밍과 JavaScript ES6+" 강의를 따라가며 작성한 코드 저장소.

단순 예제 저장이 아니라, 개념을 직접 구현하고 조합하는 방식으로 이해를 쌓았다.

## 다룬 것

- 이터러블/이터레이터 프로토콜 직접 구현
- 제너레이터 기반 지연 평가 (`L.range`, `L.map`, `L.filter`, `take`)
- `go`, `pipe`, `curry`로 파이프라인 구성
- Promise를 일급 값으로 다루고 `go`/`reduce`에 비동기 통합
- Kleisli Composition과 `nop`으로 비동기 필터링 처리

## 구조

| 폴더 | 내용 |
|---|---|
| `01-functional-javascript-basics` | 평가, 일급, 고차 함수 |
| `02-es6-iteration-iterable-iterator-protocol` | for...of, Symbol.iterator |
| `03-generator-and-iterator` | 제너레이터, odds, 무한 수열 |
| `04-map-filter-reduce` | 이터러블 기반 직접 구현 |
| `05-code-as-value-expressiveness` | go, pipe, curry |
| `06-html-output` | 장바구니 DOM 렌더링 |
| `07-laziness-1-08-laziness-2` | 지연 평가, flatMap, join |
| `09-async-concurrency-programming` | Promise + go/pipe 통합 |
| `10-async-concurrency-programming-2` | 지연 평가 + Promise, nop |
| `11-async-concurrency-programming-3` | async/await, FxJS map |
