
all:
	xelab -prj xsim.prj -debug typical top -s top
	xsim top -t xsim_run.tcl
#	xsim top -gui -t xsim_run.tcl

#all:
#	xvlog ${XILINX_VIVADO}/data/verilog/src/glbl.v
#	xelab -debug typical -L secureip -L unisims_ver -L unimacro_ver top glbl -s top_sim 
#
#all:
#	xvlog file1.v
#	xvhdl file2.vhd
#	xvlog top.v
#	xelab -debug typical top -s top
#	xsim top -t xsim_run.tcl

clean:
	/bin/rm -f  top.wdb
	/bin/rm -f  wave.vcd
	/bin/rm -f  webtalk_*.backup.jou
	/bin/rm -f  webtalk_*.backup.log
	/bin/rm -f  webtalk.jou
	/bin/rm -f  webtalk.log
	/bin/rm -f  xelab.log
	/bin/rm -f  xelab.pb
	/bin/rm -fr .Xil/
	/bin/rm -f  xsim_*.backup.jou
	/bin/rm -f  xsim_*.backup.log
	/bin/rm -fr xsim.dir/
	/bin/rm -f  xsim.jou
	/bin/rm -f  xsim.log
	/bin/rm -f  xvlog.log
	/bin/rm -f  xvlog.pb

cleanup: clean

cleanupall: cleanup
