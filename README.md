# Description
- 持续更新中
- 本分支大部分内容与原版一致，修复了一些问题，并添加了linux64下的驱动。

# Microsoft FPGA Board
Microsoft Catapult FPGA, PCIE Test Demo, On-board usb Blaster and OpenCL BSP 

- [x] Catapult V3, Longs Peak

## Milestone
- [x] PCIE On Chip Memory and DDR4 Test Ok (Windows 10)2022.04.09
- [x] On Board USB Blaster Work (Windows 10 and Linux)2022.04.23
- [ ] Catapult V3 OpenCL BSP 20.1 (Windows 10) 
    - **vecter_add Failure**, timming issue 2022.05.08
- [x] A RISC-V E203 On Catapult V3, 2022.08.24
- [x] Catapult V3 OpenCL BSP 18.1.2 277(Windows 10)
   -  run vecter_add,sobel and mandelbrot **OK**,2022.08.28,

## USB Blaster

![](docs/pictures/catapult_card_usb_blaster.jpg)
![](docs/pictures/fpga_programme.jpg)

## Demo

### PCIE_DDR DMA test

![](docs/pictures/pcie_dma_test.jpg)

## OpenCL

### DEVICE

![](docs/pictures/catapult_v3_opencl_device.jpg)

### Board TEST

![](docs/pictures/catapult_v3_opencl_diagnose.jpg)

### Sobel

![](docs/pictures/catapult_v3_opencl_sobel_0.jpg)
![](docs/pictures/catapult_v3_opencl_sobel_1.jpg)

### Mandelbrot

![](docs/pictures/catapult_v3_opencl_mandelbrot_0.jpg)
