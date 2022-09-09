# 객체 (Object)
* 참조 타입
* 이름과 값을 한 쌍으로 묶은 데이터를 여러 개 모은 것
* 프로퍼티 : 객체에 포함된 하나의 데이터(key : value)
* 생성 방법
  * 객체 리터럴   
    *  ```javascript
       var card = { suit: "하트", rank: "A"};
       card.suit //-> 하트
       card["rank"] //-> A
  * 생성자

## 프로퍼티 추가와 삭제
* 추가
  * ```javascript
    card.value = 14;
    console.log(card) 
    //-> Object {suit: "하트", rank: "A", value: 14}
* 삭제
  * ```javascript
    delete card.rank;
    console.log(card) 
    //-> Object {suit: "하트", value: 14}
--------
# 함수 (function)
* 
