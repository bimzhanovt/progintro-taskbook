# Makefile
`Makefile` поддерживает компиляцию программ для Linux и FreeBSD. По умолчанию `make` пытается автоматический обнаружить текущую операционную систему командой `uname`. Эта команда устанавливает значение переменной `OS`. Её значение можно установить вручную из командной строки с помощью команды `make OS=LINUX` или `make OS=FREEBSD`.
