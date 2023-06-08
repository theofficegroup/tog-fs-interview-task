# tog-fs-interview-task

A repo to host the full stack developer interview task for TOG candidates.

## Intro

The team has been asked to develop a website where users can browse and purchase tickets for a list of events taking place at TOG venues.

For the initial MVP the site functionality will be limited to:

* users logging in to the site
* users being shown a list of events - each entry in the list will show event name, date, time, venue and price 
* users clicking on an entry in the list will be taken to a page showing full event details and a CTA
* users clicking the CTA will be redirected into a checkout flow

A Node Express API will be created to provide data for the site. The deployed API will need to support user authentication, as only users logged in to the site should be able to make API requests. Event data will be stored in a database. A JSON example of the data for an event can be found [here](sample-data/event.json).

## Task

You don't need to produce any code for this task. Please also only spend ~3 hours of your time. The objective is to produce a high level plan - rather than implement a solution - for us to discuss in the interview.

Please provide a design for the API and the cloud infrastructure where it will be deployed.

How you present your approach is completely up to you, but please detail:

* endpoints that will be created and the data they will return
* the mechanism you would use for authentication (e.g. a software solution, or a solution that leverages cloud services)
* the mechanism for handling payments (eg. a particular provider and how we would interface)
* which database would be suitable and how it could be structured
* how you might support and monitor the API
* CI/CD processes

Even though TOG uses Azure, feel free to choose whichever cloud service, version control service and CI/CD platform you fancy for this task, we're mainly interested in seeing your approach.

Similarly, you can present the API and infrastructure design via diagrams, written explanations etc., whatever you feel most comfortable with is absolutely fine.

Please send a zip file containing your design and any supporting assets, and/or provide links to any online sites or tools you're using to host content.

## Interview

We'll use the task as the basis of the next interview, hopefully it will feel more like a discussion following this loose structure:

* 15-30 mins walk through of your design
* 15-30 mins follow up questions and discussion
* 15 mins any questions for us
* 15 mins meet the rest of the team

Please don't worry about documenting the below, but the kind of topics we tend to delve into include:

* how the front-end team & back-end team will collaborate in an agile manner
* ensuring the handling of payments is PCI compliant
* how do we ensure adequate test coverage

Good luck and look forward to catching up soon.
