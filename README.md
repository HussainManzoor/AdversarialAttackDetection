# AdversarialAttackDetection
This repository contains the demo for the paper "Reconstruction-based Adversarial Attack Detection on Deep Learning Model in Vision-based Autonomous Driving Systems."

**Demo Link for Gaussian noise Perturbation-based Advesarial Attack**

[Gaussian Nosie Perturbation-based Adversarial Attack](https://youtu.be/jUgBWJme5pA)

**Demo Link for Speckle noise Perturbation-based Advesarial Attack**

[Demo Video for Speckle Noise Perturbation-based Adversarial Attack](https://youtu.be/rtn8LrLXbDE)

**Demo Link for Shot noise Perturbation-based Advesarial Attack**

[Demo Video for Shot Noise Perturbation-based Adversarial Attack](https://youtu.be/URSU_BHP1ks)

**Demo Link for Impulse noise Perturbation-based Advesarial Attack**

[Demo Video for Impulse Noise Perturbation-based Adversarial Attack](https://youtu.be/9j_Le3tBcgk)

**Demo Link for Decision-based/Boundary Attack**

[Demo Video for Decision-based/boundary Attack](https://youtu.be/7shB1iXJnuw)

**Demo Video for HopSkipJum Adversarial Attack**

[Demo Video for HopSkipJum Adversarial Attack](https://youtu.be/EHZ8q8x6DIA)
**Demo Video for Square Adversarial Attack**

[Demo Video for Square Adversarial Attack](https://youtu.be/PAgKsws44Kg)

**Caption**
The lift pane in the uppermost window shows the adversarially perturbed image frames, while the right window shows the normal image frames. The bottom window shows the impact of these attacks on autonomous driving systems.
![Video Caption](https://github.com/HussainManzoor/AdversarialAttackDetection/assets/133944553/cf5981f0-baa3-4aad-8681-0c93f198d381)

# Impact of Adversarial Attack on Model Robustness
![Sample Deviation](https://github.com/HussainManzoor/AdversarialAttackDetection/assets/133944553/b5a7cb8c-d9a1-46ce-8990-ef303eb8caa9)

Impact of adversarial attack on the original trajectory of the target ADS. These samples were collected when the impulse noise-based adversarial attack was applied. (a) represents the initial position, (b) and (c) show the impact of the attack. We can clearly see that the ADS started deviating from its original trajectory. (d) shows that ADS is no longer driving on the road and crashed on the roadside.

**Deviation Due to Adversarial Attacks**

Sample deviation in the model's final output. 
![Deviation in steering Angles](https://github.com/HussainManzoor/AdversarialAttackDetection/assets/133944553/8fc00543-9ccb-4037-a484-7e07dfce64c2)


# Description of Experiment
In this experiment, we used the modified NVIDIA-2 model for self-driving cars. It was trained using imitation learning. After training the model, we applied adversarial attacks to verify its robustness against adversarial attacks. Our detailed experimental results showed that the state-of-the-art models are also vulnerable to adversarial attacks. We also proposed a deep autoencoder-based adversarial attack detection that effectively detects any input image-specific adversarial attacks. The detailed experimental results can be found in the manuscript. 
This experiment is part of the ongoing research in which we are developing an adversarial testing tool. The tool will soon be published on our GitHub repository. 
