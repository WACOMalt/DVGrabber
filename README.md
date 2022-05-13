# DVGrabber - A Raspberry Pi CM4-powered device for cheaper DV footage grabbing. [NOT IN A WORKING STATE - WORK IN PROGRESS]

**Project Description:**
    So, DV footage is hard to record sometimes. You have to get a firewire card, or a DV deck, get drivers for the old tech working on your machine. You have to find capture software, and then depend on it all being actually reliable (which it rarely is). So with professional Firewire recording devices costing upwards of $600 dollars… I figured it’s time we make something more accessible. Backing up your old memories, or enjoying the use of old tech should be open and free. 
    
Every aspect of this project will be documented and available for free. We will likely sell some of our completed PCBs once they’re produced, at cost.

So what do you actually need to record from DV camcorders? Well… you need a computer, you need a firewire interface for that computer, and you need a DV/Firewire cord.  These days a computer can fit in the footprint of a credit card, so that’ll be our choice for this project. The **Raspberry Pi CM4** is a tiny little computer with the ability to run PCI Express interface cards.

**T**he completed project will consist of the following**

 - A Raspberry Pi Compute Module 4, running a lightened kernel
 - A Custom PCB carrier board for the CM4, which will provide the storage interface (SD Card slot) and the PCIe expansion slot. As well as several other needed features (power delivery, LED status lights, maybe an OLED screen eventually)
 - A PCI Express Firewire interface card (be careful, only specific models will work!), which will provide our DV/FW400/FW600 ports for connecting your camera.
 - Custom software written in Python to control settings and system status monitoring (safe shutdown, alerting of failed captures, etc) This will also provide a Text User Interface (TUI) for system settings, if we get to adding a screen to the device.


## License

Schematic and PCB layout files are licensed under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.

Individual components and footprints found in the CM4IO library are licensed as per the Design Files license found [here](https://datasheets.raspberrypi.org/license.html).

THE DESIGN IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS DESIGN INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS DESIGN.
