There is 1 request format for [/initplayback](./initplayback.md):
- OnesieInnertubeRequest

There are 2 request formats for /videoplayback:
- VideoPlaybackRequestProto. Gets media data with ump.
- VideoPlaybackAbrRequestProto. Can fetch media data for two itags at the same time. Interlaced data response. Uses server abr streaming url.

The response format is [application/vnd.yt-ump](./ump.md)