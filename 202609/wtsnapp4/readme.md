# OpenFlight enclosure

Budget 3D-printable enclosure for an OpenFlight monitor. Print a front cover, back cover, kickstand, and kickstand plates, then assemble.

For main Openflight design, current release files live under [`202609/Cormac131/`](202609/Cormac131/).

![Front render](202609/wtsnapp4/screenshots/front.png)
![Rear render](202609/wtsnapp4/screenshots/rear.png)

## Documentation


CAD source: [`202609/wtsnapp4/step/Open-Flight-Monitor-2.1.step`](202609/wtsnapp4/step/Open-Flight-Monitor-2.1.step)

## Printer

Minimum bed: **250 × 210 mm**. The front and back cover are the biggest parts.

Printers that meet that (and common larger beds):

| Printer | Bed |
| --- | --- |
| Bambu Lab A1, P1S, X1C | 256 × 256 mm |
| Elegoo CC, CC2 | 256 × 256 mm |
| Prusa MK3S+, MK4 | 250 × 210 mm |

Older bed slingers such as the Ender 3 are too small.  Possibly could be sized down a bit in the future, but in it's current configuration the 220 x 220 printers are not supported

## Bill of materials

1. [UPS: Waveshare 3S UPS module](https://www.amazon.com/waveshare-Uninterruptible-UPS-Module-3S/dp/B0BQC2WNR8/)($33.  Includes power button, mountable charging port, and USB-c plug for the pi)
2. [18650 Batteries](https://www.18650batterystore.com/products/panasonic-ncr18650ga-ga6) x 3: ~$25 - Highly recommend buying 18650 batteries from a specialized seller, not Amazon, eBay, etc.)
3. [Nylon M3 screws](https://www.amazon.com/Black-Nylon-Standoff-Spacers-Screws/dp/B0F297R23T/): $9 - M3x6mm screws used to secure radars in some places to the frame to keep radar signal clear
4. [M2/2.5/3/4 Screw Kit](https://www.amazon.com/mxuteuk-Assortment-Suitable-Printing-Washers/dp/B0G8F366MV?th=1): $9 - Screws used for assembly for all non-radar components
5. [300 Piece Heated Insert Assortment](https://www.amazon.com/FFVRVSS-M2-M2-5-Threaded-Inserts/dp/B0FWCG2K1F?th=1): $8 - Heated inserts used to secure everything

&nbsp;&nbsp;&nbsp;&nbsp;Total:

&nbsp;&nbsp;&nbsp;&nbsp;  ~$84 with UPS

&nbsp;&nbsp;&nbsp;&nbsp;   $26 without a UPS (do not buy UPS and batteries)

## License

[GNU GPL v3](LICENSE)
