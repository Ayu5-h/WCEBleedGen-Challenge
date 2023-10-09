# Wireless Capsule Endoscopy (WCE):
<br/>
**Wireless Capsule Endoscopy is a non-invasive medical imaging technology used to examine the gastrointestinal (GI) tract. It involves the ingestion of a small, swallowable capsule camera that captures images or videos as it passes through the digestive system.**<br/>
<br/>

**Importance:**<br/>
Capsule endoscopy is used for diagnosing and monitoring various GI disorders, including gastrointestinal bleeding, Crohn's disease, and tumors.<br/>
Detecting bleeding frames in the captured video is crucial for identifying and treating GI bleeding conditions promptly.<br/>
<br/>
<br/>


- Precision: 0.9699248<br/>
- Recall: 0.96268654<br/>
- Binary Accuracy: 0.964<br/>
- F1 score is 0.96629214<br/>

<br/>
<img width="560" alt="Screenshot 2023-10-09 at 4 37 04 PM" src="https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/602aedd9-2a69-4c03-ae92-8505b5b03864">
<br/>
<br/>
<br/>
<br/>
<img width="560" alt="Screenshot 2023-10-09 at 4 37 07 PM" src="https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/882efcc2-ac83-48cd-853f-f65fc42def1d">
<br/>
<br/>
<br/>
<br/>
<img width="580" alt="Screenshot 2023-10-09 at 4 49 20 PM" src="https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/59f047cd-353b-42f2-8f29-d225551e049a">

<br/>
<br/>
<br/>
<br/>
<img width="580" alt="Screenshot 2023-10-09 at 4 47 01 PM" src="https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/645fed26-4573-4fbf-85ca-07113cd3132a">

<br/>
<br/><br/><br/>

![A0004](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/801dc157-7048-41c1-9cc9-2780943c5142)
![A0003](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/34d4f4d8-248a-4ba2-bbf2-b62c273e49dc)
![A0002](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/1a5ddfd9-4263-4063-80d4-577f01b303b1)
![A0001](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/a3df0104-b60b-4f5f-bd30-2ef6ccba6e14)
![A0000](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/15bcb53e-b49a-4bbe-a35c-c6365c280458)
![A0049](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/8022f24f-1bff-40f7-8070-cd183c3807b9)
![A0048](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/1f3c4cf5-7d5e-47e2-b81a-b0a3ffba2b57)
![A0047](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/c9e0a012-c12c-4547-baf3-84417fc6fbc1)

<br/><br/><br/>
<br/><br/><br/>
![A0261](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/9c097369-37f8-4ea0-b360-edee9171d8fb)
![A0260](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/9b525575-bbd1-41a7-98d7-d32e8f06b307)
![A0259](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/0485aafa-3fc5-4efa-9a07-cea0b1f98264)
![A0258](https://github.com/Ayu5-h/WCEBleedGen-Challenge/assets/107213166/4e4659f1-624f-42a3-b2ce-2f8d419c6fd7)
<br/><br/><br/>

- **Detection of Bleeding Frames:**<br/>
Machine learning and computer vision algorithms are applied to the video frames or images captured by the capsule endoscope.<br/>
Bleeding frames are identified by analyzing color, texture, and shape features, as well as changes in pixel intensity.<br/>
Deep learning techniques, such as convolutional neural networks (CNNs), are often used for feature extraction and classification.<br/>
<br/>

- **Classification of Bleeding and Non-Bleeding Frames:**<br/>
Once bleeding frames are detected, they are further classified into different categories, such as active bleeding, recent bleeding, or non-bleeding frames.<br/>
This classification helps in determining the severity of the GI condition and guiding treatment decisions.
<br/>

- **Challenges:**<br/>
Challenges in this field include dealing with noise and artifacts in the captured images, real-time processing of video streams, and achieving high accuracy in bleeding detection.<br/>
<br/>

- **Applications:**<br/>
The technology has applications in diagnosing conditions like gastrointestinal bleeding, ulcerative colitis, Crohn's disease, and tumors.
It can also be used for monitoring treatment effectiveness and disease progression.<br/>
<br/>

- **Datasets:**<br/>
Researchers in this field often rely on specialized datasets of capsule endoscopy videos and images. These datasets may contain labeled examples of bleeding and non-bleeding frames.<br/>
One well-known dataset used for this purpose is the CVC-ClinicDB dataset, which contains a collection of annotated endoscopic images and videos.<br/>
<br/>

- **Training and Validation:**<br/>
Machine learning models for bleeding detection and classification require extensive training and validation.<br/>
Data augmentation techniques are often employed to increase the diversity of training data and improve model generalization.<br/>
<br/>

- **Real-time Analysis:**<br/>
Real-time analysis is crucial in capsule endoscopy, as it allows for the timely detection of bleeding events.<br/>
Specialized hardware or efficient algorithms may be necessary to process video frames in real-time.<br/>
<br/>

- **Integration into Clinical Practice:**<br/>
The successful development of bleeding detection and classification algorithms can enhance the diagnostic capabilities of healthcare professionals.<br/>
Such technologies can assist doctors in making more informed decisions during endoscopy procedures.<br/>
<br/>

- **Interpretability and Explainability:**<br/>
In the medical field, it's important to make machine learning models interpretable and explainable. Understanding why a model makes a particular classification decision is critical for gaining trust from healthcare professionals.<br/>
<br/>

- **Research Directions:**<br/>
Ongoing research in this area includes the improvement of accuracy, sensitivity, and specificity of bleeding detection models.<br/>
Researchers are also exploring the integration of AI algorithms with capsule endoscopy devices for real-time decision support.<br/>
<br/>

- **Ethical Considerations:**<br/>
When developing and deploying AI solutions for healthcare, ethical considerations are paramount. Ensuring patient privacy, data security, and informed consent are essential aspects of this research.<br/>
<br/>

- **Clinical Impact:**<br/>
The successful development of bleeding detection and classification algorithms has the potential to reduce the time and cost of diagnosis, as well as improve patient outcomes by facilitating early intervention.<br/>
