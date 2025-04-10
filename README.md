# 📩 SMS Spam Detection Challenge

## 🔍 Overview

This project is focused on building a **machine learning model** to classify SMS messages as either:

- **Ham**: A normal message sent by a friend or contact.
- **Spam**: An unwanted or promotional message typically sent by a company.

The challenge uses the **SMS Spam Collection dataset**, which is already divided into training and test datasets.

---

## 🧠 Objective

Create a function named `predict_message` that:

- Accepts a **string message** as input.
- Returns a **list** containing:
  1. A float between `0` and `1` — the likelihood that the message is spam (closer to 1 = more spammy).
  2. A string — either `"ham"` or `"spam"` depending on the prediction.

### Example:
```python
predict_message("Win a brand new iPhone! Click here to claim.")
# Output: [0.92, "spam"]
