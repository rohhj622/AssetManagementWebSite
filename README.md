# AssetManagemenetWebSite

> 자산 비율 관리


## 10/04 (일)
- 회원가입 기능 

## 10/10 (토)
- 로그인 기능
- 로그아웃 기능 
- issue
  - session 기능 사용시, db 저장 됨 -> 세션 소멸하고자할 때 db 내용도 지워야 함.

## 11/01 (일)
  - 현재 자산 입력 받는 기능
  - 이상 비율을 맞추기 위한 금액, 지난 자산 현황, 현재 자산 비율 등 데이터 준비.
  - issue
    - 데이터가 html로 넘어가질 않음 너무 화가 남

## 11/03 (화)
  - 저번 11/01 이슈 해결
    - django template 언어 사용 오류
  - 사용자의 자산 비율을 나타낸 원형차트 구현
  - 이상 비율을 맞추기 위한 금액을 표로 나타냄
  - issue
    - line chart의 모든 값은 숫자여야함. 
    - 해결 방안 모색중
    

## 11/14 (토)
  - 11/03 이슈 -> 차트말고 표로
  - 게시판 CRUD 구현
  - 간단하게 구현함
