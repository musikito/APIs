# How to write a file(HTML) with the fs system
We will be accesing the Google sheet API to grab values from the sheets and
writing it up into a HTML file.

# Pre-requesite
you need the following prerequisites:
Node.js & npm installed.
A Google account.
The ID of the sheet that you want to access.
Create a new Cloud Platform project and automatically enable the Google Sheets API.
DOWNLOAD CLIENT CONFIGURATION and save the file credentials.json to your working directory.
Run the following commands to install the libraries using npm:

npm install googleapis@27 --save

In the index.js file change the PLACE HOLDER for your sheet ID.
Change the cell range that oyu want to access.

Run the script by typing:

node . 

If it is the first time running the script, you need to validate the access to the shhets, the script
will guide you.



