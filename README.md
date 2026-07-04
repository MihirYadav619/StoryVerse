# StoryVerse

StoryVerse is a semantic book recommendation system built to explore vector databases, embeddings, and large language models.

Unlike traditional keyword search, StoryVerse recommends books based on the meaning of a user's query. Users can also filter recommendations by genre, emotion, and minimum rating.

---

## Features

- Semantic book search
- Genre filtering
- Emotion-based filtering
- Rating filter
- AI-generated explanations for recommendations
- Interactive web interface built with Gradio

---

## Tech Stack

- Python
- Pandas
- LangChain
- ChromaDB
- Sentence Transformers
- Hugging Face Embeddings
- Mistral AI
- Gradio

---

## Project Structure

```
StoryVerse/
│
├── app.ipynb                 # Final application
├── README.md
├── requirements.txt
│
├── chroma_db/                # Vector database
│
├── data/                     # Dataset
│
├── notebooks/
│   ├── 01_preprocessing.ipynb
│   ├── 02_document_indexing.ipynb
│   ├── 03_zero_shot.ipynb
│   ├── 04_emotion.ipynb
│   ├── 05_genre_normalisation.ipynb
│   └── 06_gradio.ipynb
│
```

---

## How it Works

1. User enters a search query.
2. The query is converted into vector embeddings.
3. ChromaDB retrieves semantically similar books.
4. Genre, emotion and rating filters are applied.
5. Mistral generates explanations for the recommended books.
6. Results are displayed in the Gradio interface.

---

## Running the Project

Clone the repository

```bash
git clone https://github.com/MihirYadav619/StoryVerse.git
```

Move into the project directory

```bash
cd StoryVerse
```

Install the required packages

```bash
pip install -r requirements.txt
```

Open **app.ipynb** and run all cells.

---

## Future Improvements

- React frontend
- FastAPI backend
- User authentication
- Personalized recommendations
- Reading history
- Cloud deployment

---

## Author

**MihirYadav**