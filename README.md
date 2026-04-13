# 📰 News Fetcher (Python CLI Project)

A simple Python-based command-line application that fetches the latest news headlines using the NewsAPI.

This project allows users to select a news category and view the top headlines along with descriptions and article links.

---

## 🚀 Features

* Fetches real-time news using NewsAPI
* Category-based news selection (e.g., business, sports, technology)
* Displays:

  * Headline
  * Short description
  * Article link
* Simple and clean CLI interface

---

## 🛠️ Tech Stack

* Python
* Requests library
* NewsAPI

---

## 📂 Project Structure

```
News_Fetcher/
│── main.py        # Main program logic
│── config.py      # Stores API key (not pushed to GitHub)
│── topics.py      # Category mappings
│── .gitignore     # Ignored files
```

---

## ⚙️ Setup & Installation

1. Clone the repository:

```
git clone https://github.com/your-username/News_Fetcher.git
cd News_Fetcher
```

2. Install dependencies:

```
pip install requests
```

3. Add your API key:

Create a file named `config.py` and add:

```python
api_key = "YOUR_API_KEY"
```

Alternatively (recommended), use environment variables.

4. Run the program:

```
python main.py
```

---

## 📌 Usage

* Select a category from the list displayed in the terminal
* The program will fetch and display the top 5 latest news articles

---

## ⚠️ Note

* API keys are not included in this repository for security reasons
* Make sure to generate your own API key from NewsAPI

---

## 📈 Future Improvements

* Add keyword-based search
* Add pagination (more articles)
* Improve UI (GUI or web version)
* Add error handling for API failures

---

## 👩‍💻 Author

* Arpita Sutariya

---
