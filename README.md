# HTTP/2 in Action 문제 모음

## 1장 웹 기술과 HTTP

1. 브라우저에 `www.google.com`이동한다고 가정해 봅시다. 우리가 웹페이지를 볼때까지 어떤 과정을 거쳐서 보이게 되는지 설명해 주세요
2. HTTP가 무엇이고 HTTP/1.1까지 어떻게 진화했는지 설명해 주세요
3. HTTP헤더의 이름은 대소문자를 구분하나요?
4. HTTP헤더를 명시하는 방법에 대해서 설명해 주세요.
5. HTTP/0.9에서는 줄 바꿈 문자를 하나만 사용해도 되는데 HTTP/1.0부터는 줄바꿈 문자를 2개 써야 합니다. 그 이유에 대해서 설명해 주세요.
6. 동일한 형식의 헤더를 여러개 보내면 어떻게 되나요?
7. HTTP 응답코드는 2xx(성공), 3xx(리다렉션), 4xx(클라이언트 오류), 5xx(서버 오류)로 분류되어 있습니다. 이렇게 분류되어 있는 이유는 무엇인가요?
8. HTTP/1.1에서 Host 헤더가 필수적으로 포함된 이유는 무엇인가요? 필수로 포함되어 생긴 문제는 무엇인가요?
9. Connection: Keep-Alive가 생긴 이유는 무엇인가요?
10. HTTPS란 무엇이고 어떤 문제 때문에 나오게 되었나요?
11. HTTPS는 HTTP 메시지에 암호화, 무결성, 인증을 추가했습니다. 각각에 대해 설명해 주세요.
12. HTTPS의 키를 교환할 때 공개키 암호화를 통해서 교환하는 이유는 무엇일까요?
13. HTTPS가 동작하는 과정에 대해서 설명해 주세요.
14. 기본적인 HTTP 도구들에는 무엇이 있나요?

## 2장 HTTP/2를 향한 여정

1. HTTP/1.1의 근본적인 성능 문제란 무엇인가요?
2. HTTP/1.1에서 파이프라이닝이 잘 쓰이지 않은 이유는 무엇인가요?
3. HTTP/1.1의 성능 문제를 우회해서 해결하는 방법에는 2가지가 있습니다. 1. 여러 HTTP 연결을 사용한다. 2. 적지만 잠재적으로 큰 HTTP 요청을 만든다. 각 해결책에 대해서 설명하고 한계점에 대해서도 설명해 주세요.
4. HTTP/1.1에서 브라우저가 도메인 당 요청 수를 6개로 제한한 이유는 무엇인가요?
5. HTTP/1.1은 텍스트 기반 프로토콜입니다. 그래서 요청과 헤더도 텍스트 기반인데요. 이로인해 생기는 문제는 무엇인가요?
6. HTTP-NG는 실패하고 SPDY는 성공할 수 있었던 이유는 무엇인가요? 
7. SPDY가 HTTP/1을 어떻게 개선했나요?
8. SPDY가 HTTP/2로 표준화된 과정은 무엇인가요?
9. 만약 HTTP/2를 적용했는데 성능에 큰 이점이 없었다. 무엇을 의심해봐야 할까?
10. HTTP/1.1의 성능 문제를 우회하는 방법이 HTTP/2에서 안티패턴이 되는 이유는 무엇인가요?

## 출처

- [HTTP/2 in Action \| 배리 폴라드 저자(글) · 임혜연 번역 \| 에이콘출판](https://product.kyobobook.co.kr/detail/S000001804952)
