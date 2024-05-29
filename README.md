# cLabs_Miscellaneous

Steps:
1. Ingestion from gdrive
2. Preprocessing of data
  1. Merging all documents into single text courpus
  2. Refining and eliminating redundancy
  3. Splitting text and converting it back into docs using RecursiveCharacterTextSplitter
3. LLMs:
   1. OpenAI (used with token limits)(not enough credit)
   2. HFHub (API tries exceeded)
   3. Ollama ( neither enough space nor data to download even Quantized models)
4. Summarization:
   1. Stuff (context window issue)
   2. Map reduce( used limit : 170 tokens)
   3. Refine ( used token limit: 10)
5. Converted to PDF
