[PCB-Prototyping-Catalogue](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue)  >>  [Laboratory Automation](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/tree/main/Laboratory%20Automation) >>  [Smart DAQs](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/tree/main/Smart%20DAQ)  >>  [12-bit Smart DAQs](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/tree/main/Smart%20DAQ/12-bit)  >>  Open Science Research 12bit Smart DAQ Device with unique data fingerprint

<br>


[![Telegram](https://img.shields.io/badge/join-telegram-blue.svg?style=for-the-badge)](https://t.me/+W4rVVa0_VLEzYmI0)
 [![WhatsApp](https://img.shields.io/badge/join-whatsapp-green.svg?style=for-the-badge)](https://chat.whatsapp.com/FkNC7u83kuy2QRA5sqjBVg) 
 [![Donate](https://img.shields.io/badge/donate-$-brown.svg?style=for-the-badge)](http://paypal.me/mtpsilva)
 [![Say Thanks](https://img.shields.io/badge/Say%20Thanks-!-yellow.svg?style=for-the-badge)](https://saythanks.io/to/mtpsilva)
![](https://img.shields.io/github/last-commit/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo?style=for-the-badge)
<a href="https://trackgit.com">
<img src="https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/lbp3s4a9mizxmjn8z1lb" alt="trackgit-views" />
</a>
![](https://views.whatilearened.today/views/github/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo.svg)

<br>

<p align="right">
    sponsored by <br>
    <a href="https://be.eurocircuits.com/">
       <img height="50" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/raw/main/media/eurocircuits.png">
    </a>
</p>

<p align="right">
    2nd place <br>
    <a href="https://www.electromaker.io/project/view/how-to-setup-a-smart-daq-to-upload-live-experimental-data-to">
       <img height="50" src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/electromaker_logo.png">
    </a>
</p>

# Open Science Research 12bit Smart DAQ Device with unique data fingerprint
This is the repository for the 12bit Smart DAQ Device with unique data fingerprint able to do experimental data upload to any data repository. This hardware electronics won the 2nd place on the [Electromaker](https://www.electromaker.io/) & [Eurocircuits PCB Design Contest 2022](https://www.electromaker.io/contest/eurocircuits-pcb-2022) for the capability of the proposed firmware code be able to Upload live experimental data to a "data repository", in particular to [Harvard's dataverse](https://dataverse.harvard.edu). Read about htis project on the electromaker website [here](https://www.electromaker.io/project/view/how-to-setup-a-smart-daq-to-upload-live-experimental-data-to).

<p align="center">
  <img height="250" src="https://github.com/aeonSolutions/openScienceResearch-12bit-Smart-DAQ-Device-with-unique-data-fingerprint-/blob/main/media/2nd_place_sdad.png">
</p>

<br>

## Status

![](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/working_green.png) Fully working

<br>

## ToDo List
- PCB bug hunting
- PCB copper track optimizations

see the improvments made on more recent hardare revisions, [here](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/tree/main/Smart%20DAQ/12-bit). 

<br>
<br>

## Dataverse API C library

In paralell is being written a C library to expedite API integration on smart DAQ devices or elsewhere. Follow the link to its repository:

https://github.com/aeonSolutions/OpenScience-Dataverse-API-C-library

<p align="center">
    <img height="150" src="https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/dataverse_r_project.png">
</p>

<br>
<br>

## Testing the hardware

<p align="center">
    <img height="450" src="https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/Design/12bitSmartDAQoctober.jpeg">
</p>

On the photo above the smart DAQ is installed on an acrylic case and screwed with plastic screws to an acrylic base with the same cross section area as the specimen to be tested. 

The acrylic base can be bought [here](https://s.click.aliexpress.com/e/_DEGsZaL). And the acrylic case [here](https://s.click.aliexpress.com/e/_Dmudkjt). 

<br>

<p align="center">
    <img height="650" src="https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/Design/smartAsphaltSample.jpeg">
</p>

On the photo above is one of my many specimens I purposely fabricated to research self-sensing properties of a asphalt mixed with a known content of carbon fibers. This is a 10cm cylinder specimen and on the top is already setup my own design smart #DAQ (get it here on my GitHub ) with ability do upload LIVE experimental data to a #dataverse.


<br>
<br>

### Smart PCB Hardware Specifications
The hardware specifications for the 12bit pcb with dimensions of 23.5x43.5mm are the following:


- QFN 56 Dual Xtensa LX7 Core Processors running up to 240MHz
  -	RISC V ultra-low power co-processor
  - 512Kb RAM (PSRAM max 1 Gb);
  - 16Mb SOIC 8 NOR SPI Flash Memory (max 1Gb);
  - 2.4GHz ISM wireless connectivity;
  - Up to 118 12bit ADC Multiplexed DAQ channels;
- Authentication & Security:
  - SOIC-8 ATSHA204A SHA-256 high-security hardware authentication IC for secure and unique experimental data exchange
- Power management
  - DFN-6 AUR9718 high efficiency step-down 3.3V 1.5A DC converter;
- Onboard sensors:
  - DFN-8 SHT3.x; temperature sensor with a precision of 1.5C;
  - DFN-8 SHT3.x humidity sensor;
  - LGA-14 LSM6DS3 a 6-axis accelerometer and gyroscope;
  - reference voltage sessor calibration wiht temperature and humidity
- 	External connectivity for up to 118 sensors:
  -  1x I2C pin terminal connector (shared)
  -  1x 12 to 16bit (oversampling & digitization) digital terminal connector (shared)
  -  1x 12 to 16bit (oversampling & digitization) analog terminal connector (shared) with manual scale selection ohmeter via jumper pin
  -  12 to 16bit (oversampling & digitization) voltage reference analyser with temperature compensation 


<br>
<br>

 **In real life this smart DAQ is able to:**
- connect to all kinds of 3V to 5V Digital sensors;
- connect to all kinds of sensors compatible with the I2C protocol. (max 118 sensors simultaneously)
- measure voltage in the range of  [0;3.3V]
- measure electrical resistance [0; 10^6] Ohm 
- do temperature and humidity compensation on all measurements 
- has a voltage reference sensor for improved accuracy on ADC measurements  
- has a motion sensor to know if anyone moved a specimen during an experiment

<br>
<br>

## PCB circuit Schematic 
The PCB circuit schematic is available in PDF located in the folder "PCB Schematic"

## PCB design files
The PCB gerber files are located in the folder "gerber" and are ready to order online on any pcb fabrication store. (PCBWay, AllPCB, Eurocircuits, etc)
<br>

<p align="center">
    <img width="45%" src="https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/LDAD%20fron.png">
    <img width="45%" src="https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/LDAD%20back.png">
</p>

<br>
<br>

## Proof of Concept

To test and validate proposed smart DAQ PCB electronics and its firmware as a solution for LIVE experimental data measurements on any test specimen part of a experimental campaign, This PCB electronics is being used to measure a predefined set of variables/parameters to further study several asphalt mixtures with known carbon fiber weight content in the asphalt matrix. Below is a YouTube link to an unedited short video showing one of the experimental setups.

<p align="center">
    <a href="https://youtu.be/ycCJRiwse2M)">
    <img height="350" src="https://github.com/aeonSolutions/openScienceResearch-Smart-DAQ-Device-able-to-Upload-Live-Experimental-Sensor-Data-to-a-Data-Repo/blob/main/Design/youtube.png">
    </a>
</p>

<br />
<br />

## Author

You can get in touch with me on my LinkedIn Profile:

#### Miguel Tomas

[![LinkedIn Link](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect)](https://www.linkedin.com/in/migueltomas/)

<a href="https://stackexchange.com/users/18907312/miguel-silva"><img src="https://stackexchange.com/users/flair/18907312.png" width="208" height="58" alt="profile for Miguel Silva on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for Miguel Silva on Stack Exchange, a network of free, community-driven Q&amp;A sites" /></a>

<a href="https://app.userfeel.com/t/2f6cb1e0" target="_blank"><img src="https://app.userfeel.com/tester/737648/image?.png" width="257" class="no-b-lazy"></a>

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-Miguel--Tomas-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/aeonSolutions)

<br>

**Hire me on Fiverr**

If you like my work here and are looking to design and deploy your own smart device you can [hire me on Fiverr](https://www.fiverr.com/s/GjmPxe). The price starts at $25. 


<br>

### Be supportive of my dedication and work towards technology education and buy me a cup of coffee
The PCB Desgin Files i provide here for anyone to use are free. If you like this Smart Device or use it, please consider buying me a cup of coffee, a slice of pizza or a book to help me study, eat and think new PCB design files.

<p align+"left">
<a href="https://www.buymeacoffee.com/migueltomas">
   <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" data-canonical-src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="35" />
 </a>
<br>
<img src="https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/Designs/bmc_qr.png" height="130">
</p>

<a href="https://stackexchange.com/users/18907312/miguel-silva"><img src="https://stackexchange.com/users/flair/18907312.png" width="208" height="58" alt="profile for Miguel Silva on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for Miguel Silva on Stack Exchange, a network of free, community-driven Q&amp;A sites" /></a>


<br />

### Make a donation on Paypal
Make a donation on paypal and get a TAX refund*.

[![](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/paypal_small.png)](http://paypal.me/mtpsilva)

<br>

### Support all these open hardware projects and become a patreon  
Liked any of my PCB KiCad Designs? Help and Support my open work to all by becomming a LDAD Patreon.
In return I will give a free PCB design in KiCad to all patreon supporters. To learn more go to patreon.com. Link below.

[![](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/blob/main/media/patreon_small.png)](https://www.patreon.com/ldad)

<br />
<br />

______________________________________________________________________________________________________________________________
### License

Before proceeding to download any of AeonLabs software solutions for open-source development and/or PCB hardware electronics development make sure you are choosing the right license for your project. See [AeonLabs Solutions for Open Hardware & Source Development](https://github.com/aeonSolutions/PCB-Prototyping-Catalogue/wiki/AeonLabs-Solutions-for-Open-Hardware-&-Source-Development) for more information. 


______________________________________________________________________________________________________________________________
