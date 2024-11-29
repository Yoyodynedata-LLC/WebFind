# WebFind
Python application to search the web for keywords 
this will be a fully-automated process that can run on its own and store results in a NoSQL database in XML format 
will need to pull up a google search and extract sites from it 
will then load the first page on each website to review the html 

Using the BeautifulSoup to search websites for keywords 
Require an interface for keyword entry

will search through all known websites for keyword stored in the main page 
   get the title of the page to store with the web url and to use for calculation 

will create a method that can find new websites 
will search each website found for links coded into the html and add them to the list of known websites
   will find any well-formed links and store the root page along with any subdirectories 

   for link in soup.find_all('a'):
    print(link.get('href'))

will need a way of storing website urls with a category and a level of familiarity to identify the sites I use, the sites that are known and the discreet websites that do not show up on Google
