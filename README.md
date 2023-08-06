# 당신의 첫 번째 커밋 - TheFirstCommit

```bash
git commit # 해당 파일을 스테이지에 올린다.
git status # 스테이지에 올라가 있는 파일을 살펴본다.
git push   # 원격 저장소에 commit을 푸쉬한다.
git pull   # 원격 저장소에 있는 변경 내용을 가져온다.
git brnach # 브렌치를 만든다.
git branch -d 브렌치 이름 # 브렌치를 지운다.
git merge 브렌치 # 현재 브렌치와 병합한다.
git stash # 임시 저장
git stash pop # 임시 저장된 내용 pop 해오기
git cherrypick # 다른 브렌치의 특정 커밋만 가져오기
git rebase # rebase를 이용하면 커밋 그래프를 깔끔하게 가져갈 수 있음 하나의 브렌치를 이어 가는 개념
```

# 브렌치 전략

- git-flow
  - main: 최종본
  - develop: 개발을 하는 브렌치, 개발을 할 때 pull 받아야 하는 브렌치, 개발을 진행하기 때문에 여러 버그가 존재, 피처 브랜치를 따는 곳
  - release: 배포 브랜치, 버그만 수정하는 곳 / dev /main 머지
  - feature: 개발용 브랜치
  - hotfix: 급하게 수정되어야 하는 이슈 / dev / main에 머지 되어야 함

