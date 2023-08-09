---
name: Printt
subtitle: A simple and more sustinable printing-as-a-service
image_path: /images/clients/printt.png
published: true
date: 2016-06-01
---

Despite the fact over 300 million ink cartridges end up in the landfill each year many people still
need to print out of nesssuty and sometimes even purchasing their own equipment at home in the process.

Founded with a mission to create a simple and more sustainable way to print. Printt had already built a small 
network of public printers across 50 student accomodation locations across the UK. Using a rudimentary system
powered by Raspberry Pis, bluetooth beaconds and a business printers. Combinign this with  a smart business model 
which utilised strateigic partners to re-fill the toner and encouraged locations to provide paper to discourage
waste..

![A student next to a prototype print station](/images/printt/1.jpeg){:.centered}

## Refreshing the hardware

Having validated their idea they needed to scale to the general public but were facing reliability issues which
span from regular failure of the SD card contained within the Raspberry Pis to student's helping themselves to the
power cables to charge their phones.

![An example of a broken printt station](/images/printt/2.jpg){:.centered width="800"}

We worked with Printt to access a series of industry grade IOT hardware platforms which could meet their
requirements whilst reducing the unit costs accosiated with each device. Using a custom built OpenWRT based
operating sytem and an off the shelf router we were able to not only remove major sources of failure (The
aforementoned SD card and power cable being two of them) reducing a major source of waste. But reduce the unit cost by over 80%, allowing Printt to expand to over 250 locations.

![The more durable router based system](/images/printt/3.jpg){:.centered}

For the second phase of expansion, a new wave of smart-printers had hit the market. We were uccessfully able to
port all of our code from our IOT devices to a javascript preact application using a SDK from the printer. Fully
eliminating any hardware leaving just the printer, with this the total network expanded up to 500 printers.

![A printtstation](/images/printt/4.jpeg){:.centered width="500"}

## Expadning the service



TODO:
- Fix banner having purple bits
- Put together content for mobile app
- Add images here
- Blog Posts about the tech details around Raspberry Pi -> Open WRT