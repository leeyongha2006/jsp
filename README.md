# jsp
## jsp 처리 과정
![image](https://github.com/dldydgk/jsp/assets/126844590/7c114635-17a6-4675-b156-c085843dd3ba)

1) 클라이언트는 웹브라우저를 통해 웹 서버에게 웹 페이지 서비스를 요청한다
2) 웹서버는 jsp 스크립트 페이지인 경우, 웹 컨테이너에게 처리를 부탁한다.
3) 웹 컨테이너는 웹페이지가 서블릿 클래스를 로딩할 경우 클라이언트의 요청을 처리한다
3-1) 만일 서블릿 클래스를 로딩할 수 없는 경우, 
	jsp를 자바코드로 변환 ->	자바코드를 컴파일 -> 서블릿 클래스 생성
4) 웹컨테이너는 요청에 대한 서블릿클래스의 실행 결과를 웹 서버로 전달한다.
5) 웹 서버는 웹 컨테이너로부터 전달받은 웹 페이지(HTML형식)를 클라이언트에게 전송한다
