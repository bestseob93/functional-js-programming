함수형 자바스크립트 프로그래밍 책의 예제와 응용

## console.log 로깅 시 주의할 점
객체를 로깅할 때는 console.table 이나 JSON.stringfy를 이용할 것
-> 객체 값이 변경되고 콘솔 로그를 찍을 시에 펼치면 해당 객체의 메모리를 찾아가기 때문에 이전 console.log 값 또한 바뀐 console.log 값으로 보인다.
-> 잘못된 데이터를 가지고 원인을 파악하므로 삽질을 하기 쉽다. from https://aidanbae.github.io/code/javascript/console/