# CI-CD Pipeline for Nodejs, Circle CI, Heroku
This demo is practical demonstration of dockerizing app, continous integration using circle ci and deploy on heroku.



## Flow of a process
A picture is a graphical representation how git is integrated with circle ci and deploy built and tested image to heroku.

![nodejs-circlci-heroku](https://user-images.githubusercontent.com/21228768/159756507-38db0ac0-401e-496b-93ab-a6bb2f5e0c0a.png)

`
SETUP
- (Create a new project from template)
- Auth with CircleCI
- Pick project from list
- Docker account & Heroku account & app configured
- Set up environment values:
- $DOCKER_LOGIN
- $DOCKER_PASSWORD
- $HEROKU_APP_NAME
- $HEROKU_API_KEY
- $SNYK_TOKEN
`

Hope this will be good learning guide.
