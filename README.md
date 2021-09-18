# readme.md
I.	Introduction

The project majorly covers about the design aspects vis a vis hardware aspect of photonics. Photonics is a growing industry with major hardware and software companies like AMD, Intel and some core companies Lightwave logic investing in it. Photonics essentially means to transfer data using photons. It was first used as a means of long-distance communication. Since then, it has weaved its way into biosensors, LIDAR, HPC and an endless list of useful applications 


II.	Project Description and Motivation

In my project I want to focus on replacing metal interconnects with photonics in IC’s specifically for on chip communication. Chipsets use different metal layers or wires which is a function of technology node for data/clock or power distribution. Since complication increases with decreasing tech. node and increasing std cells. More number of metal layers are used for Power/clock/Signal. Additionally, power has been a growing concern since the end of Dennard scaling, which happened somewhere around the 90nm node. There are more transistors per mm², and the wires are thinner, which increases resistance and capacitance and generates heat. Alongside of that, the amount of data that needs to be processed and moved continues to grow, so various processing elements, memories and I/Os are being utilized more intensively than in the past. This makes it harder to move data, to deliver enough power where it is needed, and to dissipate the heat. These metal layers are an excellent way of connection but suffer from several issues most importantly electromigration, power/heat losses, coupling and much more. “The cost of communications using copper is starting to become prohibitive,” says James Pond, director of product management at Ansys[2]. “The challenge with electrical interconnect is that as you go up in performance, or up in reach, your power costs go up. The industry is getting to the point where electrical interconnects will consume your power budget in its entirety, and that’s going to happen within a few years.” Until recently, this was prohibited by cost. “It gets to be really interesting when the cost of photonics crosses below the cost of copper,” says Gilles Lamant, distinguished engineer at Cadence[2]. 


III.	Literature Review 

Photonic Integrated SoC are very popular among the research community. Immense amount of work has been done this area. One such being, in [1]. In this paper, a broadband, high directivity (>150), low loss and reconfigurable silicon photonics nanoantenna was used to enable on-chip radiation control. Using nanoantenna’s to develop wireless (unguided) silicon photonic devices, which considerably enhance the range of achievable integrated photonic functionalities. A 160 Gbit s−1 data transmission over mm-scale wireless interconnects, a compact low-crosstalk 12-port crossing and electrically reconfigurable pathways via optical beam steering was used. Moreover, they realized a flow micro-cytometer for particle characterization demonstrating the smart system integration potential for lab-on-chip devices.


IV.	Open-Source Software

There are open-source waveguide simulating software like HSFSS or Symphony to design waveguides at nanoscale levels. Cadence Virtuoso could also be used to simulate and study metal interconnects behavior.

[1] C. García-Meca, S. Lechago, A. Brimont, A. Griol, S. Mas, L. Sánchez, L. Bellieres, N. S. Losilla, and J. Martí, “On-chip wireless silicon photonics: From reconfigurable interconnects to lab-on-chip devices,” Nature News, 29-Mar-2017. [Online]. Available: https://www.nature.com/articles/lsa201753.


[2] “Chipmakers getting serious about integrated photonics,” Semiconductor Engineering, 12-Jul-2021. [Online]. Available: https://semiengineering.com/chipmakers-getting-serious-about-integrated-photonics/.


