# CI-CD Pipeline for Nodejs, Circle CI, Heroku
This demo is practical demonstration of dockerizing app, continous integration using circle ci and deploy on heroku.



## Flow of a process
A picture is a graphical representation how git is integrated with circle ci and deploy built and tested image to heroku.

![nodejs-circlci-heroku](https://user-images.githubusercontent.com/21228768/159756507-38db0ac0-401e-496b-93ab-a6bb2f5e0c0a.png)


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

## Pipeline Behavior on Triggering on code commit by Developer/Tester

- On the Failure of Test pipeline failed and stop further execution as shown below:

![Screenshot from 2022-03-25 16-12-04](https://user-images.githubusercontent.com/21228768/160149787-14d6098d-0b7c-469a-8ae1-52f56f7983e3.png)

- After Fixing the Tests pipeline runing for approval by authorized person for deployment as shown below:

![Screenshot from 2022-03-25 16-17-41](https://user-images.githubusercontent.com/21228768/160149836-529b164a-3563-41e1-b57b-146080f492fd.png)

- Pipeline succeeded and after build and test process image from dockerhub is deployed on Heroku server as shown below:

![Screenshot from 2022-03-25 16-18-20](https://user-images.githubusercontent.com/21228768/160149922-42610a48-953a-400b-b3b3-672241e5c5e5.png)

These workflow images can be really helpful for learner to know about how the whole pipeline process is executed.

Hope this will be good learning guide.
