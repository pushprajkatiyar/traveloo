# traveloo
a travel blog by pushpraj



## Setting up

##### Clone the repoo

```
$ git clone https://github.com/aviabird/traveloo.git
$ cd traveloo
```

##### Install npm dependencies
```
$ npm install
```
##### Additional Settings

For Social login to work you need to create an app on faceook and google and note down the client id and secret id of individual app.
Below are instructions for creating app on inidviudal social media site

1. <strong>Google</strong> : [Creating App Engine Project and Application](https://developers.google.com/ad-exchange/rtb/open-bidder/google-app-guide)
2. <strong>Facebook</strong> : [Creating a New Facebook App](https://developers.facebook.com/docs/apps/register)

Once you have created the app,rename `secret.ts.example` file in `app` folder to `secret.ts` and replace the dummy string with client id of respective social app.

## Development server frontend
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Deploying to Github Pages

Run `ng github-pages:deploy` to deploy to Github Pages.

