# Samatar Axmed - CV

Software engineer, most definitely T-shaped.

Passionate **teacher** and **learner**.


---


## Contents

- [Experience](#experience)
- [Teaching Experience](#teaching-experience)
- [Open Source Contributions](#open-source-contributions)
- [Languages](#languages)
- [Links](#links)


---


## Experience

<img src="assets/founders_and_coders_ml_logo.avif?raw=true" alt="founders-and-coders-ml-logo" />

### [Founders And Coders](https://foundersandcoders.com) | Machine learning apprenticeship | May 2026 - May 2027
One year machine learning apprenticeship for experienced software engineers and data scientists. 

Tech: RAG systems, Transformers, MLOps, Autonomous agents

- Building a RAG system from scratch; source ingestion, chunking, embedding, vector search, re-ranking and generation. 


---


<img src="assets/supply25_logo.png?raw=true" alt="supply25-logo" />

### [Supply25](https://supply25.com) | Senior software engineer | Remote | Jan 2026 - Present
Building the future of public procurement with close friends

Tech: Typescript, Node.js, React, AWS (CDK, DynamoDB, Lambdas), Playwright

Product:
- Allowing buyer organisations to create custom assessments for their potential suppliers. This is a big feature ask as buyers may have slightly different requirements that aren't defined in the canonical cyber security and accessibility assessments. 

Quality:
- Setup integration tests for the backend services using localstack and then its community/free edition got dropped a couple of weeks later 😅 (Luckily testing against a dynamodb container gives us the same level of confidence as before)
- Setup a CI/CD pipeline for all services and apps entailing:
	- Code quality checks on all packages on every PR before merge
	- A release workflow on merge to main that runs an E2E test suite hitting the critical flows
	- Upon success, deploy to staging followed by a manual approval to production
- Helping the company obtain ISO 27001 certification, adding things like Point-in-Time Recovery on databases and other best practices and of course whatever else gets flagged 😆
- Created an infrastructure package containing cdk constructs with good defaults
- Moved from clickops to infrastructure as code in a methodical manner, i.e. creating the cdk stack, ensuring there are no differences once deployed and otherwise using cdk import
- Setup Sentry sourcemaps and releases so we can easily find the dirty commit as well as the line of code that triggered the error


---
<kbd>
<img src="assets/restless.gif?raw=true" alt="restless" />
</kbd>


### Career break 😴 | London | Jul 2025 - Jan 2026


---


<img src="assets/maze_logo.png?raw=true" alt="maze-logo" />

### [Maze](https://maze.co) | Senior software engineer | Remote | Sep 2021 - Jul 2025
##### What is Maze and what am I building?
Maze is a rapidly growing Series B startup building the future of product discovery for user-centric teams. We're powering product research for 60,000 customers worldwide including Uber, Accenture, FairMoney, and Braze. 

Maze empowers product teams to continuously collect and consume user insights across the entire product development cycle. With solutions for participant recruitment, product research, and reporting, Maze helps teams build the habit of continuous product discovery in a platform that enables everyone to run great research.

Tech: Typescript, Node.js, Neo4j, GraphQL, XState, Nest.js, Next.js, React, AWS, SNS/SQS, Nats, Terraform, CircleCi, Github Actions, Kubernetes, Docker, A/B testing, OpenFGA

- Added a human touch to the product by allowing users to upload and set profile pictures while also syncing their gmail profile picture if they're authenticated through Google.
- Led and implemented our product's integration with a lifecycle marketing tool called [Iterable](https://iterable.com/). This helps the marketing team to guide users' journeys within the app from the moment they sign up.
- Championing the value of testing and helping the team upskill. Introduced [Playwright](https://playwright.dev/) and set up an entire test suite which is fast and reliable.
- Built a micro-frontend for the entire login/signup flow using Next.js and state machines through XState to help us more easily run experiments.
- Gave users workspaces to effectively group their research projects including member access. The authorization model was built using [OpenFGA](https://openfga.dev/)
- Giving free users a usage-based trial to allow them to explore all of the features that are offered on the Organization plans and have a taste of the real value of Maze. So far it's had a very positive impact on number of PQLs 📈
- [Usage tracking](https://www.linkedin.com/posts/mazedesign_introducing-usage-tracking-activity-7310692033021526018-Pbik?utm_source=share&utm_medium=member_desktop&rcm=ACoAACDrhtMBjdtlcGf_jN99ps9xjX_OY4uXz0c) using SNS/SQS allowing organizations to monitor their study and recruitment credit consumption which they can use to make strategic decisions and effectively plan their research budget. 


---


<img src="assets/fluidly_logo.png?raw=true" alt="fluidly-logo" />

### [Fluidly](https://fluidly.co.uk) | Software Engineer | Aug 2019 - Jul 2021

- Working in a mono-environment (production only, every commit to master/main goes directly to production). This results in extremely fast releases into production, requires very good monitoring and high quality code written exclusively using TDD.
- Working on Flask, FastAPI, and Node.js apps for the majority of our micro-services.
- Use of Postgres for our database and sqlalchemy to interact with the database. Familiar with speeding up slow queries, understanding query plans and different types of indexes from a B-tree index to a GIN index.
- Use of the **CQRS** approach to separate our logic of data changes from reading the data as the business logic of the system is quite complex (Accounting 😵). We used this together with **event-sourcing** and this made it really nice to see exactly what constitutes an update to a model. 
- Use React, TypeScript, Redux, Sass and Styled-Components to develop features for the app. React Testing Library and Cypress is used for the test-driven development of these features.
- Extensive knowledge and use of our infrastructure: CircleCI for our CI/CD pipeline, Google Cloud Platform for our cloud infrastructure and Terraform to manage all of our infrastructure.
- Introduced Domain Driven Design into our Node.js service. 
- Led on several payment platform integrations, including **Stripe**, **Chargebee** and **GoCardless**.
- Worked extensively on our data warehouse, using BigQuery and DBT. Also used Data Studio for reporting on user and connections base. First report I made resulted in the discovery of a bug in our OAuth implementation!
- Was part of the growth team to help increase our user base and also improve our retention. This involved a lot of experimenting and good use of analytics.
- Worked on and added VAT predictions to the app: The most requested feature by our users.
- Currently working on a permission system for our users. 


---

<img src="assets/tmlogo_blue.png?raw=true" alt="ticketmaster-logo" />

### [Ticketmaster](https://ticketmaster.co.uk) | Front End Engineer | Jul 2017 - Mar 2019

- Create effortless user experiences by writing components using **React** with a heavy emphasis on **accessibility**.
- Manage application state using **Redux**.
- Test components using **Jest** and **Enzyme**.
- Set up **Storybook** for a UI development environment.
- Write acceptance tests using **Selenium**, **Nightwatch** and **Cypress**.
- Successfully set up acceptance tests on CI/CD pipeline using **Docker**.
- Migrated codebase from **CSS modules** and **Sass** to using CSS-in-JS (**Styled Components**).
- Migrated build process from using **Gulp** to **Webpack**.
- Automated the build of front end assets on the CI/CD pipeline.

---

<img src="assets/foundersandcoders_logo.png?raw=true" alt="founders-and-coders-logo" />

### [Founders And Coders](https://foundersandcoders.com) | Full Stack Developer | Feb 2017 - Jul 2017

- London's leading full stack JavaScript web development course in which I worked with teams of varying sizes to deliver projects to tight deadlines.
- Core technologies used in the projects included Node.js, React, Redux, PostgreSQL.
- Delivered an MVP for the Anna Freud centre focusing on mental health, allowing young individuals to connect with high achieving adults who can help them achieve their goals.
- Also stayed on upon completion of the course to help mentor the next cohort and contributed to improvements in the curriculum.

---

## Teaching Experience

<img src="assets/codeyourfuture_logo.png?raw=true" alt="codeyourfuture-logo" />

### [CodeYourFuture](https://codeyourfuture.io) | Mentor | May 2017 - 2020

A non-profit organisation supporting refugee and disadvantaged individuals with the dream of becoming developers.

- Taught a JavaScript module which focused on ES6 and testing in JavaScript.
- Fulfilled the role as project manager of a team of three students building an MVP for an organization called [Local Welcome](https://www.localwelcome.org/).

---

<img src="assets/codebar_logo.png?raw=true" alt="codebar-logo" />

### [Codebar](https://codebar.io) | Mentor | Sep 2017 - 2020

A non-profit initiative that facilitates the growth of a diverse tech community by running regular programming workshops.

- Attend Wednesday evening workshops in London where I mentor students in React, Node.js, JavaScript, HTML, CSS and Git.
- Also provide students with general career advice.

---

## Open Source Contributions

**[Revery](https://github.com/revery-ui/revery)** - native cross platform desktop framework
- [#313](https://github.com/revery-ui/revery/pull/313) - Add mouseenter / mouseleave / mouseover / mouseout events · ✅ Merged
- [#304](https://github.com/revery-ui/revery/pull/304) - Add padding support to the style system · ✅ Merged
- [#281](https://github.com/revery-ui/revery/pull/281) - Add the missing `revery_native.install` script · ✅ Merged
- [#268](https://github.com/revery-ui/revery/pull/268) - Add a Dropdown component · ✅ Merged

**[mitmproxy/mitmproxy_rs](https://github.com/mitmproxy/mitmproxy_rs)** - HTTPS proxy
- [#314](https://github.com/mitmproxy/mitmproxy_rs/pull/314) - Fix Linux local mode missing traffic from non-main threads · ⏳ Pending

**[Paseo](https://github.com/getpaseo/paseo)** - Multi platform coding agent
- [#1077](https://github.com/getpaseo/paseo/pull/1077) - Render non-ASCII filenames correctly in git output · ✅ Merged
- [#1076](https://github.com/getpaseo/paseo/pull/1076) - Send SIGINT on hardware Ctrl+C in the iPad terminal · ✅ Merged

**[Redux Toolkit](https://github.com/reduxjs/redux-toolkit)**
- [#2020](https://github.com/reduxjs/redux-toolkit/pull/2020) - Prevent duplicate IDs when an entity's id is updated to an existing one · ✅ Merged

**[DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped)**
- [#42404](https://github.com/DefinitelyTyped/DefinitelyTyped/pull/42404) - Add the missing `path` attribute to React's SVG types · ✅ Merged


---

## Languages

Fluent in **English**, **Dutch** and **Somali**.

---

## Links

[LinkedIn Profile](https://linkedin.com/in/samatar-axmed)
