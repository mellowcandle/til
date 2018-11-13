# Linux TIL's

* How to copy while preserving the original timestamp/users etc:
  `cp -p` (14/02/16)
* Discovering current running kernel config:
  `cat /proc/config.gz | gunzip > running.config`
* Discovering tools used by scripts/compilation:
  `strace -fy -e execve -o commands.trace <cmdline>`
