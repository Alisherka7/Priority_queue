# 우선순위 큐
# Priority Queue

- 우선순위를 가진 항목들을 저장하는 큐
- 우선순위가 높은 데이터가 먼저 나가게 됨
- 가장 일반적인 큐로 상각할 수 있음

## 데이터
 - 우선순위를 가진 요소들의 모음

## 연산
  - init(): 우선순위 큐를 초기화한다.
  - insert(item): 우선순위 큐에 항목 item을 추가한다.
  - delete(): 가장 우선순위가 높은 요소를 삭제하고 반환한다.
  - find(): 가장 우선순위가 높은 요소를 삭제하지 않고 반환한다.
  - is_empty(): 우선순위 큐가 공백상태인지를 검사한다.
  - is_full(): 우선순위 큐가 포화상태인지를 검사한다.

## 우선순위 큐 구현방법

  - 배열을 이용한 구현
   <img width="370" alt="Screen Shot 2021-05-22 at 10 11 22 PM" src="https://user-images.githubusercontent.com/38793933/119249067-aaa75880-bb4a-11eb-82d0-33aed2026839.png">
  - 연결리스트를 이용한 구현
  <img width="549" alt="Screen Shot 2021-05-22 at 10 12 22 PM" src="https://user-images.githubusercontent.com/38793933/119249079-d0ccf880-bb4a-11eb-866f-9b4f8e64c825.png">
  
힙(heap)을 아용한 구현

 - 최댓값, 최솟값 계산
 - 완전이진트리
 - 우선숱위 큐를 위해 만들어진 자료구조
 - 일종의 반 정렬 상태를 유지
