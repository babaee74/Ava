# Ava dataset: 
**An open source Persian voice donation project for TTS and STT developments**

### Donate Your voice [Here](https://ava-dataset.com)  (will be up soon)




# Introduction:

Unfortunately, unlike other languages, Persian does not have any AI assistants such as Alexa, Google, etc. This is primarily due to several reasons. First, the existing datasets, such as the Mozila dataset, are not big enough. Second, the Persian language consists of people with a rich and vast culture with various accents, and in current datasets, speakers are limited to four to five people and often recorded in the formal language. Finally, as of our knowledge, there is no fund or efforts of what so ever from the government or universities in this direction, or if it even exists, it is not public! . **We have seen the power of open sourcing in the AI community, and we believe this is the key step on this path.**

The great Ferdowsi has tried for 30 years to preserve Persian culture and language. **This work is a drop before his work but may help us improve the language.** Moreover, Iranian always shown great kindness when it comes to helping and donating, We are more than sure that they will contribute more that our expectation.



متاسفانه، برخلاف زبان های دیگر، زبان فارسی هیچ گونه دستیاری همانند الکسا و گوگل و ... ندارد. برای این مشکل دلایل زیادی وجود دارد. اول اینکه دادگان فارسی بزرگی وجود ندارد و داده هایی مانند موزیلا به اندازه کافی بزرگ نیستند. همچنین زبان فارسی یک زبان غنی شامل مجموعه ای از فرهنگ ها و لهجه هاست و دیتاست های موجود معمولا به زبان رسمی و توسط چهار پنج گوینده بیان می شوند. در آخر هم اینکه، تا جایی که ما خبر داریم، هیچ گونه تلاش و یا حمایتی از طرف دولت حاکم و دانشگاه ها برای بهبود این مشکل انجام نشده است و اگر هم شده است، در دسترس همگان به صورت منبع باز قرار نگرفته است!. **ما بر این باوریم که منبع باز کردن یک روش و قدم خوب در این زمینه است، همانطوری که در انجمن هوش مصنوعی این اتفاق باعث پیشرفت چشمگیر شده است**


فردوسی بزرگ ۳۰ سال برای نگه داری زبان و فرهنگ پارسی تلاش کرد. این کار قطره ای کوچک در مقابل چیزیست که او انجام داده است. باشد که در بهبود زبان پارسی کمک کند. علاوه بر این، ایرانیان همواره در کمک کردن و هدیه دادن پیش قدم بوده اند و مطمئن هستیم اگر این کار به گوششان برسد بیشتر از انتظار کمک خواهند کرد.




## Goals and Approaches

The Digikala magezines and website contains a rich amount of articles and comments that are formal and colloquial. The articles cover almost all of our daily life and can be considered as a good source for words we use in todays Farsi. Other than that, the comments on the products are mostly in the colloquial language and are considered a good source for training any language or TTS model.

We first crawled all of the links of the articles, then we crawled all the paragraphs inside the articles. The dataset contains more than 53,000 articles with more than 1,100,000 sentences. Additionally, the dataset will contain more than 80,000 comments and more than 150,000 sentences. In total, if we have 1 person/sentence donation for each sentence, there will be more than 7,000,000 seconds (1944 Hours) of voices for the texts.

Simultaneously, we are developing a website for people to donate their voices. the website is designed so that while people are donating their voices, they also read the sentences from the same article. This way they feel more engaged and also can learn from the articles.

The article cover everyday subjects:
1- Technology
2- Game and Entertainment
3- Books and Literature
4- Culture and Art
5- lifestyle
6- Digikala daily news and magezines

The comments are also about products and are mostly in Persian colloquial language.

This is our current progress and next steps (the bold steps are done or about to be done).

**1- Collect article links.**

**2- Crawl the articles.**

**3- save them on a PostgreSQL for backend and public use.**

**4- Developing the website backend and frontend.**

5- Purchasing the server and an S3 storage.

6- Run a campaign on LinkedIn and Instagram (we will ask individuals active in literature and art to advertise us if they would like).

7- Publish Ava on HuggingFace.


## Contact Us

To participate in this project or help run the campaign, please email me at **mresi.team@gmail.com**
