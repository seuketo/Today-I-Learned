# Today-I-Learned

##### Date: 2025-04-07 (Day 1)

## 1️⃣ 오늘 배운 것
오늘은 백준을 통해 알고리즘 문제를 해결하였다.

## 2️⃣ 참고 문제, 혹은 자료
  1. 백준_1010번: 다리 놓기
  2.

## 3️⃣ 개념 정리
  ### 1. 백준_1010번: 다리 놓기
    #### 🖥 사용 개념
      - 수학의 개념 중 조합을 사용.
      - 수학의 개념 중 팩토리얼을 사용.
    
    #### 📃 문제 정리
      - 서쪽에 N개의 사이트, 동쪽에 M개의 사이트가 존재하며, 겹치지 않게 최대한 많은 다리를 지을 수 있을 경우를 출력하는 문제.
      - 순서가 따로 문제에 기재되어있지 않음.
      - 팩토리얼이 사용되었기 때문에 과정에 int, long이 감당할 수 없는 범위의 수를 다룸.
      
    #### 🔍 해결 방법
      - 순서가 없는 M개의 사이트를 N개의 사이트와 연결할 수 있는 경우의 수를 구하기 위해 조합을 사용.
      #####  C(M, N) = M! / (N! * (M - N)!) ▶ C(M, N) = M * ... * (M - N + 1) / N!
