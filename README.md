# kaist-ua-e-approval
KAIST 학부 총학생회 전자 결재 시스템


## repo
```
.env
.gitignore

README.md

index.ts
index.js

package.json
package-lock.json

src/
node_modules/
```


## project wiki
### 공문
- 구성
    - __기본 정보__
        - 문서 번호
        - 발신일
        - 매수
    - __수신 정보__
        - 수신
        - 경유
        - 참조
    - __본문__
        - 제목
        - 내용  
    - __서명란__
        - 담당자
        - 국장인란
        - 부총학생회장인란
        - 총학생회장인란
- 참조
    - [공문 양식 링크](https://docs.google.com/document/d/1mu50-_zJOQuvityzhjnJBnK56n2bKtAf/edit?usp=sharing&ouid=110635513564011490994&rtpof=true&sd=true) - 총학 계정 외 접속 제한


## logs
- park/EA-00
    - 생성일 / 관리자
        - 2022.04.26 / 박상우
    - 설명
        - 프로젝트 스펙 설계
    - 세부요소
        - 개발 환경 설정
            - 백엔드
                - ubuntu 18.04 LTS
                - nodejs 16.14.2 LTS
                - typescript 4.5.4
        - 공문 구조 분석