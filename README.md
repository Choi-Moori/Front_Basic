프론트에서 서버에 데이터 전송하는 방법
1. html에서 form 태그 사용 : 형식(Multipart/form-data, application/x-www..(url 인코딩방식))
2. js에서 axios를 통해 json 전송
3. js에서 axios를 통해 formdata(text + 파일) 전송 FormData 객체 사용
   3-1) text만 전송
   3-2) text와 파일 전송

4. js에서 json과 파일을 함께전송 -> FormData 객체 사용
