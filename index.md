# <center> Cross-modal face and voice style transfer</center>
<center>Naoya Takahashi, Mayank K. Singh, Yuki Mitsufuji</center>

# Introduction
This page provides the audio and image samples shown in the paper as well as some additional samples. All results on the audio-guided image translation, image-guided voice conversion, and latent-guided face & voice generation are obtained by the single proposed model. 
<BR><BR>

# Audio-guided image translation
The audio samples for the results shown in Fig.1a in the paper.

<table align="center"  style="text-align: center;">
  <thead>
    <tr>
      <th>Source</th>
      <th style="text-align: center;"><img src="media/A2I/src/069067.jpg"></th>
      <th style="text-align: center;"><img src="media/A2I/src/051340.jpg"></th>
      <th style="text-align: center;"><img src="media/A2I/src/006930.jpg"></th>
      <th style="text-align: center;"><img src="media/A2I/src/005735.jpg"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Reference</td>
      <td style="text-align: center;"><img src="media/A2I/ref/dk.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/A2I/ref/dk.wav"></audio></td>
      <td style="text-align: center;"><img src="media/A2I/ref/p302.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/A2I/ref/p302.wav"></audio></td>
      <td style="text-align: center;"><img src="media/A2I/ref/eh.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/A2I/ref/eh.wav"></audio></td>
      <td style="text-align: center;"><img src="media/A2I/ref/p300.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/A2I/ref/p300.wav"></audio></td>
    </tr>
    <tr>
      <td>Output</td>
      <td style="text-align: center;"><img src="media/A2I/out/SRC_069067_TRG_dk.jpg"></td>
      <td style="text-align: center;"><img src="media/A2I/out/SRC_051340_TRG_p302.jpg"></td>
      <td style="text-align: center;"><img src="media/A2I/out/SRC_006930_TRG_eh.jpg"></td>
      <td style="text-align: center;"><img src="media/A2I/out/SRC_005735_TRG_p300.jpg"></td>
    </tr>
  </tbody>
</table>
<BR><BR>  

Additional results shown in the supplimental material.
<table align="center"  style="text-align: center;">
  <thead>
    <tr>
      <th>Source</th>
      <th style="text-align: center;"><img src="media/A2I/src/055986.jpg"></th>
      <th style="text-align: center;"><img src="media/A2I/src/172559.jpg"></th>
      <th style="text-align: center;"><img src="media/A2I/src/012734.jpg"></th>
      <th style="text-align: center;"><img src="media/A2I/src/191300.jpg"></th>
    </tr>
  </thead>
  <tbody>
      <tr>
      <td>Reference</td>
      <td style="text-align: center;"><img src="media/A2I/ref/p295.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/A2I/ref/p295.wav"></audio></td>
      <td style="text-align: center;"><img src="media/A2I/ref/eh.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/A2I/ref/eh.wav"></audio></td>
      <td style="text-align: center;"><img src="media/A2I/ref/p259.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/A2I/ref/p259.wav"></audio></td>
      <td style="text-align: center;"><img src="media/A2I/ref/5cQoGNEcc5Q.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/A2I/ref/5cQoGNEcc5Q.wav"></audio></td>
      </tr>
      <tr>
      <td>Output</td>
      <td style="text-align: center;"><img src="media/A2I/out/SRC_055986_TRG_p295.jpg"></td>
      <td style="text-align: center;"><img src="media/A2I/out/SRC_172559_TRG_eh.jpg"></td>
      <td style="text-align: center;"><img src="media/A2I/out/SRC_012734_TRG_p259.jpg"></td>
      <td style="text-align: center;"><img src="media/A2I/out/SRC_191300_TRG_5cQoGNEcc5Q.jpg"></td>
    </tr>
  </tbody>
</table>
<BR><BR>  
    
# Image-guided voice conversion
The outputs are produced by converting the source voice using reference images. The images are from the image-only dataset (CelebA-HQ), hence, there is no ground truth voice. The first sample is the results shown in Fig.1b in the paper and rest are present in the supplemental material. 

