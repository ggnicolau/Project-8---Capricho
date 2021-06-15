<div align="center">
<img src="https://coursereport-production.imgix.net/uploads/school/logo/84/original/logo-ironhack-blue.png?w=200&h=200&dpr=1&q=75">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTx0OPgRAs3027QxPjMtXI-1UtLxObz5x6rpvb5bVfEASQJ19fs9Bi14CLOOwwhtJoYXw&usqp=CAU">
</div>


<div align="left">

[![](https://readme-typing-svg.herokuapp.com/)](https://git.io/typing-svg)
</div>
<!--GITHUB_ACTIVITY:{"rows": 5}-->

---

<div align="center">

[visitors](https://visitor-badge.glitch.me/badge?page_id=ggnicolau.visitor-badge)](https://badges.pufler.dev)
[![Created Badge](https://badges.pufler.dev/created/ggnicolau/Project-7-Hospital-Challenge)](https://badges.pufler.dev)
[![Updated Badge](https://badges.pufler.dev/updated/ggnicolau/Project-7-Hospital-Challenge)](https://badges.pufler.dev)
[![Commits Badge](https://badges.pufler.dev/commits/monthly/ggnicolau)](https://badges.pufler.dev)
[![Repos Badge](https://badges.pufler.dev/repos/ggnicolau)](https://badges.pufler.dev)
[![Years Badge](https://badges.pufler.dev/years/ggnicolau)](https://badges.pufler.dev)
[![ggnicolau StackOverflow](https://stackoverflow-badge.vercel.app/?userID=15673147)](https://stackoverflow.com/users/15673147/ggnicolau)

![+5511976431347](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![ggnicolau](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![ggnicolau@usp.br](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)
![https://www.linkedin.com/in/ggnicolau/](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)
![Python 3.9](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![pgAdmin](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Atom](https://img.shields.io/badge/Atom-66595C?style=for-the-badge&logo=Atom&logoColor=white)
![Windows 10 Pro](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=ggnicolau&show_icons=true&theme=darcula)
</div>
<!--GITHUB_ACTIVITY:{"rows": 5}-->

---

<div align="left">
<div class=''text-justify''>

# CAPRICHO: Brazilian Teen Magazine
I've decided to apply a template for Capricho's website as a NLP experiment.


#### Technologies
* Python version  3.9


#### Tools
* Atom
* Jupyter IPython

#### Services
* Github

#### Python Libraries
* gensim
* pyLDAvis
* sklearn
* nltk
* stop_words
* os
* time
* matplotlib
* random
* wordcloud
* re
* numpy
* pprint
* logging
* texthero
* pandas
* IPython
* warnings
* csv
* numpy
* gensim
* matplotlib
* operator
* re
* os
* warnings
* tqdm
* requests
* BeautifulSoup
* selenium
* time
* requests
* spacy
* pt_core_news_lg
* collections
* json

## Workflow
Capricho is a classic teen magazine from Brazil read by many generations. Nowadays they're also on the internet. Their website is dynamic and it's not easy to extract with traditional web scraping methods.

We decided to extract all articles published at their website.

* First we used Selenium so we could open the full list of articles from the dynamic website. Then we extracted all the links appeared and we put it on a Pandas DataFrame.
* Thus, we used BeautifulSoup to isolate each variable we want for each news. We isolated and extracted post-id, date, author, title, subtitle and text. We put it all in the same DataFrame.
* Then we extracted the 100 most important entities (places, people, blogs etc) for the average brazilian teen. We also extracted the most active authors.
* Further, we preprocessed all the text removing stopwords, weblinks, punctuation, diacritics, digits, whitespace, NaNs. We also applied lowercase for all of our text.
* At last we've applied our Topic Model template to generate tagclouds and pyLDAvis visualizations.

## Exploring CAPRICHO
I've extracted all 41327 news from Capricho Magazine dynamic website using BeautifulSoup and Selenium. Capricho is a teen magazine from Brazil.
* Those are the most active authors:
> Da Redação                                                              8874
> Gabriela Zocchi                                                         3919
> Isabella Otto                                                           2333
> Bruna Nobrega                                                           1913
> Amábile Reis                                                            1561
> Sofia Duarte                                                            1526
> Izabel Gimenez                                                           939
> Mel Trench                                                               935
> Isabella Massoud                                                         933
> Chames Oliveira                                                          775
> Aline Fava                                                               713
> Amanda Oliveira                                                          637
> Vitória Macedo                                                           615
> Amanda Caroline                                                          555
> Thais Varela                                                             448
> Anny Caroline Guerrera                                                   417
> Juliana Costa                                                            407
> Marcela Bonafé                                                           400
> Gabriela Junqueira                                                       397
> Taís Ilhéu                                                               342
> Ana Carolina Castro                                                      250
> Beatriz Arruda                                                           227
> Djenifer Dias                                                            215
> Personare                                                                214
> Juliana Morales                                                          211
> Débora Romanini                                                          194
> Gustavo Balducci                                                         182
> Bia Luisi                                                                151
> Vand Vieira                                                              122
> Redação                                                                  122
> Priscila Harumi                                                          119
> Bruno Dias                                                               105
> Danih                                                                     78
> Jordana Pires                                                             72
> Malu Pinheiro                                                             22
> Adrieny Magalhães                                                         21
> Letícia Albuquerque                                                       20
> Marô Rodrigues                                                            16
> Melissa Ery                                                                9
> Lidia Anjos                                                                8
> Malú Damázio                                                               7

I also did a NER model using SpaCy.
* those are the 100 most popular entities for the average teen in Brazil:
> [["Look do Dia", 1435], ["Anitta", 753], ["Brasil", 660], ["Kylie Jenner", 616], ["Selena Gomez", 604], ["Taylor Swift", 502], ["Bruna Marquezine", 497], ["Justin Bieber", 491], ["Instagram", 490], ["Netflix", 469], ["Ariana Grande", 460], ["Demi Lovato", 426], ["Neymar", 381], ["Meghan Markle", 366], ["Larissa Manoela", 358], ["BBB20", 311], ["Kendall Jenner", 300], ["Kim Kardashian", 296], ["Maisa", 285], ["Camila Cabello", 274], ["Katy Perry", 272], ["Rihanna", 262], ["Gigi Hadid", 262], ["Disney", 256], ["Luísa Sonza", 230], ["Blog da Galera", 221], ["Ludmilla", 219], ["Marina Ruy Barbosa", 209], ["Harry Styles", 207], ["Riverdale", 205], ["Miley Cyrus", 203],, ["Shawn Mendes", 178], ["Manu Gavassi", 174], ["Ed Sheeran", 168], ["Bella Hadid", 167], ["Beyoncé", 158], ["Twitter", 154], ["Pabllo Vittar", 146], ["BTS", 143], ["Stranger Things", 142], ["Lili Reinhart", 142], ["Zendaya", 139], ["Paris", 138], ["It Girls", 138], ["OMG!", 134], ["BBB21", 134], ["Harry Potter", 130], ["Millie Bobby Brown", 130], ["Lucy Hale", 130], ["BBB19", 125], ["Tatá Werneck", 124], ["Bianca Andrade", 123], ["Natal", 123], ["Bella Thorne", 122], ["Harry", 121], ["Kéfera", 119], ["Enem", 118], ["Halloween", 118], ["Game of Thrones", 118], ["Billie Eilish", 116], ["Hailey Bieber", 115], ["Fifth Harmony", 115], ["Teste:", 114], ["Sophie Turner", 114], ["BBB21:", 112], ["BBB18", 112], ["Hailey Baldwin", 111], ["Luan Santana", 108], ["Emma Watson", 102], ["Kate Middleton", 102], ["Oi?", 100], ["Lady Gaga", 99], ["Flavia Pavanelli", 98], ["Noah Centineo", 98], ["Whindersson Nunes", 96], ["Carnaval", 96], ["K-pop", 95], ["Joey King", 94], ["Zayn", 94], ["Liam Payne", 93], ["Kylie", 92], ["Camila Mendes", 87], ["Vanessa Hudgens", 86], ["Sasha", 86], ["Nina Dobrev", 84], ["Cole Sprouse", 83], ["Oscar", 83], ["Cara Delevingne", 82], ["Nick Jonas", 81], ["São Paulo", 81], ["Insta", 80], ["Juliette", 79], ["Dua Lipa", 75], ["The Weeknd", 74], ["Eita!", 74], ["Ashley Benson", 73], ["Drake", 73], ["Snapchat", 72], ["Dove Cameron", 71], ["Lana Condor", 70], ["Little Mix", 70], ["Joe Jonas", 70], ["Maisa Silva", 70], ["Reasons Why", 70], ["Lollapalooza", 69], ["Globo", 67], ["Rock in Rio", 66], ["Rafa Kalimann", 65]]

At last we've created a Topic Model using LDA algorithm and generated 30 topics from our full Corpus.
* Those are the tagclouds from some topics:


<div align="center">
<img src="https://github.com/ggnicolau/Project-8-Capricho/blob/main/visualizations/capricho_filter_full_clean4.png">
<img src="https://github.com/ggnicolau/Project-8-Capricho/blob/main/visualizations/capricho_filter_full_clean17.png">
<img src="https://github.com/ggnicolau/Project-8-Capricho/blob/main/visualizations/capricho_filter_full_clean22.png">
<img src="https://github.com/ggnicolau/Project-8-Capricho/blob/main/visualizations/capricho_filter_full_clean23.png">
<img src="https://github.com/ggnicolau/Project-8-Capricho/blob/main/visualizations/capricho_filter_full_clean26.png">
<img src="https://github.com/ggnicolau/Project-8-Capricho/blob/main/visualizations/capricho_filter_full_clean11.png">
</div>

As we can see most of the subjects are about fashion, customs, body, relationships and celebrities. Not much different from when I were a teen. But we've noticed some differences: the celebs are more diverse (non-white) than before, so as customs and relationships (non-heterossexual). Thus, the Magazine take in account heavy subjects such as racism, police violence and sexual offense. So, some is still the same, some have changed and as usual, a lot of contradition.


**But isn't the world contraditory?**


## Scripts & Files
* Repository: https://github.com/ggnicolau/Project-8-Capricho
* Python Files: https://github.com/ggnicolau/Project-8-Capricho/tree/main/py_files
* Tables:  https://github.com/ggnicolau/Project-8-Capricho/tree/main/tables
* Visualizations: https://github.com/ggnicolau/Project-8-Capricho/tree/main/visualizations
* Model: https://github.com/ggnicolau/Project-8-Capricho/tree/main/Models

## Versioning

1.0.0.0

## Autor

* **Guilherme Giuliano Nicolau**: @ggnicolau (https://github.com/ggnicolau)

</div>

<!--GITHUB_ACTIVITY:{"rows": 5}-->

---

<div align="center">

<br/><br/>
![Quote](https://github-readme-quotes.herokuapp.com/quote?theme=dark&animation=grow_out_in)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ggnicolau&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

![https://medium.com/@ggnicolau](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)


</div>
