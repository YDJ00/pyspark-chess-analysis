\# PySpark Chess Analysis



Analyze large-scale chess games using \*\*PySpark\*\*. This project processes PGN datasets, extracts useful insights, and generates meaningful visualizations.



---



\## 📊 Visualizations



\### Overall Heatmap of Checkmating Squares



!\[Overall Heatmap of Checkmating Squares](images/Overall\_Heatmap\_of\_Checkmating\_Squares.png)



\### Scatter Plot: Bullet vs Classical



!\[Scatter Plot Bullet vs Classical](images/scatter\_plot\_bullet\_vs\_classical.png)



\### Opening Success Rate



!\[Opening Success Rate](images/opening\_success\_rate.png)



\### Square Where King Delivers Checkmates



!\[Square Where King Delivers Checkmates](images/square\_where\_king\_delivers\_checkmates.png)



\### Histogram of Checkmates by Piece



!\[Histogram of Checkmates by Piece](images/histogram\_of\_checkmates\_by\_piece.png)



\### Distribution of Ratings



!\[Distribution of Ratings](images/distribution\_of\_ratings.png)



---



\## 📁 Project Structure



```

chess\_project/

├── images/

│   ├── Overall\_Heatmap\_of\_Checkmating\_Squares.png

│   ├── scatter\_plot\_bullet\_vs\_classical.png

│   ├── opening\_success\_rate.png

│   ├── square\_where\_king\_delivers\_checkmates.png

│   ├── histogram\_of\_checkmates\_by\_piece.png

│   └── distribution\_of\_ratings.png

├── data/

├── processed/

├── 1\_download.ipynb

├── 2\_decompress.ipynb

├── 3\_process\_parititon.ipynb

├── 4\_moves\_partition.ipynb

├── 5\_visualizations.ipynb

├── requirements.txt

└── README.md

```



---



\## 🛠 Tech Stack



\* \*\*Python 3.x\*\*

\* \*\*PySpark\*\*

\* \*\*Pandas, NumPy\*\*

\* \*\*Plotly, Matplotlib, Seaborn\*\*

\* \*\*Rich, Psutil, Zstandard\*\*



---



\## 🚀 Setup \& Usage



```bash

\# Clone the repo

git clone git@github.com:YDJ00/pyspark-chess-analysis.git

cd pyspark-chess-analysis



\# Create and activate venv

python3 -m venv .venv

source .venv/bin/activate



\# Install dependencies

pip install -r requirements.txt



\# Ensure Java \& Spark are installed

java -version

spark-submit --version

```



Run the notebooks in order:



1\. `1\_download.ipynb`

2\. `2\_decompress.ipynb`

3\. `3\_process\_parititon.ipynb`

4\. `4\_moves\_partition.ipynb`

5\. `5\_visualizations.ipynb`



---



\## 📬 Contact



\*\*Author:\*\* Yash Jadhav

\*\*GitHub:\*\* \[YDJ00](https://github.com/YDJ00)

\*\*Email:\*\* \[yash918jadhav@gmail.com](mailto:yash918jadhav@gmail.com)



