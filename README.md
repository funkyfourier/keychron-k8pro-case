# WIP: 3D Printable Case for the Keychron K8 Pro keyboard

![Keychron K8 Pro with 3D printed case](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/k8pro01.jpg)

When I got me a [Keychron K8 Pro](https://www.keychron.com/collections/keychron-k-pro-series-normal-profile-keyboards/products/keychron-k8-pro-qmk-via-wireless-mechanical-keyboard) I liked everything about it except the height. Having some CAD skills and a 3D printer I therefore set out to design my own custom case.

It has taken way much more time than I thought and is basically a product of [the sunken cost fallacy](https://en.wikipedia.org/wiki/Sunk_cost#Fallacy_effect). Still, I ended up with something I really liked and overall it has been a fun experience.

### Disclaimer

*This is to be regarded as a work in progress*, since there still are some [issues](https://github.com/funkyfourier/keychron-k8pro-case/issues) which you should be aware of before attempting to print this. At the time of writing I am not sure how much more time I am going to put into this since it already has stolen a lot of valuable time from my [other](https://github.com/funkyfourier/spitback) [projects](https://play.google.com/store/apps/details?id=info.casualcomputing.sputter).

**Important:** I have **not** dared testing using the battery yet since I do not need it personally. According to the text on the charging chip it uses the TP5000X charging IC, which I have included the [data sheet](https://github.com/funkyfourier/keychron-k8pro-case/blob/master/tp5000x.pdf) for. I am quite confident that it will work, but **do not blame me if it does not**. Also, if you need the battery, beware of [issue#7](https://github.com/funkyfourier/keychron-k8pro-case/issues/7).

**Also:** Pay attention to the polarity when you insert the battery. I do *not* know wether the board has reverse polarity protection, and the board could get fried if you insert the battery the wrong way.

### Advantages:

* Probably as low profile as it can get with a PCB and hot swap sockets.
* USB connector on backside.
* Labels for the PC/Mac and BT/Cable switches are actually visible without a lamp and magnifying glass.
* More visible screws, which is masculine and cool.
* Replaceable battery.
* Possibly better looking, depending on your taste, than the aluminium frame which [some find to be hideous](https://youtu.be/LNVKRTX5gCQ?t=504).

### Drawbacks:

* Won't do any favors to the sound of the keyboard.
* No flip out feet to adjust angle.
* Increased depth due to the compartment housing the battery and daughter board.

### In use

Even with the remaining [issues](https://github.com/funkyfourier/keychron-k8pro-case/issues) unsolved, I am quite enjoying using this as my main keyboard. Obviously it does not sound as good as in the original case, mostly due to the lack of dampening materials. On the other hand the relatively low profile without having to resort to a wrist rest and still having full travel keys makes for a pretty great experience. I have tried a [K3 Pro](https://www.keychron.com/products/keychron-k3-pro-qmk-via-wireless-custom-mechanical-keyboard) at work and definetely like this better.

Of course getting the [Keychron V3 QMK](https://www.keychron.com/products/keychron-v3-qmk-custom-mechanical-keyboard) instead is a more sensible option. I was not aware of it at the time I got my K8 Pro. Still, having the option to switch to bluetooth for my work laptop while the keyboard is plugged into my PC, and being able to switch between them quickly, is a great convenience. The V3 is probably also a couple of millimeters taller.

### Printing and assembly

The case is made in [FreeCAD](https://www.freecad.org/). If you want to adjust dimensions it should be sufficient to do that in the spreadsheets.

All parts should be printable without supports. Please rotate the models to the correct orientation in the slicer before printing.

The daughter board cover is printed with a pause command which can be set in the slicer to change the color while printing. This allows for the letters being printed in another color. If your slicer/printer does not support that the letters should still be visible.

### Bill Of Materials

* 6 M3 machine screws, max 11mm length excluding head, and max 6mm head diameter.
* 6 M3 threaded inserts.
* 4 M2 machine screws, max 5mm length excluding head, and max 3mm head diameter.
* 4 wood screws. Not quite sure about the dimensions, but mine are 4mm in diameter across the threads, 19mm length excluding head and head diameter of 8mm.
* 20mm x 5mm x 1.5mm self adhesive rubber feet
* A 21700 battery of well known brand like Molicel or Samsung.
* A 21700 battery holder [like this](https://vi.aliexpress.com/item/1005004464947052.html?spm=a2g0o.productlist.main.15.70155b8eZTWrik). **See first:** [issue#7](https://github.com/funkyfourier/keychron-k8pro-case/issues/7)
* One 2 pin ZH 1.5 JST connector [like this](https://vi.aliexpress.com/item/1005003082340140.html?spm=a2g0o.order_list.order_list_main.27.124e18027wA48)
* Cables to go from battery holder to daughter board.

## Pics

Please excuse the dust. It is amazing how clean things can look in person while lots of dust and debris still show up on camera.

**Side profile:**

![Side profile](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/k8pro02.jpg)

**Back side:**

![Back side](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/k8pro04.jpg)

**Front screws:**

![Front screws](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/k8pro15.jpg)

**USB plug and switches:**

![USB plug and switches](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/k8pro09.jpg)

**PCB partly exposed underneath:**

![PCB partly exposed underneath](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/k8pro08.jpg)

**Battery compartment:**

![Battery compartment](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/k8pro10.jpg)

**Daughter board compartment:**

![Daughter board compartment](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/k8pro13.jpg)

**Surface finish front:**

![Surface finish front](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/k8pro11.jpg)

**Surface finish backside:**

![Surface finish backside](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/k8pro12.jpg)

**In FreeCAD, in all its glory:**

![In FreeCAD, in all its glory](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/fc01.png)

**In FreeCAD, from behind:**

![In FreeCAD, from behind](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/fc02.png)

**In FreeCAD, daughter board compartment:**

![In FreeCAD, daughter board compartment](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/fc04.png)

**In FreeCAD, gap underneath:**

![In FreeCAD, gap underneath](https://raw.githubusercontent.com/funkyfourier/keychron-k8pro-case/master/images/fc03.png)
