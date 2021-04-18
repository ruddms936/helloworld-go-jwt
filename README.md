# helloworld-go-jwt

golang의 gin 프레임 워크를 이용하여 제작한 인증서버입니다.

> 실제 DB와 연동하여 User 정보를 검증하는 로직은 구현되어 있지 않습니다.

# Spec

| 카테고리  | 내용   | 비고                                |
| --------- | ------ | ----------------------------------- |
| Editor    | vscode |                                     |
| Language  | go     | v1.15                               |
| Framework | gin    | v1.6.3                              |
| DB        | redis  | token을 관리하기 위해서 사용됩니다. |
| Protocal  | OAuth  | jwt 이용하여 구현되었습니다.        |

# 필수

1. go가 설치되어 있어야 합니다.
1. redis server가 활성화 되어있어야 합니다.
   > 현재 기본값인 `localhost:6379`을 가르키고 있습니다.

# 빠른 시작

1. `go mod download` 으로 의존된 package를 설치합니다.
1. vscode에서 `F5` 으로 디버깅 모드를 활성화합니다.
1. `api-sample.http`를 참고하여 API Spec에 맞게 요청을 보내봅니다.
