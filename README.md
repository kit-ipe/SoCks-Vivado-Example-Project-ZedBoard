# SoCks-Vivado-Example-Project-ZedBoard

Vivado project for the SoCks ZedBoard example project

## Prerequisites

To be able to use this project you need a Vivado 2024.2 installation with board support for the ZedBoard. If you install the board from the Vivado Store, it will probably not be recognized by Hog, because Vivado installs it in `/home/<you>/.Xilinx/Vivado/2024.2/xhub/board_store/xilinx_board_store/XilinxBoardStore/Vivado/2024.2/boards/`. Instead, you should download the board support package from this [repo](https://github.com/Xilinx/XilinxBoardStore/tree/2024.2/boards/Avnet/zedboard) and install it directly in you Vivado installation in `<vivado_installation>/2024.2/data/boards/board_files`. Basically, copy the folder `zedboard` from the repo into the `board_files` folder of your Vivado installation.

## Getting started

1. Navigate to this Repo:
```
$ cd socks-vivado-example-project-zedboard
```

2. Create the Vivado project with Hog:
```
$ ./Hog/Do CREATE zedboard-socks-vivado-example-project
```

3. Build the Vivado project with Hog:
```
$ ./Hog/Do WORKFLOW zedboard-socks-vivado-example-project
```

