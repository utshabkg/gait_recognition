## [Gait Recognition](https://www.sciencedirect.com/science/article/abs/pii/S0045790622006450)

[![Author](https://img.shields.io/badge/author-NahianAlindo-red)](https://github.com/NahianAlindo/)
[![Author](https://img.shields.io/badge/author-utshabkg-red)](https://github.com/utshabkg/)
[![Stars](https://img.shields.io/github/stars/NahianAlindo/gait_recognition?style=social)](https://github.com/NahianAlindo/gait_recognition/stargazers)


<p align="justify">Gait recognition is one of the most successful biometric recognition technologies. Earlier studies have employed inertial sensors to capture gait dynamics for individual identification. Still, the overall performance of gait recognition is improvable. In this work, we have suggested a new deep neural network architecture named FCN-BiLSTM. The architecture concatenates the extracted features of a Bidirectional LSTM Network with the extracted features provided by a Fully Convolutional Network that uses Squeeze-and-Excitation blocks to provide a better feature map. That map is then input to a softmax classifier. We assessed our model on multiple benchmark datasets, particularly the OU-ISIR and whuGAIT datasets. The suggested architecture surpasses the existing state-of-the-art methods on the OU-ISIR dataset, Dataset #1, and #3 of the whuGAIT datasets. The performance was equivalent on Dataset #2 and Dataset #4 of the whuGAIT Datasets. Therefore, we believe the proposed architecture can be employed for biometric systems benefitting humans.</p>

Datasets:
- Dataset #1: 
- Dataset #2: 
- Dataset OU-ISIR: 

### Accuracy achieved:

<table>
<tr> 
  <th> Datasets </th> 
  <th> Without Tuner </th>
  <th> With Tuner </th>
</tr>

<tr> 
  <td> Dataset 1 </td>
  <td> 93.23 </td> 
  <td>94.30 </td>
</tr>

<tr>
  <td> Dataset 2 </td>
  <td> 97.37 </td>
  <td> 97.65 </td>
</tr> 

<tr> 
  <td> Dataset OU-ISIR </td>
  <td> 94.39 </td>
  <td> 96.45 </td>
</tr>
</table>

Thank you. Please let us know, if you find any mistake or way of development in this repository. Cheers!

### Read our [Published Journal Research Paper](https://www.sciencedirect.com/science/article/pii/S2352914821002872) based on this repository. Cite if this helps your work:
```
    @article{rifaat2022accurate,
    title={Accurate gait recognition with inertial sensors using a new FCN-BiLSTM architecture},
    author={Rifaat, Nahian and Ghosh, Utshab Kumar and Sayeed, Abu},
    journal={Computers and Electrical Engineering},
    volume={104},
    pages={108428},
    year={2022},
    publisher={Elsevier}
    }
```
