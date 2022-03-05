# 구독봇
유튜브의 채널을 구독하거나 트위치 채널을 팔로우하고  디스코드 채널에 알림을 보낼 수 있는 봇입니다.
### Koreanbots
https://koreanbots.dev/bots/878240313188175922

## 🛠️ 기능

- 유튜브 업로드 감지 기능
- 유튜브 라이브 감지 기능
- 트위치 라이브 감지 기능
- 알림을 보낼 때 특정 역할을 멘션할 수 있는 접두사 기능
- 직접 알림 메시지를 작성하는 커스텀 메시지 기능

## 메시지 설정
구독 / 팔로우한 채널의 알림을 보낼 때 전송되는 메시지를 직접 수정할 수 있습니다.

### ⌨️ 명령어 사용법
- ``/message``로 메시지를 변경할 수 있습니다.
- 자세한 도움말은 [여기](https://github.com/skinmaker1345/subscriber-bot/blob/main/edit_messages.md)에서 확인할 수 있습니다.

## 설정
구독한 내용에 대해 설정을 변경할 수 있습니다.

### ⌨️ 명령어 사용법
- 설정 메뉴를 열기 위해 채팅 채널에서 명령어를 사용합니다.
- ``/settings``

## 유튜브 구독

### ⌨️ 명령어 사용법

#### 채널 구독

- 유튜브 알림을 받고 싶은 채팅 채널에서 명령어를 사용합니다.
- ``/subscribe [유튜브 채널]``
- 예시: ``/subscribe 1theK``

#### 구독 취소

- 구독을 취소하고 싶을때는 ``/unsubscribe [유튜브 채널]`` 명령어를 사용할 수 있습니다.
- 예시: ``/unsubscribe 1theK``

#### 접두사 설정

-  구독한 채널에서 영상이 업로드 되었을 때 맨 앞에 나올 메시지를 추가할 수 있습니다.  (역할을 핑하고 싶을때, 사용하면 좋겠죠?)
-  접두사를 설정하려면 ``/prefix youtube [유튜브 채널]``을 사용하세요.
-  예시: ``/prefix 1theK [내용]``

#### 채널 검색

-  유튜브 채널을 검색하고 해당 채널에 대해 원하는 기능을 바로 실행할 수 있습니다.
-  채널을 검색하려면 ``/search youtube [유튜브 채널]``을 사용하세요.
-  예시: ``/search youtube 1theK``

## 트위치 팔로우

### ⌨️ 명령어 사용법

#### 채널 팔로우

- 라이브 알림을 보내고 싶은 채팅 채널에서 명령어를 사용합니다.
- ``/follow [트위치 채널]``
- 예시: ``/follow zilioner``

#### 팔로우 취소

- 팔로우를 취소하고 싶을 때는 ``/unfollow [트위치 채널]`` 명령어를 사용할 수 있습니다.
- 예시: ``/unfollow zilioner``

#### 접두사 설정

-  팔로우한 채널에서 영상이 업로드 되었을 때 맨 앞에 나올 메시지를 추가할 수 있습니다.
-  접두사를 설정하려면 ``/prefix twitch [트위치 채널]``을 사용하세요.
-  예시: ``/prefix twitch zilioner [내용]``

#### 채널 검색

-  트위치 채널을 검색하고 해당 채널에 대해 원하는 기능을 바로 실행할 수 있습니다.
-  채널을 검색하려면 ``/search twitch [트위치 채널]``을 사용하세요.
-  예시: ``/search twitch zilioner``
