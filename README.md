# Mobile-Programming-Project

## Project Title
Random Routine To-Do App

## Intro
카테고리별 주간 루틴을 등록하면 하루의 할 일을 자동으로 추천해 주는 루틴 실천 보조 앱입니다.

## Details
Random Routine To-Do App은 사용자의 주간 루틴을 효율적으로 관리하고, 하루에 한 가지 할 일을 자동으로 추천해 주는 것을 목표로 제작되었습니다.
일상에서 반복되는 루틴을 꾸준히 유지하는 것은 쉽지 않으며, 무엇을 해야 할지 매일 결정하는 과정도 사용자에게 부담이 될 수 있습니다.

이 앱은 다음과 같은 문제를 해결합니다
- 루틴 선택의 피로 감소
카테고리(지식/건강/일상)별 등록된 주간 루틴 중, 오늘 이미 수행한 항목을 제외한 상태에서 무작위 추천을 제공하여 결정 피로를 줄입니다.
- 간편한 루틴 관리
루틴 등록 및 삭제
추천된 항목을 “오늘의 할 일”로 저장
체크박스로 완료 여부 표시
전체 삭제 기능
사용자는 직관적 UI로 하루·주간 루틴을 손쉽게 관리할 수 있습니다.
- 시각적 통계 제공
주간 루틴 개수, 오늘의 할 일 현황(완료/미완료)을 통계 화면에서 확인해 사용자의 루틴 실천 정도를 한눈에 파악할 수 있도록 설계되었습니다.
- 상태 저장
SharedPreferences를 활용해 앱을 종료해도 데이터가 유지되어, 매일 안정적인 사용 경험을 제공합니다.

## Features
### Main Features
- 주간 루틴 등록 (지식/건강/일상)
- 랜덤 오늘의 할 일 추천 (중복 추천 방지)
- 오늘의 할 일 목록 관리 (체크박스 완료 상태 저장)
- 항목 개별 삭제 / 전체 삭제
- 주간·일간 통계 제공
### Additional Features
- SharedPreferences 기반 데이터 저장
- 카테고리 필터링
- UI 일관성 유지(Blue 기반 디자인 시스템)

## Technologies used
  Java – 앱 기능 구현 
  XML – UI 레이아웃 구성 
  Android Studio – 개발 환경
  SharedPreferences – 로컬 데이터 저장
  Android UI Components – Spinner, ListView, Button, CheckBox, Dialog 등
