# 🔁 PDF Reorder Tool

This simple Python-based tool allows you to **reorder the pages of any PDF file** based on custom input. It's built using the powerful `PyMuPDF` library and runs smoothly in **Google Colab** or any local Python environment.

---

## 🚀 Features

- 📤 Upload any PDF file
- ✏️ Specify a custom page order (e.g., `2,0,1`)
- 📄 Reorders pages exactly as specified
- 📥 Download the reordered PDF
- ✅ Works on scanned or standard PDFs

---

## 🛠 Built With

- Python
- [PyMuPDF (`fitz`)](https://pymupdf.readthedocs.io/en/latest/)
- Google Colab (for easy upload & download UI)

---

## ▶️ How to Use (Colab)

1. Open this notebook in [Google Colab](https://colab.research.google.com/)
2. Run the cell to install dependencies
3. Upload your PDF file
4. Enter the new page order (comma-separated, e.g., `3,2,0,1`)
5. Download the reordered PDF

---

## 💡 Example

For a 4-page PDF, to reverse the order:

```text
Enter new page order:
3,2,1,0
