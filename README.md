# WikiRacer
WikiRacer is a web crawler that tries to find the shortest path between two Wikipedia articles.

***

### Requirements
The script was written in Python 2.7 and uses the `json`, `argparse`, `requests`, `BeautifulSoup`, `collections`, and `time` packages.

***


### Instructions for running
The `wikiracer.py` script takes a command line argument in the form of a JSON object. The JSON object must have a `"start"` name with a string value of the starting Wikipedia article and an `"end"` name with a string value of the ending Wikipedia article.

```
python wikiracer.py '{"start": "https://en.wikipedia.org/wiki/Battle_of_Cr%C3%A9cy", "end": "https://en.wikipedia.org/wiki/Wehrmacht"}
```


### Example results and times
Times may vary due to internet connection.

![image](https://github.com/sweetpand/WikiRacer/blob/master/Screen%20Shot%202020-09-21%20at%2010.53.48%20AM.png)
