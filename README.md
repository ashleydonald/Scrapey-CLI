![fig1](/assets/fig1.png)

## Project Description

Scrapey-CLI extracts challenge solutions from CodeWars.com, stores them locally, and pushes them to Github.

## Getting Started

1. Clone this repo.
2. In the command-line navigate to the root of the project folder.
3. Enter `npm install`.
4. Login to your Github account, then make a new repository that will store the extracted Katas.
5. On your local machine create a directory for your extracted Katas. This should be seperate from the project folder containing the source code of the Scrapey-CLI tool.
6. At the root of the project create a `.env` file. Using the template below add the proper information:

```
CODEWARS_EMAIL=<Codewars Email>
CODEWARS_USERNAME=<Codewars Username>
CODEWARS_PASSWORD=<Codewars Password>
CODEWARS_TOKEN=<Codewars API Token>

DIR_PATH=<File path of your folder containing the Katas>

GITHUB_REPO=
  <
  Remote of the github repository,
    i.e. https://github.com/<Username>/<Repo Title>.git
  >
```

7. From the root of the Scrapey-CLI project folder enter `node index.js` to begin scrapeing your challenges.
