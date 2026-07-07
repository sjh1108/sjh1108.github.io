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

- [ ] **백준 아이디 확인**: 티어 배지의 `boj=sjh1108` 부분이 실제 백준 아이디와 다르면 수정 (배지가 안 뜨면 아이디가 다른 것)
- [ ] 헤더/타이핑 문구를 원하는 대로 수정
- [ ] 기술 스택 배지 추가/삭제 — [shields.io](https://shields.io) + [simpleicons.org](https://simpleicons.org)에서 로고 검색
- [ ] 통계 카드 테마 변경 — `theme=tokyonight` 을 `radical`, `gruvbox`, `onedark` 등으로 교체 ([테마 목록](https://github.com/anuraghazra/github-readme-stats/blob/master/themes/README.md))
- [ ] private 커밋까지 통계에 포함하려면 github-readme-stats를 [본인 Vercel로 배포](https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own) (선택)

## 통계 카드가 깨질 때

`github-readme-stats.vercel.app` 은 전 세계가 같이 쓰는 **공용 서버**라서, 트래픽이 몰리면
GitHub API 요청 제한에 걸려 카드가 일시적으로 깨지거나 "Something went wrong"이 뜹니다.

- **대부분은 기다리면 복구됩니다.** GitHub가 이미지를 캐시(camo)하므로 새로고침 몇 번 후 정상화되는 경우가 많음
- **확실한 해결책은 내 Vercel로 직접 배포**: [공식 가이드](https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own) 따라 Vercel 무료 배포 후, README의 `github-readme-stats.vercel.app` 부분을 내 배포 주소로 교체 (10분 소요, private 커밋 카운트도 가능해짐)
- 백준 티어 배지가 깨지면: `boj=` 뒤의 아이디가 실제 백준 아이디와 다른 경우이니 수정
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
