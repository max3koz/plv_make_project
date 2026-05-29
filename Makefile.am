bin_PROGRAMS = hello_world
hello_world_SOURCES = main.c func.c

# Include the header to /usr/local/include
hello_worlddir = /usr/local/include
hello_world_HEADERS = func.h

# Remove installed and autotool (autoreconf --install) files
clean-all: uninstall distclean
	rm -f /usr/local/bin/hello_world
	rm -f /usr/local/include/func.h
	rm -rf autom4te.cache config.h
	find . -maxdepth 1 ! -name '*.c' ! -name '*.h' ! -name '*.am' ! -name '*.ac' ! -name 'README.md' -type f -exec rm -f {} \;
