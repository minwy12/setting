- git 사용자, 이메일 등록
```
git config user.name wymin
git config user.email minwy12@github.com
```

- config 조회
```
# global 설정
vi ~/.gitconfig

# local 설정
cd $GIT_REPOSITORY
vi .git/config
```

- git 로그인 정보 저장
```
git config credential.helper store
```
