# tog-fs-interview-task

A repo to host the full stack developer interview task for TOG candidates.

## Intro

The team has been asked to develop a website where users can browse and purchase tickets for a list of events taking place at TOG venues.

For the initial MVP the site functionality will be limited to:

* users logging in to the site
* users being shown a list of events - each entry in the list will show event name, date, time, venue name and price 
* users clicking on an entry in the list will be taken to a page showing full event details and a CTA to purchase tickets
* users clicking the CTA will be redirected into a checkout flow

A Node Express API will be created to provide data for the site. The deployed API will need to support user authentication, as only users logged in to the site should be able to make API requests. Event data will be stored in a database. A JSON example of the data for an event can be found [here](sample-data/event.json).

## Task

You don't need to produce any code for this task. The objective is to proudce a plan - rather than impliment a solution - for us to discuss in the interview.

Some things to consider:

* how the front-end team & back-end team will collaborate in an agile manner
* handling of payments needs to be PCI compliant
* how do we get adequate test coverage

Please provide a design for the API and the cloud infrastructure where it will be deployed.

How you present your approach is completely up to you, but please detail:

* endpoints that will be created and the data they will return
* the mechanism you would use for authentication (e.g. a software solution, or a solution that leverages cloud services)
* teh mechanism for handling payments (eg. a particular provider and how we would interface)
* which database would be suitable and how it could be structured
* how you might support and monitor the API
* CI/CD processes

Even though TOG uses Azure, feel free to choose whichever cloud service, version control service and CI/CD platform you fancy for this task, we're mainly interested in seeing how you approach the design.

Similarly, you can present the API and infrastructure design via diagrams, written explanations etc., whatever you feel most comfortable with is absolutely fine.

Please send a zip file containing your design and any supporting assets, and/or provide links to any online sites or tools you're using to host content.
