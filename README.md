# mincoin
Run the Jekyll webserver using `bundle exec jekyll serve`

### TODO:

Follow below step for create new language or translate home page content in different language:
1. In _config.yml
   under # Lang settings
   add #'nl': 'Nederlands' **[after complete translate remove #]**
   and its short code under lang_codes: like  - 'nl'
2. create file with lang codes like this **[nl.yml]** under  _data\langs
   In this file search word  #TRANSLATE HERE  and translate under this word like 
   **eg**
   meta:  #TRANSLATE HERE [description and title ] here need to translate [description and title ] text
	description: "Official MinCoin Website" to --->>> description: "Site officiel de MinCoin" 
	title: "MinCoin &#8211; Official MinCoin Website" to --->>> description: "MinCoin & # 8211; Site officiel de MinCoin"
	
3. create folder under langs with lang codes like langs/nl/index.html
   till translate/development assign **draft: true** after remove it
   





 