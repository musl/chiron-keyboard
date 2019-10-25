# Chiron Keyboard

![chiron](https://i.imgur.com/3XZACfs.jpg)

This is a custom keyboard meant to be easily and quickly 3D printable on
most FFF/FDM printers. It's inspired by the [Viterbi](https://keeb.io/products/viterbi-keyboard-pcbs-5x7-70-split-ortholinear), [Iris](https://keeb.io/products/iris-keyboard-split-ergonomic-keyboard), and
[Dactyl Manuform](https://github.com/adereth/dactyl-keyboard) keyboards.

## The Case

This case has been designed to be easily 3D printed on most FFF/FDM
printers. I designed it in Autodesk Fusion 360, and printed it on a
Prusa MK3s.	It should print in just over 19 hours for all four parts you
need. All you need for the case are these printed parts and 6 qty. M2x10
screws that are commonly available.

I've provided the following files:

- chiron-r7-v21.f3z
	
	  Autodesk Fusion 360 source files
	
- chiron-r7-v21.3mf
	
	  The whole Slic3r project with all the parts in the recommended
	  orientations for printing on the Prusa MK3s.
	
- chiron-r7-v21-single-print.stl
	
	  A single STL file for all the parts in the recommended orientation for
	  printing.

I've also included STLs for each part separately in case you want to
slice and print them separately. I have not included gcode because it's
not safe to print gcode you get from the internet without reading and
understanding it all first. It's way safer and easier to slice things
yourself.

## The Firmware

If you make this, you can use whatever controller and firmware you like. My board runs QMK. Find my firmware and default keymap here: [https://github.com/qmk/qmk_firmware/tree/master/keyboards/handwired/chiron](https://github.com/qmk/qmk_firmware/tree/master/keyboards/handwired/chiron) 

