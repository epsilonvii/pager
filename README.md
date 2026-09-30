# pager

## Setup Alpine on your Pi

helpful guide: [Link Text](https://github.com/lehmanjo/doc-alpine-linux-raspberry-pi-zero-w)

## USB OTG  
  
 load dwc2 and g_ether kernel modules
  
 into /etc/network/interfaces ...

```	
	auto usb0 
	iface usb0 inet static
	address <your chosen ip>
```

 now on your chosen device add an ip with same subnet onto the usb using nmcli or others

 can now ssh to your pi over usb connection :p

- 
