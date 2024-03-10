# Protected-pdf-converter

So, here comes the scenario...
You get password protected sensitive pdf documents from your clients or workplace or whatever, and if you are trying to type the password and download the file without password each time, here is your time saver!
I have created a code for extracting your documents if they are password protected. 
All you want to do is:
1. Keep all your protected documents in a folder in your google drive.
2. Give the same folder name in the code at old_pdf_dir.
3. Create a new folder to keep extracted pdf files.
4. Give the folder name in the code at new_pdf_dir.
5. At pdf_pass, store your passwords.

Yaay! you are ready to go. 
My code will go through each document in old_pdf_dir and try each passwords given. If any one of it get worked, hurreyy! The pdf gets extracted and stored in new_pdf_dir.
Don't worry, your old_pdf_dir won't get affected!
