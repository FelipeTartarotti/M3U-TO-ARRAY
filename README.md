# M3U-TO-ARRAY

## How to use it? 

- Deploy m3u-parser-simple.php to a server. (Could be hosgator or you can use Wamp for local host).

- Send a GET REQUEST to this URL-> <b>http://YOURSERVER/m3u-parser-simple.php?url=http://YOURLIST.M3U</b>

- I have it online if you want to try-> <b>http://parser.prottar.com.br/m3u-parser-simple.php?url=http://YOURLIST.M3U</b>

# Result for m3u-parser-simple.php
```
JSON
[
  {
    "id": 1,
    "tvtitle": "Newsmax TV",
    "tvmedia": "http://nmxlive.akamaized.net/hls/live/529965/Live_1/index.m3u8",
    "tvname": "Newsmax TV",
    "tvlanguage": "English",
    "tvcountry": "US",
    "tvid": "Newsmax-TV",
    "tvlogo": "http://i.imgur.com/Twkovic.gif",
    "tvgroup": "Entertainment"
  },
  {
    "id": 2,
    "tvtitle": "Infowars Live",
    "tvmedia": "http://infowarslive-lh.akamaihd.net/i/infowarslivestream_1@353459/index_800_av-p.m3u8",
    "tvlogo": "http://i.imgur.com/ODIWC6n.jpg",
    "tvname": "Infowars",
    "tvid": "Infowars",
    "tvgroup": "News"
  },
]
```
Good Luck =)

