Image-Caption-Llava
Smart AI-powered Image Captioning
🚀 Image-Caption-Llava is an advanced AI-driven tool designed to generate meaningful captions for images using state-of-the-art deep learning models. Whether you're automating alt text for accessibility, analyzing images for content insights, or simply exploring AI-generated descriptions, this project provides a powerful solution.
Features:
- 🖼️ AI-powered captioning – Generate accurate and context-aware descriptions for images.
- ⚡ Optimized performance – Efficient processing with deep learning frameworks.
- 🌍 Real-world application – Useful for social media, accessibility, and automated content tagging.
- 🔧 Customizable options – Fine-tune caption generation for various use cases.
  - Vision-Language Model (LLaVA)
    - FastAPI backend
    - Streamlit UI

    ## How to Run
    1. Pull model: `ollama pull llava`
    2. Start backend: `uvicorn backend.main:app --reload`
    3. Start frontend: `streamlit run frontend/app.py`
    4. Upload an image and generate captions

