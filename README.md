# Deployment to production - Required changes

You need to replace the engine key on two files.

Replace `engineKey: 'T6stQ2m7sf88bS7x75Vk'` inside of jquery.swiftype.autocomplete.js  
Replace `engineKey: 'T6stQ2m7sf88bS7x75Vk'` inside of jquery.swiftype.search.js

This key gives this application read-only access to the search api provided by swiftype.
