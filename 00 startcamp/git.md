# Git 필기

## 처음 Git을 시작할 때 1번만 하면 되는 작업

### `git init` 

### `git remote`
    * `git remote add origin [My GitHub Remote Repository Address]`
        - `origin`은 별명이지만 일반적으로 origin을 사용하기 때문에 협업할 때에 중요!
    * `git remote -v`
        - 내가 등록한 원격저장소 레포 주소 확인
    * `git remote remove origin`
        - 원격저장소 삭제

## working directory에 변동이 있을 때마다 하는 작업
    * `.git`이 있는 폴더 경로에서만 가능
### `git add`
    * add할 파일 명도 적어줘야함
        - e.g. `git add .`

### `git commit`

### `git push`