Professional Nim Programming – Code Extracts

This archive contains all the code examples extracted from the book Professional Nim Programming, organized chapter by chapter for easy navigation.

📂 Folder Structure

chapter-01/, chapter-02/, …
Each folder corresponds to a chapter in the book. Inside you’ll find the code snippets that appeared in that chapter.

snippet-XXX.nim
Standard Nim source files. Most of the examples in this book are written in Nim.

snippet-XXX.yml
YAML configuration files (often for GitHub Actions or CI pipelines).

snippet-XXX.toml
TOML configuration files (e.g., nimble package definitions).

snippet-XXX.json
JSON data files used in examples.

snippet-XXX.sh
Shell script examples (build scripts, environment setup).

snippet-XXX-Dockerfile
Docker build definitions.

snippet-XXX-Makefile
Makefile examples for automation.

MANIFEST.csv
A catalog listing all snippets with their chapter, snippet number, filename, and the first line of code.

🔎 How Files Were Extracted

Code blocks were detected based on formatting (monospace text, indentation, and keywords like proc, import, FROM, etc.).

Contiguous code-like paragraphs were grouped into one snippet.

File extensions were inferred from context:

Nim code → .nim

Docker examples → Dockerfile

Makefiles → Makefile

YAML/TOML/JSON → respective formats

Shell commands → .sh

Unknown → .txt

🗂 How to Use

Browse to the chapter folder you’re interested in.

Open the snippet files directly in your text editor or IDE.

Use MANIFEST.csv to quickly search for examples (e.g., by keyword in the first line).

You can run the Nim files with the Nim compiler, or adapt the config files for your own environment.

⚠️ Disclaimer

These code extracts are provided for educational purposes. They are copied as-is from the source material and may require adaptation to run on your system. Refer to the original book for full explanations and context.
