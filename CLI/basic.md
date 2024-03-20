# CLI basic(Unix commands)


## 기본 조작
- $프로포토 : 현재 명령어를 받을 준비가 되었다/터미널 명령어다.
- ctl + c : 취소
- ctl + l : 클리어
- 화살표 위아래:기존 명령어 불러오기
- tab : 자동 완성

## 명령어들
- touch : 파일 생성
- 파일 생성 ls : 현재 폴더의 내용물을 보여줌(list)
- ls -a : 현재 폴더의 내용물을 모두 보여줌(-a all)
- rm : 파일 삭제(removea)
- rm -r : 파일/폴더모두 삭제(-r recursively)
- rm -rf : 파일/폴더 모두 강제 삭제
- pwd : 현재 작업 폴더
- mkdir : 폴더 생성
- rmdir : 빈폴더 삭제
- cd : 폴더 이동
- cp : 폴더 복사
- cp -r : 파일/퐁도 복사
- mv : 파일 / 폴더 이동 + 이름 바꾸기

## 경로 관련
- . : 현재폴더
- .. : 상위 폴더
- ~ : home dir
- / : root dir
- .xxx : .으로 시작 => 숨김 파일/폴더


# git를 학습합니다.
git를 학습합니다.

## `init`
```
%git init
```

## `commit`
```
%git add .
%git commit -m 'MASSAGE'
```

## `remote add `
```
#github에 원격 저장소 생성 후 URL 획득
%git remote add origin 'URL'
```

## `push`
```
%git push origin master
```

## `clone`
```
#현재 터미널의 위치에 다운로드함.
%git clone 'remote repo URL'
``` 

git branch <branch-name>
git switch <branch-name>
git branch -d <branch-name>
git merge <target-branch>
git switch -c <new-branch>