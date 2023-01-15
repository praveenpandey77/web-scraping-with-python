# web-scraping-with-python

## Scraping Movies and TV Show Details From Using Python
TMDB is a website where world's famous entertaining movies and TV Shows are available on the ranking of viewer's star ratings .This web site is free plate form for entertaining. This site has two section, first is releted to movies and second is based on TV shows. This website changes the content according to the viewer's ranking ratings. For scrapping topic TMDB has chosen because it changes the contents every week or may be every month as per the demand of viewers. Due to this reason it's database also changed simultaneously . Therefore the scrapping of web page is not same with the time. it is also observed that properties of HTML using to create web page also chages

For scrapping we are using website https://www.themoviedb.org

we are going to apply Python libraries request and after that we will call BeautifulSoup.

Built functions like get_titles(doc), date_movie(doc) ,all_details(urls) to parse titles, ratings etc data Stored data consisting of 100 rows x 3 column into TMDB.csv using Pandas

Here we will use first page of popular TV Show, Movies Now Playing, Movies Top Ratings, Movies Upcoming and main page of TMDB.

Here following stepes will be followed:

Download the webpage using requests

parse the HTML source code using beautifulSoup

Extract viewer's rating stars, titles of the movies and TV Shows, and it's releasing dates

compile extracted information into python list and dictionaries

Extract and combine data from the multiple page to give it 100 rows because each page having only 20 movies or tv shows details are available.

save the extracted information to a csv file
