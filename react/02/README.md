React는 서버가 소스 코드를 확인, 변환하여 HTML 파일을 수정해 script 태그를 추가한 이후 변환된 소스 코드를 로드한다.

이런 절차를 따르는 이유
1. 처리되지 않은 리액트 코드는 브라우저가 실행할 수 없다. JSX 코드이기 때문이다.
   - JSX 코드는 JS 파일에 작성된 HTML 코드이다. 브라우저는 JS 파일을 실행할 수 있지만, JSX 코드를 실행할 수 없다.
   - React의 핵심은 JSX 코드이다. 따라서 JSX 코드를 변환하여 브라우저가 실행할 수 있는 JS 코드로 변환해야 한다.
2. 작성한 코드가 서비스를 위해 최적화되지 않았기 때문이다.
   - React는 JSX 코드를 변환하여 최적화된 코드로 변환한다. 이렇게 변환된 코드는 브라우저가 빠르게 실행할 수 있다.
