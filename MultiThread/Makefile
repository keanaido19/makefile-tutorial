.PHONY: all multi
multi:
	$(MAKE) -j8 all

all: targets

targets: target1 target2
	echo done

target1:
	sleep 2 && echo "$$!"
	echo target1 is done

target2:
	echo target2 is done

target3:
	echo target3 is done
