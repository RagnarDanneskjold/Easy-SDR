# Antenna Mini-Whip

An easy and quick building of active PA0RDT Mini-Whip antenna ([TH component group](./TH)) or RA0SMS Mini-Whip antenna ([SMD component group](./SMD/EasyEDA)). The module includes schematic (EasyEDA) and PCB files (EasyEDA, Sprint layout). Based on the submitted files, you can independently manufacture a PCB or order its manufacturing at the factory. The antenna consists of the antenna itself and power feed unit (PFU). In turn, I developed PCB for the independently manufacturing based on the existing circuit. As a result, the self-made manufacture of the antenna is cheaper than buying a ready-made module.

## Current development progress:
[![Progress](https://img.shields.io/badge/Antenna%20Mini--Whip%20%28TH%29-tested-green.svg)](https://easyeda.com/igor.nikolaevich.96/Antenna_Mini_Whip-d8935f151d3a4221a9a3aacae3acdb65) [![Progress](https://img.shields.io/badge/version-5.9.EE-blue.svg)](./TH/EasyEDA)  
[![Progress](https://img.shields.io/badge/Antenna%20Mini--Whip%20%28TH%29-tested-green.svg)](./TH/Sprint%20Layout) [![Progress](https://img.shields.io/badge/version-7.5.SL-blue.svg)](./TH/Sprint%20Layout)  
[![Progress](https://img.shields.io/badge/Antenna%20Mini--Whip%20%28SMD%29-tested-green.svg)](https://easyeda.com/IgrikXD/Antenna_Mini_Whip_SMD-74e9e6740b814f6c901a811855125754) [![Progress](https://img.shields.io/badge/version-3.9.EE-blue.svg)](./SMD/EasyEDA)  

## Current available implementations at EasyEDA platform:
- [Antenna Mini-Whip (TH)] ([Components list](./TH/Components%20list.md), [Assembly guide](./TH/Assembly%20guide.md))
- [Antenna Mini-Whip (SMD)] ([Components list](./SMD/Components%20list.md), [Assembly guide](./SMD/Assembly%20guide.md))

## How does it work?
Example of working an SDR receiver on antenna Mini-Whip: [Wide-band WebSDR in Enschede, the Netherlands]  
The detailed description of the principle of operation: [Fundamentals of the MiniWhip antenna]

## Basic characteristics of the antenna:

- **Frequency range:** 10 kHz - 30 MHz
- **Power:** DC 5 - 13 V, 100 mA
- **Second order output intercept point:** > + 70 dBm
- **Third order output intercept point:** > + 30 dBm
- **Maximum output power:** in excess of – 15 dBm
- **RF connector:** SMA
- **Feed line:** 50 Ohm coaxial cable

An important point is the **good grounding of the antenna**.

## What was used in the development?
| Source | Description |
| ------ | ------ |
| [PA0RDT Mini-Whip] | The original circuit of the active receiving antenna was used. The PCBs for TH components on platforms EasyEDA and Sprint Layout was implemented. |
| [RA0SMS Mini-Whip] | The original circuit of the active receiving antenna was used. The PCBs for SMD components on platform EasyEDA was implemented. |
| [Fundamentals of the MiniWhip antenna] | Description of the principles of operation of the antenna. A qualitative article with a detailed step-by-step description. |
| [Grounding of MiniWhip and other active whip antennas] | Explanation of the need for a good grounding of the active receiving antenna. |
| [Теоретические основы антенны MiniWhip] | Translation of the two previous articles into Russian.  |

And also some videos about Mini-Whip (Russian language, original names saved):

- [Антенна Mini-Whip. Изготовление активной приёмной антенны на все КВ диапазоны.](https://www.youtube.com/watch?v=wIoeg69Uv6g)
- [Антенна Mini-Whip. Устройство запитки антенны по кабелю.](https://www.youtube.com/watch?v=J28H7zGxNyg)
- [Антенна Mini-Whip. Проверка антенны в полях. Приём сигналов в диапазонах ДВ/СВ/КВ.](https://www.youtube.com/watch?v=SuCMK43mWR0)
- [Антенна Mini-Whip - активная приёмная КВ/СВ/ДВ/СДВ антенна.](https://www.youtube.com/watch?v=mPkObZw7KLg)
- [MiniWhip vs Dipol. Сравнение работы антенны MiniWhip и диполь на диапазон 40м. Радиосвязь.](https://www.youtube.com/watch?v=QXBOGIJIDug&t)

[PA0RDT Mini-Whip]: <http://dl1dbc.net/SAQ/miniwhip.html>
[RA0SMS Mini-Whip]: <http://www.ra0sms.ru/p/the-active-antenna-mini-whip-10-khz-30.html>
[Fundamentals of the MiniWhip antenna]: <http://www.pa3fwm.nl/technotes/tn07.html>
[Grounding of MiniWhip and other active whip antennas]: <http://www.pa3fwm.nl/technotes/tn09d.html>
[Теоретические основы антенны MiniWhip]: <http://www.ra0sms.ru/p/mini-whip.html>
[Wide-band WebSDR in Enschede, the Netherlands]: <http://websdr.ewi.utwente.nl:8901/>
[Antenna Mini-Whip (TH)]: <https://easyeda.com/igor.nikolaevich.96/Antenna_Mini_Whip-d8935f151d3a4221a9a3aacae3acdb65>
[Antenna Mini-Whip (SMD)]: <https://easyeda.com/IgrikXD/Antenna_Mini_Whip_SMD-74e9e6740b814f6c901a811855125754>
