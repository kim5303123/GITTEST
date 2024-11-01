# GIT과 GITHUB
## GIT

- GIT : **분산** 버전 관리 시스템
- GITHUB : **원격 GIT 저장소**

### Local Git

- 저장소 생성
```bash 
git init 
```

- git 설정
```bash
- git 설정
git config user.name "KSR"
git config user.email kim5303123@gmail.com
# 공용 git 설정을 하려면 -g를 사용
# 예) git config -g user.name 이름
```

- git 상태 확인
```bash
git status
```

- staging
```bash
# 모든 Untracked files(추적안되는파일들)이 add가 되며 staging에 올라감
git add . 
```

- 저장소에 반영 (commit)
```bash
# git commit -m "코멘트"
git commit -m "First Commit" 
```

- 상태 확인과 로그 확인
```bash
# 상태 확인
git status  
# 로그 확인
git log     
```