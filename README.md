# rpi-dv6510

My son turns 8 this year. Seems like a good time to get him an educational computer he deserves. My first thought was RP400 or a used monitor with RPI screwed to the VESA mount. The problem is desk space. I don't want to clutter it with permanent setup, I need something mobile.

I had HP Pavilion DV6510eu sitting in the parts bind. The model's heatsink was crapy and the GPU kept unsoldering making it unusable.
This was my first-ever laptop, wrote my engineering thesis, got a slight sentiment towards it.

Compute Module 4 based board seems like an ideal candidate to replace the damaged mainboard.

I did some research online and it seems quite feasible.

# Plan

- tear-it-down !
- start with CM4+TOFU (https://store.oratek.com/products/tofu)
- prototype a USB controller for the keyboard (try using RP2040 Pico)
- bring-up the display using of-the-shelf HDMI controller
- touchpad controller
- built-in speakers
- multi-media keys
- battery interia replacement
- try to reuse stock cooling or look for less heavy solution
- design protoboard that uses existing mounting holes, LEDs, buttons, socket holes, etc. route goldpins to the side, replace VGA socket with second HDMI, M2 storage, all other nice-to-haves
- ...
