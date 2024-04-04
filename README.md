The purpose of document understanding is to extract, interpret, and process different types of documents such as PDFs, images, handwritten documents, etc.

Benefits include: 
•	Don’t need to purchase licenses for external ML tools/integrate them with UiPath as it all in one place
•	Reduced time and costs spent on manual document processing
•	Mitigates risk of human error when processing

So how does it work? 
1.	Load taxonomy – taxonomy is a collection of document types (ex: invoice). Here we define documents and data to be processed using the Taxonomy Manager.
2.	Digitize – use one of the available optical character recognition (OCR) engines to digitize the text and determine its location.
3.	Classify – classify the documents from the user-specified list.
4.	Extract – choose the most suitable extractors according to your document type (ex: invoice number, date, total)
5.	Validate – if needed, a human can check in to confirm or correct the extracted data or handle exceptions.
6.	Export – send the extracted info for further usage, for example, to email, spreadsheet, or SAP software.

The use case that I’ll be looking at is where I have multiple invoices that I need to process to extract specific fields (invoice number, date, total), and 
then export these pieces of information to an Excel.
