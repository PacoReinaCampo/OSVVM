all: build

build:
	if [ ! -e work ]; then vlib work; fi
	vcom -2008 -f system.vc

simulate:
	vsim -c -do run.do work.AlertLog_Demo_Global

clean:
	rm -rf work transcript
