# test definitions

## requirements validation

-   owned by: qa
-   location: product backlog
-   impact: requirement quality increases, speeding up delivery
-   description: qa team members reviewing backlog items and calling out missed requirements, inconsistencies, or clarity issues to product and dev team

## unit testing

-   owned by: dev
-   location: dev local machine/IDE, dev environment
-   impact: confidence in quality code standards, smallest, fastest, earliest test to catch potetial defects
-   description: developer writing test code to validate a single 'unit' of code executes correctly

## functional testing

-   owned by: qa
-   location: test environment
-   impact: verification that developed code matches story and acceptance criteria
-   description: qa team members writing and executing manual test cases against user story to validate basic functional requirements are met

## regression testing

-   owned by: qa
-   location: test, staging, production environments
-   imact: catching a regression post-deployment to an environment to validate no existing functionality broken before a feature makes it to a user

---

# test tools

## test case management

-   test cases are written and managed in azure devops test plans
-   test plans are created per team, per sprint
-   each requirement/user story has a test suite containing that story's relevant test cases

## test automation

-   qa engineers utilize playwrite for web app automation
-   qa engineers utilize postman for api test automation
-   devs utilize junit for unit tests
-   all 3 are integrated into build pipelines to execute tests before or after a code builds and deploys to the dev, test, stg environments

## product management

-   dev, qa, and product utilize azure devops for product backlogs and sprint management
