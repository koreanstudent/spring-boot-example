# 인메모리 데이터베이스
	- h2
	   ● spring-boot-devtools를 추가 or 
	   ● spring.h2.console.enabled=true 만 추가. 
	   ● /h2-console로 접속 (이 path도 바꿀 수 있음) 
	   
	   Spring-JDBC가 클래스패스에 있으면 자동 설정이 필요한 빈을 설정 해줍니다. 
	   ○ DataSource  
	   ○ JdbcTemplate 