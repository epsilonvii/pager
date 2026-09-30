# pager

- Setup Alpine on your Pi

- USB OTG  
  
  load dwc2 and g_ether kernel modules
  
  into /etc/network/interfaces ...
'''	
	auto usb0 
	iface usb0 inet static
	address <your chosen ip>
'''

  now on your chosen device add an ip with same subnet onto the usb using nmcli or others

  can now ssh to your pi over usb connection

- 
