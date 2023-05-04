# Transliteration
Transliteration is the process of converting text from one script to another script, while keeping the phonetic meaning of the words intact. In the context of machine learning, transliteration is a task where given a word in one script, the goal is to predict its pronunciation in another script.

| DATASET | LINK |
| ------------- | ------------- |
| FIRE 2013 | [link](http://cse.iitkgp.ac.in/resgrp/cnerg/qa/fire13translit/index.html) |

In this project English is transliterated to Hindi

Example of Transliteration


![Example](https://user-images.githubusercontent.com/86826802/236172512-79982ad7-46c0-48e1-8f26-2d44fffc78dc.png)

## Result



| Model  | Link | Iteration | Loss | Accuracy |
| ------------- | ------------- | ------------- | ------------- |------------- |
| Model 1  | [Link](https://github.com/vidiptvashist/Transliteration/blob/main/model/model1__lr_0.01_nb%3D100_bs%3D64_e%3D256.pt)   | 100 | 0.21607725322246552 | 60.39542043070043 |
| Model 2  | [Link](https://github.com/vidiptvashist/Transliteration/blob/main/model/model1__lr_0.01_nb%3D200_bs%3D64_e%3D256.pt)   | 200 | 0.14442181587219238 | 77.11415632218576 |
| Model 3  | [Link](https://github.com/vidiptvashist/Transliteration/blob/main/model/model1__lr_0.01_nb%3D300_bs%3D64_e%3D256.pt)   | 300 | 0.12240982055664062 | 79.13928839476316 |
| Model 4  | [Link](https://github.com/vidiptvashist/Transliteration/blob/main/model/model1__lr_0.01_nb%3D500_bs%3D64_e%3D256.pt)   | 500 | 0.09494910389184952 | 80.78228581698959 |
| Model 5  | [Link](https://github.com/vidiptvashist/Transliteration/blob/main/model/model1__lr_0.01_nb%3D100_bs%3D128_e%3D256.pt)   | 100 | 0.10732661187648773 | 71.24015788947327 |
| Model 6  | [Link](https://github.com/vidiptvashist/Transliteration/blob/main/model/model1__lr_0.01_nb%3D200_bs%3D128_e%3D256.pt)   | 200 | 0.06515125930309296 | 80.07900605723651 |

## Graphs


1 [Iteration 99 Loss 0.21607725322246552](https://user-images.githubusercontent.com/86826802/236028741-112b98d4-f350-49d9-9625-43af0d0c7ada.png) 


2 [Iteration 199 Loss 0.14442181587219238](https://user-images.githubusercontent.com/86826802/236167712-7834ecfb-ce9e-4ca8-a53c-5b88f7819695.png)

3 [Iteration 299 Loss 0.12240982055664062](https://user-images.githubusercontent.com/86826802/236178193-5acc4ce7-c213-4d92-834e-a81cc3092505.png)

4 [Iteration 499 Loss 0.09494910389184952](https://user-images.githubusercontent.com/86826802/236190593-f5dc62cd-683e-42e5-9da9-0eaeae8b5209.png)

5 [Iteration 99 Loss 0.10732661187648773](https://user-images.githubusercontent.com/86826802/236207579-83b6772c-51b6-43fe-8b57-0ac6f1034d56.png)

6 [Iteration 99 Loss 0.06515125930309296](https://user-images.githubusercontent.com/86826802/236248584-856da06c-c188-4ee4-9072-40f518a0f9ce.png)



