# Raspberry Pi CM4 Carrier Board for Capturing DV Footage via Firewire PCIe Card.

![Rendered example of RPi CM4 Carrier Template PCB](https://raw.githubusercontent.com/ShawnHymel/rpi-cm4-carrier-template/main/images/rpi-cm4-carrier-template-rendered.png)

This project aims to be an open source replacement for expensive and closed-source Firewire Capture devices, that anyone can build themselves.

**NOTE** This project requires KiCad 6 or higher.

**NOTE** As of this writing, only one type of Firewire card has been tested to work with the CM4 (by someone other than myself). The chipset on the working card was a VT6307 and it had an ASM1083 on it. Once I have more first-hand information about specific working cards this info will be updated with model numbers/purchase links.

This project uses the CM4 library parts from the IO board KiCad files ([found here](http://datasheets.raspberrypi.org/cm4io/CM4IO-KiCAD.zip)). This project used as a starting point ShawnHymel's wonderful carrier board template ([found here](https://github.com/ShawnHymel/rpi-cm4-carrier-template)).

## License

Schematic and PCB layout files are licensed under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.

Individual components and footprints found in the CM4IO library are licensed as per the Design Files license found [here](https://datasheets.raspberrypi.org/license.html).

THE DESIGN IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS DESIGN INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS DESIGN.
