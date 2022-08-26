# tog-fs-interview-task

A repo to host the full stack developer interview task for TOG candidates.

## Intro

The team has been asked to develop a website where users can browse a list of events taking place at TOG venues.

For the initial MVP the site functionality will be limited to:

* users logging in to the site
* users being shown a list of events - each entry in the list will show event name, date and time, and venue name
* users clicking on an entry in the list will be taken to a page showing full event details

A Node Express API will be created to provide data for the site. The deployed API will need to support user authentication, as only users logged in to the site should be able to make API requests. Event data will be stored in a database. A JSON example of the data for an event can be found [here](sample-data/event.json).

## Task

Please provide a design for the API and the cloud infrastructure where it will be deployed.

You don't need to produce any code at this stage, but please detail:

* endpoints that will be created and the data they will return
* the mechanism you would use for authentication (e.g. a software solution, or a solution that leverages cloud services)
* which database would be suitable (e.g. PostgreSQL/MongoDB etc.) and how it would be structured (for example, would you have separate tables for venue and event information?)
* the cloud services and infrastructure required to deploy and support the API
* CI/CD processes

Even though TOG uses Azure, feel free to choose whichever cloud service, version control service and CI/CD platform you fancy for this task, we're mainly interested in seeing how you approach the design.

Similarly, you can present the API and infrastructure design via diagrams, written explanations etc., whatever you feel most comfortable with is absolutely fine.

Please send your agency a zip file containing your design and any supporting assets, and/or provide links to any online sites or tools you're using to host content.
