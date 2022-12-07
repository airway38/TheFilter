<h2>THE FILTER</h2>

![filter model](https://user-images.githubusercontent.com/40711977/205870094-7e7c07b6-8fc4-48cc-be1a-14624c461d2c.PNG)
<h2>ABOUT</h2>

THE FILTER is a custom mod of my own design. I was intially inspired to embark on this project after my Nevermore melted. It is a hybrid of Andrew ellis's bed fan's and the Nevermore in a completly custom housing. It features 3 5015 blower fans (only works with Fysetc bed hole spacing) and a large capacity for pellet charcoal in a two piece model with a bracket using a minimal amount of supplies. It is mounted from the front to DRASTICALLY improve heating of your printer chamber by blowing air over the bottom of the bed. I also wanted it to be easily removable so it features a optional magnetic quick disconnect using POGO connectors which is what I believe to be a first for a mod of this kind. This connector makes removal for PLA prints and maintenance easy. It is tested extensivly with over 40 hours of runtime and 50 connects and disconnects. Its high airflow and compact design makes it melt and warp resistant. Using 3d printed spacers it is also thermally isolated from the printer frame. 



<h2>Testing</h2>

Time the printer took to reach 40c
* Stock VORON 2.4 350mm - 55 minutes
* Nevermore VORON 2.4 350mm - 40 minutes
* THE FILTER VORON 2.4 350mm - 12 minutes

Quick statistics graph (courtesy of Discord user akinferno#3062)

Testing heat up time to 40°C

![image](https://user-images.githubusercontent.com/40711977/205898660-43da5bac-684c-4fba-b842-941ae9fd0de9.png)



<h2>Parts Required</h2>

* (3) 5015 fans 
* (1) optional magnetic pogo power connector from digikey https://www.digikey.com/en/products/detail/adam-tech/PHR-C4777-02-FVP-800/9832016
* (1) optional power cord for pogo connector from digikey https://www.digikey.com/en/products/detail/adam-tech/CA-ST2-PHR-198-M/9832013 
* (1) jst-XH 2 pin connector with metal pin
* (1) 2 pin microfit molxex if not using the POGO connector
* (1) MISC heatshrink and solder (best) or Solder heatshrink tubing (better) or buttsplices (ok)

<h2>Cheaper alternative pogo connector and cord from ali-express</h2>

* (1) https://www.aliexpress.us/item/3256803531038291.html?spm=a2g0o.productlist.0.0.65b231cdL4B9KI&algo_pvid=d942f52a-126a-4209-835e-aec6d4ec4877&algo_exp_id=d942f52a-126a-4209-835e-aec6d4ec4877-0&pdp_ext_f=%7B%22sku_id%22%3A%2212000026915987305%22%7D&pdp_npi=2%40dis%21USD%213.72%212.98%21%21%21%21%21%402101d8b516703451694166001e84e0%2112000026915987305%21sea&curPageLogUid=LSwHGmyIJeaz

note this connector is untested but identical the digikey parts  



<h2>Installation</h2>

1) Print the Models
2) Remove top covers of 5015 fans (Required)
3) Run Wires neatly and solder fans in parallel or use Solder heatshrink tubing
4) Remove bed from frame and mount Bracket to frame in the appropriate position (see pictures)
5) install spacers that prevent contact with aluminum extrusion

If Using Adam Tech connector's:
1) Print Soldering Jig (connector is magnetic and is very hard to solder with out being secured)
* center pin is positive 
* side pins are GND
* place connector into jig and tape down to more easily attach wires
2) Cut USB connector off it has two 24awg one red wire and one black. the sheath needs to be cut back and the wires stripped to prepare for crimping
3) Crimp on jst-XH and press the end of the connector into mounting bracket use super glue if the connector feels to loose
4) Connect to spider and adjust your config ( I encourage the filter to be set up using andrew ellis bed fan macro)





<h2>Sample config (pulled from andrew ellis github)</h2>

https://github.com/VoronDesign/VoronUsers/blob/master/printer_mods/Ellis/Bed_Fans/Klipper_Macros/bedfans.cfg





<h2> Prototype Install Picture's (Current CAD and models have minor cosmetic changes compared to these picture)</h2>

![IMG_0457](https://user-images.githubusercontent.com/40711977/205880160-19b53a0d-086c-4124-b755-1bd57a20bb04.JPG)
![IMG_0444](https://user-images.githubusercontent.com/40711977/205880165-3ba21d84-3fa3-4597-8a1a-d5fb0c207cd1.JPG)
![IMG_0460](https://user-images.githubusercontent.com/40711977/205880170-c08e3687-5b1d-4777-b2e4-76c74d392f3e.JPG)
![IMG_0467](https://user-images.githubusercontent.com/40711977/205882261-f7613fc7-078c-4e10-b99c-e62a4e7fb66f.JPG)


<h2> Final Version Install Picture's (courtesy of Discord user akinferno#3062)</h2>

![20221205_220519](https://user-images.githubusercontent.com/40711977/205881109-4aa58c7d-35be-4ae4-be15-2baa56751e13.jpg)
![20221206_010521](https://user-images.githubusercontent.com/40711977/205881644-587e96b5-8cd0-4ca9-aa05-1afefbcfe172.jpg)
![20221206_010509](https://user-images.githubusercontent.com/40711977/205881742-36108412-69ed-4d52-9f34-2b4bd104d77b.jpg)
![20221206_010500](https://user-images.githubusercontent.com/40711977/205881845-884542e1-b4b2-4eb9-b5bb-b9ea2c7275e4.jpg)

<h2> CAD Picture's</h2>

![bottom view](https://user-images.githubusercontent.com/40711977/205851851-4863b4ee-53e6-448c-a159-26f771029f4b.PNG)

![filter model](https://user-images.githubusercontent.com/40711977/205851854-b87cc02e-d695-470d-bf33-a2b171963b07.PNG)

![inside view](https://user-images.githubusercontent.com/40711977/205851856-7284b339-7efa-431a-9686-6a903136f9c5.PNG)

![top view](https://user-images.githubusercontent.com/40711977/205851858-27d315b3-28c8-4e19-901a-dce9d5ad0bdd.PNG)


<h2>My Discord Username</h2>
nate#5815

<h2>Credits</h2>

Discord user akinferno#3062)

Andrew ellis for inspiration and for a macro that I couldnt make myself https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Ellis/Bed_Fans

The nevermore (click the link to learn about VOC's) https://github.com/nevermore3d/Nevermore_Micro