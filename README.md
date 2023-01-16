# Dataland Starter Instructions

You can fork this boilerplate repo to create your own Dataland module to store your own custom workers + tables.

# Prerequisites:

You have completed the Dataland quickstart here: https://docs.dataland.io/quickstart.html#installation

# Setup

1. Fork this repository.

2. In the `module.yaml` file in this repo, rename the `moduleId` to something new.

3. Run the commands `npm install` and then `dataland deploy` in the root of the directory.

   This fully deploys all of the tables and workers in this repo into your Dataland workspace. This boilerplate contains a table called `greetings` and a worker that fetches data from the weather.

4. Add whatever new tables and workers you wish!

5. You can optionally run `dataland tail` to also get a stream of logs from the workers.
