## cmus-lrc

cmus lyrics play in terminal.

- lyrics server provided by [NetEase](https://music.163.com) [Xiami](https://xiami.com)

##Options
* -log, --log. log file filepath. default: ~/.cmus/cmus-lrc.log
* --lyrics-dir. lrc file save dir. default: ~/.cmus/lyrics/
* --disable-download. disable auto download lrc file. default: false

##Command
type `:` start input command
* q, quit, exit. exit cmus-lrc.
* shift `time`. `time` default use ms, support s, m. example: `shift 100`, `shift 1s`, `shift 1m`.
* wrong. set lrc wrong. delete current lrc file and disable auto download for current song.
* search `keyword`. use `keyword` search lyrics .
* save. save lyrics to lrc file.
* reload. reload lyrics from lrc file.