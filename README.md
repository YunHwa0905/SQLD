# SQLD Study

SQLD(SQL 개발자) 자격증 취득을 위해 데이터 모델링과 SQL 핵심 개념을 단계별로 정리한 학습 저장소입니다.

---

## 기술 스택

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=amazondynamodb&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat&logo=markdown&logoColor=white)

---

## 프로젝트 구조

```
SQLD/
├── 01_데이터 모델의 이해.md    # 데이터 모델링 개념, ERD, 엔티티·속성·관계, 식별자
└── 02_데이터 모델과 성능.md    # 정규화·반정규화, 인덱스, 키 종류, 무결성, 슈퍼/서브타입
```

---

## 학습 방법

별도의 실행 환경 없이 Markdown 파일을 순서대로 읽으며 학습합니다.

```
1. 파일명 번호 순서대로 학습 (01 → 02 → ...)
2. 각 섹션의 개념 정리 후 기출문제 풀이로 이해도 확인
3. 오답·약점 개념은 해당 파일에 직접 내용 추가·수정
```

> Markdown 렌더링은 **VS Code** 미리보기, **IntelliJ** 내장 뷰어, 또는 **GitHub 웹**에서 확인할 수 있습니다.

---

## 학습 내용

| 파일 | 주요 학습 내용 |
|------|--------------|
| `01_데이터 모델의 이해` | 데이터 모델링 개념·유의점, ANSI-SPARC 3단계 스키마, ERD 작성법, 엔티티·속성·관계 정의, 식별자 분류(주/보조·내부/외부·단일/복합·본질/인조) |
| `02_데이터 모델과 성능` | 성능 데이터모델링 순서, 정규화(1NF~BCNF·4NF·5NF), 반정규화 기법(중복칼럼·파생칼럼), 인덱스(클러스터드·넌클러스터드), 키 종류(슈퍼키·후보키·PK·FK), 무결성 제약조건, 슈퍼/서브타입 변환 |

---

## 개발 환경

- **Markdown 편집기** — VS Code / IntelliJ IDEA / GitHub 웹 뷰어
- **참고 자료** — SQLD 기출문제집, [데이터전문가 지식포털(DBGuide.net)](http://www.dbguide.net)
