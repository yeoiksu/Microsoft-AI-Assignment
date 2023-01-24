# 0116. Dangerous Flight Classification System
Dangerous Flight Classification System of Drone vs. Bird with Alarm Message  

## Summary of Project and Team
- Microsoft AI School Team 2 Project
- Schedule : 
    - Processing : 2023.1.10 ~ 1.17
    - A result briefing session : 2023.1.18 | Presentation : [PDF file link](https://github.com/yeoiksu/Microsoft-AI-Assignment/blob/main/2023.01/0112.pdf)
- Member of Project   
    Team Leader : @yeoiksu | https://github.com/yeoiksu  
    Team Member : @TaeYounKwon | https://github.com/TaeYounKwon  
    Team Member : @ssyjgs1 | https://github.com/ssyjgs1  
    Team Member : @Byunggu-Son | https://github.com/Byunggu-Son  
    Team Member : @yuyeon | https://github.com/yuyeon-choi  
- Project Environment and Technical Stacks
    - Stacks : Python, PyTorch, Anaconda Environment, etc...
    - Environments : Processing Model on Microsoft Azure Data Science Virtual Machine
    - Detail Information of Used Pkg List : ```package list info.yaml```

## Introduction
![title](https://user-images.githubusercontent.com/16416502/213843630-d7d76a68-a72c-4866-bc26-9f2ff1dc6205.png)  
Real-time camera checks drones and birds for binary classification, and when dangerous goods are found, GPS information of dangerous goods is provided to users by email with an alarm message.  

## Intention of Project  
![1](https://user-images.githubusercontent.com/16416502/213843774-23875a87-1cbf-47e4-8c89-a3d2b349a129.png)  

## Architecture of System
![architecture](https://user-images.githubusercontent.com/16416502/213843827-726b4fe6-13e5-49ce-bd90-103b40805f94.png)  
- We used MobileNetV2 on our system. Because of
    - Accuracy not inferior to other image classification models
    - Requirement of lightweight models in limited environments  
    
## Examples of Demonstration Picture
![ex01](https://user-images.githubusercontent.com/16416502/213844008-e9005100-c09b-4f88-9f4f-69cc49ddb16a.png)
![ex02](https://user-images.githubusercontent.com/16416502/213844009-2b894303-ad24-4bd7-82c1-06bbd14a093f.png)
![ex03](https://user-images.githubusercontent.com/16416502/213844010-a198cf8c-f709-4e61-99c1-9de2a194bc8a.png)  
