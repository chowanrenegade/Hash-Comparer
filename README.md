# Hash Comparer

A simple, client-side utility to verify if two cryptographic hashes (like MD5, SHA-1, or SHA-256) are identical. This is particularly useful for verifying file integrity or ensuring that a downloaded file matches the checksum provided by the source.

---

## ✨ Features

* **Case-Insensitive Comparison:** Automatically converts inputs to lowercase to prevent false mismatches caused by casing.
* **Whitespace Trimming:** Removes accidental leading or trailing spaces from the input fields.
* **Visual Feedback:** Provides instant color-coded results (Green for a match, Red for a mismatch).
* **Privacy-Focused:** Performs all logic locally in the browser; no data is sent to a server.

---

## 🧠 How It Works

The tool uses a basic string comparison algorithm in JavaScript:

1.  **Normalization:** The script captures values from the input fields, applies `.trim()` to remove extra spaces, and `.toLowerCase()` to standardize the characters.
2.  **Validation:** It checks if both fields contain data before proceeding.
3.  **Strict Equality:** It uses the `===` operator to check if the two strings are bit-for-bit identical.



---

## 🛠️ Installation & Usage

1.  **Save the file:** Copy the source code into a file named `hash-comparer.html`.
2.  **Launch:** Open the file in any web browser.
3.  **Input:** Paste your first hash (e.g., from a website) into the first box.
4.  **Compare:** Paste your second hash (e.g., generated from your local file) into the second box and click **"Compare Hashes"**.

---

## 📝 Use Case Example

If you download a software installer
