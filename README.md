# indian-railways-seat-availability

Usage:

```python3 crawl --src=<src station code> --dest=<dest station code> --class=<SL|1A|2A|3A|CC|FC|2S> --date=<date of travel in %Y%m%d>```

This script helps you get confirmed seats on indian trains if you can't finding direct tickets from station A to station B on irctc.
It does the following things:
* Fetches the list of train that goes from station A to station B
* For all the trains it checks for availability between all pairs of stations that encapsulates route from station A to station B and reports that availability.
* Once you find availability on any of the pair you can go to irctc and book your ticket
