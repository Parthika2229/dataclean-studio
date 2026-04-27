# 🧹 DataClean Studio

A powerful, browser-based data cleaning tool. Upload your messy CSV, TSV, or JSON files and clean them in seconds — no installation, no account, no API key required.

🔗 **Live Demo:** [parthika2229.github.io/dataclean-studio](https://parthika2229.github.io/dataclean-studio)

---

## ✨ Features

### 🔍 Overview & Issues
- Instant data preview table
- Auto-detects missing values, duplicates, and type mismatches
- Color-coded cells for quick issue spotting

### ♻️ Deduplicate
- Remove duplicate rows by full row or specific column
- Keep first, last, or remove all duplicates
- Case-sensitive or case-insensitive matching

### 🕳️ Handle Missing Values
- Drop rows with empty cells
- Fill with mean, median, or zero
- Fill with a custom value
- Add an `_is_missing` flag column

### ⚙️ Transform & Format
- Trim leading/trailing whitespace
- Lowercase column headers
- Remove special characters
- Normalize numbers (remove commas)
- Standardize dates to YYYY-MM-DD
- Remove empty columns
- Collapse multiple spaces
- Strip HTML tags
- Text casing: UPPER, lower, Title, Sentence

### 🧹 Filter & Trim
- Filter rows by column conditions
- Conditions: contains, equals, starts with, ends with, greater than, less than, is empty, and more
- Keep or remove matching rows

### ✅ Validate & Flag
- Type mismatch detection
- Outlier detection (IQR method)
- Email format validation
- Phone number format check
- Date validity check
- Negative value flagging

### 💾 Export
- Export as CSV, TSV, or JSON
- Optional header row and row index
- Custom filename

---

## 🚀 How to Use

1. Open the [live tool](https://parthika2229.github.io/dataclean-studio)
2. Upload a CSV, TSV, or JSON file
3. Review detected issues in the **Overview** panel
4. Apply cleaning operations from the sidebar
5. Export your cleaned file

---

## 📁 Supported File Formats

| Format | Extension | Notes |
|--------|-----------|-------|
| CSV | `.csv` | Comma-separated, with header row |
| TSV | `.tsv` | Tab-separated, with header row |
| JSON | `.json` | Array of objects |
| TXT | `.txt` | Treated as CSV |

---

## 💡 Sample Test File

Want to try it out? Use the included [`sample-messy-data.csv`](./sample-messy-data.csv) which contains:

- Duplicate rows
- Missing values
- Invalid emails
- Inconsistent casing
- Extra whitespace
- Mixed date formats
- Type mismatches
- Negative values

---

## 🛠️ Tech Stack

- Pure HTML, CSS, JavaScript
- Zero dependencies
- No backend or server required
- Works 100% in the browser
- No data is uploaded anywhere — everything stays on your device

---

## 📦 Self Hosting

Just download `index.html` and open it in any browser. That's it.

Or deploy to any static hosting:
- GitHub Pages
- Netlify
- Vercel
- Any web server

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

Made with 💚 by [parthika2229](https://github.com/parthika2229)
