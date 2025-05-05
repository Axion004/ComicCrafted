# 🎨 ComicCrafter — AI Comic Strip Generator

**ComicCrafter** uses Generative AI to create an entire comic strip from just a short scenario description. It integrates LLMs and text-to-image models to deliver creative comic panels styled in manga, Belgian, or American comic formats.

---

## 🚀 Features

1. **Panel Generation** – Uses OpenAI's GPT to split your scenario into six meaningful comic panels.
2. **AI Image Creation** – Uses StabilityAI’s Stable Diffusion to generate panel artwork.
3. **Text Overlay** – Adds dialog/narration to images.
4. **Comic Strip Output** – Merges all six panels into a complete comic strip!

---

## 🛠️ Technologies Used

* Python
* OpenAI API (LLM)
* Stability AI API (Stable Diffusion)
* LangChain
* Pillow (v9.5.0 or lower)

---

## 🛆 Installation

```bash
git clone https://github.com/yourusername/comiccrafter.git
cd comiccrafter
pip install langchain openai stability-sdk pillow==9.5.0
```

> 🔑 Don’t forget to export your API keys:

```bash
export OPENAI_API_KEY=your_openai_key
export STABILITY_KEY=your_stability_key
```

---

## ✏️ Usage

1. Edit the `SCENARIO` and `STYLE` variables in `kartoon.py` to define your story and style.
2. Run the script:

```bash
python kartoon.py
```

3. Your final comic strip will be saved as a `.png` file in the project folder.

---

## 📸 Example Scenarios

**Style: Belgium Comic**

> Francis, a medieval knight, hears about a dragon. He slays it, only to find it was the princess's friend.

**Style: Manga**

> Adrien and Vincent stay up all night creating a startup pitch. They present it the next day.

**Style: American Comic**

> Peter and Steven run for their lives as aliens attack New York. The army rescues them.

---

## 💡 350-character Description (for GitHub Summary)

AI-powered comic generator using GPT and Stable Diffusion to convert short scenarios into full comic strips. Outputs 6-panel stories styled as manga, Belgian, or American comics using OpenAI + Stability APIs.
