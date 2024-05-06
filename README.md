<div align="center">
<h1>InstantID-Rome</h1>

Supreme [**InstantID**](https://github.com/InstantID/InstantID). Indulge your slight fantasy about Identity-Preserving Generation. 

</div>

When in Rome, do as the Romans do.


<div align="center">
<img src="./data/res_yangmi.jpg" width = "400" />
</div>


# Characteristic

* 💃  [Better Body Composition](#better-body-composition).

* 🎨  [More Comfortable Facial Saturation](#more-comfortable-facial-saturation).

* ✏️  [Stronger Editability](#stronger-editability).

* 📐  [More Stable Layout](#more-stable-layout).

* 🇺🇳  [Higher Consistency](#higher-consistency).

* 📷  [More Realistic](#more-realistic).

* 🤔  [Larger Range of Image Scale](#larger-range-of-image-scale)

Unless otherwise specified, the base model is [YamerMIX-V8](https://civitai.com/models/84040?modelVersionId=196039).


## Better Body Composition
Face key points is Not necessary in InstantID-Rome. InstantID-Rome can fully comply with the body composition of raw T2I.

| <img src="./data/musk_resize.jpeg" width = "60" /> | Face <br> Landmark | Style |
|:-----:|:-----:|:-----:|
InstantID | <img src="./data/bad_face_kps.png" width = "80" /> | <img src="./data/betterbodycomposition_iid_1.jpg" width = "140" />  <img src="./data/betterbodycomposition_iid_2.jpg" width = "140" />  <img src="./data/betterbodycomposition_iid_3.jpg" width = "140" />  <img src="./data/betterbodycomposition_iid_4.jpg" width = "140" /> |
InstantID- <br>  Rome | self- <br> adaptive | <img src="./data/betterbodycomposition_iidrm_1.jpg" width = "140" />  <img src="./data/betterbodycomposition_iidrm_2.jpg" width = "140" />  <img src="./data/betterbodycomposition_iidrm_3.jpg" width = "140" />  <img src="./data/betterbodycomposition_iidrm_4.jpg" width = "140" /> |




## More Comfortable Facial Saturation
InstantID sometimes increases the saturation of the facial image to an uncomfortable level. This issue is particularly noticeable in the realistic style.  InstantID-Rome has significantly resolved this issue. 


| <img src="./data/yann-lecun_resize.jpg" width = "60" /> | self- <br> adaptive | Style |
|:-----:|:-----:|:-----:|
InstantID | ❌ | <img src="./data/morecomfortablefacialsaturation_iid_1.jpg" width = "140" /> <img src="./data/morecomfortablefacialsaturation_iid_2.jpg" width = "140" /> <img src="./data/morecomfortablefacialsaturation_iid_3.jpg" width = "140" /> <img src="./data/morecomfortablefacialsaturation_iid_4.jpg" width = "140" /> |
InstantID- <br>  Rome | ✅ | <img src="./data/morecomfortablefacialsaturation_iidrm_1.jpg" width = "140" /> <img src="./data/morecomfortablefacialsaturation_iidrm_2.jpg" width = "140" /> <img src="./data/morecomfortablefacialsaturation_iidrm_3.jpg" width = "140" /> <img src="./data/morecomfortablefacialsaturation_iidrm_4.jpg" width = "140" /> |


## Stronger Editability
While InstantID is unable to achieve this, InstantID-Rome is capable of doing so.
| ID | 'sunglasses' | 'girl' | 'young' | 'old' | 
|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|
<img src="./data/my.png" width = "100" /> | <img src="./data/my_sunglasses.jpg" width = "150" /> | <img src="./data/my_girl.jpg" width = "150" /> | <img src="./data/my_young.jpg" width = "150" /> | <img src="./data/my_old.jpg" width = "150" />


| 'a prince wearing headphones and a red and glod armor, reading a book and sitting on bench in front of Eiffel Tower'  |
|:-------------------------:|
<img src="./data/my_longprompt_1.jpg" width = "390" />  <img src="./data/my_longprompt_2.jpg" width = "390" /> 


## More Stable Layout
While InstantID is unable to achieve this, InstantID-Rome is capable of doing so.
|| Style |
|:-------------------------:|:-------------------------:|
T2I w/o ID |<img src="./data/t2i_1_raw.jpg" width = "108" /> <img src="./data/t2i_2_raw.jpg" width = "108" /> <img src="./data/t2i_3_raw.jpg" width = "108" /> <img src="./data/t2i_4_raw.jpg" width = "108" /> <img src="./data/t2i_5_raw.jpg" width = "108" /> <img src="./data/t2i_6_raw.jpg" width = "108" /> |
<img src="./data/Djy.png" width = "100" /> | <img src="./data/t2i_1_id.jpg" width = "108" /> <img src="./data/t2i_2_id.jpg" width = "108" /> <img src="./data/t2i_3_id.jpg" width = "108" /> <img src="./data/t2i_4_id.jpg" width = "108" /> <img src="./data/t2i_5_id.jpg" width = "108" /> <img src="./data/t2i_6_id.jpg" width = "108" /> |


## Higher Consistency
While InstantID is unable to achieve this, InstantID-Rome is capable of doing so.
| sunglasses | cap |
|:-------------------------:|:-------------------------:|
<img src="./data/fe342e172f4f79f0f18e0cfecbf86de27a6058e329240b4bfdb73fb5.jpg" width = "425" /> | <img src="./data/2b008e52c4a66093b4aa7697a38e7ab6b21a898dcb43dd75a088d6a6.jpg" width = "425" />
| **mask** | **skin** |
<img src="./data/829d06193e5334e1036e1dd5a41b510848ef52225c49b2c7463e7215.jpg" width = "425" /> | <img src="./data/e1f454de3bfb8ece436cb4084837c0f8e1287b111f2819dd37ca9f92.jpg" width = "425" />



## More Realistic
While InstantID is unable to achieve this, InstantID-Rome is capable of doing so.

base model: [RealVisXL V4.0](https://civitai.com/models/139562/realvisxl-v40?modelVersionId=344487)
|ID| Realistic Style  |
|:-------------------------:|:-------------------------:|
<img src="./data/ym_2.jpg" width = "100" /> | <img src="./data/realistic_ym_1.jpg" width = "130" /> <img src="./data/realistic_ym_2.jpg" width = "130" /> <img src="./data/realistic_ym_3.jpg" width = "130" /> <img src="./data/realistic_ym_4.jpg" width = "130" />  <img src="./data/realistic_ym_5.jpg" width = "130" /> 
<img src="./data/Djy.png" width = "100" /> | <img src="./data/realistic_Djy_1.jpg" width = "130" /> <img src="./data/realistic_Djy_2.jpg" width = "130" /> <img src="./data/realistic_Djy_3_new.jpg" width = "130" /> <img src="./data/realistic_Djy_4.jpg" width = "130" /> <img src="./data/realistic_Djy_5.jpg" width = "130" />


## Larger Range of Image Scale
While InstantID is unable to achieve this, InstantID-Rome is capable of doing so.

base model: [RealVisXL V4.0](https://civitai.com/models/139562/realvisxl-v40?modelVersionId=344487)
|ID|  Different Image Scale |
|:-------------------------:|:-------------------------:|
<img src="./data/Johnson.png" width = "200" /> | <img src="./data/largerange_Johnson_3.jpg" width = "660" /> <img src="./data/largerange_Johnson_1.jpg" width = "524" />  <img src="./data/largerange_Johnson_2.jpg" height = "524" /> 


coming ...
