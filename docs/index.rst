:title: Creating a Post or Page

**Writing It**
Create a new XML file in a text editor or code editor such as Notepad and name it something like helloworld.xml
Start by adding <?xml version="1.0" encoding="UTF-8"?> on the first line, then <page> on the next and </page> on the last
In between <page> and </page>, add <headline> and </headline> then write your title in between them
Create a new line and add <author> and </author> if you are writing a blog post, if not read on. Add an author's name in between
Create another new line and add <date> and </date> if you are writing a blog post, if not read on. Add a publication date in between
Create yet another new line and add <body> and </body> then add your body text in between
**Creating the page and uploading**
Duplicate the page.xml template file for the correct page type from the release you should have downloaded. Open it in a plain text or code editor such as Notepad and change the / in <xsl:template match="/"> to the name of your xml file you created in the last part (eg. helloworld.xml)
Then upload both of these files to your webserver (they could be in different folders, but if you followed the last step they must be in the same)
