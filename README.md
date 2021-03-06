XE 슈퍼 캐시 모듈
=================

[XE](https://www.xpressengine.com) 또는 [라이믹스](https://www.rhymix.org)로 만들어진
대규모 사이트에서 성능을 높이고 서버 부하를 줄이기 위한 몇 가지 방법을 제공하는 모듈입니다.
XE 또는 라이믹스 버전에 따라 일부 기능이 지원되지 않을 수도 있습니다.

### 전체화면 캐시

웹 페이지 전체를 캐시에 저장해 두었다가 다른 방문자들에게도 똑같이 뿌려 주는 기능입니다.
로그인하지 않은 방문자가 대부분인 블로그, 단순 홍보성 사이트 등에서 큰 효과를 얻을 수 있으나,
사용자에 따라 내용이 달라져야 하는 사이트라면 적용이 곤란할 수도 있습니다.

### 게시판 캐시

게시판의 글 수가 많아지면 검색, 페이징, 목록 처리 등의 쿼리 소요시간이 전체 로딩 시간의 상당 부분을 차지하게 됩니다.
이 문제를 덜어 주는 페이징 캐시 기능은 대형 게시판을 사용하는 커뮤니티 사이트에 도움이 되며,
검색 결과 캐시는 DB 부하가 심한 검색 작업에 소요되는 시간을 절약해 줍니다.

### 위젯 캐시

캐시를 설정하지 않았거나 0분으로 설정한 위젯에도 모두 캐시를 적용하는 기능입니다.
위젯이 많은 화면의 로딩 속도와 DB 부하를 크게 줄일 수 있으며, 로그인 사용자가 많은 사이트에서도 효과는 동일합니다.

### 기타 편의기능

- 일부 게시판 스킨에서 검색 요청을 2번 반복하는 문제를 해결합니다.
- 일부 레이아웃과 스킨에서 페이지 전체를 CSS 또는 이미지로 다시 로딩하려고 시도하는 것을 차단합니다.
- 기본 URL 이외의 도메인으로 접속하거나 IP 주소로 직접 접속한 경우 기본 URL로 자동 리다이렉트하여 캐시 효율을 높입니다.
- Gzip 압축 기능을 세부적으로 조절하고, 일부 검색엔진에서만 압축을 끄도록 설정할 수 있습니다.

라이선스: GPLv2 이상
