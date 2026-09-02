all:
	@echo "Try: make test"
	@false

runtests:
	bash ./test-gpu-bank.sh
	bash ./test.sh

test:
	../wvtestrun $(MAKE) runtests

clean::
	rm -f *~
