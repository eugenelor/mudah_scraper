# mudah_scraper
A scraper that I made to scrape web data from Malaysian listings website Mudah.com to obtain all the listings under "Master Rooms" category.

The idea was to create a scraper from BeautifulSoup that would work on the listings on Mudah.com that grabs the following:
1) Post Date' - listing's posting date
2) 'Locality' - listing's locality
3) 'Desc' - listing's title 
4) 'Price' - price listed
5) 'Gender' - Gender Preferred for listing
6) 'Area' - Area of listed property in sq ft. Note that this might mean the size of the room listed or it could mean the size of entire property.
7) 'Property_Type' - Type of room listed. Defaulted to "Room"
8) 'Url' - URL of the listing
