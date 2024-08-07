![adadadada](https://github.com/liujiawei725/Data-Free-APG-Framework/blob/main/assets/logo.png)

## Implementation Detail
Code has been released after publication.  

## Organization
* School of Artificial Intelligence, Jilin University, Changchun, China
* Department of Control Science and Engineering, Jilin University, Changchun, China
* Engineering Research Center of Knowledge-Driven Human-Machine Intelligence, MOE, Jilin University, Changchun, China
* College of Electronics and Information Engineering, Tongji University, Shanghai, China

## Background
![adadadada](https://github.com/liujiawei725/Data-Free-APG-Framework/blob/main/assets/DF-APG.png)

Existing data-dependent physical attacks can hardly apply to privacy-critical situations when attackers have no access to training data of target models. This paper presents a hierarchical adversarial patch generation (APG) framework for data-free attacks with proxy datasets assuming that the training data is blinded. In the upper layer, average patch saliency (APS) is introduced as a quantitative metric to determine the best proxy dataset for APG among a bunch of publicly available datasets. In the lower layer, Data-Free Expectation of Transformation (DF-EoT) is developed to generate patches while considering perturbing background simulation and sensitivity alleviation. Evaluation results in digital settings show that the proposed framework enables attackers to accomplish targeted attack results in data-free scenarios and averagely outperforms a benchmark APG method by 10.05\% on five diverse target models. Finally, a case study in physical settings is included to verify the validness of the framework.

## Quantitative Evaluation in the Digital World

![adadadada](https://github.com/liujiawei725/Data-Free-APG-Framework/blob/main/assets/quantitive_result.png)

## Case Study in the Physical World

The object to be attacked is the well-learned class “banana” by CNN-based image classifiers, and the target class of adversarial patches is the butterfly “monarch”. As we can see, the bananas correctly classified with high confidence can be misled into a pre-defined target class with high confidence scores, thus actively exposing the potential flaws of CNN. Notably, the adversarial patches in the videos are generated with a manually synthesized dataset composed of black images, white images and uniform noise, thereby demonstrating the possibility of performing robustness evaluation under data-scarce situations.


Adversarial patches are presented on digital screen.![adadadada](https://github.com/liujiawei725/Data-Free-APG-Framework/blob/main/assets/digital_screen.gif)
Adversarial patches are presented on paper.![adadadada](https://github.com/liujiawei725/Data-Free-APG-Framework/blob/main/assets/paper.gif)
Adversarial patches are presented on digital screen.![adadadada](https://github.com/liujiawei725/Data-Free-APG-Framework/blob/main/assets/test_1420.gif)


## Acknowledgements 
This work was supported by National Key R&D Program of China (No.2020AAA0108105), Development and Reform Commission Foundation of Jilin Province (No.2023C034-3) and Shanghai Automobile Industry Technology Development.
Foundation (No.2105)
