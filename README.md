# git_connect

# git 설치 

# 시작버튼에서 git bash 열기

```
git config --global user.name "lshwan"
```
# github 가입시 입력한 이메일과 동일해야한다
```
git config --global user.email "tjdwns8314@naver.com"

```
# 정보확인하기
```
git config --list
```
![image](https://github.com/leesh0787/git_connect/assets/131154479/c4f2a98a-c40e-4c34-9bff-ffae58761c35)

🥖 ⬆️ 의 내용은 컴퓨터에 한번만 설치하면 됨
------------------------------------
------------------------------------

GitHub에 코드 업로드하기  🐬

1. 초기화
  ```
  git init
  ```

# .git이라는 폴더가 생성된다

2. 파일 올리기

  ```
  git add .
  ```

3. 히스토리 만들기
   ```
   git commit -m "내가 적고싶은 메세지"
   ```
# 메세지에는 한글이 가능함
# -m 메세지의 준말

4. GitHub repository랑 내 로컬 프로젝트랑 연결 (깃업에 프로젝트를 올릴 repository를 먼저 만들어야 한다)
# 아래주소는 깃업에서 만든 repository에서 복사해서 가져와야한다(repository를 만들때 readme 선택하지 말기)
```
Initialized empty Git repository in D:/lsHwan/webstandard/.git/
```
5. 잘 연결되었는지 확인 (필수아님)
```
git remote -v
```

6. GitHub에 자료올리기
```
git push origin master
```

# ⬆️ 여기까지 하면 GitHub의 repository에 자료가 올라가 있다.
