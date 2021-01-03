# SirayaTech_Blu_ExposureGuide
Exposure guide for SirayaTech Blu on a Creality LD-002H

Since there has not been any guide written for this particular resin and printer pair, i may as well do one myself.

Printer: Creality LD-002H MSLA
Material: Siraya Tech Blu
Test temperature: 25-28C

TL;DR Conclusions and Reccomendations

Exposure time: 3.0-3.5s
Bottom Exposure time: 15-17.5s

Bulge Busting Method: Reduction + Pixel Dimming
BB Settings: -10px reduction | 40% dimming

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Tests Conducted on 3/1/2021
Test 1: Resin Exposure Test V2 (https://github.com/Photonsters/Resin-exposure-finder-v2/releases?fbclid=IwAR3hrCXqKMlwHnAaABLnkbuglFiruxyTAbbeCAbrL6l95PZbqFXgJUWzCpY)
Test strip results: (See Exposure Test Images)
Failed to print at 0.5-1.0s
Smaller details (<0.5mm) Failed at 1.5-2s

Exposure Time: 3.5-4.0s
Bottom Exposure Time: 17.5-20s

Due to the transparent/Translucent nature of the material, it was not easy to visually compare the test strip results.
Having used this resin at 2s exposure before and having some success, it seems that the multiple pulse exposure of this test also results in more failures as compared to a constant exposure (eg 4x0.5s vs 2s)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Test 2: Nerdtronic BulgeBuster (Reducing/Compensating for elephants foot) https://nerdtronic3d.com/bulgebuster/
I performed two sets of tests, at 3.0s and 4.0s exposure times|12s and 20s bottom exposure times
The LD-002H supports pixel dimming, so that feature will be tested as well as it provides better results as compared to only pixel reduction.

Each test set covers a. Bottom layer pixel reduction(0-7px) | b. Reduction & Dimming (10px 0-70%)

Test 2.1(3s exposure time)
2.1.a: E.Foot was eliminated at 4 pixels, however fine details such as sharp corners were not flush with control areas, reduction of 0.2mm compared to control
2.1.b: E.Foot eliminated at 40% with near perfect fine detail preservation

test 2.2(4s Exposure time)
2.2.a: E.Foot eliminated at 5px, significant loss of fine detail(corners turning into curves)
2.2.b: E.Foot eliminated at 50%, corners again slightly rounded
