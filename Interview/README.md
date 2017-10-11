# iOS 신입 개발자 면접 질문 정리

`작성자 : 구찬우(Brix)`

## CS

* ### 자료구조와 알고리즘

  ##### `아래 목록들이 어떤 원리로 구현되는지 꼭 찾아보세요.`

  * ##### 알고리즘 복잡도 개념

    * 빅오 표기법
    * 시간 복잡도
    * 공간 복잡도

  * ##### Sort 알고리즘

    ##### `코드까지 아니더라도 구현 원리와 시간 및 공간 복잡도는 기본적으로 숙지`

    * QuickSort
    * MergeSort
    * InsertionSort
    * SelectionSort
    * BubbleSort

  * ##### 연결 리스트(Linked List)

    * Single Linked List
    * Double Linked List

  * ##### 배열

    * 연결 리스트(Linked List)와 차이점 (장/단점)

  * ##### 선형 구조

    * 스택 (Stack)
    * 큐 (Queue)
    * 데크 (Deque)

  * ##### 비선형 구조

    * 그래프 (graph)
    * 트리 (Tree)

  * ##### 피보나치 수열을 구현해보세요.

  * ##### 10진수 -> 16진수 또는 16진수 -> 10진수 변환 알고리즘을 구현해보세요.




* ### 운영체제

  * ##### Process와 Thread의 차이는?

  * ##### 한 Process내에서 각각의 Thread가 공유하는 영역과 공유하지 않는 영역은?

  * ##### 스케쥴링

  * ##### 메모리 구조에 대해 설명하세요.

    * 데이터 영역

    * 스택 영역

    * 힙 영역

      ##### `각 영역에 대해 찾아보세요.`

* ### 네트워크

  * 인터넷 브라우저 주소창에 `http://www.naver.com` 를 입력했을 때 네트워크가 통신하는 과정을 설명하세요.
  * HTTP Method의 종류를 나열하고 설명하세요.
  * HTTP Method 중 GET과 POST의 차이

* ### 데이터베이스

  * 본인이 경험한 DBMS에 대해 설명하세요.

* ### 기타

  * ##### 디자인 패턴

    * MVC 패턴
    * MVP 패턴
    * MVVM 패턴
    * 싱글톤 패턴
      * 싱글톤 패턴의 장점과 단점

  * ##### 객체 지향 프로그래밍(Object Oriented Programming)

    * OOP에 대해 찾아보세요.
    * Override와 Overload의 차이

  * ##### 인터프리터와 컴파일러의 차이

    * Swift는 인터프리터 언어인가 컴파일러 언어인가?

  * ##### 다중 Thread 환경에서 Model에 접근시 유의해야할 점

    ##### 


## iOS

* Frame, Bound 차이
* ARC(Automatic Reference Counting)에 대해 설명하세요.
  * ARC란?
  * 동작 원리
  * [구체적인 예시 설명](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/AutomaticReferenceCounting.html)
* ARC와 GC(Garbage Collection)의 차이점
* Weak와 Strong에 대해 설명하세요. ( + unowned)
* 클로저 블럭내에서 `[weak self] in` 코드를 넣는 방법으로 순환 참조를 해결하는데 이때 `[weak self] in` 코드가 하는 역할과 그 이유는?
* ViewController의 생명 주기
* App의 생명주기 (AppDelegate)
* ViewController의 생명 주기
* 고차함수(Map, Reduce, Filter, Flatmap)에 대해 설명하세요.
* Map과 Flatmap의 차이
* 동기 비동기에 대해 설명하세요.
* GCD에 대해 설명하세요.
* 다중 Thread를 관리하는 방법에 대해 설명하세요.
  * OperationQueue
  * DispatchQueue
  * NSThread
* DispatchQueue와 OperationQueue의 차이
* UITableView가 동작하는 원리에 대해 설명하세요.
  * ReuseableCell 원리
* Notification에 대해 설명하세요.
* Delegation 패턴에 대해 설명하세요.
* Notification과 Delegation 패턴의 차이점에 대해 설명하세요.
* 지정 초기화(Designated Initializers)와 편의 초기화(Convenience Initializers)에 대해 설명하세요.
* 프로토콜 지향 프로그래밍(Protocol Oriented Programming)에 대해 설명하세요.



## 기타

* 자기소개 준비
* 본인이 다른 사람보다 이거 하나만큼은 '자신있다' 라고 생각하는 점
* 왜 개발자가 하고 싶은가?
* 왜 iOS를 선택했는가?
* 회사에 지원한 동기가 무엇인가?
* 앞으로 어떤 개발자가 되고 싶은가?
* 최신 기술 동향에 대해 어떤 경로로 접하는가?
* 최근 접한 최신 기술은?
* 최근 읽은 책에 대해 설명하세요.
* 버전 관리 시스템(GIT) 경험 내용
* 본인의 협업 스타일
* 협업을 하면서 각자 다른 의견을 조율했던 경험
* 손코딩을 대비해 자동완성 없이 코딩해볼것.