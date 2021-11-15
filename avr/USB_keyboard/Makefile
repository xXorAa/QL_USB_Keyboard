

debug : 
	arduino-cli compile -b arduino:avr:uno --build-property "build.extra_flags=-DDEBUG" --export-binaries --output-dir debug USB_keyboard.ino

release :
	arduino-cli compile -b arduino:avr:uno --export-binaries --output-dir release USB_keyboard.ino

