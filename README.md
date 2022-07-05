# Fullstack Assignment

Because we at Exxeta love music very much, we would like to ask you to create a music library app for us with the following requirements:

- music albums are shown to the user
- new albums can be added / existing ones can be edited or deleted
- albums can be rated (1 to 5 scala)
- albums with rate more than 4 can only be deleted if there are less than 10 ratings - we don't want someone to delete our favorite albums by mistake ;) 

### Backend

Create an executable web server application:

- implemented in any language
- store album data (name, artist, release date, ...) in any database
- provides an API to retrieve/update album data
- has unit tests

### Frontend

Create a web app that:

- implemented in any language
- calls the backend and retrieves the album information
- shows a grid of albums (thumbnails, cards, etc.)
  - items in the grid show up to four items per row and gracefully degrade to a vertical list on narrow screens
- shows album details (large image or other information available from the API's response) when an album is clicked
- has some unit tests 
- uses web fonts (eg. Google Fonts)
