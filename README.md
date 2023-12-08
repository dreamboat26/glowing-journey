# Alzheimer Analysis

## Abstract 

- This study explores the application of Machine Learning (ML) and Deep Learning (DL) architectures for the early detection of Alzheimer's disease. A comprehensive analysis is conducted using traditional ML models, including Support Vector Machine (SVM),Random Forest, and Logistic Regression, alongside advanced DL models employing 
Convolutional Neural Networks (CNN). 

- Additionally, the performance of the widely  used Inception method, a specialized CNN architecture, is investigated for comparative 
purposes. The study involves preprocessing diverse datasets comprising demographic information, genetic data, and neuroimaging scans. Performance evaluation metrics 
such as accuracy, precision, recall, and F1-score are employed, utilizing validation techniques to ensure robust results. The findings offer insights into the strengths and limitations of each model, shedding light on their applicability in  Alzheimer's analysis. This research contributes to the growing body of knowledge on 
ML and DL applications in neurodegenerative disease detection, paving the way for enhanced diagnostic methodologies and intervention strategies.

## Introduction
- Dementia, a broad term encompassing a spectrum of cognitive disorders, manifests as a decline in memory and thinking skills significant enough to impede everyday 
activities. Among these disorders, Alzheimer's disease stands out, characterized by a progressive deterioration in memory, cognition, and behavior. The onset of symptoms 
is gradual, intensifying over time and ultimately affecting an individual's ability to perform routine tasks. Despite extensive research, the intricate nature of Alzheimer's 
disease remains only partially understood, emphasizing the critical need for early diagnosis.

- In the contemporary era, the emergence of machine learning (ML) and artificial intelligence (AI) technologies provides a promising avenue for addressing the complexities of Alzheimer's disease. ML models demonstrate unparalleled proficiency in identifying intricate patterns and making predictions by harnessing the power of 
extensive datasets. This technological advancement offers a beacon of hope in the pursuit of early detection, allowing for interventions at crucial stages of the disease.

- One of the key challenges in Alzheimer's research is the multifaceted nature of the disease. By leveraging ML algorithms to analyze diverse data types such as neuroimaging, Clinical Dementia Rating, intracranial volume, and more, researchers have the potential to unlock novel insights into the detection and progression of Alzheimer's disease. This integrative approach aims to capture the heterogeneity of the disease, providing a more comprehensive understanding of its underlying mechanisms.

- As the technological landscape continues to evolve, the fusion of machine learning and Alzheimer's research holds promise for transformative breakthroughs. The subsequent 
sections of this discourse will delve into specific ML and AI methodologies employed in the pursuit of early Alzheimer's detection, highlighting their potential contributions to unraveling the intricate dynamics of this debilitating disease

## Objectives and problem statement
- Conduct a comprehensive review of studies employing Machine Learning (ML) methodologies for Alzheimer's disease detection, with a primary focus on research utilizing the OASIS dataset.
- Investigate the applications of Deep Learning (DL) techniques, specifically Convolutional Neural Networks (CNNs) and the Inception model, in Alzheimer's detection using MRI scans.

## Dataset Used -
Oasis Dataset (Longitudinal) and MRI Scans Dataset (Kaggle)

## Models used
- Machine Learning Models - SVM,Random Forest,Logistic Regression
- Deep Learning Models- CNN(Transfer Learning - Inception Model), Customized CNN Architecture

## Scripts Used

- Alzheimer_Analysis_CNN : CNN Models used here are Inception Model using Transfer Learning and customized CNN architecture
- Alzheimer_Analysis_ML_Models : Using SVM,Random Forest and Logistic Regression
- Final_Report : Here we have report of the project


## Results And Discussions
- Random Forest emerges as the top-performing model among the chosen ML approaches. Its ensemble nature, amalgamating diverse decision trees, contributes to heightened accuracy by synergistically addressing complexities within the Alzheimer's dataset. We got accuracy of 84%.
- SVM, securing the second position in performance, demonstrates its effectiveness in handling more complex datasets. Its operational principle, relying on a hyper plane as a class boundary, allows SVM to navigate intricate patterns within the data. We got accuracy of 77%.
- Logistic Regression, while performing less optimally compared to Random Forest and SVM, imparts valuable insights. Its simplicity, characterized by a straightforward mechanism and the sigmoid function, offers predictability but compromises on accuracy. We got accuracy of 72%.
- The Inception model, leveraging Transfer Learning,demonstrated a commendable training accuracy of 92%. While the training accuracy is  noteworthy, the efficiency observed in the test and validation phases stood at 62%.
- The custom-designed CNN architecture yielded a training efficiency of 72% after running for 40 epochs.

## Conclusions
- In our quest to enhance Alzheimer's disease detection, our study has yielded promising results and crucial insights into the efficacy of Machine Learning (ML) and Deep 
Learning (DL) methodologies. Traditional ML models, including Random Forest, SVM, and Logistic Regression, demonstrated commendable accuracies, with Random Forest emerging as the top performer, aligning well with existing literature.Comparatively, our DL models, featuring a custom CNN architecture and the Inception 
model with Transfer Learning, provided valuable findings. 

- The CNN architecture displayed a training efficiency of 72%, underscoring its potential for capturing intricate patterns. However, when compared to benchmark CNN accuracies from literature, there exists room for improvement. The Inception model, while achieving a high training accuracy of 92%, showed a lower efficiency of 62% in test and validation phases, indicating potential for enhancement through hyper parameter tuning and fine-tuning.

- In comparison to literature, where CNN models achieved around 98.6% accuracy, our CNN architecture exhibited a lower accuracy of 76%. To bridge this gap, future directions include exploring additional epochs and conducting optimizations to align more closely with benchmark performances. Additionally, the integration of Recurrent Neural Networks (RNNs) presents an intriguing avenue for capturing temporal dependencies within Alzheimer's-related data, offering a holistic approach for future research. As for the ML techniques the researches got an accuracy of 85.71% whereas we got accuracy of 84% from our SVM model. 

- In conclusion, our study contributes nuanced insights into the landscape of Alzheimer's detection, shedding light on the strengths of traditional ML models and the potential for refinement in DL architectures. The identified future directions provide a roadmap for further optimization and exploration, aiming towards more accurate and robust early 
detection strategies for Alzheimer's disease.

Please go through the report file to get more insights into the project

Thanks
