[![built-with-azurra-framework](https://github.com/Elbullazul/Azurra_framework/raw/assets/azurra_framework_smaller.png)](https://github.com/Elbullazul/Azurra_framework)

# Haiku

GTK theme based on the appearance of the open source operating system [Haiku](https://www.haiku-os.org/)<!--- R1 Beta 1 -->, the successor to BeOS.

![haiku-beta-1](https://github.com/B00merang-Project/gallery/raw/master/Haiku%20R1%20Beta%201%20(1).png)

**Maintainer:** [Elbullazul](https://github.com/elbullazul)

**Distributor:** [B00merang Project](https://github.com/B00merang-Project)

**License:** GPL v3

**More info :** http://b00merang.weebly.com/haiku.html

### Manual installation
Under Haiku:

`mkdir -p /boot/home/config/non-packaged/data/themes`

`cd /boot/home/config/non-packaged/data/themes`

`git clone https://github.com/khallebal/Haiku-GTKtheme.git`


Then open the file

`nano /boot/system/non-packaged/data/glib-2.0/schemas/00_org.gnome.desktop.interface.gschema.override`

And change the line from

`gtk-theme='Adwaita'`

 to

`gtk-theme='Haiku-GTKtheme'`

Then run the following cmd:

`glib-compile-schemas /boot/system/non-packaged/data/glib-2.0/schemas`

That's it you're done.

### Requirements

- GTK+ 3.20 or above

Under linux:

Extract the zip file to the themes directory i.e. `/home/USERNAME/.themes`

### Requirements

- GTK+ 3.20 or above
- Murrine and Pixmap theme engines

### Contribute

Contact us @ http://b00merang.weebly.com/contact.html
