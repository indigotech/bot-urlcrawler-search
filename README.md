# Deployment to production - Required code changes

You need to replace the engine key on two files.

Replace `engineKey: 'T6stQ2m7sf88bS7x75Vk'` inside of jquery.swiftype.autocomplete.js  
Replace `engineKey: 'T6stQ2m7sf88bS7x75Vk'` inside of jquery.swiftype.search.js

This key gives this application read-only access to the search api provided by swiftype.

# Deployment to production - Swiftype search engine documents

There must be a document named links, created inside of a engine on Swiftype.com
This document should respect the following structure.

`{'links': ['url','title','description', 'keywords']}`

If you would like to update this strucutre, the `fetchFields` attribute must be changed on two files: jquery.swiftype.autocomplete.js and jquery.swiftype.search.js

# The future - To be implemented

- search by link author
- search by date