<table align="center"  style="text-align: center;">
  <thead>
    <tr>
      <th>Source</th>
      <th style="text-align: center;"><img src="media/I2A/p271_79.jpg" width="128" height="128"><BR><audio  controls="" style="width:150px;" preload="auto">
        <source src="media/I2A/p271_79.wav"></audio></th>
      <th style="text-align: center;"></th>
      <th style="text-align: center;"></th>
      <th style="text-align: center;"></th>
    </tr>
  </thead>
  <tbody>
      <tr>
      <td>Reference</td>
      <td style="text-align: center;"><img src="media/I2A/female_195650.jpg" width="128" height="128"></td>
      <td style="text-align: center;"><img src="media/I2A/female_064119.jpg" width="128" height="128"></td>
      <td style="text-align: center;"><img src="media/I2A/male_116032.jpg" width="128" height="128"></td>
      <td style="text-align: center;"><img src="media/I2A/male_156498.jpg" width="128" height="128"></td>
      </tr>
      <tr>
      <td>Output</td>
      <td style="text-align: center;">
        <img src="media/I2A/CMST_SRC_p271_79_TRG_female_195650.jpg.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/I2A/SRC_p271_79_TRG_female_195650.jpg.wav"></audio></td>
      <td style="text-align: center;">
        <img src="media/I2A/SRC_p271_79_TRG_female_064119.jpg.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/I2A/SRC_p271_79_TRG_female_064119.jpg.wav"></audio></td>
      <td style="text-align: center;">
        <img src="media/I2A/SRC_p271_79_TRG_male_116032.jpg.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/I2A/SRC_p271_79_TRG_male_116032.jpg.wav"></audio></td>
      <td style="text-align: center;">
        <img src="media/I2A/SRC_p271_79_TRG_male_156498.jpg.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/I2A/SRC_p271_79_TRG_male_156498.jpg.wav"></audio></td>
    </tr>
  </tbody>
</table>
<BR><BR>  

<table align="center"  style="text-align: center;">
  <thead>
    <tr>
      <th>Source</th>
      <th style="text-align: center;"><img src="media/I2A/p228_1.jpg" width="128" height="128"><BR><audio  controls="" style="width:150px;" preload="auto">
        <source src="media/I2A/p228_1.wav"></audio></th>
      <th style="text-align: center;"></th>
      <th style="text-align: center;"></th>
      <th style="text-align: center;"></th>
    </tr>
  </thead>
  <tbody>
      <tr>
      <td>Reference</td>
      <td style="text-align: center;"><img src="media/I2A/female_031796.jpg" width="128" height="128"></td>
      <td style="text-align: center;"><img src="media/I2A/female_058881.jpg" width="128" height="128"></td>
      <td style="text-align: center;"><img src="media/I2A/male_047763.jpg" width="128" height="128"></td>
      <td style="text-align: center;"><img src="media/I2A/male_083510.jpg" width="128" height="128"></td>
      </tr>
      <tr>
      <td>Output</td>
      <td style="text-align: center;">
        <img src="media/I2A/SRC_p228_1_TRG_female_031796.jpg.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/I2A/SRC_p228_1_TRG_female_031796.jpg.wav"></audio></td>
      <td style="text-align: center;">
        <img src="media/I2A/SRC_p228_1_TRG_female_058881.jpg.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/I2A/SRC_p228_1_TRG_female_058881.jpg.wav"></audio></td>
      <td style="text-align: center;">
        <img src="media/I2A/SRC_p228_1_TRG_male_047763.jpg.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/I2A/SRC_p228_1_TRG_male_047763.jpg.wav"></audio></td>
      <td style="text-align: center;">
        <img src="media/I2A/SRC_p228_1_TRG_male_083510.jpg.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/I2A/SRC_p228_1_TRG_male_083510.jpg.wav"></audio></td>
    </tr>
  </tbody>
</table>
<BR><BR> 

# Latent-guided face and voice generation
We sample four latent codes, compute style vectors from the codes using the mapping network, and gnerate faces and voices from two source face and voices using the style vectors. The samples are the results shown in Fig.6 in the paper. 

