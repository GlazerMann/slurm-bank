all:
	@echo "Try: make test"
	@false

runtests:
	./test.sh

functional:
	bash ./functional.sh

test:
	../wvtestrun $(MAKE) runtests

clean::
	rm -f *~
