# RAK1910_GPS_UBLOX7

There's a bug (or let's call it omission to be generous) in the original example, whereas the latitude and longitude displayed have the North/South & East/West values omitted – that works for people in the top-right quater of the Earth, but for the rest of the world, oops.

I fixed the bug – but the code overall feels screwy (and that's *me* talking). I suggest using TinyGPS++ rather. I put up [sample code](https://github.com/Kongduino/WisBlock_TinyGPSpp_Example) as a demo.