top_builddir = ..
include ${top_builddir}/makeinclude

DIRS = lib


install:
	for dir in ${DIRS}; do \
		${MAKE} -C $${dir} install; \
	done

clean:
	for dir in ${DIRS}; do \
		${MAKE} -C $${dir} clean; \
	done
	rm -rf *~

.PHONY: all clean
