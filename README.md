# WordTally
Web application that displays frequencies of English token words.

In bash run:
```
python -m venv env 
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
```

Enter URL (beginning w/ http:// or https://) and press submit to view English token words, as identified by [punkt.english.pickle](https://github.com/MattLondon101/Word-Tally-Two/blob/main/nltk_data/tokenizers/punkt/english.pickle) from [Natural Language Toolkit (NLTK)](https://www.nltk.org/), and with [stop words](https://github.com/MattLondon101/Word-Tally-Two/blob/main/stop_words.py) filtered out.
&nbsp;


<p align="center">
  <img width="1000" height="1000" src="https://github.com/MattLondon101/Word-Tally-Two/blob/main/WordTally.png?raw=true"
</p>
