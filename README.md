# 일정 관리 프로젝트

## 프로젝트 개요
Spring MVC를 활용하여 CRUD를 연습하기 위한 일정 관리 프로젝트

## 기능 정의

- 전체 할 일을 조회할 수 있다.
- 특정 한 일을 조회할 수 있다.
- 할 일을 작성할 수 있다.
  - 필수 항목은 `null`이 될 수 없으며, 만약 `null` 값이 들어오면 `CustomException` 예외를 발생시킨다.
- 할 일을 수정할 수 있다.
  - 수정하기 전에 비밀번호를 검사한다.
    - 만약, 비밀번호가 틀리다면 `CustomException` 예외를 발생시킨다.
- 할 일을 삭제할 수 있다.
  - 수정하기 전에 비밀번호를 검사한다.
    - 만약, 비밀번호가 틀리다면 `CustomException` 예외를 발생시킨다.

## 기술 스택

- JDK 17
- SpringBoot 3.2.1
- Spring MVC
- Lombok
- Jpa
- MySQL

## ERD

![Screenshot 2024-01-22 at 8 36 43 PM](https://github.com/Modafi/diary/assets/155048724/d6185908-7e1a-47c2-8fd4-b78098065028)

## Usecase Diagram

![Screenshot 2024-01-22 at 8 36 51 PM](https://github.com/Modafi/diary/assets/155048724/7096db88-f7c7-499a-a438-b5c0607b2dfe)



## [API 명세서](/document/api.pdf)
