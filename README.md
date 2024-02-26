A web application that allows ot parse given sites and collect information from them. Two sites are given by default:
a Ukrainian State Bank and a financial news site.

A scraper parses information, stores in the MySQL DB and supports different filters.

Technologies used:
Flask, Scrapy, MySQL, Docker, Docker-Compose.

To run it locally you need to:

1. Launch the docker daemon
2. cd /path/to/project/folder
3. Run "docker-compose up --build" in the terminal
4. Wait ~2-3 mins till the docker images will be built and pulled
5. Run app on http://127.0.0.1:5000
