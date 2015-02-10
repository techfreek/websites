build: deps static
	node_modules/.bin/metalsmith

deps: node_modules

static:
	mkdir -p build/filecoin.io
	mkdir -p build/ipfs.io
	mkdir -p build/ipn.io
	cp -r styles build/filecoin.io/styles
	cp -r styles build/ipfs.io/styles
	cp -r styles build/ipn.io/styles

node_modules: package.json
	# npm install

.PHONY: build
