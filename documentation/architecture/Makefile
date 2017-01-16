all: architecture.png

architecture.png: architecture.dot
	dot architecture.dot -Tpng -Gsize=9,16 -Gdpi=200 -o architecture-Main.png

.PHONY: clean
clean:
	rm architecture-Main.png
