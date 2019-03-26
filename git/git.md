
### 0. Git에 대해
Git은 리눅스(Linux) 커널 프로젝트를 위한 버전 관리 시스템(VCS, Version Control System)으로 리눅스를 개발한 리누스 토발즈에 의해 2005년도에 개발되었다. 프로젝트를 진행하면서 생성하는 코드를 분산 관리 하기 위해 사용되는 도구이다.


#### Git 이유
1. 속도 (네트워크 및 파일 처리)
2. 동시 다발적인 개발 (협업 관리)
3. 책임성 (코드 오류 발생 근원지 파악/처리)
4. 대형 프로젝트를 효율적으로 지원


### 1.1. Git 설치
[Git Download](http://git-scm.com/download) 클릭 후, 사용 중인 운영체제 버전에 맞게 설치
※ Windows 사용자의 경우, 설치 과정에서 __Use Git from the Windows Command Prompt__ 체크 권장.

### 1.2. Git 설정 정보
계정 이름. 이메일

#### 사용자 정보 설정

```sh
$ git config --global user.name <사용자 이름>
$ git config --golbal user.email <사용자 이메일>

# 예시 -----------------------------------------------------------
# [user]
#   name = sherazzang
#   email = shera9961@gmail.com
# ------------------------------
# 글로벌 Git 설정 파일 편집(수정)
# ------------------------------
$ git config --global --edit
```

### 2. Git 작업 흐름(Workflow)

명령어 | 설명
--- | ---
`init` | Git 저장소(Repository) 초기화
`status` | Git 저장소 현재 상태 조회
`add` | 파일을 스테이지(변경 관찰)에 추가
`commit` | 스테이지에 있는 파일을 저장소에 추가
`log` | 작성한 커밋 및 작업한 파일 변경 이력 조회
`diff` | 이전/현재 커밋 차이점 비교
`branch` | 브런치(가지치기) 처리
`tag` | 태그 추가
`checkout` | Branch 이동 및 특정 파일 다운로드
`merge` | 병렬적으로 진행된 Brach를 하나의 Brach로 병합  병합 병합 

ddd
ddss