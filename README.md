# OCR_qwen_txt
Supports both printed and handwritten text extraction.  Enhanced image preprocessing for better OCR performance.  Generates structured JSON output:  raw_text: full extracted text  lines: list of individual text lines  fields: dictionary of key-value pairs if identifiable  Handles invalid JSON   Uses Ollama to run Qwen2.5-VL locally


# Qwen2.5-OCR

**Qwen2.5-OCR** is an open-source Python tool for text extraction from document images (printed & handwritten) using Alibaba’s Qwen2.5-VL model via [Ollama](https://ollama.com).

## 🚀 Features

✅ Preprocesses images (grayscale, contrast, sharpen)  
✅ Sends images to Qwen2.5-VL via Ollama API  
✅ Outputs structured JSON with raw text, lines, and fields  
✅ Handles malformed JSON from the model with a fallback parser

---

## 📸 Example Usage

```bash
python main.py
