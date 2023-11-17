# Problem Solving

## 설명

- 백준, 프로그래머스 등의 코딩 테스트 정답 코드입니다.
- Algorithm의 예제 코드 및 설명은 GPT4 및 웹 서핑을 통해 작성했습니다.

## 목차

- Backtracking
- BFS / DFS
- Binary Search
-
-
-

## BFS / DFS

### BFS (너비 우선 탐색)가 적합한 경우

- 최단 경로 문제: 특히 가중치가 없는 그래프에서 각 노드까지의 최단 거리를 찾을 때.
  > - 예시: 미로 찾기 문제, 소셜 네트워크에서 두 사람 사이의 최소 친구 연결 수 찾기.
- 레벨 별 탐색: 그래프의 각 레벨 또는 깊이를 차례대로 탐색할 때.
  > - 예시: 트리의 레벨 순서대로 노드를 출력하는 문제.
- 컴포넌트 연결성: 그래프에서 연결된 모든 노드 또는 컴포넌트를 찾을 때.
  > - 예시: 섬의 개수를 세는 문제, 바이러스 감염 영역의 크기 계산.

### DFS (깊이 우선 탐색)가 적합한 경우

- 경로 탐색: 모든 가능한 경로를 탐색하거나 특정 조건을 만족하는 경로를 찾을 때.
  > - 예시: 미로의 모든 가능한 경로 찾기, 경로에 특정 조건이 있는 여행 경로 계획.
- 사이클 감지: 그래프에서 사이클이 존재하는지 확인할 때.
  > - 예시: 방향성이 있는 그래프에서 사이클 찾기.
- 백트래킹: 모든 가능한 해를 찾거나 최적의 해를 찾기 위해 가능성 있는 경로를 따라 탐색하고, 조건에 맞지 않으면 이전 단계로 되돌아가는 경우.
  > - 예시: 스도쿠, N-Queens 문제.
- 트리의 깊이 또는 특성 계산: 트리의 최대 깊이나 특정 특성을 계산할 때.
  > - 예시: 이진 트리의 최대 깊이 계산, 이진 탐색 트리의 유효성 검사.
