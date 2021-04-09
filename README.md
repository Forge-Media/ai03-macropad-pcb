# ai03 Inspired Macropad PCB

My attempt at learning and implementing ai03's guide to pcb design for keyboards. The aim of this project is to design and manufacture a simple 3by3 MX style macropad pcb, which actually works. The pcb can then be manufactured and either assembled by hand or by the manufacturer if they provide assembly service.

## Project requirements:

- 9 1U switches (mx style)
- USB-C support
- Atmega32u4
- QMK support
- VIA support (TBD)
- Solder support (rev. A)
- Hotswap support (Rev. B)

## CAD

KiCad 5.1.9 is used for the pcb design, based on [ai03's guide](https://wiki.ai03.com/books/pcb-design).

**Required KiCad libraries:**

- [ai03's KiCad Type-C library](https://github.com/ai03-2725/Type-C.pretty) (USB-C 2.0 connector)
- [ai03's hybrid footprints](https://github.com/ai03-2725/MX_Alps_Hybrid/tree/master/MX_Only.pretty) (Kailh Hotswap LED footprints)
- [KiCad included switches](https://kicad.github.io/footprints/Button_Switch_Keyboard) (Solder MX footprints)
- [Perigoso's KiCad Keyboard libraries](https://github.com/perigoso/keyswitch-kicad-library) (Kailh Hotswap footprints)
- [ebastler's various components](https://github.com/ebastler/kicad-keyboard-parts.pretty) (3D Kailh Hotswap)
- (TBD)

Autocad, Rhino and Fusion 360 are used for the case design.

## References:

- [ai03's - pcb guide](https://wiki.ai03.com/books/pcb-design)
- [ai03's KiCad library list](https://wiki.ai03.com/books/pcb-design/page/list-of-kicad-keyboard-parts-libraries)
- [Keyboard Atelier Discord](https://discord.gg/b7vwhHS)
- [QMK Docs](https://beta.docs.qmk.fm/developing-qmk/c-development/compatible_microcontrollers)
- [Hadi's - PCB design series](https://www.youtube.com/channel/UCpWGAJr2AU7LPUwVYbBQZRg/playlists) (Incomplete!)
- [KoBuss' - How we designed a mechanicial keyboard pcb](https://www.youtube.com/watch?v=ezk02GJ9iMs)
- [MrKeebs' - PCB from Scratch with Gondo series](https://www.youtube.com/watch?v=Nk0egpDFqRA)
- (TBD)

## License

MIT License

Copyright (c) 2021 ForgeMedia (Jeremy Paton)

Permission is hereby granted, free of charge, to any person obtaining a copy of this hardware, software, and associated documentation files (the "Product"), to deal in the Product without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Product, and to permit persons to whom the Product is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Product.

THE PRODUCT IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE PRODUCT OR THE USE OR OTHER DEALINGS IN THE PRODUCT.

## For the Keyboard Community

You can produce and sell this keyboard design. ForgeMedia (Jeremy Paton) is not liable. Creator attribution is required however, no use of the creator's or 3rd party branding may be utilised in a derivative. This includes logos and brand names.
