# AI-Based Bilingual Activity Matcher

A sophisticated bilingual activity matching system that processes and validates business activities in French and Arabic using advanced NLP techniques.

## ✨ Features

- Bilingual text processing (French & Arabic)
- Smart activity validation against existing and forbidden activities
- Multiple similarity detection methods:
  - TF-IDF vectorization
  - BERT embeddings (using multilingual-mpnet)
  - Fuzzy string matching
- Field-based statistical analysis
- Batch processing optimization
- Detailed debugging capabilities

## 🚀 Getting Started

### Prerequisites

```bash
pip install -r requirements.txt
```

### Usage

1. Initialize the preprocessor.
2. Load your data.
3. Preprocess the data.
4. Initialize and use the matcher.

## 📊 How It Works

1. **Text Preprocessing**:

   - Language detection (Arabic/French)
   - Stopword removal
   - Text normalization
   - Special character handling

2. **Similarity Analysis**:

   - TF-IDF based similarity (30% weight)
   - Fuzzy string matching (30% weight)
   - BERT semantic similarity (40% weight)

3. **Validation Process**:
   - Field statistics calculation
   - Activity pattern validation
   - Similarity checking against existing activities
   - Forbidden activity detection

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 🙏 Acknowledgments

- Built using state-of-the-art NLP libraries
- Optimized for bilingual text processing
- Designed for scalability and accuracy
