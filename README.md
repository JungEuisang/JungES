<aside>
💡

**OverView of the Project**

- Opening background information 

- General description of the current project 

- Proposed idea for enhancements to the project 

- Value and significance of this project 

- Current limitations

- Literature review

</aside>

# Title

[Topic] 

Veggie Stock AI using YOLOv5 (Vegetable Inventory AI)

---

# Opening background information

[Background information]

<aside>
✅ The importance of inventory management has increased recently due to the growing distribution and consumption of vegetables. In particular, Veggie Stock AI utilizes artificial intelligence technology to enhance the efficiency of real-time vegetable inventory monitoring and management. It aims to address the limitations and inefficiencies of traditional inventory management methods.

</aside>

---

# General description of the current project

[Overall project description]

<aside>
✅ This project aims to implement a vegetable inventory monitoring system using YOLOv5, a deep learning technology. By utilizing YOLOv5, we will collect vegetable sales data, assess inventory status, and analyze consumption patterns to develop inventory prediction algorithms and demand forecasting models. Additionally, we will conduct performance evaluations based on prototype development and field application cases, assessing not only accuracy and processing speed but also analyzing user feedback to enhance inventory management efficiency and improve consumer satisfaction.

</aside>

---

# **Proposed idea for enhancements to the project**

<aside>
✅ [Strengths of the proposed project]

  1. "Increase in inventory management efficiency.”

- The vegetable inventory AI system significantly enhances inventory management efficiency through real-time data analysis and predictive algorithms. This system reflects consumption patterns and seasonal fluctuations, enabling timely inventory replenishment and minimizing waste by reducing unnecessary stock. Additionally, it lowers labor costs through automated management processes and supports decision-making by quickly assessing inventory status, thereby improving overall operational efficiency. As a result, these improvements contribute to providing fresh products to consumers and increasing customer satisfaction.

  2.  **"Cost reduction and waste minimization.”**

- The vegetable inventory AI system achieves cost reduction and waste minimization through data-driven decision-making. By providing accurate demand forecasting and inventory optimization, it prevents overstocking and reduces the disposal of products that have lost freshness. Additionally, the automated inventory management process decreases the need for labor, thus lowering personnel costs and enhancing operational efficiency, which overall reduces costs. This approach helps businesses utilize resources more effectively and enables sustainable operations.

  3.  "Improvement in consumer satisfaction.”

- The vegetable inventory AI system plays a crucial role in enhancing consumer satisfaction. By analyzing real-time data, the system identifies consumer preferences and purchasing patterns, enabling personalized product recommendations. Furthermore, it ensures the timely supply of fresh products, allowing consumers to consistently receive high-quality items. This optimized inventory management and personalized service enhance the customer purchasing experience and contribute to building trust in the brand. As a result, this leads to increased repurchase rates and helps secure loyal customers.
</aside>

---

# Value and signifiance of the project

[ The importance of the project] 

<aside>
✅ The vegetable inventory monitoring system serves as a crucial element in the modern distribution environment. The improved system developed through this project can maintain automation, accuracy, and optimized inventory levels through efficient inventory management. By managing inventory effectively, it minimizes waste and reduces labor and management costs due to automation. This plays a significant role in enhancing consumer satisfaction by providing fresh products and personalized recommendation services based on consumer pattern analysis. Furthermore, by reducing resource waste and contributing to the establishment of sustainable agricultural and distribution systems, this project extends beyond mere technological innovation, becoming essential for enhancing corporate competitiveness and pursuing sustainability.

</aside>

---

# **Current limitations**

[Limitations faced]

<aside>
✅ The vegetable inventory management system utilizing artificial intelligence faces several limitations, including uncertainties in data quality, technical complexity, initial investment costs, and market volatility. In particular, inaccurate data can diminish the accuracy of predictions, and a lack of expertise required for system implementation and maintenance can hinder effective operation. Additionally, rapid fluctuations in consumer demand and seasonal factors may complicate inventory management, leading to challenges that undermine the overall reliability and efficiency of the system.

</aside>

---

# **Literature review**

<aside>
✅ [Literature Review on AI-Based Vegetable Inventory Management Systems]

