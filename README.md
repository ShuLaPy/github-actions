# Repo to practice Github Actions

This repo is created to test the Github Actions to deploy this Simple react app created with `create-react-app --template typescript` on github-pages.


### Agenda of this github-actions

Whenever any branch is merged in main branch or any changes pushed to the main branch this event should trigger the github-actions

1. 🐧 Fist it should provision ubuntu-latest machine for our build process

1. 🛠️ Then it should install the required packages and start the build process

1. 🚀 On completion of build it should deploy the `build` folder on the `gh-pages` branch.