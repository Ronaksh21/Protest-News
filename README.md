# Protest-News
This Project Uses ACLED Database and Finds the links to each one of the News Summary and Then Uses those Links to Extract the Full Articles and then Re-summarize them.

# Flow for the Project:
1. Acled Database Extraction for India and Africa.
2. Shortening of Summary by using POS.
3. Using Summary for extracting best possible Urls by Google Search API.
4. Using News-Please for full aticle extraction from the Urls.
5. POS on the summary for the main actor, Date and Place.
6. Summarization of Article by PageRank.
