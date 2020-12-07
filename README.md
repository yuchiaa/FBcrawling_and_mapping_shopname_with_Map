# FBcrawling_and_mapping_shopname_with_Map
Facebook private group online crawling and organizing the post contents.


## Facebook Private Group Posts Crawling
Run `the facebook_crawling.py` before setting your facebook username and password via .env and revise the chromedriver path if needed.


## Organizing the Post Contents
Run `fb_content_all_store.ipynb` to get the output `store_id_done.csv`.


## Mapping Shops' names 
Run `merge_fb_map.ipynb` to map the shops' names in `Map_Ramen_data.csv` and `store_id_done.csv`.
The final output tables are `fb_store_id_done.csv` and `map_store_id_done.csv`.

* The same `store_id` means that those shops' brands are the same, due to they have certain same keywords.

* `store_id` == '9999' means that the shop name is needed to be processed. 

* The non-related columns or rows can be deleted manually in the end.

