build:
	./node_modules/.bin/browserify-server \
		--bundle=index.js -o ./static/bundle.js

watch:
	./node_modules/.bin/wr "make build" .

live-reload:
	./node_modules/.bin/live-reload

open:
	google-chrome localhost:8080

all:
	make live-reload &
	make watch
