# 1. Sound

<img width="600" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/7e408fac-2379-46d8-a14e-c20e10f2b681">
<img width="226" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/1966ea51-a752-442b-9111-7994c802b85f">
<br>

1. violet ⇅ 1nF (Part 526)<br>
2. red ⇅ 1µF (Part 528)


***

<img width="600" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/0581399f-fdf2-41b6-971d-51a20a20e985"><br>
<img width="600" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/40b9697b-411f-4a08-8b09-2bf3b42278ac">
<br>
who did it?<br> 
Matteo?<br> 
BK7IKD<br>
<br>
[YT-Video "Quansheng uv-k5 - audio Hi-Cut (1nF capacitor) hardware mod. AirBand test." from Andrzej Kuczwara](https://www.youtube.com/watch?v=j4ccuYOg2NU)
<br>
# 2. Add possiblity to use USB-PD-Cable (USB-C-to-USB-C) <br> or USB-A-to-USB-C-Cable

Insert 2 resistors of 5.1 kΩ each from ground to the CC pins (A5 / B5). This hack requires a good eye and good nerves ;-)<br>
Wiring the two configuration pins CC with 5.1kΩ resistor signals the PD charger that it can apply 5V.<br> Without this resistor-combination, no voltage is applied.
<br>
<br>
<img width="600" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/e0ee1d09-cb92-4150-912b-c4f917b5ea79">

<br>

USB-C Port |  |  |  |  |  |  |  |  |  |  |  | USB-C
-- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | --
Soldersite  | **GND**| Vbus | **CC** | SBU | bD- | aD+ | aD- | bD+ | **CC**  | SBU | Vbus | **GND**
  |▮ ▮|▮ ▮|▮|▮|▮|▮|▮|▮|▮|▮|▮ ▮|▮ ▮
  |   ┃  |   | ┃ |  |  |  |  |  | ┃ |  |  | 
  |   ┃  |  | 5,1kΩ  |  |  |  |  |  | 5,1kΩ |  |  | 
  |   ┃  |    | ┃ |  |  |  |  |  |┃  |  |  |
  |   ┗  | ━ |┻| ━━ | ━  | ━  | ━  | ━ | ┛  ||  | 


<img width="203" alt="image" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/eaa41ae1-d6f2-45a1-b253-70a95c51df99">


<img width="600" src="https://github.com/ludwich66/Quansheng_UV-K5_Wiki/assets/12202733/79a76a31-6c8b-4c9c-968b-cb66362b6c9a">




↧↥ ⇅ 