# start 
.PHONY: start
start:
	echo "Start openocd for stm32f3x series"
	sudo openocd -f ./runner.cfg -f target/stm32f3x.cfg

.PHONY: terminal
terminal:
	echo "Start terminal"
	telnet localhost 4444

