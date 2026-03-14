# 🎬 Netflix Data Analysis

Exploratory Data Analysis (EDA) of Netflix movies dataset to uncover trends in genres, popularity, ratings, and release patterns using Python and interactive visualizations.

---

## 📁 Project Structure

```
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main Jupyter Notebook with full EDA
├── NetflixData.csv               # Dataset used for analysis
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 📊 Dataset

The dataset (`NetflixData.csv`) contains information about Netflix movies with the following columns:

| Column | Description |
|---|---|
| `Release_Date` | Date the movie was released |
| `Title` | Movie title |
| `Overview` | Short description of the movie |
| `Popularity` | Popularity score |
| `Vote_Count` | Number of votes received |
| `Vote_Average` | Average rating (out of 10) |
| `Original_Language` | Language of the movie |
| `Genre` | Genre(s) of the movie |
| `Poster_Url` | URL to the movie poster image |

---

## 🔍 Analysis Highlights

- **Genre Distribution** — Drama dominates as the most frequently occurring genre on Netflix.
- **Popularity by Genre** — Adventure movies lead in average popularity, followed by Action and Science Fiction.
- **Vote Average Distribution** — Explores how audience ratings are spread across all titles.
- **Release Trends** — Movie releases grew significantly post-2000, reflecting the rapid expansion of the streaming industry.
- **Popularity Distribution** — Highly skewed: most movies are average performers, with only a few blockbuster hits.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

```bash
jupyter notebook Netflix_Data_Analysis.ipynb
```

> **Note:** The notebook was originally created on Google Colab. If running locally, update the CSV path from `/content/NetflixData.csv` to `NetflixData.csv` in the data loading cell.

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** — Data loading and manipulation
- **Plotly Express** — Interactive visualizations
- **Jupyter Notebook** — Development environment

---

## 💡 Key Insights

- Drama is the most frequently occurring genre, indicating Netflix's heavy investment in drama content.
- Adventure movies show the highest average popularity — audiences strongly engage with exciting, high-energy content.
- Action and Science Fiction also enjoy high audience interest.
- The number of movie releases surged after 2000, reflecting the growth of global film production and streaming platforms.
- Overall, high-energy genres (Action, Adventure, Sci-Fi) tend to outperform in popularity scores.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
# Netflix-data-analysis
