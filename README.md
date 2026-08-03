# e-zundapp
This is an electric conversion project for an old Moped, using a VESC controller and a
1800W Vevor motor. The moped is mostly Zundapp parts, but probably has a Mustang frame and
is likely from the early 1980s. The seat, fork and handlebars are newer and of unknown
origin.

Since the moped is old, it's capped to 30km/h as per the regulations of the time. The cap is
done via an RPM limit for the VESC controller, and otherwise I would guess around 45 would be the
top speed. The converted moped looks like this:

<p align="center">
  <a href="images/converted_moped.jpg"><img src="images/converted_moped.jpg" alt="how it looks mounted on the moped" width="31%"></a>
  <a href="images/right_side.jpg"><img src="images/right_side.jpg" alt="right side view" width="31%"></a>
</p>

<p align="center">
  <a href="images/right_back.jpg"><img src="images/right_back.jpg" alt="right back view" width="31%"></a>
  <a href="images/left_back.jpg"><img src="images/left_back.jpg" alt="left back view" width="31%"></a>
</p>

The basic tasks I've done are:

* Designed motor mounts for the Vevor motor, for attaching to the frame (with help from David Ålind)
* Designed a battery holder for a e-bike style battery (also David Ålind)
* Adaptors for the VESC controller and adaptor board
* Converted lightning to 12V LED light bulbs
* Added turn indicators and a horn :-)
* Designed various other small mounting brackets etc, 3D printed
* Ordered steel parts for the motor mounts from [Ståldirekt](https://staldirect.se/)

Apart from the moped itself, I've also created a speedometer/infotaintment for it. The speedometer
can display a map with the current position, trip data and navigation instructions as well as the speed.
It's based on an esp32p4+display from Waveshare, and the source code and more information, can be found
at [the radbuzz GitHub repository](https://github.com/SimonKagstrom/radbuzz).

<p align="center">
  <a href="images/gps_on_the_moped.jpg"><img src="images/gps_on_the_moped.jpg" alt="GPS on the moped" width="31%"></a>
  <a href="images/with_speedometer.jpg"><img src="images/with_speedometer.jpg" alt="with speedometer" width="31%"></a>
</p>

All in all, the project has taken about a year. As these things are, it's never really finished, but
it's now in a fully functioning state.

## Riding it
So how does it ride? The seating position isn't very comfortable, probably mostly due to the clip-on style handlebars.
The moped is also slightly noisy, although nowhere near what it would be with the original 2-stroke engine.

More positively, it's easy to ride and powerful enough also for uphills. I also really like the styling, which was mostly
done by the previous owner. The speedometer works very well, and I'd say it's useful and fulfil it's purpose. A worry
I had before testing was daylight visibility of the display, but it works well even in bright sunlight.

As for the range, I haven't tested it (yet), but consumption indicates that it should be 50-60km - more than I initially
expected.

## Parts

* Motor: [Vevor 1800W](https://eur.vevor.com/brushless-dc-motor-c_11227/vevor-1800w-electric-brushless-dc-motor-48v-4500rpm-motor-for-e-bike-dirt-bike-p_010506884872)
* Battery: [EM3ev 52V (14S4P) 21700 King Shark Ebike Battery](https://em3ev.com/shop/em3ev-52v-14s4p-king-shark-ebike-battery/)
* Controller: [Spintend Ubox 100V 100A](https://spintend.com/collections/esc-based-on-vesc/products/single-ubox-100v-100a-motor-controller-based-on-vesc)
* Adapter board: [Spintend Adapter V3](https://github.com/JohnSpintend/Spintend-manuals/wiki/Adapter-V3-manual)
* Rear sprocket: 42 tooth, probably similar to [Mustang/MCB](https://mopeddelar.se/sv/products/bakdrev-42t-mustang-mcb-hercules)
* Front sprocket: 410, 8 tooth

## 3D Modeling / CAD
3D printing has been used for functional parts and prototyping, and has been designed in onshape
(with big help David Ålind!):

* [onshape model](https://cad.onshape.com/documents/3593b0cc97d98cb427c31ef7/w/a1e1b7fa8532312e6433ce5a/e/34df62003381d55de4daf521?renderMode=0&uiState=69162cb1db0e5ee5867435a5)
