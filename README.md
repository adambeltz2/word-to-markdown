# Word (.docx) to Markdown Converter 📝➡️💻

A lightning-fast, **100% client-side** web application that instantly converts Microsoft Word documents (`.docx`) into clean, formatting-rich Markdown.

🚀 **[Click Here to Use the Live App Now!](https://adambeltz2.github.io/word-to-markdown/)**

---

Built for developers, technical writers, and note-takers who want to move content from Word into repositories, Obsidian, Notion, or static site generators without losing their formatting.

## ✨ Features

- **🔒 Privacy First (Zero Backend):** No data ever leaves your computer. The entire conversion process happens locally inside your browser window.
- **🛠️ High-Fidelity Conversion:** Preserves complex formatting including nested bullet points, bold/italics, headers, blockquotes, and hyperlinks.
- **📊 Table Support:** Automatically maps Word tables into clean GitHub-Flavored Markdown (GFM) tables.
- **📋 One-Click Copy:** Easily copy the generated markdown straight to your clipboard.
- **🎨 Modern UI:** Sleek, responsive interface built with Tailwind CSS.

## 🚀 How to Use

1. Navigate to the [Live Link](https://adambeltz2.github.io/word-to-markdown/).
2. Click the upload area or **drag and drop** your `.docx` file into the box.
3. Click the **Convert Document** button.
4. Your Markdown will instantly generate in the output box below.
5. Click **Copy Code** and paste it into your favorite Markdown editor or IDE!

## 🧠 Under the Hood

This application does not rely on a server or API. Instead, it combines two powerful open-source client-side libraries:

1. **[Mammoth.js](https://github.com/mwilliamson/mammoth.js):** Parses the complex binary structure of the `.docx` file and generates clean, semantic HTML based on document styles.
2. **[Turndown.js](https://github.com/mixmark-io/turndown):** Takes that semantic HTML and runs it through a robust conversion engine to produce strict, perfectly formatted Markdown (with the GFM plugin enabled for table support).

## 🌐 Hosting it Yourself

Because this is a static, client-side application, hosting it is incredibly easy and completely free. 

**Deploy to GitHub Pages in 60 seconds:**
1. Fork or clone this repository.
2. Go to your repository's **Settings** tab.
3. Select **Pages** from the left sidebar.
4. Under *Build and deployment*, set the Source to **Deploy from a branch**.
5. Select the `main` branch and click **Save**.

## 📜 License

This project is open-source and free to use. Not responsible for edge-case formatting discrepancies originating from heavily stylized or non-standard Word documents.