<table align="center"  style="text-align: center;">
  <thead>
    <tr>
      <th>Source</th>
      <th style="text-align: center;">Output 1</th>
      <th style="text-align: center;">Output 2</th>
      <th style="text-align: center;">Output 3</th>
      <th style="text-align: center;">Output 4</th>
    </tr>
  </thead>
  <tbody>
      <tr>
      <td style="text-align: center;"><img src="media/L2AI/016387.jpg" width="128" height="128"></td>
      <td style="text-align: center;"><img src="media/L2AI/SRC_016387_Domain0_3.jpg" width="128" height="128"></td>
      <td style="text-align: center;"><img src="media/L2AI/SRC_016387_Domain1_8.jpg" width="128" height="128"></td>
      <td style="text-align: center;"><img src="media/L2AI/SRC_016387_Domain0_6.jpg" width="128" height="128"></td>
      <td style="text-align: center;"><img src="media/L2AI/SRC_016387_Domain1_9.jpg" width="128" height="128"></td> 
      </tr>
      <tr>
      <td><img src="media/I2A/p271_79.jpg" width="128" height="128"><BR><audio  controls="" style="width:150px;" preload="auto">
        <source src="media/I2A/p271_79.wav"></audio></td>
      <td style="text-align: center;">
        <img src="media/L2AI/SRC_p271_79_Domain0_3.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/L2AI/SRC_p271_79_Domain0_3.wav"></audio></td>
      <td style="text-align: center;">
        <img src="media/L2AI/SRC_p271_79_Domain1_8.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/L2AI/SRC_p271_79_Domain1_8.wav"></audio></td>
      <td style="text-align: center;">
        <img src="media/L2AI/SRC_p271_79_Domain0_6.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/L2AI/SRC_p271_79_Domain0_6.wav"></audio></td>
      <td style="text-align: center;">
        <img src="media/L2AI/SRC_p271_79_Domain1_9.jpg" width="128" height="128"><BR>
        <audio  controls="" style="width:150px;" preload="auto">
        <source src="media/L2AI/SRC_p271_79_Domain1_9.wav"></audio></td>
    </tr>
    <tr>
    <td style="text-align: center;"><img src="media/L2AI/039913.jpg" width="128" height="128"></td>
    <td style="text-align: center;"><img src="media/L2AI/SRC_039913_Domain0_3.jpg" width="128" height="128"></td>
    <td style="text-align: center;"><img src="media/L2AI/SRC_039913_Domain1_8.jpg" width="128" height="128"></td>
    <td style="text-align: center;"><img src="media/L2AI/SRC_039913_Domain0_6.jpg" width="128" height="128"></td>
    <td style="text-align: center;"><img src="media/L2AI/SRC_039913_Domain1_9.jpg" width="128" height="128"></td> 
    </tr>
    <tr>
    <td><img src="media/I2A/p228_1.jpg" width="128" height="128"><BR><audio  controls="" style="width:150px;" preload="auto">
    <source src="media/I2A/p228_1.wav"></audio></td>
    <td style="text-align: center;">
    <img src="media/L2AI/SRC_p228_1_Domain0_3.jpg" width="128" height="128"><BR>
    <audio  controls="" style="width:150px;" preload="auto">
    <source src="media/L2AI/SRC_p228_1_Domain0_3.wav"></audio></td>
    <td style="text-align: center;">
    <img src="media/L2AI/SRC_p228_1_Domain1_8.jpg" width="128" height="128"><BR>
    <audio  controls="" style="width:150px;" preload="auto">
    <source src="media/L2AI/SRC_p228_1_Domain1_8.wav"></audio></td>
    <td style="text-align: center;">
    <img src="media/L2AI/SRC_p228_1_Domain0_6.jpg" width="128" height="128"><BR>
    <audio  controls="" style="width:150px;" preload="auto">
    <source src="media/L2AI/SRC_p228_1_Domain0_6.wav"></audio></td>
    <td style="text-align: center;">
    <img src="media/L2AI/SRC_p228_1_Domain1_9.jpg" width="128" height="128"><BR>
    <audio  controls="" style="width:150px;" preload="auto">
    <source src="media/L2AI/SRC_p228_1_Domain1_9.wav"></audio></td>
</tr>    
  </tbody>
</table>
<BR><BR>
  
# Results on out-of-domain samples
To test the generalizability of the model to out-of-domain samples, we use FFHQ dataset, which is not included during training, for source images of audio-guided image translation. For audio, we use VCTK, LRS3, Wav2Lip, as well as VoxCeleb2, which is unseen during training.  

<img src="media/A2I/out/ffhq_female.png" width="600" >
<BR><BR>  
<img src="media/A2I/out/ffhq_male.png" width="600" >
