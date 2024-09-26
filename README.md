# VR44-Keyboard-PCB

> &#128679; `Placeholder for future project` &#128679; <br>
> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &#9888;&#9888;&#9888;&#9888;&#9888;&#9888;&#9888;&#9888;&#9888;&#9888; <br>
> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &#9888; ***DO NOT BUILD*** &#9888; <br>
> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &#9888;&#9888;&#9888;&#9888;&#9888;&#9888;&#9888;&#9888;&#9888;&#9888; <br>
> &#128679; `==============================` &#128679;



## Intent

A macro-pad / num-pad cluster **companion** keyboard with QMK f/w, *for those who use 60%/70% keyboards but need a num-cluster*.  Also something for thoes extra key-caps to do.


## Layout ideation renders

#### Render

![Render](docs/vr44-render.png)

#### Layout

![Layout](docs/vr44-layout.png)

#### Matrix

![Matrix](docs/vr44-matrix.png)


## Planned Features

- [ ] QMK build
- [ ] MCU `RP2350` *(Depending on QMK support.  Keep track: [#24346](https://github.com/qmk/qmk_firmware/pull/24346) )s*
- [ ] C3/4 UDB Usb-C
- [ ] Hotswap MX or Choc switches *(dual support. MAYBE NOT)*
- [ ] 5 x positions for Skyloong Rotary Encoder *(with all 5 in concurent use capability)*
- [ ] USB PD Sink controler for 5V-3A Power Delivery. `HUSB238` ~~*or*~~ ~~`TPS25730`~~ ~~*or*~~ ~~`STUSB4500`~~
- [ ] Built in USB-Hub, 3-port.  Two back, one on right side.  `CH334F`
  - with option to off-line the Hub but keep the KB working. Needs `TS3USB221`
- [ ] OLED Display screen module.
  - White *(a.k.a. 0.91-inch OLED)* *or* Color *(?? imposible to find)*
  - 128x32 resolution 
  - 19 x 33 mm (0.75 x 1.5 inch) &#177;Max size
- [ ] Battery backed-up RTC for time display. `DS1307`
- [ ] Temperature sensor. `DS18B20`
- [ ] All 2U keys have 2x 1U options *(hotswap)*
- [ ] Additional optional keys arround the arrow cluster


## Wish List

- *undecided*


## Possible BIG issues

- *Way to far in the futire to know*

&nbsp;<br>&nbsp;

---
Made with &#9829; by Vino Rodrigues
