# 숫자야구 프로젝트
> 프로젝트 기간 2022/04/12 ~ 2022/04/15
> 팀원: Kiwi, bonf 

## 목차
- [프로젝트 소개](#프로젝트-소개)
- [순서도](#순서도)
- [STEP 1](#STEP-1)
- [STEP 2](#STEP-2)

## 프로젝트 소개
사용자의 입력값을 받는 숫자야구 게임

### 개발환경 및 라이브러리
[![swift](https://img.shields.io/badge/swift-5.6-orange)]()
[![xcode](https://img.shields.io/badge/Xcode-13.3-blue)]()


### 프로젝트 수행 중 핵심 경험
- [x]  순서도 익히기
- [x]  함수 단위 고민하기
- [x]  Git의 기본 사용(add, commit, push, pull)
- [x]  GitHub의 원격 공동 저장소 활용
- [x]  Git 저장소의 충돌 해결
- [x]  Git Branch의 이해
- [x]  GitHub에서 Pull Request 전송
- [x]  Swift API Design Guidelines 읽어보기
- [x]  Swift Set의 이해와 활용
- [x]  Swift의 Optional 안전하게 처리하기
- [x]  Git의 커밋단위 고민하기
- [x]  Git 커밋 로그 형식 고민하기
- [x]  스위프트 코딩 컨벤션 고민하기
- [x]  동료와 협업자세 고민하기

## 순서도
#### STEP1 순서도

![](https://i.imgur.com/BYbGlyR.png)

#### STEP2 순서도

![](https://i.imgur.com/Fd4pPRJ.png)

## STEP 1

### 고민한점 🤔
1. 들여쓰기 2회 초과 금지 제한을 제대로 이해하지 못하여 뒤늦게 고민하게 되었습니다. 그러나 들여쓰기를 없애려 노력하다 보니 함수의 기능 분화가 자연스럽게 이루어 지게 되었습니다

2. Array 중복 제거 코딩을 하는 중 들여쓰기 2회 초과 금지 조건을 충족시키기 위해 오래 고민하였습니다. For if 문의 굴레에서 벗어나지 못하던 중 Set의 존재를 인식하여 Set을 이용하여 해결하게 되었습니다.

3. Set 인덱스 여부 오인
Set은 인덱스 순서가 없어서 자리를 비교할 수 없었습니다. 그래서 Array를 Set으로 변경하려고 보니 변경 시에 정렬이 되는 문제가 생겨서, 결국 Set을 Array로 먼저 변환하고 숫자의 자리를 비교하는 방법을 사용하여 해결하게 되었습니다.

4. git을 통한 협업 과정에서 pull을 하지 않은 상태에서 코드의 변경을 진행하여 충돌이 발생 하였습니다.
그래서 충돌 부분을 수동으로 삭제를 하였고 push에 성공하게 되었습니다.

5. 코드 네이밍을 진행할 때에 축약어들을 사용하거나, 타입명을 사용을 하는 경우가 있었습니다. 그래서 리뷰어분의 조언을 받아 축약어를 완전한 단어로 변경하였으나, 타입명의 경우 타입명을 제외시키고 네이밍을 다시하는 것에 어려움이 있었습니다.

### 배운개념 ✏️

- 함수 네이밍
- 함수 기능별 분화
- Set
- git의 활용


## STEP 2

### 고민한점 🤔

1. components와 split의 차이점
split의 경우 타입이 'subString’타입의 배열이 생성되고, foundation을 import해주지 않아도 사용 가능하다. 반면 components의 경우 'String’타입으로 배열이 생성되고, import foundation을 해주어야만 이용 가능하다.

### 배운개념 ✏️

- 고차 함수
- import Foundation을 통해 componets 사용할 수 있음
