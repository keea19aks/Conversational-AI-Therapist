# Conversational-AI-Therapist
🧠 Conversational AI Therapist using LoRA, DPO for human preference alignment, and Dynamic RAG with intelligent memory mechanisms, clinical knowledge integration, and crisis detection. Research under NTU URECA 2024-25.

The system implements a three-stage methodology:

1. **Stage 1: Parameter-Efficient Fine-tuning with LoRA**
   - Fine-tuned on MentalChat16K dataset 
   - Training loss: 0.7210, Evaluation loss: 0.7314

2. **Direct Preference Optimization**
   - Trained on a subset of PsychoCounsel-Preference dataset 
   - Training accuracy: 100%, Evaluation accuracy: 98.57%

3. **Stage 3: Dynamic RAG with Safety Protocols**
   - FAISS-indexed clinical knowledge base
   - Real-time crisis detection and intervention
   - Sliding window memory with automatic summarization
