# Web scraper for TripAdvisor

This project involves creating a custom dataset to train a machine-learning model for identifying locations in London based on user-provided images. Initial attempts to find suitable datasets on platforms like Kaggle were unsuccessful, prompting the development of a new dataset using web scraping. Selenium was employed for automated web browsing to navigate TripAdvisor and locate popular London attractions, while BeautifulSoup was used to scrape image URLs from these pages. Challenges included TripAdvisor's anti-bot measures, which were mitigated using the `undetected-chromedriver` library to disguise Selenium's activities, and the recent updates to Selenium and BeautifulSoup methods, which required adapting to new techniques. Resource constraints, such as unstable internet and limited computational power, were managed by optimizing BeautifulSoup with different parsers. Ultimately, 200 attractions were selected, and over 100 images per attraction were scraped and stored in a Pandas DataFrame, then saved as pickle and CSV files for future model training. This comprehensive dataset now supports the development of models to identify London locations based on images accurately.

Please check https://github.com/yasiruTJ/TripAdvisor_Scraper/blob/main/gg.csv and other sample CSV files provided, to witness the findings of the scraper in different stages.


## List of packages and version numbers used

Package                      Version

absl-py                      2.1.0

appnope                      0.1.4

asttokens                    2.4.1

astunparse                   1.6.3

attrs                        23.2.0

beautifulsoup4               4.12.3

bs4                          0.0.2

cachetools                   5.3.3

certifi                      2024.2.2

charset-normalizer           3.3.2

click                        8.1.7

clip                         1.0

comm                         0.2.1

contourpy                    1.2.0

cycler                       0.12.1

debugpy                      1.8.1

decorator                    5.1.1

dill                         0.3.8

dm-tree                      0.1.8

executing                    2.0.1

filelock                     3.13.1

flatbuffers                  23.5.26

fonttools                    4.49.0

fsspec                       2024.2.0

ftfy                         6.1.3

gast                         0.5.4

google-auth                  2.28.1

google-auth-oauthlib         1.2.0

google-pasta                 0.2.0

grpcio                       1.62.0

h11                          0.14.0

h5py                         3.10.0

html5lib                     1.1

idna                         3.6

install                      1.3.5

ipykernel                    6.29.2

ipython                      8.21.0

jedi                         0.19.1

Jinja2                       3.1.3

joblib                       1.3.2

jupyter_client               8.6.0

jupyter_core                 5.7.1

keras                        2.15.0

kiwisolver                   1.4.5

libclang                     16.0.6

lxml                         5.1.0

Markdown                     3.5.2

markdown-it-py               3.0.0

MarkupSafe                   2.1.5

matplotlib                   3.8.3

matplotlib-inline            0.1.6

mdurl                        0.1.2

ml-dtypes                    0.2.0

mpmath                       1.3.0

multiprocess                 0.70.16

namex                        0.0.7

nest-asyncio                 1.6.0

networkx                     3.2.1

nltk                         3.8.1

numpy                        1.26.4

oauthlib                     3.2.2

opt-einsum                   3.3.0

outcome                      1.3.0.post0

packaging                    23.2

pandas                       2.2.0

parso                        0.8.3

pathos                       0.3.2

pexpect                      4.9.0

pillow                       10.2.0

pip                          24.0

platformdirs                 4.2.0

pox                          0.3.4

ppft                         1.7.6.8

prompt-toolkit               3.0.43

protobuf                     4.25.3

psutil                       5.9.8

ptyprocess                   0.7.0

pure-eval                    0.2.2

pyasn1                       0.5.1

pyasn1-modules               0.3.0

Pygments                     2.17.2

pyparsing                    3.1.1

PySocks                      1.7.1

python-dateutil              2.8.2

pytz                         2024.1

pyzmq                        25.1.2

regex                        2023.12.25

requests                     2.31.0

requests-oauthlib            1.3.1

rich                         13.7.1

rsa                          4.9

scikit-learn                 1.4.1.post1

scipy                        1.12.0

selenium                     4.18.1

setuptools                   65.5.0

six                          1.16.0

sniffio                      1.3.0

sortedcontainers             2.4.0

soupsieve                    2.5

stack-data                   0.6.3

sympy                        1.12

tensorboard                  2.15.2

tensorboard-data-server      0.7.2

tensorflow                   2.15.0

tensorflow-estimator         2.15.0

tensorflow-io-gcs-filesystem 0.36.0

tensorflow-macos             2.15.0

termcolor                    2.4.0

threadpoolctl                3.3.0

torch                        2.2.1

torchvision                  0.17.1

tornado                      6.4

tqdm                         4.66.2

traitlets                    5.14.1

trio                         0.24.0

trio-websocket               0.11.1

typing_extensions            4.9.0

tzdata                       2024.1

undetected-chromedriver      3.5.5

urllib3                      2.2.1

useragent                    0.1.1

wcwidth                      0.2.13

webencodings                 0.5.1

websockets                   12.0

Werkzeug                     3.0.1

wheel                        0.42.0

wordcloud                    1.9.3

wrapt                        1.14.1

wsproto                      1.2.0






