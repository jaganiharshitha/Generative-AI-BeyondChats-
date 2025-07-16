# Reddit User Persona Generator

This project is a submission for the Generative AI Internship assignment at BeyondChats.

## 🧠 What It Does

Given a Reddit user profile URL, the script:
1. Scrapes the user’s latest posts and comments.
2. Analyzes the content to generate a user persona.
3. Outputs the persona as a `.txt` file, including citations to specific posts/comments.

## 🚀 Technologies Used

- Python 3
- [PRAW](https://praw.readthedocs.io/) – Reddit API wrapper (free to use)
- Google Colab compatible
- No paid APIs or login required

## 🛠️ How to Run

1. Clone the repository or upload files to your environment (e.g., Colab or local Python).
2. Install dependencies:
```bash
pip install praw
```
3. Add your Reddit API credentials at the top of the notebook/script:
```python
REDDIT_CLIENT_ID = "your_client_id"
REDDIT_SECRET = "your_secret"
REDDIT_USER_AGENT = "script:reddit-user-persona:v1.0 (by u/your_username)"
```
4. Run the script and enter a Reddit username (e.g. `kojied`).
5. A `.txt` file will be generated in the `output/` directory.

## 📁 Folder Structure

```
.
├── main.py
├── requirements.txt
├── output/
│   └── kojied_persona.txt
```

## 📄 Example Output

See `output/kojied_persona.txt` for a sample persona generated from real Reddit activity.

## 🧑‍⚖️ Disclaimer

This script only uses public data. Generated personas are fictional summaries based on behavioral patterns, not definitive character assessments.
