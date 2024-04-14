
## Requirements

* Python 3.8 or later
* NodeJS v18.12.1 or later
* Minimum 16GB of memory

## How to run

1. Go to client folder and run the below commands

   ```shell
   npm install   
   ```

   ```shell
   npm run dev
   ```

2. Go to server folder and run the below commands

   ```shell
   pip install -r requirements.txt
   ```

   ```shell
   python privateGPT.py
   ```

3. Open <http://localhost:3000>, click on download model to download the required model initially

4. Upload any document of your choice and click on Ingest data. Ingestion is fast (some example is puted in to the file , you can just click ingest data and ask question)

5. Now run any query on your data. Data querying is slow and thus wait for sometime


## Data

The supported extensions for documents are:

* .csv: CSV,
* .docx: Word Document,
* .enex: EverNote,
* .eml: Email,
* .epub: EPub,
* .html: HTML File,
* .md: Markdown,
* .msg: Outlook Message,
* .odt: Open Document Text,
* .pdf: Portable Document Format (PDF),
* .pptx : PowerPoint Document,
* .txt: Text file (UTF-8),
