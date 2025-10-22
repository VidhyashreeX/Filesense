

# FileSense – Intelligent File Management of files through content analysis

FileSense is a desktop-based application that intelligently analyzes and organizes files based on their content. Leveraging modern AI technologies, including large language models (LLMs) and multimodal models, it classifies both text and image files to reduce digital clutter and improve productivity. The system offers a seamless user experience with a Python + Flask backend and Electron frontend.

---

## Features

- **Content-Aware Classification**: Automatically categorizes files using AI models like Qwen2, CLIP, and BART.
- **Supports Multiple Formats**: Handles text documents (.txt, .pdf, .docx) and images (.jpg, .png, etc.).
- **Zero-Shot Classification**: No prior training needed for new or unseen files.
- **User Control**: Dry-run mode allows users to review AI-suggested organization before applying changes.
- **Desktop-Friendly Interface**: Built with Electron for a responsive and intuitive desktop experience.
- **Privacy-Safe**: All file processing happens locally with no cloud dependency.


---

## Tech Stack

- **Backend**: Python, Flask
- **Frontend**: Electron.js
- **AI Models**: Qwen2 LLM, CLIP, BART
- **Other Tools**: Zero-shot classification, semantic analysis

---

## Getting Started

### Prerequisites

- Python 3.8+
- Node.js 18+
- Electron 25+
- Required Python packages listed in `requirements.txt`

### Installation

1. Clone the repository:
```bash
git clone https://github.com/VidhyashreeX/Filesense.git
cd Filesense
```

2. Install backend dependencies:
```bash
pip install -r requirements.txt
```

3. Install frontend dependencies:
```bash
npm install
```

4. Start the application:
```bash
npm start
```

---

## Usage

1. Open FileSense on your desktop.
2. Add the folder or files you want to organize.
3. Choose to run the AI-based analysis.
4. Review the suggested file organization in dry-run mode.
5. Accept to apply changes, and FileSense will reorganize files into content-aware folders.

---
