# 당신의 첫 번째 커밋 - TheFirstCommit

```bash
git commit # 해당 파일을 스테이지에 올린다.
git status # 스테이지에 올라가 있는 파일을 살펴본다.
git push   # 원격 저장소에 commit을 푸쉬한다.
git pull   # 원격 저장소에 있는 변경 내용을 가져온다.
git brnach # 브렌치를 만든다.
git merge 브렌치 # 현재 브렌치와 병합한다.
```

# 브렌치 전략

- git-flow
  - main: 최종본
  - develop: 개발을 하는 브렌치, 개발을 할 때 pull 받아야 하는 브렌치, 개발을 진행하기 때문에 여러 버그가 존재, 피처 브랜치를 따는 곳
  - release: 배포 브랜치, 버그만 수정하는 곳
  - feature
  - hotfix
- github-flow