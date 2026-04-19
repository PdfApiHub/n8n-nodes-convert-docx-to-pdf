# n8n-nodes-convert-docx-to-pdf

[![NPM Version](https://img.shields.io/npm/v/n8n-nodes-convert-docx-to-pdf.svg)](https://www.npmjs.com/package/n8n-nodes-convert-docx-to-pdf)
[![License](https://img.shields.io/npm/l/n8n-nodes-convert-docx-to-pdf.svg)](LICENSE.md)

> Convert Word, Excel, PowerPoint, and other office documents to PDF — supports 10+ input formats.

This is an [n8n](https://n8n.io/) community node powered by **[PDF API Hub](https://pdfapihub.com)**.

---

## 🚀 Install

1. Go to **Settings → Community Nodes** in n8n
2. Enter `n8n-nodes-convert-docx-to-pdf`
3. Click **Install**

## 🔑 Setup

Sign up at [pdfapihub.com](https://pdfapihub.com) → copy your API key → add to n8n credentials.

---

## ✨ Supported Input Formats

| Format | Description |
|--------|-------------|
| DOCX | Microsoft Word 2007+ |
| DOC | Microsoft Word 97–2003 |
| XLSX | Microsoft Excel 2007+ |
| XLS | Microsoft Excel 97–2003 |
| PPTX | Microsoft PowerPoint 2007+ |
| PPT | Microsoft PowerPoint 97–2003 |
| ODT | OpenDocument Text |
| ODS | OpenDocument Spreadsheet |
| ODP | OpenDocument Presentation |
| RTF | Rich Text Format |
| TXT | Plain Text |

### Features

| Parameter | Description |
|-----------|-------------|
| **Input Type** | URL, Base64, or Binary file |
| **Input Format** | Auto-detect or specify explicitly |
| **Output Format** | URL, Base64, Both, or Binary File |
| **Output Filename** | Custom filename for the PDF |

---

## 💡 Use Cases

- **Document pipeline** — convert uploaded Word docs to PDF automatically
- **Report generation** — transform Excel reports to PDF for distribution
- **Presentation archiving** — convert PPTX slides to PDF for storage
- **Email processing** — convert office attachments to PDF

## License

[MIT](LICENSE.md)
