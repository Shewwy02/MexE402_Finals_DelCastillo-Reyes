# MexE402_Finals_DelCastillo-Reyes

Topic 8: Isolating Objects by Color
 Apply the HSV thresholding code to extract and display objects of specific colors from an image.

Revise topic: Isolating Plant leaves 
Test HSV thresholds under various lighting conditions.

![Documentation (2)](https://github.com/user-attachments/assets/18c422bd-d8cb-4436-a60b-0001ff7d4e9a)

![Introduction](https://github.com/user-attachments/assets/affe4841-7b2c-4393-bd4b-bf8e6c336e83)

Isolating plant leaves from images is a critical task in computer vision, particularly in applications like plant health monitoring, agricultural analysis, and automated crop management. However, the appearance of leaves can vary significantly under different lighting conditions, such as sunlight, shade, or artificial light. These variations affect the color properties of the leaves, making it challenging to develop robust algorithms for consistent detection.  

The HSV (Hue, Saturation, Value) color space provides a powerful tool for handling these variations, as it separates color information (Hue) from brightness (Value). By carefully testing and fine-tuning HSV thresholds under various lighting conditions, we can enhance the reliability of leaf isolation, enabling accurate segmentation and analysis across diverse environments. This process is essential for developing adaptable and scalable solutions in agricultural technology and environmental monitoring.  


![Abstract](https://github.com/user-attachments/assets/92b00675-f944-4405-933b-0b7adca11212)

The objective of this project is to isolate plant leaves from images and test HSV (Hue, Saturation, Value) thresholds under various lighting condition. Accurate leaf isolation is essential for applications in precision agriculture, plant health assessment, and automated crop management.

The approach involves converting images to the HSV color space, where color information is decoupled from brightness, allowing for more reliable segmentation. Predefined HSV thresholds are applied to isolate green hues associated with leaves. The method is tested across diverse lighting scenarios—bright sunlight, overcast conditions, and artificial light—to identify an optimal HSV range that performs consistently.

The expected results include a fine-tuned HSV threshold range that minimizes detection errors such as false positives and negatives, even under challenging lighting conditions. This project aims to develop a robust, adaptable framework for plant leaf segmentation, with potential applications in real-world agricultural and environmental monitoring systems.

![ProjectMEthods](https://github.com/user-attachments/assets/683476a6-d26e-4ae3-8255-d0667d26c621)

- **Image Acquisition**:  
  - Collect images of plants under various lighting conditions, including sunlight from the dataset
    
- **Image Preprocessing**:  
  - Load each image using OpenCV.  
  - Convert images from BGR to HSV color space to separate color information (Hue) from intensity (Value).  

- **Define Initial HSV Thresholds**:  
  - Set initial lower and upper HSV values to isolate green hues typically associated with plant leaves.  

- **Analyze Lighting Variations**:  
  - Test the thresholds on images taken under different lighting conditions.


![Conclusion](https://github.com/user-attachments/assets/bf0fab92-82f6-4245-82d8-9f4447538ab3)  

This project successfully demonstrated the use of HSV thresholds to isolate plant leaves under various lighting conditions. Through iterative testing and refinement, an optimal HSV range was identified, providing consistent leaf isolation across different environments, including bright sunlight.  

One significant challenge was dealing with the variability caused by extreme lighting conditions commonly encountered in natural environments. For example, harsh sunlight created high-contrast shadows that obscured parts of the leaves, while overly bright areas caused reflections that distorted the perceived color. Similarly, dim or uneven lighting, such as in indoor settings or cloudy weather, reduced color saturation, making it harder to distinguish leaves from the background.

The project outcomes include a isolating plant leaves and test hsv threshold unver various lighting conditions. These findings can be applied to agricultural and environmental monitoring systems, with potential extensions involving machine learning models for even greater adaptability.

![AdditionalMAterials](https://github.com/user-attachments/assets/76159a34-594e-43f1-a84c-e14cc2625c36)

## Dataset plant leaves

https://www.kaggle.com/datasets/csafrit2/plant-leaves-for-image-classification

plant leaves
![plant](https://github.com/user-attachments/assets/15a9522a-4af5-413c-b78c-e286541351ab)

plant leaves1
![plant1](https://github.com/user-attachments/assets/6b7a8530-42c4-44f9-8ebc-c7c76f8c38fb)

plant leaves2
![plant2](https://github.com/user-attachments/assets/aacb7f2b-11d1-4818-a8c5-d6ce88d1e383)

plant leaves3
![plant3](https://github.com/user-attachments/assets/0a18df51-b56c-480b-ad56-ff15d18a92b6)

## Codes
![carbon (12)](https://github.com/user-attachments/assets/07ef37c7-28c0-4afc-a0da-ff3eb1fcd4fb)
![carbon (13)](https://github.com/user-attachments/assets/e4a6752f-1869-4883-90c9-11352dfcbb9f)
![carbon (9)](https://github.com/user-attachments/assets/ea201b47-346a-45db-b4a9-7823dad7ee9e)
![carbon (10)](https://github.com/user-attachments/assets/f3802fab-0640-4d7e-9baf-9d1c8e58887b)









