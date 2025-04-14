# 🧠 Using LLMs to Classify Parliamentary Debates from the French National Assembly 🇫🇷

This project explores the use of Large Language Models (LLMs) to classify speeches from members of the French National Assembly based on their political group, using official transcripts of parliamentary debates.

## 📌 Goals

- Build a supervised dataset from the French National Assembly’s XML-formatted debates
- Fine-tune a CamemBERT model to classify speeches by political group
- Investigate the impact of speech themes and contextual information on classification performance

## 📂 Project Structure

- `data/`: raw XML files, processed datasets, and data processing scripts
- `notebooks/`: Jupyter notebooks for exploratory data analysis, training and evaluation
- `scripts/`: reusable scripts for parsing, training, and evaluation
- `models/`: trained models or links to model checkpoints (e.g. on Hugging Face)
- `results/`: evaluation metrics, visualizations, and reports
- `assets/`: images and graphics used in presentations or documentation

## 📊 Model & Results

_(To be updated with experiment results)_

| Model                   | DatasetSize | Number of Previous Interventions taken into account | Accuracy | F1 (macro) |
|-------------------------|-------------|-----------------------------------------------------|----------|------------|
| distilbert-base-uncased |      4450   |                         5                           |   53 %   |    54 %    |
| camenBERT               |      4450   |                         5                           |   53 %   |    54 %    |

## 🚀 Tech Stack

- Python
- Hugging Face Transformers
- scikit-learn
- pandas
- lxml / BeautifulSoup for XML parsing
- Matplotlib / Seaborn

## 📚 Data & Resources

- Official source: [Assemblée nationale – Open Data](https://www.assemblee-nationale.fr/)
- Pretrained model: [CamemBERT](https://camembert-model.fr/) (Martin et al., 2020)

## 👤 Author

**Augustin Viot**  
This is a personal project designed to deepen my expertise in Natural Language Processing and LLM fine-tuning, with a focus on applying AI to political discourse analysis.

## 📝 License

MIT License — feel free to use, modify and contribute.
