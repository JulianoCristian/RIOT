APPLICATION = thread_flags
include ../Makefile.tests_common

BOARD_INSUFFICIENT_MEMORY := nucleo32-f031

USEMODULE += core_thread_flags
USEMODULE += xtimer

include $(RIOTBASE)/Makefile.include

test:
	tests/01-run.py
