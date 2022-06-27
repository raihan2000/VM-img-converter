# Convert Virtual Box Images to Qcow2/Qemu Images

## Description

- I have written this script to easily convert vdi,vda,ova to Qcow2 cuz
  I'm using Qemu or Gnome Boxes to create virtual machines
- I am noob pentester who is a Linux Enthusiast
- This script will work only if your given Directory or
  File Name without empty spaces so make sure your Directory and Image File does not contains
  any spaces
- This script will take only One image to convert dont use multiple image

## Supported Extensions
- 01 : vdi
- 02 : vda
- 03 : ova

## Usage

	./vmImg-to-qemu [~/Full/Path/to/The/Image.ext] or [Only-Image-File-Name.ext]
	sh /full/path/to/the/vmImg-to-qemu [~/Full/Path/to/The/Image.ext] or [Only-Image-File-Name.ext]

## Installation

	git clone https://github.com/raihan2000/VM-img-converter.git
	cd VM-img-converter
	chmod +x vmImg-to-qemu

## Extra

- Install pv on linux it will give visualization to conversion process
- Hope this script will helpfull if you have any query let me know in the issue
