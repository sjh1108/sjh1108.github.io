# 프로필 README 적용 방법

`profile/README.md`를 GitHub 프로필(github.com/sjh1108)에 띄우는 3단계:

## 1. 특수 레포 만들기

GitHub에서 **유저명과 똑같은 이름**의 새 레포를 만듭니다.

- 레포 이름: `sjh1108` (→ `sjh1108/sjh1108`)
- **Public** 이어야 함
- "Add a README file" 체크

이름이 유저명과 일치하면 GitHub가 "✨ special repository" 라고 알려줍니다.

## 2. README 붙여넣기

`profile/README.md`의 내용 전체를 새 레포의 `README.md`에 복사해서 커밋합니다.

## 3. 커스터마이징 체크리스트

- [x] **백준 아이디**: 티어 배지에 `boj=thdwngjs1108` 적용 완료
- [ ] 헤더/타이핑 문구를 원하는 대로 수정
- [ ] 기술 스택 배지 추가/삭제 — [shields.io](https://shields.io) + [simpleicons.org](https://simpleicons.org)에서 로고 검색
- [ ] 통계 카드 테마 변경 — `theme=tokyonight` 을 `radical`, `gruvbox`, `onedark` 등으로 교체 ([테마 목록](https://github.com/anuraghazra/github-readme-stats/blob/master/themes/README.md))
- [ ] private 커밋까지 통계에 포함하려면 github-readme-stats를 [본인 Vercel로 배포](https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own) (선택)

## 통계 카드가 깨질 때

통계 카드는 공용 서버 대신 **개인 Vercel 배포**(`sjh1108-readme-stats.vercel.app`)를 사용 중이라
공용 서버의 요청 제한/서비스 정지 영향을 받지 않습니다. 그래도 깨진다면:

- Vercel 대시보드에서 `github-readme-stats` 프로젝트가 Paused 상태가 아닌지 확인 (Paused면 Resume)
- GitHub PAT 만료 시 카드에 에러가 뜸 → 새 토큰 발급 후 Vercel 환경변수 `PAT_1` 교체하고 Redeploy
- 백준 티어 배지가 깨지면: `boj=` 뒤의 아이디(`thdwngjs1108`)가 실제 백준 아이디와 다른 경우이니 수정
- 방문자 카운터는 서비스가 종료된 hits.seeyoufarm 대신 [komarev](https://github.com/antonkomarev/github-profile-views-counter)를 사용 중

## 사용된 도구

| 요소 | 도구 |
|---|---|
| 헤더/푸터 배너 | [capsule-render](https://github.com/kyechan99/capsule-render) |
| 타이핑 애니메이션 | [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg) |
| 기술 스택 배지 | [shields.io](https://shields.io) |
| GitHub 통계/언어 카드 | [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) |
| 커밋 스트릭 | [streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) |
| 백준 티어 배지 | [mazassumnida](https://github.com/mazassumnida/mazassumnida) |
| 트로피 | [github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) |
| 방문자 카운터 | [komarev](https://github.com/antonkomarev/github-profile-views-counter) |
