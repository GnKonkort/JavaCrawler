# JavaCrawler  
A simple web scraper and crawler that scans and follows urls in search for unique emails.
## Usage
```
./app [url] [search level]
```
Where 
- url - initial web page url from which to start crawling
- level - the depth of search (how many external urls app should follow)

## Building from source
Simply run 
```
./gradlew clean build
```
This will create distribution packages in build subdirectory
