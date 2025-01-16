# Books Repository

This repository contains PDF books used by the QuizMaker API. The PDFs are stored using Git Large File Storage (Git LFS).

## File Structure

- `compressed_books/`: Contains compressed PDF files
- Each PDF follows the naming convention: `compressed_[book-name].pdf`

## Available Books

- bangla-sahitto
- bgs
- chemistry
- english
- ict
- dhromo
- biology
- physics
- bangla-sohopat
- bekaron

## Using Git LFS

This repository uses Git LFS to handle large PDF files. To clone and use this repository:

1. Install Git LFS:

```bash
git lfs install
```

2. Clone the repository:

```bash
git clone https://github.com/siam500561/books.git
```

3. Pull LFS files:

```bash
git lfs pull
```

## Note

- PDF files are tracked using Git LFS
- Maximum file size: 2GB per file
- Total repository size: ~154MB
