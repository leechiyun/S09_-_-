# 스터디 규칙

## 스터디 일정
- 매주 화요일 오후 7시에 대면 스터디를 진행합니다.

## 문제 풀이 규칙
- 매주 3개의 문제를 풀이합니다.
- 본인이 작성한 코드는 README.md에 템플릿을 참고하여 기록합니다.
- 다른 사람의 코드를 보고 코드 리뷰할 경우, PR에 코멘트를 남깁니다.

## 백준 문제 만들기
([이치윤](https://www.acmicpc.net/workbook/view/18136))

## 문제집
- 1주차 ~ 10주차의 문제 목록이 있습니다.

| 날짜         | 알고리즘       | 출처 | 문제1                  | 문제2                             | 문제3                   |
|--------------|----------------|------|-----------------------|-----------------------------------|------------------------|
| 1주차 (03.01. ~ 03.07.) | 분할 정복 | 백준 | [종이의 개수](URL) | [쿼드트리](URL)                   |                        |
| 2주차 (03.08. ~ 03.14.) | DP           | 백준 | [쉬운 계단 수](URL) | [가장 긴 증가하는 부분 수열](URL) | [오르막 수](URL)        |
| ...          | ...            | ...  | ...                   | ...                               | ...                    |

## 폴더 구조
- [문제 출처] / [알고리즘명] / [문제 제목] / [이름]

## 깃허브 사용법

### 전체적인 흐름
1. 매주 대면 회의에서 문제 선정 직후, 한 사람이 `main` 브랜치에 새로운 문제 폴더를 생성합니다.
2. `main` 브랜치에서 본인 이름으로 각자 브랜치를 생성합니다.
3. 본인 브랜치에서 첫 commit, push 후 깃허브 페이지에서 PR을 생성합니다. (레포지토리에서 Compare & pull request 버튼 클릭)
4. 한 번 생성한 PR은 일주일간 유효하며, 다음 회의 시작 시 스터디원들과 함께 merge합니다.

### Pull Request
- PR 제목은 [해당 주]-[본인 이름]으로 합니다. (예시: week1-doheez)
- Merge base가 `main`임을 확인합니다.
- Assignees에 본인을 태그하고, Labels에 해당 주에 사용하는 알고리즘을 태깅합니다.
- 덧붙일 코멘트가 있다면 자유롭게 작성합니다.

### Commit Convention
- 새로운 문제 파일 추가 시: `Create [문제 번호] [문제 제목]`
- 기존 코드 수정 시: `Modify [문제 번호] [문제 제목]`

### 코드 설명 방법
- `template.md`를 참고하여 `README.md`를 작성하고 문제 풀이 코드와 동일한 폴더에 올립니다.

## 코드 리뷰
- PR에 직접 코멘트를 남기거나, 코드 일부분에 리뷰를 작성할 수 있습니다.
