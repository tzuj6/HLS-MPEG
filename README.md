MPEG forward : Wang's DCT
======================================


Below are from original author: https://github.com/Xilinx/HLx_Examples/tree/master/Vision/mpeg_forward



## 1. OVERVIEW

Implementing MPEG-DCT 

## 2. SOFTWARE TOOLS AND SYSTEM REQUIREMENTS

Any Vivado HLS release from 2014.1 to 2016.1

## 3. DESIGN FILE HIERARCHY
```
	
	|   README.md
	\---code
			dct.h
			dct_coeff_table.h
			fdctref.cpp
			my_dct.cpp
			wang_fdct.cpp
	\---code-opt
			dct.h
			dct_coeff_table.h
			fdctref.cpp
			my_dct.cpp
			wang_fdct.cpp
	\---testdata
			test_wang_fdct.cpp
	\---impl
			top_fdct_csyth.rpt
	\---script
			script.tcl
			
```

## 4. INSTALLATION AND OPERATING INSTRUCTIONS

1. In the Vivado HLS command line window:

```
	vivado_hls script.tcl
```

