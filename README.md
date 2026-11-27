# M465A Reverb Module · Dynamics

Ward-Beck Systems M465A, 1977|10. Wiki page: [M465A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M465A.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 17 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 8 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 3 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 8 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 5 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 12 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Specifications

From the technical data sheet: [1977 - M465A - p4.jpg](MANUALS/1977%20-%20M465A%20-%20p4.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** |  |
| &nbsp;&nbsp;Return | Send: 15 dB ±0.5 dB _ 33 dB ±0.5 dB. |
| **Frequency response** | ±0.25 dB from 20 Hz to 20 kHz. |
| **Noise** |  |
| &nbsp;&nbsp;Return | Send: 80 dB S/N 85 dB S/n (20 Hz:0 20 kHz) below nomina ] operating signa 1 level |
| **Harmonic distortion** | Less nan 0.252 from 20 Hz to 20 kHz 2t +28 dBm output Teve] or Tess Less than 0.16 at 1 kHz at +28 dBm output. |
| **Source impedances** | 600 onm Or Tess, balanced. |
| **Input impedances** | 600 onm, balanced. |
| **Input levels** | -10 dBm nomina ] +30 dBm maximum. |
| **Output impedances** | Return Send: Less than 200 ohm, balanced. 600 ohm, balanced |
| **Load impedances** |  |
| &nbsp;&nbsp;Return | Send 3,000 ohm minimum, each output baLanced 600 ohm, ba anced. |
| &nbsp;&nbsp;Output levels |  |
| &nbsp;&nbsp;Return send | -10 dBm nomina ] +30 dBm maximum _ +8 dBm nomina ] +24 dBm maximum |
| **Phasing** | Input and output terminals designated by numbers are in phase. |

## Circuit description

