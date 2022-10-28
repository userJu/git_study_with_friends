# git_study_with_friends

git을 이용해서 협업해보자!

## 🍀 알아두면 좋은 git 명령어들

</br>
</br>

### 커밋 로그

git log
커밋 로그 보기

git log --oneline
커밋 로그 한번에 보기

git log --oneline --all
모든 브렌치의 커밋 로그 한번에 보기

git log --oneline --all --graph
커밋 로그를 그래프처럼 보이게 함
</br>
</br>

### branch

git branch
branch 확인하기

git branch `<branch name>`
branch 만들기

git switch `<branch name>`
만들어진 것에 이동하기

git switch -c `<branch name>`
브랜치 만들고 이동하기
</br>
</br>

### merge

git merge `<branch name>`
</br>
</br>

### 기타

touch signout.txt
새 파일 만들기

</br>
</br>

### 아직 정리하지 않은 내용들

```
<Shared repository model>
git commit --amend

Fast forward
빨리감기처럼 브랜치가 가리키는 커밋을 앞으로 이동시키는 방법

branch와 원격 저장소를 이용히 협업하기

- 원격 저장소 소유권이 있는 경우 : Shared
- 소유권이 없는 경우 : pull request

원격 저장소가 자신의 소유이거나 collaborator로 등록되어 있는 경우
master branch에 직접하지 않고 기능별로 브랜치를 따로 만들어 개발
pull request로 소통
```
