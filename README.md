# HLTV-Match-Data-Scraper
The script expects 2 command line arguments. The first is the team name which is case sensitive and if there are spaces will still be space seperated. The next command line argument should be the number of matches to scrape.
Each match will produce its own csv file as output.
Examples:

1. 'python get_data.py Grayhound 10' 
- Will retrieve the 10 most recent match data for Grayhound. 
2. 'python get_data.py Natus Vincere 5'
- Will retrueve Navis 5 most recent match data.
