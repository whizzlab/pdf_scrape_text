# pdf_scrape_text
scrape research pdfs and convert to text for NLP and analysis

01_combined_scrape
Uses Pubmed-Batch-Download and scidownl in sequence to obtain pdfs from list of DOIs / PMIDS

02_pdf_to_text
Batch converts pdfs into text, creating dataframe for NLP annotation
Uses PyMuPDF / fitz
