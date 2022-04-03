# Subscriber
Subscriber sends Youtube / Twitch notifications to a Discord channel.

## 🛠️ Features
- Detect YouTube Video Uploads
- Detect YouTube Live Streams
- Detect Twitch Live Strams
- Customize prefix which you can mention specific roles 
- Customize Notification Messages

## Subscribe to YouTube Channel

### ⌨️ How to Use

#### Subscribe

- Use the command in which you want to get notifications.
- ``/subscribe [CHANNEL]``
- Example: ``/subscribe 1theK``

#### Unsubscribe

- Use the command in which you don't want to get notifications anymore.
- ``/unsubscribe [CHANNEL]``
- 예시: ``/unsubscribe 1theK``

#### Set Prefix

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

## Set Messages
You can set your own messages which will be sent when notify.

### ⌨️ How to Use
- Type ``/message`` to set messages.
- You can see the guide [here](https://github.com/skinmaker1345/subscriber-bot/blob/en/edit_messages.md).

## Settings
You can adjust settings for specific channel.

### ⌨️ How to Use
- Type ``/settings`` to adjust settings.
