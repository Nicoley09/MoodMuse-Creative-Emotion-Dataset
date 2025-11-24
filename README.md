

**MoodMuse: Creative Emotion-to-Recommendation Dataset**

---

## **Description**

The MoodMuse dataset is a curated collection of creative content mapped to different emotional states. It is designed for projects that analyze user emotions and generate personalized recommendations, such as music, book quotes, affirmations, and aesthetic color palettes. This dataset powers the **MoodMuse interactive tool**, which transforms a user’s emotional input into fun, meaningful, and uplifting suggestions.

The dataset is ideal for **emotion-based recommendation systems**, **sentiment analysis**, and **creative AI projects**.

---

## **Dataset Contents**

The repository contains **five CSV files**:

| File Name            | Description                                                                        |
| -------------------- | ---------------------------------------------------------------------------------- |
| `songs.csv`          | Contains songs categorized by mood, including the song title and artist.           |
| `book_quotes.csv`    | Contains inspirational or mood-aligned book quotes with the book title and author. |
| `affirmations.csv`   | Contains positive affirmations linked to emotional states.                         |
| `color_palettes.csv` | Contains aesthetic color palettes for different moods (HEX codes).                 |
| `mood_keywords.csv`  | Contains keyword lists for each mood category to assist in NLP emotion detection.  |

---

## **Mood Categories**

The datasets use the following **six core mood categories**:

* Happy
* Sad
* Calm
* Stressed
* Motivated
* Romantic

---

## **File Formats**

All files are in **CSV format**, suitable for Python (Pandas), R, Excel, or any data processing tool.

---

## **Example Entries**

### songs.csv

| mood  | song_title | artist            |
| ----- | ---------- | ----------------- |
| happy | Happy      | Pharrell Williams |
| calm  | Yellow     | Coldplay          |

### book_quotes.csv

| mood     | quote                                                                                    | book          | author       |
| -------- | ---------------------------------------------------------------------------------------- | ------------- | ------------ |
| inspired | "And, when you want something, all the universe conspires in helping you to achieve it." | The Alchemist | Paulo Coelho |

### affirmations.csv

| mood     | affirmation                               |
| -------- | ----------------------------------------- |
| stressed | "Take a breath. You are doing your best." |

### color_palettes.csv

| mood | color1  | color2  | color3  |
| ---- | ------- | ------- | ------- |
| calm | #A8DADC | #457B9D | #F1FAEE |

---

## **Source**

The dataset is **manually curated** from publicly available, non-copyrighted sources including:

* Open book quote collections
* Public mood-based song lists
* Open-source color palette libraries

No copyrighted content is included; only metadata, titles, HEX codes, and short text.

---

## **Usage**

This dataset can be used to:

* Build **mood-based recommendation engines**
* Train **NLP models for emotion detection**
* Create **interactive applications** linking user emotions to music, books, and aesthetics
* Research **emotional well-being AI tools**

**Example usage in Python (Pandas):**

```python
import pandas as pd

songs = pd.read_csv('songs.csv')
print(songs.head())
```

---

## **License**

This dataset is provided for educational and research purposes.
Feel free to use, share, and modify it for non-commercial projects.

---

## **Contact**

For questions, suggestions, or collaboration:
**Nicole Mugo**

---



Do you want me to do that next?
# MoodMuse-Creative-Emotion-Dataset
