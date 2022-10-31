# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. spin up a github codespace at: https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=560149526 (No need to change anything in the default options, just click on the Create codespace button and wait for it to boot)
2. run docker compose up
3. test that backend by pointing your browser to https://stephenatwell-reimagined-umbrella-p6pq4rjp6qg36pwv-3000.githubpreview.dev/api/ping
4. Navigate to https://stephenatwell-reimagined-umbrella-p6pq4rjp6qg36pwv-3001.githubpreview.dev/register and create a new user.

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
