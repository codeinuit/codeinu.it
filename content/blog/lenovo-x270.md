---
title: "Upgrading a Thinkpad x270"
date: 2023-08-19T20:17:21+02:00
draft: false
menu: Blog
showToc: true
---

{{< notice warning >}} [22/08/2023] This article is a draft. More details and explanations are planned. {{< /notice >}} 

## Motivations


I appreciate the Thinkpad X series from Lenovo and I am convinced that their products are reliables and comfortable to use.
From the subreddit [r/thinkpad](https://www.reddit.com/r/thinkpad/), I learned that some ultrabooks from 2015 were still viable in 2022. If you want to more know about the device, you can find a detailed review on [notebookcheck.biz](https://www.notebookcheck.biz/Courte-critique-du-PC-portable-Lenovo-ThinkPad-X270-Core-i5-Full-HD.215376.0.html)

I’m a Mac user but I use to prefer a PC, and I really like the small form factor of the ultrabooks.
So, I looked on Leboncoin for a used X270 and I bought one for 150€ with the following specs :

**Screen** : TN 1366x768\
**RAM** : 8gb DDR4\
**CPU** : Intel Core i5-7200U\
**Storage** : M2 SSD 256GB

In overall, the laptop is nice and seems robust, but the screen panel is aweful. It does not look nice and its almost unreadable if you are not exactly facing the screen, so it’s an obvious upgrade.

I also upgraded the RAM, the SSD and the WiFi card, but honnestly, but it’s more an optionnal comfort. Since my wifi router support 6E, i wanted to take profits of this.

## Upgrading

Before doing anything, I recommand to gather every required tools. Don’t forget to power off the device, disconnect every cables, remove cards inside and the external battery.

Upgrading the screen does not require any tool, there is no glue or screws. The plastic bezels are clipped and does only require to gently pull off from the top to the bottom.

For every part located inside, you will need a Philips screwdriver and I *really* recommand using a [plastic tool opener](https://www.amazon.fr/gp/product/B075R1LLVC/ref=ppx_yo_dt_b_asin_title_o07_s00?ie=UTF8&th=1) or another thin tool to pop the backplate without damaging anything.


### Replacing the screen

It seems scary but actually it’s the easiest part, and it does not even requiert any tool, the bezel of the screen pops off easily. The most difficult part is finding the correct panel.
[This reddit comment](https://www.reddit.com/r/thinkpad/comments/9xl5ud/comment/eabwlw6/?utm_source=reddit&utm_medium=web2x&context=3) does explain well how to choose a panel.

Personnaly I bought this IPS panel with FHD from Aliexpress (https://fr.aliexpress.com/item/1005003361028659.html?spm=a2g0o.order_list.order_list_main.5.29535e5b8T5lKT&gatewayAdapt=glo2fra)

![Laptop topless](/lenovo/lenovo-topless_compress.png)

Once you removed the bezels, the panel shouldn’t be attached, so you can flip it easily. You must disconnect the connector by pulling the adhesive and you can remove and replace with the new panel after.

![Laptop topless](/lenovo/screen-connector_compress.png)

Once the new panel connected, you can place the new panel inside, and re-attach the bezels starting below, and it should be OK. 

### Upgrading inside parts

Flip the laptop and check every screws. The screws are attached to the backplate, they will come loose when you unscrew them. This is the cool part since you will not be afraid of loosing a screw. 

Remove the SIM tray located on the left side using a SIM tool or anything thing before doing anything here.


![Laptop screws](/lenovo/backplate_compress.png)

Once ready, unscrew the backplate, and open it by sliding a plastic opener tool (or any variant) all along the side.

![Laptop inside without backplate](/lenovo/inside_compress.png)

I only drew on part I upgraded, but there is still room for other improvements, like adding a 2nd battery or adding a WAN card.

Replacing the pieces is intuitive and would be useless to explain. However, The Wifi card is kept by a screw, and the cables are clippable, they just need to be pulled. Just remember how they were attached before.

The RAM I used is the [Corsair Vengeance DDR4 2400MHz in SODIMM format](https://www.amazon.fr/gp/product/B077S17RPZ/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1), and regarding

Wifi card is a [AX210](https://www.amazon.fr/gp/product/B0B39631G1/ref=ppx_yo_dt_b_asin_title_o07_s00?ie=UTF8&psc=1) with a M.2 port that supports WiFi 6E.

I also replaced the SSD with a [Samsung 980 NVMe M.2](https://www.amazon.fr/gp/product/B08TJ2649W/ref=ppx_yo_dt_b_asin_title_o06_s00?ie=UTF8&psc=1) that works just fine.

## Conclusions

Buying this laptop was a kind of bet actually. I wasn’t expecting this to be *that good* but it really comes handy once upgraded. However, the screen is the only part that needs to be replaced.

The battery is really fine. Obviously, upgrading from a HD to a FHD panel does impact the time on battery, but it’s ok since the main batterie is removable and there is also room for improvement with the internal battery slot.

The only disapointing part is the internal microphone and the speakers. The speaker is muffled, low, and the microphone is aweful, it’s even not usable. But hopefully, it could be replaced by using a headset, so for my part it’s still ok.

I spent more on upgrading pieces than the whole unit (almost 164€). I’m not sure it was really worth comparing to others computers on the market for the same price, but it was definitely fun to play with. 

The form factor comes really handy, so I’m keeping this laptop as my main driver on the go with Gentoo.
