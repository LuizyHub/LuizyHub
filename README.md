## Skills
- Programming Language: Java (Java 8+), TypeScript, JavaScript (ES6+)
- Framework: Spring, NestJS, Express.js
- Tool: Git, Docker

## Projects
### Git Challenge
[레포지토리](https://github.com/boostcampwm2023/web01-GitChallenge), [배포 링크 : git-challenge.com](https://git-challenge.com)

- **역할:** Backend
- **기간:** 2023.11 ~
- **기술 스택:** NestJS, Express, MongoDB, SQLite, Docker
- **핵심 기능 및 기여:**
  - **도커 컨테이너를 이용한 환경 구축:** 사용자별로 격리된 Git 문제 풀이 환경을 제공하기 위해 도커 컨테이너를 활용했습니다. 이를 통해 안정적이고 일관된 테스트 환경을 보장하며, 서버 자원의 효율적인 사용을 도모했습니다.
  - **HTTP로 원격 터미널 조작:** 전통적인 SSH 대신 HTTP/1.1 프로토콜을 활용하여 사용자의 명령어를 컨테이너로 전송하고 결과를 받아오는 시스템을 개발했습니다. 이로 인해 통신 속도와 효율성이 개선되었습니다.
  - **Git editor 커스터마이징:** 기존의 vi Editor 등의 편집기와의 호환성 문제를 해결하기 위해, Git core.editor로 사용할 수 있는 편집기 프로그램을 직접 개발하여, 사용자의 Git 커밋 메시지 작성 경험을 개선했습니다.
  - **AI 시스템 프롬프트 설정:** 사용자가 Git 관련 질문을 했을 때, 정확하고 유용한 답변을 제공할 수 있도록 AI 시스템의 프롬프트를 설정했습니다. 이를 통해 사용자의 학습 경험이 향상되었습니다.
    - [naver cloud forum 소개](https://www.ncloud-forums.com/topic/213/)
    - [클로바 스튜디오 사용기](https://code-l.tistory.com/34)

### 프로젝트 성과:
- **효율적인 문제 해결 환경 제공:** 도커 컨테이너와 HTTP 기반 터미널 조작을 통해 사용자는 빠르고 안정적인 환경에서 Git 문제를 해결할 수 있었습니다.
- **사용자 경험 개선:** 커스텀 Git editor 개발을 통해, 사용자들이 Git 커밋 메시지를 보다 쉽게 작성할 수 있게 되어 사용자 경험이 개선되었습니다.
- **AI 기반 학습 지원:** AI 시스템을 통해 사용자들이 Git에 대해 보다 정확하고 실질적인 학습을 할 수 있게 되었습니다.

## Open Source Contribution
### start.spring.io 수정
https://start.spring.io/
- **기여 내용:** `Spring REST Docs` 링크 오류 수정
- **문제:** 생성된 `help.md`에 잘못된 링크 포함 ([Issue : # Fix broken link to Spring REST Docs reference documentation in help.md](https://github.com/spring-io/start.spring.io/issues/1407))
- **해결:** `application.yml` 내 링크 접미사 `html5`를 `htmlsingle`로 변경 ([PR : Fix documentation link for Spring REST docs #1409](https://github.com/spring-io/start.spring.io/pull/1409))
- **결과:** `Spring REST Docs` 접근성 개선, 사용자 경험 향상 
- **기여 링크:**  ([Commit : Fix documentation link for Spring REST docs](https://github.com/spring-io/start.spring.io/commit/62d0497016e4e626252829318da42922d31238bc))

### Solved.ac
[![Solved.ac프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=luizy991212)](https://solved.ac/luizy991212)

<!--
**LuizyHub/LuizyHub** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
