# Generative Arabic Sayings   
* `scraping data` folder goes throgh the steps taken to scrape 3 websites to gather the Arabic sayings
* `preprocessing_all_scraped_data.ipynb` combines all scraped data and apply several pre-processing on them to generate a signle file `all_sayings_data.txt`
* `Arabic sayings_finetune_GPT2.ipynb` fine-tunes a GPT-2 model using the `all_sayings_data.txt` for over 100K steps.
* `model_output_samples.txt` shows the GPT-2 model output during the fine-tuning every 500 steps as part of framing infomation.
* To download the fine-tuned model use this link https://drive.google.com/file/d/1t96VoAH2Vlk5WPql0J2Sz74L7xydZYNu/view?usp=sharing
