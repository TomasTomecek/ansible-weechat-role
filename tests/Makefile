build:
	docker build --tag=weechat-role .
test:
	docker run -v $(abspath $(CURDIR)/..):/src/roles/weechat weechat-role
