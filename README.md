## `git init`
- 프로젝트를 git repository를 만들기 위해 사용하는 명령어. 최초의 프로젝트를 생성한다고 생각하면 좋다. 여기서 프로젝트라 함은 개발하고자 하는 소스코드들이 있는 디렉토리를 말한다. `git init` 을 해서 git repo로 만들어야 git으로 버전 관리가 시작된다.

## `git add`
- modified, 즉 수정된 파일을 staged된 상태로 옮기고자 할 때 사용하는 명령어이다. 무언가 수정하게 되면 그것에 대해서 중간저장을 하기 위해서 `commit`을 하기 전에 `git add`을 해야한다. 또한, git repo에 새로 추가된 파일들은 staged 상태로 옮길때도 사용된다. 새로 추가된 파일들을 'untracked' 파일이라고 하는데, git 에서는 이들도 수정사항으로 본다.

## `git commit`
- add된 파일들은 하나의 commit으로 만들어서 commit 메세지를 부여하고, commit 하는 작업을 말한다.

## `git diff`
- modified 상태에서만 결과물이 나오는데, 말그대로 수정사항들을 보여준다.
