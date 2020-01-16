# 연결리스트 (LinkedList)
*written by sohyeon, hyemin 💡*

<br>

## 1. 연결 리스트란?

먼저, `리스트`는 데이터를 순서대로 나열한 자료구조이다. 

<img src="./resources/list.png" style="width: 600px;">  

위의 그림 처럼 순서가 있으며 각각의 데이터가 나열되어 있는 형태이다.

`연결 리스트`는 나열된 불연속적인 데이터를 서로 연결한 형태이다.  

<img src="./resources/linkedlist.PNG" style="width: 600px;">

각 노드가 데이터와 포인터를 가지고 한 줄로 연결되어 있는 방식으로 데이터를 저장하고 있다.  
이때 리스트의 데이터는 노드 또는 요소라고 한다.  
각각의 노드는 데이터와 다음 노드를 가리키는 포인터를 가지고 있다. (위의 그림에서 회색 선)  

하나의 노드를 기준으로 바로 앞에 있는 노드를 `앞쪽 노드(predecessor node)`, 바로 뒤에 있는 노드를 `다음 노드(successor node)`라고 한다.  

    < 배열의 단점 >
        
    - 크기를 변경할 수 없다.
    - 비순차적인 데이터의 추가, 삭제에 시간이 많이 걸린다.  
      (배열 중간 데이터를 추가하려면 빈자리를 만들기 위해 데이터 복사, 이동 과정이 필요하다.)

    -> 연결 리스트는 이러한 배열의 단점을 보완한다.
       배열처럼 데이터를 복사, 이동하는 과정 없이 노드 간의 참조 변경만으로 데이터 추가, 삭제가 가능하다.  

## 2. 연결 리스트 만들기

### 2-1. 노드 만들기



## 3. 이중 연결 리스트

이중 연결 리스트의 구조는 단일 연결 리스트와 비슷하지만, 포인터 공간이 두 개가 있고 각각의 포인터는 앞의 노드와 뒤의 노드를 가리킨다.
