# JM 항해 시네마소개

## 프로젝트 소개
- 해당과정은  [단기 스킬업 Redis 교육 과정](https://hh-skillup.oopy.io/) 을 하면서 진행한 프로젝트이다.
- 영화목록을 조회할수 있는 서비스 프로젝트
- 향후 진행하면서 README파일은 계속 업데이트

## API
### Get
|#|API|내용|비고|
|---|------|---|---|
|1|/api/movies|서버가 가지고 있는 영화목록 리턴|   |

### Post
|#|API|내용|비고|
|---|------|---|---|
|1|/api/movies|서버에 영화목록을 입력|   |

## Architecture
 - 해당과제는 Controller, Service, domain으로 나누어져있는 Layered Architecture를 기본으로한다.
 - 구현을 진행하면서, 필요시 Layered Architecture를 기반으로 Module을 분리예정
<img width="375" alt="image" src="https://github.com/user-attachments/assets/98b55ce4-fea4-46ef-9525-fe0485645097" />


## TABLE
- 현재 DB에 저장되는 Data는 아래와 같다.
- 구현 진행하면서, 필요시 변경예정
<img width="148" alt="image" src="https://github.com/user-attachments/assets/fdb9bb75-d6a9-4710-b67a-a278d1079f26" />



## TODO
- docker compose를 사용하여 container화 (현재 미사용)
- 메인페이지 추가 구현



