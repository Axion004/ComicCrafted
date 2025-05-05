# ComicCrafter 🎨🦸‍♂️  
**Generate full comic strips from simple scenarios using Generative AI!**

ComicCrafter uses powerful language and image generation tools to bring your creative ideas to life as comic strips.

---

## 🚀 How It Works

1. A **Large Language Model** (OpenAI GPT) turns your scenario into 6 descriptive comic panels with dialogues.
2. **Stable Diffusion** (via Stability API) generates an image for each panel.
3. Text is added to each image using Pillow.
4. All panels are merged into a final comic strip.

---

## 🧪 Example Scenarios

**Style: Belgium Comic**  
Characters: Francis (a medieval knight), Madeline (a long-haired princess)  
Francis fights a dragon terrorizing the kingdom. The twist: the dragon was the princess's friend!

**Style: Manga**  
Characters: Adrien (blond hair), Vincent (black hair)  
They build a new product overnight and present it at work.

**Style: American Comic**  
Characters: Peter (tall, blond), Steven (short, black hair)  
Aliens attack New York. Peter and Steven try to escape before the army steps in.

---

## ⚙️ Requirements

Install all required libraries:

```bash
pip install -r requirements.txt


🧾 Setup Instructions
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/ComicCrafter.git
cd ComicCrafter
Set up API keys

Rename the .env.example file to .env and add your keys:

env
Copy
Edit
OPENAI_API_KEY=your_openai_key
STABILITY_KEY=your_stability_key
Edit the script

In kartoon.py, change:

SCENARIO: Your story idea

STYLE: Choose from 'manga', 'american', etc.

Run the script

bash
Copy
Edit
python kartoon.py
📁 Output
Your comic strip will be saved as:
strip-[style].png in the project folder.


