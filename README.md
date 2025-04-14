**🔍 Object Detection with OWL-ViT and CLIP**

This notebook compares object detection using OWL-ViT and CLIP on a video file. OWL-ViT provides grounded object detection, while CLIP identifies the most similar text label for each frame.

**📦 Dependencies**
transformers

clip-by-openai

torch

opencv-python

matplotlib

Pillow

**How It Works:**

OWL-ViT detects and localizes objects in frames based on natural language prompts.

CLIP scores each frame for similarity with given text prompts and annotates with the top match.

🧠 Example Labels
python
Copy
Edit
text_labels = ["matchbox and matchsticks", "pc monitor", "lion", "drone", "light bulb", 
               ]
📹 Input
Drop your input video as input_vid.avi in the working directory.

📤 Output
output_with_owlvit.avi

output_with_clip.avi
