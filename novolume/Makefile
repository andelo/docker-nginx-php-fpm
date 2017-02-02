all: files

files:
	cp -Rp ../files .
	cp ../Dockerfile .

clean:
	rm -rf files
	rm Dockerfile

update: clean files

.PHONY: files
