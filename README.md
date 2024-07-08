CSS적용방법 3가지
1) 인라인스타일
2) 내부스타일
3) 외부스타일
인라인 > 내부 > 외부 순으로 진행된다.

프론트에서 서버에 데이터 전송하는 방법
1. html에서 form 태그 사용 : 형식(Multipart/form-data, application/x-www..(url 인코딩방식))
2. js에서 axios를 통해 json 전송
3. js에서 axios를 통해 formdata(text + 파일) 전송 FormData 객체 사용
   3-1) text만 전송
   3-2) text와 파일 전송

4. js에서 json과 파일을 함께전송 -> FormData 객체 사용


JavaScript - 
단일 스레드 프로그래밍, 기본적으로는 동프로그래밍, DB작업 또는 API요 같은
네트워크 작업인 경우에는 비동기함수 사용. 비동기 함수 내에 실행되어야 하는 코드가
동기적, 연쇄적인 코드가 있을 경우 가독성이 떨어지고 복잡해지는 콜백지옥이 나올 수 있다.
