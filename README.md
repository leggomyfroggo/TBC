# TBC
The Tad Boy color is an answer to the question: how small can you make a Game Boy Color while still accepting original cartridges? That's it, that's all you get.

# Attribution
Before getting to the build, it's important to provide attribution to the other project(s) that have in part gone into the Tad Boy Color.
- **[Gekkio/gekkio-kicad-libs](https://github.com/Gekkio/gekkio-kicad-libs)**: The TBC incorporates several of Gekkio's excellent kicad symbols and footprints, including for the CPU, RAM(modified), link port, and cartridge connector. Huge thanks to Gekkio for making these available for others to use!
- Cody Wick for the incredible name suggestion, holy shit

# Disclaimer/Warning/For the love of God, read this
The Tad Boy is not an easy project, nor is it a professional product, and as such there are some things to keep in mind as you consider building one.

Assembly of the Tad Boy requires intermediate-advanced skills in soldering and electronics tinkering, including:
- Desoldering/soldering of large ICs
- Desoldering of through hole parts
- Soldering of small surface mount components, down to 0402
- Soldering of leadless ICs, for example the TPS61202
- Proficiency with a multimeter for troubleshooting and validation
This is in no way a project for beginners, and if you don't have experience with the above, I highly recommend starting smaller -- solder practice kits are cheap and easily available.

Along with needing the requisite skills, there is a very real possibility that you will irreparably damage either your donor Game Boy Color, or the resulting Tad Boy. Even the most skilled among us make mistakes, but it's important to keep in mind your own limits to avoid heartache and sorrow.

I am in no way a professional electrical engineer. All of my skills are self taught, or learned from other members of the modding community. While I have taken common sense measures to ensure that the Frog Boy is functional and safe, I can not guarantee that each and every decision made is correct. Build at your own discretion.

In summary, build at your own risk. I am not liable for any damage or injury caused by your insatiable need to build a Game Boy named after a baby amphibian.

# Bill of Materials(BOM)
Below is the breakdown of all materials you will need to build a Frog Boy Color.

Here is a Digikey cart for most of the components. You will need to source the crystal and volume potentiometer from another vendor.
https://www.digikey.com/en/mylists/list/A9QP98UG8B
## Build Components
- **PCB:** The Tad Boy Color uses a fully custom PCB designed to fit within the custom shell while still using many of the original GBC components. The following board parameters should be used:
  - **Layers:** 4-layer
  - **Thickness:** 1mm
  - **Surface finish:** HASL or ENIG
  - **Color:** Whatever you want
- **Shell:** The shell for the Tad Boy Color is a fully custom design, designed specifically for CNC machining. Order in other materials at your own risk
- **Volume Wheel:** The volume wheel is another custom piece, and is intended to be CNC machined. Resin printing will probably work, but is untested.
  - Step file available in `Accessories` folder so you can get it produced where you wish.
  - [**Order from PCBWay**](https://www.pcbway.com/project/shareproject/Frog_Boy_Color_PCB_29101ba1.html)
- **Cartridge Shield:** Custom piece that fits behind the cartridge, allowing for a large enough opening in the metal shell to machine. Can be FDM printed with supports, or with SLS/MJF nylon.
  - STL files available in `Accessories` folder so you can get it produced where you wish.
- **Light pipe:** An optional light pipe can be added for the indicator LEDs to better diffuse them. An STL for this can be found in `Accessories`. This should be printed with clear filament or resin.
  - STL files available in `Accessories` folder so you can get them produced where you wish.
- **Screws:** The shell is designed to be put together using 7 x M2 3mm machine screws with flat tops. Options:
  - **450pcs M2 M2.5 M3 Screw Kit:** [From Amazon](https://www.amazon.com/gp/product/B07TDHZJLL/)
- **Buttons:** The Tad Boy Color uses buttons from the Game Boy Advance SP, either OEM or aftermarket. You will need a complete set, including the brightness button which is repurposed here as the power button. Some suggested buttons:
  - **FunnyPlaying:** [From RGRS](https://retrogamerepairshop.com/collections/gba-sp-buttons/products/funnyplaying-game-boy-advance-sp-buttons)
  - **RetroCNC(membrane version):** [From RGRS](https://retrogamerepairshop.com/collections/gba-sp-buttons/products/new-game-boy-sp-metal-buttons-by-retrocnc)
- **Membranes:** Similarly, the membranes used are also from the Game Boy Advance SP. Some suggested membranes:
  - **FunnyPlaying:** [From RGRS](https://retrogamerepairshop.com/collections/gba-sp-buttons/products/funnyplaying-game-boy-advance-sp-silicone-pads)
- **Screen:** This project is designed exclusively for the CGS 2.45" LCD kit for the Game Boy Color.
  - [Order from RGRS](https://retrogamerepairshop.com/collections/gbc-displays/products/game-boy-color-2-45-drop-in-backlight-lcd-kit?variant=41377297629356)
  - [Order from AliExpress](https://www.aliexpress.us/item/3256803777135552.html)
- **Screen Lens:** The Tad Boy color makes use of a custom designed screen lens. Technical drawings are available in the `Accessories` folder for you to order your own at a manufacturer of your choice. I will also try to keep them in stock on my website.
- **Batteries:** The Tad Boy Color is designed to make use of Joy Con batteries with minimal effort. The outer shroud must be removed to fit properly.

  NOTE: LiPo batteries can be dangerous if mishandled. NEVER use unprotected cells.
