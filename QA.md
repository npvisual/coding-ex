## Introduction

The objectives of this exercise is to understand your ability to create validation projects using a testing framework of your choice.
It will also allow us to better comprehend how you'd go about managing testing in a realistic environment. 

You need to demonstrate that you can :
  * produce some tests and run jobs against an instance of Mperativ's application,
  * collect the test results and present that information

> __HINT :__ You can clone this repo locally and create new feature branch. You can then use your feature branch to submit a PR (pull request) against `dev` at the end of the exercise to present your masterpiece ! This is completely optional.


### 1. End-to-end tests

Using the URLs below, provide some tests that will validate the following areas : 
  * authentication
  * landing page
  * Active Sales Pipeline Growth in Revenue Insights

Those are the links to use : 
  - https://test.my.mperativ.de/login
  - https://test.my.mperativ.de/revenue-supply-chain
  - https://test.my.mperativ.de/revenue-insights/active-sales-pipeline-growth

Credentials : support+testqa@mperativ.de / Password123

### 2. API tests

In order to validate that the backend is performing properly and not breaking the frontend -- common root cause for e2e tests -- you should try and demonstrate that a few of the API endpoints are behaving properly.
You can use both positive and negative tests to demonstrate your findings.

To support your effort, you can take a look at the Swagger interface : 
  - https://test.api.mperativ.de/v1/swagger/index.html

Since the user we provide is not an Admin user, only some API endpoints will be available. Find a way to tell from the response provided. IF you can't immediately find an endpoint, we suggest looking at : 

  - https://test.api.mperativ.de/v1/filters


### 3. Present your findings

If you have time, use a tool of your choice (it could be the one you were using) to present your results (pass / fail).
Take this opportunity to explain : 
  * what you would do in case some or all of the test above (e2e and API) were in a FAIL state
  * how you would mock some of the tests while the development of the APIs is in progress


