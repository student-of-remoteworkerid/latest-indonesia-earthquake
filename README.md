# Latest Indonesia EarthQuake
This project will get the latest earthquake from BMKG | Indonesian Agency for Meteorology, Climatology, and Geophysics

## HOW IT WORK?
This package will scrape data from [BMKG](https://www.bmkg.go.id) to get the latest quake happened in Indonesia.

This package will use module BeautifulSoup4 and Requests, to produce output in the form of JSON that is ready to be used in web or mobile applications

## HOW TO USE
```
import earthquakelatest

if __name__ == '__main__':
    earthquake_in_indonesian = earthquakelatest.LatestEarthquake('https://bmkg.go.id')
    print(f'My application using package have description {earthquake_in_indonesian.description}')
    earthquake_in_indonesian.display_description()
    earthquake_in_indonesian.run()
```

# Author
Muhammad Shaufi Imanulhaq