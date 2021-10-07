## git 사용법
### git 최초 가이드
```bash
echo "# git" >> README.md
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin http://github.com/rsd2011/git.git
git push -u origin main
```
- 계정정보를 입력할 때 비밀번호에 토큰 정보를 입력해야 한다.
  
### git 사용자 정보 설정
```bash
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```
### git 설정 확인
```bash
git config --list
```
### git 상태확인
```bash
git status
```
### 알아보기
- [ ] ?
```bash
git branch --set-upstream-to=origin/main main
```
- [ ] rebase