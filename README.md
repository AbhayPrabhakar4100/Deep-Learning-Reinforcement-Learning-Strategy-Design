## Deep-Learning-Reinforcement-Learning-Strategy-Design

## 📌 Project Overview
This project demonstrates two complementary areas of AI research:  
1. **Image-Based Deep Learning Pipeline**  
   - Attempted GAN-based image generation using DCGAN on MS COCO subset.  
   - Due to poor output quality, fallback strategy was adopted using 5 real images.  
   - Implemented **object detection** with YOLOv8n and **image captioning** with BLIP-base.  

2. **Reinforcement Learning Strategy Design**  
   - Designed a conceptual Deep Q-Network (DQN) agent for the **classic Pong game**.  
   - Defined states, actions, and rewards.  
   - Outlined training techniques: experience replay, target networks, epsilon-greedy exploration, and reward discounting.  

---

## 📂 Contents
- **Part A: Deep Learning (Image Pipeline)**  
  - GAN-based generation attempt (DCGAN)  
  - Fallback with real images  
  - YOLOv8n object detection  
  - BLIP-base captioning  
  - Results and limitations  

- **Part B: Reinforcement Learning (Pong Agent)**  
  - Pong environment description  
  - DQN architecture  
  - Training design (experience replay, epsilon-greedy)  
  - Evaluation metrics (average score, win rate, rally length)  

---

## 🔧 Tools & Libraries
- **Deep Learning:** PyTorch, YOLOv8n (Ultralytics), Hugging Face Transformers (BLIP)  
- **Dataset:** MS COCO train2017  
- **Reinforcement Learning:** DQN (conceptual design), Gym-like environment  

---

## 📊 Key Results
- GAN struggled to generate realistic images → fallback strategy improved results.  
- YOLOv8n: effective detection but occasional misclassifications.  
- BLIP-base: robust captions even when detection failed.  
- Pong RL agent design provided a solid foundation for future implementation.  

---

## 🚀 Future Work
- Implement Pong RL agent training and evaluation.  
- Explore advanced GANs (StyleGAN, diffusion models).  
- Fine-tune captioning/detection models for better domain alignment.  

---

## 📅 Author
- **Abhay Prabhakar**  
  Graduate Student, Data Science & Analytics  
