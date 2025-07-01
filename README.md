# 🔍 AI Object Detection using OWL-ViT and CLIP

This project performs zero-shot object detection on video files using OWL-ViT and CLIP models. It compares grounded object localization (OWL-ViT) with semantic frame classification (CLIP).

## 📦 Dependencies

- transformers  
- clip-by-openai  
- torch  
- opencv-python  
- matplotlib  
- Pillow  

Install all with:

```bash
pip install -r requirements.txt
🚀 How It Works
OWL-ViT: Detects and localizes objects in each video frame using natural language prompts

CLIP: Matches each frame with the most similar text label based on image-text similarity

🧠 Example Labels
python
Copy
Edit
text_labels = ["matchbox and matchsticks", "pc monitor", "lion", "drone", "light bulb"]
You can change or add more labels in the script.

🎬 Input
Place your input video file in the project folder and rename it as:

Copy
Edit
input_vid.avi
📤 Output
The following output files will be generated:

css
Copy
Edit
output_with_owlvit.avi   → OWL-ViT detection
output_with_clip.avi     → CLIP classification
