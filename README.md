### 오픈소스 기여

- `toss/es-toolkit`
  - [unzip 함수 구현](https://github.com/toss/es-toolkit/pull/100)
    - unzip 함수 명령형 코드로 퍼포먼스를 중점으로 구현
- `toss/slash`

  - [useStorageState 버그 픽스](https://github.com/toss/slash/pull/494)
    - 브라우저 Storage와 React State를 동기화하는 커스텀 훅에서 발생한 버그 픽스
  - [useOutsideClickEffect 이슈라이징](https://github.com/toss/slash/issues/354)
    - 모바일환경에서 'click' 이벤트와 'touch' 이벤트에서 두번 콜백이 발생하는 버그
  - [useOutsideClickEffect 문서 수정](https://github.com/toss/slash/pull/304)
    - 실제 동작과 문서가 다른 부분을 수정
  - [isMobile 리팩토링](https://github.com/toss/slash/pull/290/files)
    - userAgent를 파싱하는 방식을 재사용 가능한 함수를 사용하도록 리팩토링

- `toss/es-hangul`

  - [한글 문자열에 대한 검증, assert, parsing 함수를 구현](https://github.com/toss/es-hangul/pull/136)
    - 한글 문자열에 대한 검증, assert, parsing 함수를 구현
  - [hangulIncludes 불변성 버그 이슈라이징](https://github.com/toss/es-hangul/issues/106)
    - 한글 문자열을 다루는 함수에서 불변성을 지키지 않는 버그

- `Nextjs.kr`
  - [useSearchParams 문서 번역](https://github.com/Nextjs-kr/Nextjs.kr/pull/417)
- `reactjs`
  - [createElement 문서 번역](https://github.com/reactjs/ko.react.dev/pull/677)
- `lerna`
  - [문서화](https://github.com/lerna/lerna/pull/3987)
    - 모노레포 라이브러리를 작업하며 사용한 lerna에서 발견한 오타 수정
