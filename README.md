# gmail-collector
*Initial investigations*

will move to a more mail driven model - helps with load balancing as well
python/node app to listen to webhooks to recieve mails and work on them 
- a server will listen to mail notifications through gmail push notifications, read the mail, do the required job, and complete the process/maybe send a notification?

Required Process - 
Phase 1 : 
 - read mail
 - read attachments
 - save with required filenames as discussed
 - save it to Google Drive as a PDF/change to Gdoc format?
 - parse all data 
 - save it to a database
 
 Phase 2 : 
 
 TBD


Another Avenue : 

Use Google Cloud Scripts - listen to webhooks mails, save attachments to drive with required names, save as pdfs, parse PDFs, save parsed data to database(where are we hosting the database, how are we saving the data)?