From [1977 - M465A - p6.jpg](MANUALS/1977%20-%20M465A%20-%20p6.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M465A REVERB MODULE is designed to be used in conjunction with an externa] reverberation chamber The modu ]e is divided into REVERB SEND (RS) and REVERB RETURN RR) section. &quot;:' (Reverb Send as Originating from tne Reverb Send mixing bus the s igna ] enters the module at Pins 1/4 of the modu ]e connector and is fed via the MIXdOWN switch SXi to the insert point 3/€ and 6 / F, The potentiometer Ri/rz serves a$ the RS MASTER Teve] contro] The 4-109C Booster Amplifier raises the combined or mixed $ igna ] to standard Tine Level VU-Meter is connected to the output of the 4-109€ Booster Amplifier 1t is calibrated to read vu with pins 4 / D and/or 5 / E terminated into 600 onm and producing an output Teve] of +8 dBm The MIXDOWN switch Shi maybe used to route the Mixdown section of console to the Revert Send input Switch SW5 a ]Tows to feed tne pre-fade Reverb Send signa ] to the SOLO output at pins 9/K. Reverb Return The Return signa 7 from the reverberation chamber is applied to pins 15/5 From here it continues via the MIXdoWN switch Sh1 and the RR N switch SW7 Fader Insert is provided between pins 13/P and 12/N _ The 4-109 Booster Amplifier recovers the nomina ] 15 dB in-hand Toss incurred by the fader and develops sufficient additiona ] power to drive the PAn and output circuitry The outputs igna ]of the 4-109 amplifier is routed via PAN switch SW3 and PAN contro] R5 through R8 to the LEFT and RIght outputs at pins 16/T and 17/U respectively. In addition, DIRECT output is provided at pins 11/M_ FOLDBAck output is made ava i Tab ]eat pins 8 / J. Switch SW6 facilitates pre-fade or post-fade source selection for the FOLDBACk output Potentiometer R3/ R4 serves as the FOLDBACk level contro] followed by switch SW2

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaXFNaFdMTlV6YXc/view?resourcekey=0-62ppqJ13wMcR910qkSdMEw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaXFNaFdMTlV6YXc&resourcekey=0-62ppqJ13wMcR910qkSdMEw" width="240" alt="1977 - M465A - 465-04-005 - RETPRETURAS CHE OUTPUT NOTE THAT THE SOLO OUTPUT.jpg"></a><br><sub>1977|10 · 465-04-005 - RETPRETURAS CHE OUTPUT NOTE THAT THE SOLO OUTPUT · <a href="MECHANICAL/1977%20-%20M465A%20-%20465-04-005%20-%20RETPRETURAS%20CHE%20OUTPUT%20NOTE%20THAT%20THE%20SOLO%20OUTPUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRTZzWGhsbXhMRFE/view?resourcekey=0-liuNMm2nD2090ldHKKPA3A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRTZzWGhsbXhMRFE&resourcekey=0-liuNMm2nD2090ldHKKPA3A" width="240" alt="1977 - M465A - 4-132-06-002.jpg"></a><br><sub>1977|10 · 4-132-06-002 · <a href="SCHEMATICS/1977%20-%20M465A%20-%204-132-06-002%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRWhkRmRSSENtcGc/view?resourcekey=0-NYvGYp-2-Rch_OzlX12-eA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRWhkRmRSSENtcGc&resourcekey=0-NYvGYp-2-Rch_OzlX12-eA" width="240" alt="1977 - M465A - 465-02-002.jpg"></a><br><sub>1977|10 · 465-02-002 · <a href="SCHEMATICS/1977%20-%20M465A%20-%20465-02-002%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNF9ia1FxODZ4Y1E/view?resourcekey=0-OidaLiHKTZ61W-xqvjbRuQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNF9ia1FxODZ4Y1E&resourcekey=0-OidaLiHKTZ61W-xqvjbRuQ" width="240" alt="1977 - M465A - B 465-01-002 - M465A - REVERB MODULE - FUNCTIONAL DIAGRAM.jpg"></a><br><sub>1977|10 · B 465-01-002 - M465A - REVERB MODULE - FUNCTIONAL DIAGRAM · <a href="SCHEMATICS/1977%20-%20M465A%20-%20B%20465-01-002%20-%20M465A%20-%20REVERB%20MODULE%20-%20FUNCTIONAL%20DIAGRAM%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1ZHThYX8nbie0x6mMzMgCIWUBsX70CRjc/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1ZHThYX8nbie0x6mMzMgCIWUBsX70CRjc" width="240" alt="19xx - M465A - DOC - 465-02-002 - FIMISH REVERB MODULE SCHEMATIC IOLS.png"></a><br><sub>19xx - M465A - DOC - 465-02-002 - FIMISH REVERB MODULE SCHEMATIC IOLS · <a href="SCHEMATICS/19xx%20-%20M465A%20-%20DOC%20-%20465-02-002%20-%20FIMISH%20REVERB%20MODULE%20SCHEMATIC%20IOLS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbFdnVDEzNFpjMDQ/view?resourcekey=0-o0XT2rH5goAcKskRj5ASJg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbFdnVDEzNFpjMDQ&resourcekey=0-o0XT2rH5goAcKskRj5ASJg" width="240" alt="1977 - M465A - p1.jpg"></a><br><sub>1977|10 · p1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLUhNS2R2c1JReVE/view?resourcekey=0-vl25OPVe89Az7ixgTWyH8A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLUhNS2R2c1JReVE&resourcekey=0-vl25OPVe89Az7ixgTWyH8A" width="240" alt="1977 - M465A - p2.jpg"></a><br><sub>1977|10 · p2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSFdkbWlzYlZ6UlE/view?resourcekey=0-oIcZuIZf7uZJhrkwDkhJ6g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSFdkbWlzYlZ6UlE&resourcekey=0-oIcZuIZf7uZJhrkwDkhJ6g" width="240" alt="1977 - M465A - p3.jpg"></a><br><sub>1977|10 · p3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb21LZjRQQlVOdnM/view?resourcekey=0-m9zfkFn3Da4kfVa41gq7Lw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb21LZjRQQlVOdnM&resourcekey=0-m9zfkFn3Da4kfVa41gq7Lw" width="240" alt="1977 - M465A - p4.jpg"></a><br><sub>1977|10 · p4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVmZRQ2Z6OVJWNU0/view?resourcekey=0-JaBO_SsBR1xpF-dNiIzkUg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVmZRQ2Z6OVJWNU0&resourcekey=0-JaBO_SsBR1xpF-dNiIzkUg" width="240" alt="1977 - M465A - p5.jpg"></a><br><sub>1977|10 · p5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYnRRMUl6dGhtQzg/view?resourcekey=0-6qaulYjZJnKDEKKqhG7npA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYnRRMUl6dGhtQzg&resourcekey=0-6qaulYjZJnKDEKKqhG7npA" width="240" alt="1977 - M465A - p6.jpg"></a><br><sub>1977|10 · p6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTThYOUlmOHN1ekU/view?resourcekey=0-zmbhLEduLSz85anrIhbR0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTThYOUlmOHN1ekU&resourcekey=0-zmbhLEduLSz85anrIhbR0Q" width="240" alt="1977 - M465A - p7.jpg"></a><br><sub>1977|10 · p7</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1977 - M465A - 465-02-002.kicad_sch](KICAD/1977%20-%20M465A%20-%20465-02-002.kicad_sch)
- [1977 - M465A - B 465-01-002 - M465A - REVERB MODULE - FUNCTIONAL DIAGRAM.kicad_sch](KICAD/1977%20-%20M465A%20-%20B%20465-01-002%20-%20M465A%20-%20REVERB%20MODULE%20-%20FUNCTIONAL%20DIAGRAM.kicad_sch)
- [19xx - M465A - DOC - 465-02-002 - FIMISH REVERB MODULE SCHEMATIC IOLS.kicad_sch](KICAD/19xx%20-%20M465A%20-%20DOC%20-%20465-02-002%20-%20FIMISH%20REVERB%20MODULE%20SCHEMATIC%20IOLS.kicad_sch)
- [M465A.kicad_sym](KICAD/M465A.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
