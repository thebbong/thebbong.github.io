---
id: 0
title: "코딩테스트 관련 팁 with JAVA"
subtitle: "좌표 및 등등"
date: "2023.08.13"
---

> 코딩테스트 관련하여 알아두면 좋을만한 것들.

## 좌표관련 문제는 좌표배열을 사용.

```java
static final int[] directX = {0, 0, -1, 1}; //상 하 좌 우
static final int[] directY = {-1, 1, 0, 0}; //상 하 좌 우
```

위와 같이 선언하고 이동 할 때마다 X,Y좌표값을 변경해주면 직관적으로 알 수 있고, 디버깅도 쉽다.

## stream

stream을 사용하면 유용한 경우가 많다.

### stream이 만능은 아니다.

```java
filter사용시 2중루프 되버림
```

### list to array, array to list.
