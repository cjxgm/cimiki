.PHONY: all clean build
all: build
clean:
	rm -rf ../build/
build: build-latest

.PHONY: build-latest build-full-history
build-latest: clean
	cmake -P cmake/build-doc.cmake
build-full-history: clean
	cmake -P cmake/build-doc.cmake -DFULL_HISTORY=1

