# CleanCSV
https://clean-csv-bice.vercel.app/

AI-powered CSV &amp; Excel cleaner that runs entirely in the browser. Drop in a messy spreadsheet, describe what you want fixed in plain language (Turkish or English), and download the cleaned result. CleanCSV / Tarayıcıda çalışan, yapay zeka destekli CSV ve Excel temizleme aracı. Dosyanızı bırakın, ne istediğinizi yazın, temizlenmiş veriyi indirin.

**About**

CleanCSV is a privacy-first data cleaning tool built for analysts, researchers, and anyone tired of wrestling with messy spreadsheets. Instead of writing pandas scripts or hunting through Excel menus, you just drop in your file, describe what you want in plain language ("trim whitespace from names", "convert dates to ISO format", "fill empty city cells with Unknown"), and let an AI model produce a clean, downloadable result.
Everything runs in your browser — your CSV or Excel file is parsed locally with papaparse and xlsx, and the AI provider you choose is called directly from the client using your own API key. No backend, no upload server, no data retention. If you'd rather not send anything to a third party at all, plug in a local Ollama model and the entire pipeline stays on your machine.
**License**
MIT

