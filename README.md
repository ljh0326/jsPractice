|1|2|3|4|
|-----|-----|-----|-----|
|**$(선택자)**|**.검색&탐색()**|**.작업();**|**이벤트 처리**|
|*(전체) / #(ID) / .(클래스)|**체이닝 용도**|addClass() / removeClass() -> toggleClass()|on():이벤트 on / off():이벤트 off|
|h1, p (And)|**filter()** / **find()** -> 선택자에 **context**(this)를 넣어서 filter,find와 같이 한정할 수 있음|attr() / removeAttr() -> **prop()**|one():이벤트 한 번만 실행|
|h1 p (후손)|is() / has()|**html()** / text() / **val()** -> 인자 없으면 getter, 있으면 setter|trigger():이벤트 강제 발생|
|h1 > p (자손)|eq() / not()|each() : 배열 순회|-|
|h1 ~ p (형제)|first() / last()|remove():삭제 / clone():복제 / empty():지우기|-|
|h1 + p (근접 형제)|add():새로 추가 / end():이전 선택|append() / prepend() / after() / before() / appendTo() / prependTo() / insertAfter() / insertBefore()|-|
|요소:입력양식타입(button,checkbox,...)|get()|**extend()**:객체에 데이터 추가(xml자동화)|-|
|요소:입력양식상태(checked,disable,enable,focus,input,selected)|-|-|-|
