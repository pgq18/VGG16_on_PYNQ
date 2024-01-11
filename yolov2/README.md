Source from [dhm2013724/yolov2_xilinx_fpga(100MHzTn2Tm32Tr26Tc26)](https://github.com/dhm2013724/yolov2_xilinx_fpga/tree/100MHzTn2Tm32Tr26Tc26)

Device: PYNQ-Z1(xc7z020clg400-1)

Vivado 2021.2 for block design, Vitis HLS 2021.2 for ip core synthesizing

# Problems in Implementaion

## Long C-sim Time

## M-AXI Number of Synthesized Ip Core

## Address Allocation in Block Design

## API to Allocate Buffers

pynq.allocate will be used to allocate the buffer.

## Address Mismatchs between the Synthesized Ip Core and the ipynq File