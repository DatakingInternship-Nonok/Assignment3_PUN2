# ASSIGNMENT3_PUN2

시작: 2023-10-12 </br>
보류: 2023-10-25 ~ </br>
완료: </br>

<details>
<summary>과제 요구사항 접기/ 펼치기</summary>

============ Assignment3_PUN 과제 내용 ============

플랫폼: PC</br>

PUN을 통한 네트워킹(멀티플레이) 구현

- 방목록 확인기능
- 방목록 갱신기능
- 게임시작/종료 (게임내용 없이 시작, 종료만 => 모든플레이어 게임시작 및 종료 동기화)
- 룸프로퍼티 ( 룸이름, 인원표시, 난이도, 플레이중 => [Hard] 방제목 (2/3) 진행중 )
- 플레이어프로퍼티 (준비완료 => 모든플레이어가 준비완료여야 방장이 시작가능)
- 플레이어별로 캐릭터생성, 플레이어 이름표시, Transform 동기화
- 스킬사용(이펙트, 1회성)

=================================================
</details>

## 이슈 메모

## 진행중

> 메타버스 추모관 프로토타입 제작 프로젝트로 인해 보류됨.

onPunRoomCreated 이벤트 처리

## 작업 계획

- [ ]  UI 제작
    - [x]  로비
        - [x]  내 정보
        - [x]  방 목록 및 방 정보
        - [x]  새로고침
        - [x]  새 방 만들기(버튼)
            - [x]  새 방 UI (방 이름, 난이도, 최대인원, 생성버튼)
    - [ ]  방
        - [ ]  참가자 목록 및 정보, 버튼
        - [ ]  채팅창
- [ ]  시스템 구현
    - [ ]  로비
        - [ ]  내 정보: 닉네임을 필드를 통해 수정
        - [ ]  방 생성
        - [ ]  방 정보 받아오기(새로고침)
    - [ ]  방
        - [ ]  플레이어 프로퍼티별 UI 표시
        - [ ]  플레이어 시스템
        - [ ]  방장 시스템
        - [ ]  채팅
    - [ ]  인게임
        - [ ]  로컬 조작 (이동, 스킬)
        - [ ]  멀티 플레이어
        - [ ]  방장 전용: 게임 시작, 종료

## 보류

