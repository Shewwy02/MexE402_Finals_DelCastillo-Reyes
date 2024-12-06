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

- **Apply Thresholding**:  
  - Use the `cv2.inRange()` function to create a binary mask highlighting regions within the defined HSV range.  

- **Morphological Operations**:  
  - Apply morphological transformations (e.g., opening and closing) to remove noise and refine the mask.  

- **Analyze Lighting Variations**:  
  - Test the thresholds on images taken under different lighting conditions.

