---
title: Dell Precision M3800 Workstation
date: 2023-09-18
description: 
tags:
  - dell
  - laptops
  - linux

---

Dell's Precision M3800 is an ultrabook-shaped mobile workstation, combining powerful components with a slim chassis.

I've owned this laptop for a number of years now, I rebuilt this unit after being given it by a friend who purchased a newer laptop after a mainboard & internal battery failure. [I replaced the motherboard & battery](//youtu.be/RAMERaW26nM); roughly $300nzd / $180usd is what it cost me, additionally I purchased a sata adapter cable since this didn't come with one included.

I installed a 2TB SATA SSD, after installing this [SATA Adapter (PN: DG95V)](https://www.aliexpress.com/item/32879310306.html). **Note:** Ensure you have a 61WH Battery, as a 91WH battery wont allow space for the SSD. 
 
- AliExpress [M3800 Mainboard](https://www.aliexpress.com/item/4001110094560.html)
- eBay [T0TRM 61Wh Battery](https://www.ebay.com.au/itm/275251039869)
- [SATA Adapter (PN: DG95V)](https://www.aliexpress.com/item/32879310306.html)

## Linux

[eBay listings](//ebay.com/sch/i.html?_from=R40&_trksid=p2380057.m570.l1313&_nkw=dell+m3800&_sacat=0) for this laptop make it a good decent proposition, especially if you pick up a 4K and/or [4K touch SKU](//ebay.com/sch/i.html?_from=R40&_trksid=p2334524.m570.l1313&_nkw=dell+m3800+4K&_sacat=0&LH_TitleDesc=0&_odkw=dell+m3800&_osacat=0), as a great Linux laptop. Using the SATA cable adapter, you can install the OS on the mSATA drive, mounting the SATA SSD on the adapter on /home.

Linux support on the Precision M3800 is really quite good, as it was one of the first retail developer edition that received official OEM Ubuntu Linux support[^1].

[^1]: ZDNET - [Dell offers new Ubuntu Linux workstation laptop](//zdnet.com/article/dell-offers-new-ubuntu-linux-workstation-laptop/)

## Documentation
- [Owners Manual PDF](https://dl.dell.com/topicspdf/precision-m3800-workstation_owners-manual_en-us.pdf)
- [M3800 Spec Sheet](https://i.dell.com/sites/doccontent/shared-content/data-sheets/en/Documents/dell-precision-m3800-spec-sheet.pdf)

