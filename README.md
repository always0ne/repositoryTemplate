# 레포지터리 초기 세팅 템플릿

## How To Contribute
### commit
- commit Template 엄수   
(로컬 환경에서 `git config --local commit.template .github/.gitmessage.txt` 세팅 필요)
- resolves, see also에 ISSUE 링크시킬것
- 1 commit 1 작업(히스토리 관리를 위함)

### issue
- Issues 트래킹을 위해 작업단위로 issue를 생성(ex. ~버그 수정, ~기능 추가)
- project에 링크 걸것

### branch
- gitflow 모델을 사용
- `feature/(이슈번호)-(작업명)`의 네이밍 으로 브렌치 생성

### pull request
- 작업 완료 후 develop로 pull request 작성할 것
- team 멤버들이 pull request의 리뷰를 끝내야 머지가능
- project에 링크 걸것
