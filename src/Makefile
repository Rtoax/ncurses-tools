CFLAGS += $(shell pkg-config --cflags ncursesw json-c)
CFLAGS += -DHAVE_JSON_C=1
LDFLAGS += $(shell pkg-config --libs ncursesw json-c)
LDFLAGS += -lm

plotcake: plotcake.o loadavg.o plot.o ram.o stdin.o line.o ltypes.o keyboard.o \
	file.o utils.o lgroup.o axis.o
