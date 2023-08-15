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

## 괄호의 Input이 있다면 Stack문제일 확률이 높다.

대표적인 괄호가 올바른가의 문제를 비롯하여 대부분이 스택자료구조에 쓰이기가 좋기 때문에

## stream

stream을 사용하면 유용한 경우가 많다.

### stream이 만능은 아니다.

```java
filter사용시 2중루프 되버림
```

### list to array, array to list.
