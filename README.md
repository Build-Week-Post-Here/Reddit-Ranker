# Reddit Ranker

You can find the project at [RedditRanker](https://post-here-frontend-n33nsapg6.now.sh/).

## Contributors
[Samuel Hepner](https://github.com/samuelhepner)
----------------------------------------------------------------------------------------------------------- 
[<img src="https://ca.slack-edge.com/T4JUEB3ME-UJ5GAHMS7-abc28b1e9d94-512" width = "200" />](https://github.com/samuelhepner)

[<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/samuelhepner)|
[ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/samuel-hepner/)  


## Project Overview

The idea of this project was to develop a web app that users could submit their reddit post and get back a list of subreddits that they could submit their post.

### Tech Stack

 -   Languages: Python
 -   Libraries: Pandas, Scikit-Learn, Pickle, NLTK, and Flask
 -   Services: Flask and Heroku

### Predictions

The DS API takes in a JSON object of a reddit post, generates a list of subreddits, and spits out a JSON object with the subreddits. The current API is using TfidfVectorizer, NLTK wordnet Lemmatizer, regexp_tokenize, and a Random Forest Classifier model.

### Explanatory Variables

-   Text of the post

### Data Sources

-   Reddit API

### Python Notebooks

[Python Notebook link](https://github.com/Build-Week-Post-Here/Reddit-Ranker/blob/master/BW2.ipynb)

## Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](./code_of_conduct.md.md). Please follow it in all your interactions with the project.

### Issue/Bug Request

 **If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**
 - Check first to see if your issue has already been reported.
 - Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
 - Create a live example of the problem.
 - Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes,  where you believe the issue is originating from, and any potential solutions you have considered.

### Feature Requests

We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.

#### Pull Request Guidelines

- Ensure any install or build dependencies are removed before the end of the layer when doing a build.
- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

### Attribution

These contribution guidelines have been adapted from [this good-Contributing.md-template](https://gist.github.com/PurpleBooth/b24679402957c63ec426).
