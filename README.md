# Plagiarism Checker

This Python script is designed to check for plagiarism among a set of text documents.

## Usage

Run the script, providing two command-line arguments:
- Input file containing a list of file names.
- The output file for recording similarity metrics.

## input.txt

    ```
    input_file_1.txt input_file_2.txt scores.txt
    ```

## Code Description

- `vectorize(Text)`: Function for vectorizing a list of text documents using TF-IDF.
- `similarity(doc1, doc2)`: Function for calculating cosine similarity between two documents.
- `check_plagiarism()`: The main function that reads the list of files, vectorizes the text, and compares the similarity between each pair of documents.
