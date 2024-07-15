이 프로그램은 C 언어로 작성된 간단한 학생 정보 관리 프로그램입니다. 학생의 나이, 이름, 주소(도시와 국가)를 저장하고 출력합니다.

중첩 구조체를 사용하는 이유는 조직적 데이터 관리, 재사용성, 가독성 향상, 유지보수 용이성 때문입니다.

## 프로젝트 설명

이 코드는 C 언어로 작성된 간단한 학생 정보 관리 프로그램입니다. 학생의 나이, 이름, 주소(도시와 국가)를 저장하고 출력합니다.

## 기능

- 학생의 나이, 이름 및 주소 정보를 저장
- 학생 정보를 출력

## 구조체 설명

### City 구조체

- `city`: 도시 이름을 저장하는 문자열
- `country`: 국가 이름을 저장하는 문자열

### Student 구조체

- `age`: 학생의 나이를 저장하는 정수
- `n`: 학생의 이름을 저장하는 문자열
- `city`: `City` 구조체를 사용하여 학생의 주소 정보를 저장
