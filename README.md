# 8-9-
```생활 코딩 자바스크립트(30강): 객체 기본 문법(읽고 쓰기)```

# 1). 객체 쓰기와 읽기

- 배열은 정보를 '순서대로' 저장하는 기능이 있다.

- 객체는 이름이 있는 정리정돈 상자, 순서대로 저장할 필요는 없음

- ```배열은 대괄호[ ], 객체는 중괄호 { }```

- 객체를 생성하는 방법:
  ```var coworkers = {
     "programmer" : "Dan",
     "designer" : "Sam"
    };```

- 객체를 추가하는 방법: 변수에 객체 이름을 .으로 추가해서 value 값을 준다.
  ```coworkers.bookkeeper = "Tom";```

- 객체명이 띄어쓰기를 필요로 하는 경우: . 대신 대괄호를 이용

 ```coworkers["data scientist"] = "Mac"; <br>
    document.write("data scientist: "  + coworkers["data scientist"] + "<br>");```
