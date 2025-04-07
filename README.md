# ir-project-book-recommendations
Judging a Book by its Cover: Visual Features in LTR on the BookCrossing Dataset
# IR Project: Book Recommendations

This project, explores book recommendation systems by leveraging visual features, text embeddings, and user representations. The project uses the BookCrossing dataset to build and evaluate recommendation models.

---

## Project Structure

### 1. **Dataset Preparation**
- **File:** `dataset_prep.ipynb`
- **Description:** 
  - Prepares the BookCrossing dataset for further use.
  - Includes data filtering.
### 2. **Add Image URLs**
- **File:** `add_image_urls.ipynb`
- **Description:** 
  - Adds image URLs to the processed book dataset.

### 3. **Visual Feature Extraction**
- **File:** `visual_extraction.ipynb`
- **Description:** 
  - Extracts visual features from book covers.
  - These features are integrated into the recommendation model to enhance its performance.

### 4. **Text Embeddings**
- **File:** `text-embeddings.ipynb`
- **Description:** 
  - Generates text embeddings for book titles.
  - These embeddings are used as features in the recommendation model.

### 5. **Dataset Splitting**
- **File:** `dataset_split.ipynb`
- **Description:** 
  - Splits the dataset into training, validation, and test sets.

### 6. **User Representation Split**
- **File:** `user_representation_split.ipynb`
- **Description:** 
  - Retrieves 10 highest ratings per user
  - Splits these 10 ratings in 8 used for reading history and 2 for testing. 

### 7. **User Representation**
- **File:** `User_representation.ipynb`
- **Description:** 
  - Constructs user representations based on their interactions with books.

### 8. **Dual Encoder (Basic)**
- **File:** `DualEncoderTraining_Basic.ipynb`
- **Description:** 
  - Implements a dual encoder model for book recommendations for baseline model.

### 9. **Dual Encoder (Visual)**
- **File:** `DualEncoderTraining_Visual.ipynb`
- **Description:** 
  - Implements a dual encoder model for book recommendations for multimodal model.

### 10. **Model Training**
- **File:** `new-training.ipynb`
- **Description:** 
  - Trains the recommendation model using the prepared dataset.

---

## Dataset

The project uses the **BookCrossing Dataset**, which contains user ratings, book metadata, and other relevant information. The dataset is processed and stored in CSV format for analysis.

---

## Authors

- **Mirella Günther**
- **Lucia Navarčíková**
- **Domi Chabior**
- **Tereza Ležovičová**

---

## Acknowledgments

This project was developed as part of an Information Retrieval (IR) assignment.

---