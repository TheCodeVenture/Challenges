Hacker News top stories with github authentication

##User Story
Users should be able to sign up in the application using their github accounts, since they are logged in behind a protected route a list of the top stories of hacker news should be presented.
User should be able to see the details of those stories (number of comments, score and creation date), when a user click on the comments counter those comments should be presented in the screen without forcing the user to leave the current page.
The list should have a mechanism to perform pagination of those stories, when the user picks a story he should be redirected to that respective story url.

###Requirements
- This app should be developed in JavaScript both for backend and frontend.
- You could use a database if you feel like it
- User experience is also evaluated

###References
- [GitHub Oauth](https://developer.github.com/v3/oauth/)
- [Hacker News API](https://github.com/HackerNews/API)

###Example
![hackernews](/imgs/hackernews.png)
