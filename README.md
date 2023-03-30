# terrain_classifier



INTRODUCTION 
THIS PROJECT IS ABOUT ANALYZING DIFFERENT TERRAINS THROUGH CONVOLUTIONAL  NEURAL NETWORK.






IMPORTANCE OF TERRAIN ANALYZING IN  AGRICULTURE 


Farm strategies and economic results seem to be related to entrepreneurial characteristics as much as to natural constraints. The analysis of Pillar I payments and RDP payments for farms located in this mountainous area shows a very complex situation where the strategies implemented by farmers of the strongest farming styles may successfully counteract natural constraints. Besides, in the Authors’ opinion, the analyses performed highlight the importance of spatial analysis as a tool for evaluating how public resources are distributed on a territory, thus providing also useful information on the way this distribution could be improved, e.g. for ensuring a higher level of environmental services[1]




DATASET:- 


                              Dataset included for analyzing different uses Landsat 8 satellite images self collected through https://earthexplorer.usgs.gov/ 


Link to Dataset
                         https://drive.google.com/drive/folders/1qP8ceXoLhBKOV3f32j8c_6u3mkTGEzb-?usp=sharing
Csv file
https://drive.google.com/file/d/1eqWjJWH0x2pXsl75eEwVjzTmASW7Ia5R/view?usp=sharing


This dataset features:-
* 514 images of 3 classes
* Class 1 174 images of Jakhal (Haryana)
* Class 2 189 images of Una (Himachal Pradesh)
* Class 3  151 images of Hathnoda (Rajasthan) 
* Dataset includes images from 1st January 2014 to 3rd May 2022
* Cloud coverage 0% to 50% (min to max)                              






Jakhal
Teh. Tohana Distt Fatehabad Haryana
Terrain :- Plane Land
Coordinates :- 29.801541574024416, 75.79092304463639 


  



Una 
Near iiitu Solah, Distt: Una Himachal Pradesh
Terrain:- Hilly (step up farming is also practiced)
Coordinates:- 31.478261101397706, 76.18897539659974
  





Hathnoda
Teh. Chomu Distt. Jaipur Rajasthan
Terrain:- Desert soil little bit mountainous feature due to Aravali Ranges
Coordinates:- 27.196709242022784, 75.75230524266067  














ANALYZATION


Link to code:- 
https://drive.google.com/file/d/1O5pCxnt5gt-PvPq3WjWs0aax8bbM_3yn/view?usp=sharing
Model Layer Summary 
  





















Graph of Model
  



  



  



  


Loss Plot
  



Accuracy Plot
  



Mean Square Error Plot
  

Mean Absolute Plot
  



Prediction on Test Data
  



Challenges
* The Clouds cover  some regions of the image. Very few images were available with minimum Cloud
* In Each bundle of image only 21 image were usable because formats of images were very different jpg, tiff, json, text not all were convertible 


Conclusion
Knowing the terrain of a farm is very important because different terrain needs very different treatment and by analyzing we strategically grow crops accordingly rather than following surrounding people where it changes drastically. 


This model can predict the terrain of land with the accuracy of 95.35%
References
* Importance of terrain attributes in relation to the spatial distribution of soil properties at the micro scale: a case study
Vivekananthan Kokulan, Olalekan Akinremi, Alan Pierre Moulin, and Darshani Kumaragamage


________________
[1]  From article:-  A spatial analysis of terrain features and farming styles in a disadvantaged area of Tuscany (Mugello): implications for the evaluation and the design of CAP payments
