# homecloud

- 사이트 주소 : https://homecloud.lemondouble.com/

- 집에서 RPI같은 싼 온보드 컴퓨터, 구형 데스크톱등을 이용해 Cloud Service를 만들어 보는 가이드 문서입니다.
- [Hugo](https://gohugo.io/) 기반의 스킨인 [Doks](https://getdoks.org/) 를 이용해 만들었습니다.

---

### Requirements

- pnpm : [Link](https://pnpm.io/installation)
- Hugo : [Link](https://gohugo.io/installation/)
  - Hugo 설치시 APT로 설치하면 구버전 설치되므로, Snap으로 설치하길 권장
  - (2025.04 기준) Hugo 0.146.0 버전부터 Template 깨지는 버그 있으므로, Hugo 0.145.0 버전으로 일단 사용 권장 (관련 Issue [Link](https://github.com/thuliteio/doks/discussions/1348#discussioncomment-12836034))
- Nodejs, Golang

### 프로젝트 셋업

- 막히는 경우 공식 문서 (Doks [Docs](https://getdoks.org/docs/start-here/installation/) 확인)

### 로컬 실행

로컬 dev서버 실행
```
pnpm dev
```

새 글 작성

```
hugo new hello.md
```
