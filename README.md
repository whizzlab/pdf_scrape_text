# pdf_scrape_text
scrape research pdfs and convert to text for NLP and analysis

**01_combined_scrape**

Adaptation of [Pubmed-Batch-Download](https://github.com/billgreenwald/Pubmed-Batch-Download) and [scidownl](https://github.com/Tishacy/SciDownl), used in sequence to obtain pdfs from list of DOIs / PMIDS. Notebook calls fetch_pubmed.py.

**02_pdf_to_text**

Batch converts pdfs into text, creating dataframe for NLP annotation
Uses PyMuPDF / fitz
