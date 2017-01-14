all: architecture.png

architecture.png: architecture.dot
	dot architecture.dot -Tpng -Gsize=9,16 -Gdpi=200 -o architecture.png

.PHONY: clean
clean:
	rm architecture.png
