# Retrieve Blocked Gmail Attachments
Whenever Gmail blocks an attachment due to virus scan, we have to go for other means to download it. This script is inspried from the blog http://spapas.github.io/2014/10/23/retrieve-gmail-blocked-attachments/.

#Steps
- Download the code as a zip file or clone it
- For the email message that has the attachment, use the dropdown beside the reply button and select "Show original" option. Save the content of this file as message.txt (or anything)
- Open a terminal or command prompt and run `python extract.py message.txt`
- The attachment will be saved in the parent folder of extract.py

Amazing. Isn't it!
