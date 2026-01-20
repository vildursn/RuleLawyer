

# 🎲 RuleLawyer

**RuleLawyer** is a lightweight, extensible framework for building a board game rules assistant using Retrieval-Augmented Generation (RAG). Upload your rulebooks (PDFs), process them into searchable chunks, and query them using a local interface powered by OpenAI.

---

## 🧠 What It Does

- 🔍 Extracts text from board game rule PDFs
- ✂️ Splits text into manageable chunks
- 🧬 Embeds the chunks using OpenAI's embedding model
- 🤖 Answers questions about rules using semantic search + GPT

---

## 🚀 Getting Started

1. Clone the repo

```bash
git clone https://github.com/vildursn/RuleLawyer.git
```

2. Install necessary packages
```bash
   pip install -r requirements.txt
```

3. Create a folder inside `data/raw` for your rulebook, and upload your PDF(s) into that folder

4. Add your OpenAI key to the .env file

5. Run the following

### Extract and chunk rulebooks
```bash
python src/ingest.py
```
### Embed the text chunks
```bash
python src/embed.py
```

### Ask questions (WIP)
```bash
python src/gui.py
```
