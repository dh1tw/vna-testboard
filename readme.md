# VNA Testboard PCB

I really like this small PCB testboard for prototyping and experimenting with my Vector Network Analyzers. [SDR-Kits](https://www.sdr-kits.net) used to sell it as a complimentary item for the DG8SAQ VNA. Unfortunately, mine showed some wear and SDR-Kits doesn't sell the PCB / Testkit anymore. So I clone it.

![testboard](/docs/testboard.jpeg)

![testboard with original one from sdr-kits](/docs/testboard_with_original.jpeg)

## Layout

![PCB layout](/docs/layout.png)

## Design considerations

The PCB was designed in KiCad 7. You will most likely have to **change / adopt the SMA connectors** since I used a couple of non-standard ones which, I just had in stock.

I designed the traces as microstrip lines, matching 50 Ohm. This resulting trace width is 1.85mm using __1,0mm PCB thickness__ and an Epsilon r = 4.5 of the FR4 material. I get accurate results up to a few hundred Megahertz.

The pin sockets have a 2.54mm spacing.

I use Nylon M3 screws & nuts as feet.

## License

[Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/deed.en)