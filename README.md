# best-repo-ever


### 폴더 생성하고자 하는 위치에서 git bash 실행
```
git clone <repositirt address>
```

### 브랜치 생성
```
git branch <myfeaturebranch>
```

### 브랜치로 체크아웃
```
git checkout <myfeaturebranch>
```

### 브랜치 생성 후 체크아웃
```
git checkout -b <new-branch-1>
```

### 작업 후 상태 확인
```
git status
```

### 작업트리에서 스테이징 영억으로 파일 이동
```
git add README.md
```

### 커밋 
```
git commit -m "<My first commit>"
```

### 푸시 - branch 이름으로
```
git push -u origin <myfeaturebranch>
```

### 풀 
- 모든 변경사항을 검색 한 다음 현재 사용중인 브랜치를 업데이트하여 원격의 변경 사항을 포함하는 조합 명령
```
git pull 
```

### ↓ 따로 하려면 
```
git fetch
git merge
```

### 브랜치 삭제
```
git branch -d <new-branch-1>
```

### 작업중인 파일있어서 안될때
```
git branch -D <new-branch-1>
```
### 하고 remote branch도 삭제
```
git push :<new-branch-1>
```