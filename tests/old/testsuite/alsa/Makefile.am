testprogs = formats state srcstate

noinst_PROGRAMS = $(testprogs)

formats_SOURCES = formats.c sinesrc.c sinesrc.h
state_SOURCES = state.c sinesrc.c sinesrc.h
srcstate_SOURCES =srcstate.c

# we have nothing but apps here, we can do this safely
LIBS = $(GST_LIBS)
AM_CFLAGS = $(GST_CFLAGS)

noinst_HEADERS = sinesrc.h
