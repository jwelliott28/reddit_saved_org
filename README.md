# reddit_saved_org
Uses PRAW package to access a Reddit user account, gathers saved links and attributes related to links, and organizes them in to a .xlsx file.

# Current Status
Accesses Reddit using the Python package "PRAW". Asks for username and password to desired Reddit account. Upon intake and successful login, the program scans all of the described user's saved links and stores data about them. This data is currently separated in to four categories: submission title, submitting user's profile name, current score, and the subreddit it was saved from. The data is written to a .xlsx workbook that is created earlier in the script. 

# Plans for later versions
* Allow user to decide what to name the document and where on their computer to store it
* Create a worksheet for each unique subreddit found in the saved submissions
* Add the html for each saved submission so that it can be accessible

