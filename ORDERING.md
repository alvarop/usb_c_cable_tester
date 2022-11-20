# Ordering Instructions on [JLCPCB](https://jlcpcb.com/).

## Download Files
Download jlcpcb.zip from [releases page](https://github.com/alvarop/usb_c_cable_tester/releases)

## Upload Gerbers and Select PCB Parameters
Go to JLCPCB, click on "instant quote" or "order now" and upload the file GERBER-usb_c_cable_tester.zip

Select the following settings (or change how you like them)
> ENIG will look better, but it's a bit more expensive. I definitely recommend lead free HASL at the very least

![Selection page](img/1.png)

Make sure you select PCB Assembly as well then click Next

# Upload BOM and Placement files

![Upload BOM](img/2.png)

Verify BOM

![BOM](img/3.png)

## Fix Component Placement
Verify component placement (it's not quite right by default)

First, rotate the battery holder 90 degrees to the left
![component placement](img/4.png)
 
Then select each USB connector and use the arrows on the top right to move it into place
![front of board](img/5.png)

You can change the view to the back to make sure the pins line up

![back of board](img/6.png)

The 3d view is also quite useful when trying to line things up

![3d view](img/7.png)

## Checkout!

![Checkout!](img/8.png)
