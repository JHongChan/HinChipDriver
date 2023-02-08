dts  := axi_usb2_device_V5_0_overlay.dts
dtbo := axi_usb2_device_V5_0_overlay.dtbo

$(dtbo): $(dts)
	dtc -@ -I dts -O dtb -o $@ $<
	
clean: $(dtbo)
	rm -rf $<
