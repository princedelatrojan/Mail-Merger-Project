

---

# Python Mail Merger Project

## Overview
This project automates the creation of personalized emails by merging a predefined template with recipient data. The Python script reads information from a CSV file and generates customized emails for each recipient.

## Requirements
- Python 3.x
- `pandas` library

You can install the required package using:

```bash
pip install pandas
```

## Usage
1. **Prepare Your Email Template:**  
   Create a text file (e.g., `email_template.txt`) with placeholders like `{name}`, `{email}`, and `{message}`.

2. **Prepare Your Data File:**  
   Store recipient details in a CSV file (e.g., `recipients.csv`) with headers corresponding to your placeholders.

3. **Run the Script:**  
   Execute the script to generate personalized emails:

   ```bash
   python mail_merger.py
   ```

## License
This project is licensed under the [MIT License](LICENSE).

---
