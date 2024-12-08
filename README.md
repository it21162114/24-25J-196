Research Group Number # 24-25J-196

Machine learning based Smart learning platform for Nursery school children.


Project Overview  

SmartEdu is an AI-driven platform designed to enhance early childhood education for nursery school children. The system focuses on improving key skills such as speaking, drawing, and coloring through personalized learning experiences. By using machine learning models, the platform provides feedback based on individual performance, helping children develop skills progressively. The goal is to support both teachers and parents by providing tools for early intervention and targeted learning strategies.  


System Overview

Our research aims to develop a comprehensive machine learning-based smart learning platform designed specifically for 
nursery school children, delivered through a web application. Utilize advanced machine learning techniques to refine 
voice recognition patterns, tailored to the linguistic nuances of Sri Lankan nursery school children, thereby improving their 
pronunciation, fluency, and overall speaking abilities. Develop interactive drawing quizzes that leverage machine learning to 
assess and enhance children's drawing skills, encouraging creativity and fine motor development. Create an AI-driven 
coloring module that provides real-time feedback and mini-lessons on color theory, helping children develop better coloring 
techniques and artistic expression. Implement a personalized learning system that adapts to each child's unique learning 
pace and style, while also identifying and mitigating potential learning risks early on to ensure a smooth educational journey. 
By integrating these components into a user-friendly web application, our platform aims to provide a holistic, engaging, 
and effective learning experience for nursery school children, laying a strong foundation for their future educational 
endeavors

![Overall system diagram](https://github.com/user-attachments/assets/55ca437e-bac2-4a91-adf6-ec7d4ab18245)

  

System Architecture
The system is organized into three primary layers:  

1. Client Tier (Mobile Application)  
   The front-end is developed using **React** and **Node.js**, allowing seamless interactions for children, parents, and teachers on both Android and iOS platforms.  

2. Middle Tier (Backend API)  
   The back-end is powered by **Flask** and **Python**, processing user input, running machine learning models for speech, drawing, and coloring skill analysis, and managing real-time feedback.  

3. Data Tier (Database)  
   The app uses **Firebase** for real-time data storage, tracking progress, and storing user profiles and performance data.  



Key Modules and Features  

 1. Speech Skill Development  
   - Description:  
     This module utilizes voice recognition and machine learning algorithms to assess and improve children's speaking skills, focusing on pronunciation and vocabulary development.  

   - Functionality:  
     - Children speak into the app, and the system analyzes pronunciation and speech patterns.  
     - Feedback is provided on accuracy, along with corrective suggestions and new vocabulary.  
     - Progress is tracked over time to offer personalized learning paths.  

   - Value:  
     - Improves speaking skills by identifying pronunciation issues early.  
     - Provides children with personalized language development exercises.  

 2. Drawing Skills Enhancement  
   - Description:  
     Using image processing technology, this module helps children improve their drawing skills by comparing their work to a reference image.  

   - Functionality:  
     - Children complete drawing tasks, and the system compares their drawings to a reference image.  
     - Personalized sub-quizzes are generated based on the child’s weak areas (e.g., proportions, shapes, details).  
     - Feedback is provided on areas that need improvement, helping children enhance their drawing abilities progressively.  

   - Value:  
     - Encourages creative development and enhances fine motor skills.  
     - Provides tailored exercises that adapt to the child's current drawing level.  

 3. Coloring Skill Development  
   - Description:  
     This module focuses on improving children's ability to color within the lines and apply color theory concepts through AI-based feedback.  

   - Functionality:  
     - Children color digital images and the system analyzes the quality of their work, focusing on color consistency, accuracy, and overall presentation.  
     - Feedback is provided on areas that need improvement, such as color mixing or applying colors correctly to specific areas.  

   - Value:  
     - Enhances artistic expression while teaching children color theory.  
     - Provides immediate, constructive feedback to improve coloring techniques.
  Here’s the **key modules and features** for the **4th Component: Personalized Learning and Risk Assessment** in the same format:

 4. Personalized Learning and Risk Assessment  

   - Description:  
     This module focuses on identifying learning difficulties in children and providing tailored interventions to improve their skills in real-time.

   - Functionality:  
     - The system analyzes children’s progress in speaking, drawing, and coloring tasks, detecting areas of struggle.  
     - Based on performance, it adjusts learning paths, providing personalized activities and feedback.  
     - Sends alerts to parents and teachers when a child is at risk of falling behind.  

   - Value:  
     - Enables **early identification** of learning challenges, promoting early intervention.  
     - Provides **personalized learning experiences**, ensuring that children receive the support they need to progress.  
     - Informs **teachers and parents** with real-time updates to optimize support and intervention.  


============================================================================

Technologies Used  

 Frontend (Client Tier)  
- React: A cross-platform framework for building mobile applications on both Android and iOS.  

Backend (Middle Tier)  
- Flask: A micro web framework for handling API requests, running machine learning models, and processing data.  
- Python: For building and training machine learning models for speech recognition, image processing, and feedback generation.  

Database (Data Tier)  
- Firebase: For real-time storage of user data, progress tracking, and notifications.  

Machine Learning & AI 
- Voice Recognition Models: To assess children's speaking patterns and provide feedback.  
- Image Processing Algorithms: To evaluate and compare children's drawings with reference images.  

===============================================================

 Installation  

Prerequisites  
- Node.js: Required for the React front-end development.  
- Python 3.x: For Flask API and machine learning model integration.  
- Firebase: For real-time database management.  

===============================================================

REPOSITORY LINK : https://github.com/it21162114/24-25J-196.git




