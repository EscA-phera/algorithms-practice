# algorithms-practice
* https://codeup.kr/index.php
* https://programmers.co.kr/

# 알고리즘의 정의와 분석방법
* 알고리즘의 정의
  * 주어진 조건에서 컴퓨터를 사용하여 효율적으로 문제를 해결하는 방법
* 알고리즘의 표기 방법
  * O 표기법 - 알고리즘의 서응 평가 방법 중에서 가장 많이 사용하는 방법, 최악의 성능에 대한 측정 방법
  * O(1) - 처리해야 할 데이터의 양과 상관 없이 항상 일정한 실행 시간을 갖는 알고리즘
  * O(log2N) - 처리해야 할 데이터의 양이 증가할수록 실행 시간도 약간씩 증가함
    * 증가폭 자체가 급격하게 증가하지는 않음, 효율이 좋은 검색 알고리즘이 해당
  * O(N) - 처리해야 할 데이터의 양과 비례하여 실행 시간도 증가하는 경우
  * O(NlogN) - 처리해야 할 데이터의 양에 비해 정비례보다 약간 더 증가하는 실행 시간을 가짐
    * 효율이 좋은 정렬 알고리즘
  * O(N^2) - 반복문 2개가 중첩되어 있는 경우
    * 처리해야 할 데이터의 양이 증가하면 증가할수록 데이터의 제곱만큼의 실행 시간이 소요
    
# 알고리즘에 따른 O 표기법
* 반복문은 최대 반복 횟수로 계산
* 중첩된 반복문은 각각의 중첩문의 최대 반복 횟수를 곱셈하여 계산
* 반복문이 떨어져서 2개 이상 있는 경우는 그 중 가장 큰 값으로 계산
* if-else문은 알고리즘의 성능에 영향을 미치지 않는다
* 재귀 호출은 풀어서 계산한다
