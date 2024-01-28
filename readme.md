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

## This means you are free to:

- **Share** - copy and redistribute the material in any medium or format
- **Adapt** - remix, transform, and build upon the material for any purpose, even commercially

## under the following terms:

- **Attribution** - You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **ShareAlike** - If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.