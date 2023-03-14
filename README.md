[강제로 원격 저장소를 현재 로컬로 초기화 한다]
git push --force --set-upstream origin main

[원격저장소 내용을 로컬에 강제로 똑 같이 만들기, 로칼이 덮어쓰여진다]
git fetch --all
git reset --hard origin/main
git pull origin main

#일반명령어 들
- git clone
- git push
- git pull
- git add
- git commit m "처음 커밋"
- git log

## 좀더 공부하자

#### Issue 생성을 통해 버그를 제보하거나, 다른 작업자들과 공유할 내용을 Open 할수 있다.
또한 Issue 별로 tag를 설정할 수 있다.
관리자는 Issue를 확인하고 Issue를 Close 상태로 변경할 수 있다.

[이슈 처리 프로세스]
Issue Open -> 버그수정 (commit) -> Issue Close

## 소프트웨어 버전명을 기록하기 - tag
현재 소스코드 상태에 대한 기록을 남긴
- git tag -a v0.0.1

생성된 tag를 확인
- git tag -l

생성된 tag를 원격 저장소에 반영
- git push origin v0.0.1









