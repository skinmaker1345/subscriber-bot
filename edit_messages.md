# Editing Notification Message of Subscriber
- You can edit notification messages on your own style.

### How to
- To set default server settings, use ``/settings``.
- If else, your follow / subscription by using ``/list``.

### Variable
- Notification messages may contain ``variables``.
- variables are used to populate videos / streams' information, such as title, channel, url.

#### Using variables
- To use variables on your message,  form variables in ``{variable_name}``.

#### Variables that are usable for YouTube
|Name|Description|Additional|
|-|-|-|
|title|Video title||
|id|Video ID||
|channel_id|Channel ID||
|channel_name|Channel name||
|url|Video URL||
|channel_url|Channel (URL)||
|published_time|[Unix timestamp for published time](https://cdn.discordapp.com/attachments/1115539853862510712/1115539858677579806/image.png)||
|start_time|[Unix timestamp for livestream start time](https://cdn.discordapp.com/attachments/1115539853862510712/1115539858677579806/image.png)|Only available for livestreams|
|end_time|[Unix timestamp for livestream end time](https://cdn.discordapp.com/attachments/1115539853862510712/1115539858677579806/image.png)|Only available for livestreams|

#### Variables that are usable for Twitch
|Name|Description|Additional|
|-|-|-|
|title|Stream title||
|url|Stream URL||
|channel_name|Streamer name||
|start_time|[Unix timestamp for stream start time](https://cdn.discordapp.com/attachments/1115539853862510712/1115539858677579806/image.png)||
