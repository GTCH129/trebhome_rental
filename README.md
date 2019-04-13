# trebhome_rental
rental repo

Request method: GET

url= "https://listings.trebhome.com/listings?%24loc=Toronto&%24zoom=0&%24latitude=35.422943522054865&%24longitude=0&%24orderby=price&saleOrRent=RENT&latitude=%3E%3D-89.91227567527925&latitude=%3C%3D89.9766532819623&longitude=%3E%3D-180&longitude=%3C%3D180&%24gid=treb&class=FREE&class=CONDO&availability=A&_min_price=%24300&price=%3E%3D300&price=%3C%3D50000&area=Toronto&%24take=3164"

Request filter:
Loc: Toronto
min_price: $300 ( exclude locker and parking spot lease priced below $300)
max_price:$50,000

Web Scraping method: Use BeautifulSoup and Requests in Python ( see Request py code file )
 
Request Header:
ID
Address
Bedrooms
Bathrooms
Type
Price

The final output dataset is written as " rental1.csv".




