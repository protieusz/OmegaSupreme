# OmegaSupreme
RP2040 integrated components with integrated PMW3360 trackball sensor &amp; PER56 encoder. The OmegaSupreme is inspired by Ariamelon's Kiwano VIK module and jfedor2's RP2040 and PMW3660 module. The RP2040 pins are fully broken out into either pads or ribbon connections. Design this for convienience and easier to design a keyboard pcb around the OmegaSupreme itself.
Current on print by JLCPCB. Cost is a little bit on the pricey side. Around $89 CAD with shipping included. SK6812 mini e was omitted from the assembly to keep the cost down.  Part of the reason behind being pricey was the use of 3 extended parts i.e. 2 ribbon connectors and 1 JSH connector.  [Gerber](https://github.com/protieusz/OmegaSupreme/tree/main/OmegaSupremeRev4) files will be posted once I tested it. As always print at your "OWN RISK".  I do not offer support. You can feel free to modify it as long as you credit me. Thanks.

# Note: Currently there are 2 versions of Omega Supreme. OmegaSupreme USB C & [Non USB C Version using a C3 Unified USB C Daughterboard card](https://42keebs.eu/shop/parts/unified-daughterboard-c3-c4/?attribute_version=C3)

# Update: Nov 13, 2023: OmegaSupreme USB Version.
Uploaded OmegaSupreme USB Version files. This is my preferred OmegaSupreme version. This version's production file will include a converted json file from EasyEDA to KiCad pcb file.  Please print and assembly at your own risk. I have the PCBs printed and tested so it works. No support will be given. Please follow the license when you modify, use, etc. Thanks.

# Extra BOMs:

[PMW3360 Sensor for trackball](https://www.aliexpress.com/item/1005005355003386.html?spm=a2g0o.order_list.order_list_main.23.31a51802RLpcrc)

[M3 3mm standoffs](https://www.aliexpress.com/item/1005004127890102.html?spm=a2g0o.order_list.order_list_main.60.31a51802RLpcrc)

[M3 8mm screw, buy 6mm just in case](https://www.aliexpress.com/item/1005003733948224.html?spm=a2g0o.order_list.order_list_main.41.31a51802RLpcrc)

[MJ311 or MJ310 steel or ceramic ball bearings for the trackball support holder unit. Steel is slightly noisy and scratchy compared to ceramic. Test it out on your own](https://www.aliexpress.com/item/1005005334424631.html?spm=a2g0o.order_list.order_list_main.66.31a51802RLpcrc)

[RGBs SK6812](https://www.aliexpress.com/item/1005003636607308.html?spm=a2g0o.order_list.order_list_main.5.31a51802RLpcrc)

[Reset & Boot switches](https://www.aliexpress.com/item/4001317902663.html?spm=a2g0o.order_list.order_list_main.240.31a51802RLpcrc)

# OmegaSupreme USB Version Final Pics:

Back Side
![IMG_0315](https://github.com/protieusz/OmegaSupreme/assets/118025702/6a4732ec-f716-4b29-b402-3ed3624cf6a6)

Front & Back Side
![IMG_0314](https://github.com/protieusz/OmegaSupreme/assets/118025702/0b37fde8-24fb-47a5-8771-490657f145b7)

# Update: Nov 12, 2023. 
Currently there are 2 versions of Omega Supreme. The Rev 4 with all the extended connectors and a USB C version that does not require a USB C daughterboard card. I printed both versions and I find that Rev 1 is very annoying since it needs a USB C daughterboard card.  Nowadays, the reliability of PCBA and PCB printing from China factories are not that good if you are doing small 5 PCBs prototyping.  In my experience PCBA can be hit and miss.  Even the USB C daughterboard card can be a miss also.  So in order to eliminate headaches, I use the Omega Supreme USB C version where everything is in one place. Easier to diagnostic if shit goes south.

# REV 4 has 2 copper plated holes for the trackball support mount on the PCB which was missed during REV 1 print.  This PCB picture is REV1 without the corrected copper plated mount holes.

![IMG_0183](https://github.com/protieusz/OmegaSupreme/assets/118025702/997ba5ab-78ea-4e53-a9d4-407494ee46b1)

![IMG_0182](https://github.com/protieusz/OmegaSupreme/assets/118025702/03d9b50e-256e-4b01-878c-b4d6c3d58da9)

![IMG_0191](https://github.com/protieusz/OmegaSupreme/assets/118025702/f333bb38-0cb5-41f5-b209-4b4d953910af)

![IMG_0192](https://github.com/protieusz/OmegaSupreme/assets/118025702/d9a2a37a-a12e-4871-9467-40836265af1f)


# D- and D+ pins are switched so when you attach your usb c daughterboard card, please be caution.

![IMG_0190](https://github.com/protieusz/OmegaSupreme/assets/118025702/96943a52-82a4-4b0c-ab9f-b3ada77fea8c)



# REV 4 render. I don't have funds to print anymore.

![Screenshot 2023-11-12 at 9 12 45 AM](https://github.com/protieusz/OmegaSupreme/assets/118025702/21dfda4e-f5e1-4ab0-b2c0-a94e89a5aad7)

![Screenshot 2023-11-12 at 9 12 57 AM](https://github.com/protieusz/OmegaSupreme/assets/118025702/ae3edb7b-2735-49e8-b767-62c7dba4001c)


# REV 1
![Screenshot_2023-10-11_at_2 01 03_AM](https://github.com/protieusz/OmegaSupreme/assets/118025702/cf3687f4-d5f7-4fb6-9766-32e13981567a)

![Screenshot_2023-10-11_at_1 53 02_AM](https://github.com/protieusz/OmegaSupreme/assets/118025702/fe26ab19-ed4b-4c0f-b58e-1c2aebdde11c)

# REV 3 Forgot to add M3 plated mounts for the trackball support and added RGB DOUT, 5v and GND for the last RGB on the OmegaSupreme

![Screenshot 2023-10-12 at 11 52 33 AM](https://github.com/protieusz/OmegaSupreme/assets/118025702/95dcc4fa-4cf6-428d-a9e4-a9afe95ae956)
![Screenshot 2023-10-12 at 11 53 11 AM](https://github.com/protieusz/OmegaSupreme/assets/118025702/87e0a188-bfa7-4783-a7fc-dd2c92fd397f)
















# License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

You are free to:

Share — copy and redistribute the material in any medium or format

Adapt — remix, transform, and build upon the material

The licensor cannot revoke these freedoms as long as you follow the license terms.
Under the following terms:

Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

NonCommercial — You may not use the material for commercial purposes.

ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

OmegaSupreme by ProtieusKeebs is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1)
