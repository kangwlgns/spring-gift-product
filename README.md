# spring-gift-product
### 클래스
* ProductController - controller
  * 상품에 대한 연산을 처리하는 핸들러가 모여 있는 클래스
  * CRUD 연산을 처리하고 결과를 반환한다.
* Product - model
  * 상품 하나하나에 대한 정보를 담는 클래스
  * Service로 분리하지 않고 로직도 포함한다.
* Products - model
  * 상품들에 모아 놓은 리스트 클래스
  * 일급 컬렉션

### Controller 사용 방법
* CREATE  
  * 상품 추가: **/products/create**
* READ
  * 상품 전체 조회: **/products/read**
  * id가 i인 상품 조회: **/products/i/read**
* UPDATE
  * id가 i인 상품 수정: **/products/i/update**
* DELETE
  * 상품 전체 삭제: **/products/delete** 
  * id가 i인 상품 삭제: **/products/i/delete**
 
### Product model 구조
* id: int
* name: String
* price: int
* img: String
