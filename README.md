Created: 20240305 2111
Status: Completed
Tags:
Links: [[Arduino IDE]] , [[Projects]]

---

This is an adaptation of Nick's from [educ8s.tv](https://educ8s.tv/arduino-fm-radio-project/)

---

### 1. Inspiration:

Family reached out inquiring about the possibility of building her a simple crude radio receiver.

### 2. Conceptualization:

- simple, small, 9V battery operated.
- should seem like DIY device
- Should receive FM signals and output good quality signal

### 3. Minimum Viable Product:

#### Hardware:

- [ ] Microcontroller (Arduino Nano works well)
- [ ] [FM Radio Module](https://www.ebay.com/itm/310795359575)
- [ ] [Nokia 5110 LCD](https://www.ebay.com/itm/400488314619?hash=item5d3ef6b6fb%3Ag%3AuNYAAOSw2GlXHye0&siteid=0&customid=&toolid=20012)
- [ ] 10K Potentiometer \*2
- [ ] [Audio Amplifier](https://www.ebay.com/itm/404836913275)
- [ ] [3W Speaker](https://www.digikey.com/en/products/detail/cui-devices/CMS-402811-28SP/10821307)
- [ ] breadboard / prefboard for prototyping
- [ ] [Audio Cable](https://www.digikey.com/en/products/detail/tensility-international-corp/10-00344/2350247)
- [ ] Jumper Wires
- [ ] Solder station + Solder wire (not required but preferable)
- [ ] Antena

### Iterative Design:

Later improvements will come here.

---

# Dependencies:

[FM Radio Library](https://github.com/mroger/TEA5767)
[Nokia 5110 Graph](http://www.rinkydinkelectronics.com/library.php?id=48)

# References

If you want to work with Nucleos instead of Arduino, but want to utilize the classic Arduino IDE you follow the insturctions here: https://www.youtube.com/watch?v=yssEiMLGH90

- https://github.com/stm32duino
