# 스프링 부트와 AWS로 혼자 구현하는 웹서비스

- Controller(web)
    - 외부 요청과 응답에 대한 전반적인 영역

- Service
    - 일반적으로 Controller와 DAO의 중간 영역에서 사용
    - Repository의 method를 이용

- Repository(dao)
    - Database와 같이 데이터 저장소에 접근하는 영역
    - Service와 DB를 연결하는 고리의 역할을 한다
    - JPA

---
 
- DTO
    - 계층간 데이터 교환을 위한 객체  
    - DB에서 데이터를 얻어 Service나 Controller 등으로 보낼 때 사용하는 객체  
    - 즉, DB의 데이터가 Presentation Login Tier로 넘어오게 될 때는 DTO의 모습으로 바껴서 오가는 것이다.

- Entity Class
    - 실제 DB의 테이블과 매칭