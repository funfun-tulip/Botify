# Made with :heart: by a :banana: developer :ghost:

This program makes a telegram chatbot from any webpage with any html-table. As an example you can see how it made a chatbot from a wikipedia's table of HOMM3 creatures stats. User can query a chatbot with natural language, ask questions with reasoning, e.g. 'which unit does have maximum defence?'.
Currently only telegram supported.

Usage: $python bofily.py -help

After creating new chatbot you need to go to 'botname' folder and edit database, using any software(e.g. DB Browser SQLite), because automatically created default field names probably are not very useful, then substitute "botname.sql" file with "Export db to sql dump file..." menu option. 

For example we are making a chatbot which answer questions about Heroes 3 unit's stats. Table name 'List_of_creatures_The_Heroes_of_Might_and_Magic_III_wiki_html1' is not right, we need it to be 'heroes3 units creatures characters'. And field name "Def" we substitute with "strength defense". And this way for all fields, user will be able to query db with any of this synonyms.
