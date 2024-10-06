# 접근 방식
> 반복문에서 배열이 왜 필요할까?
- _일상_
  - 시간이 지날수록 살림이 늘어남 -> 늘어날수록 힘듬 -> 정리와 공간 확보 위해 수납공간 마련
- _프로그래밍_
  - 방대한 데이터를 다루게 된다 -> 데이터들은 제각각 성질이 다르고, 데이터 양이 많으니 관리 힘듬 -> 정리와 공간 확보 위해 수납공간 마련

<br>

# Array(배열) 이란?
> '서로 연관된 데이터를 정리정돈해서 담아두는 수납상자'

<br>

"'''"html
  <body>
    <h1>Array</h1>

    <h2>Syntax</h2>
    <!-- 수납 공간 생성 !! -->
    <script>
      var coworkers = ["egoing", "leezche"];
    </script>

    <h2>get</h2>
    <!-- 수납 공간에서 가져오는 방법 !! -->
    <script>
      document.write(coworkers[0]);
      document.write(coworkers[1]);
    </script>

    <h2>add</h2>
    <!-- 데이터 추가하는 방법 !! -->
    <script>
      coworkers.push("duru");
      coworkers.push("kiyun");
    </script>

    <h2>count</h2>
    <!-- 개수 세는 방법 !! -->
    <script>
      document.write(coworkers.length);
    </script>
  </body>
  "'''"
