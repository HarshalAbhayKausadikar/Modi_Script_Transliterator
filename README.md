# Modi_Script_Transliterator
Modi Script Transliterator tool which instantly translates text in a Modi Script image to its equivalent text in Devanagari. The task of direct conversion is achieved by using the novel concept of Transliteration through Image Captioning.

![aim](img/aim.jpg)

---
### About Modi Script
Modi Script is a script which was used to write Marathi during medieval India. During the Maratha rule, it served as the official script. The Modi script was not only restricted to the state of Maharashtra. Other parts of India also saw widespread use of the script.

### Transliteration v/s Translation
To be concise,
Translation is LANGUAGE to LANGUAGE
Transliteration is SCRIPT TO SCRIPT

![difference](img/diff.jpg)

### Introducing MODI-2043 Dataset
The MODI-2043 dataset contains 2043 images of Modi script text along with their corresponding Devanagari transliterations in text. This dataset consists of letters of _Peshawekaalin_ and _Shivakaalin_ Modi Script. It also includes a variety of Modi writing styles.
<!-- You can find the dataset here -  -->

### Methodology

##### Classical CNN-RNN Approach
Using Merging Architecture, textuals captions are generated for an input image.
##### Transformer based Approach

### Results
| Model                   | BLEU1 | BLEU2 |
|-------------------------|-------|-------|
| VGG16 + Transformer     |0.006731|0.001247|
| EfficientNetB0 + Transformer |0.088344|0.017591|
| InceptionV3 + Transformer |0.109254|0.020413|
| ResNet50 + Transformer  |0.011143|0.001680|

It is observed that the InceptionV3 model gave better results as compared to the ResNet50 and EfficientNet models.