- The integration of artificial intelligence (AI) into vegetable inventory management has emerged as a transformative approach to enhancing efficiency and reducing waste in the agricultural sector. AI technologies, such as machine learning and computer vision, enable precise tracking and management of perishable goods. However, the effectiveness of these systems largely depends on the quality of data collected. Research highlights that inaccurate or inconsistent data can significantly undermine the predictive capabilities of AI, emphasizing the need for robust data management practices. Additionally, the complexity involved in implementing AI solutions often requires specialized knowledge, which can pose challenges for smaller farms or businesses with limited technical expertise.
- Moreover, the initial investment costs associated with AI technologies can be substantial, potentially deterring stakeholders from adoption despite the long-term benefits. The agricultural market's inherent volatility, driven by seasonal fluctuations and changing consumer demands, further complicates inventory management. Studies suggest that AI systems must be adaptable to these market dynamics to optimize stock levels effectively. Successful case studies demonstrate the potential of AI in improving inventory turnover and reducing spoilage, underscoring the importance of continued research and development in making these technologies accessible and efficient for diverse agricultural stakeholders.
- For this project, we are investigating relevant papers to consider the latest research and technological trends in utilizing YOLOv5. Through a literature review on the performance and applicability of YOLOv5, we are exploring the core ideas and technical aspects of the project.
</aside>

---

## **Dataset acquisition process**

1. [**https://universe.roboflow.com/](https://universe.roboflow.com/) Go to the link.**

![image](https://github.com/user-attachments/assets/2fa960e0-d6fe-400a-8a1a-37b4f166e74c)

1. **Find the tomato dataset and download the YOLOv5 dataset.**

![image (1)](https://github.com/user-attachments/assets/44ce0386-6200-41f8-8f04-b98128a21c6f)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/c326c1cd-8152-49c7-8a6f-0b47fe857da2/image.png)

**“Download zip to computer”.**

**Create code using Google Colab.**

**1.  Google Drive integration.**

- **Connect Google Colab to Google Drive.**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/7c5eb437-b91f-4b60-88a5-4a63f11e85a5/image.png)

        ****

**2.  Install YOLOv5.**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/cfd80eae-ad59-477e-9b68-119f8859d717/image.png)

1. **Image file management.**
- **Create a folder to manage image files.**

![스크린샷 2024-11-24 162315.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/65a392b0-d582-42ea-83c8-ad2bd1f29c2c/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_162315.png)

1. **Generates verification data.**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/18e623d7-5716-4a8b-b30c-806616e5c523/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/3547a8bd-11ee-4edc-a5a0-8fde73642068/image.png)

1. **Gets the requierd library.**

![스크린샷 2024-11-24 163142.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/9ebaaa7d-ed5a-4e9c-8cd1-56b015ff595f/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_163142.png)

![스크린샷 2024-11-24 163332.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/1d08c657-8984-4355-9377-0f00fc9331ec/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_163332.png)

1. **Let them learn**

![스크린샷 2024-11-24 163557.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/f9548584-a848-4ad7-8ebf-b83282e71450/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_163557.png)

1. **Learning outcome**
    
    ![스크린샷 2024-11-24 165343.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/293a7eae-3296-48aa-b874-c00072b09eec/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_165343.png)
    

![스크린샷 2024-11-24 165521.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/08c91e9c-6483-4238-98e4-090f65cf0b3d/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_165521.png)

- **F1_curve**

![스크린샷 2024-11-24 170135.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/bf3e0ed1-079f-42ea-99f5-722936189231/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_170135.png)

- **PR_curve**

![스크린샷 2024-11-24 170224.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/1b959fd1-026d-4afc-8d83-bbc55a2be1d5/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_170224.png)

- **P_curve**

![스크린샷 2024-11-24 170315.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/7ff7525a-105c-43c4-b8f1-d33ee7551bf6/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_170315.png)

- **R_curve**

![스크린샷 2024-11-24 170339.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/243d9e82-23f7-42f0-878d-1e8c0b0d275f/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_170339.png)

- **confusion_matrix**

![스크린샷 2024-11-24 170420.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/28b86ffb-190b-402e-966e-d9dcdab7433d/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_170420.png)

- **results**

![스크린샷 2024-11-24 170517.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/93f52e5e-58eb-43b6-8798-103a42c4087a/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_170517.png)

1. **Validate model results**

![스크린샷 2024-11-24 171212.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/ad4c7dee-1502-40bc-835b-c06f85eceeba/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_171212.png)

![스크린샷 2024-11-24 171248.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/5ff06de4-898b-4433-835b-50f2ac362a40/cd291057-3487-42bf-8d94-5b9bc6907b60/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2024-11-24_171248.png)

- **아래의 명령어를 통해 검증을 할 수 있습니다. 또는 아래 명령어로 영상으로 테스트할 수 있습니다.**

**python [detect.py](http://detect.py/) --weight runs/train/exp9/weights/best.pt --source [테스트할 영상의 경로] --img 640 --conf 0.8**

**tomato_in_mart_final 영상은, 다른 채소를 제외한 데이터셋을 학습시켜 토마토만 인식시킨 테스트 영상입니다.**

**tomato_and_other_veg 영상은, 다른 채소들을 포함한 데이터셋을 학습시켜 토마토만 인식시킨 테스트 영상입니다. 추후, 따로 다른 채소들에 대한 데이터셋을 학습시켜 최신화 시켰습니다.**# JungES

awefawefawef
