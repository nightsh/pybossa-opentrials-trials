## Description

This [PyBossa]() project exposes the trials matches done on OpenTrials for
deduplication reasons, allowing the crowd to vote on specific matches as
correct or incorrect.

For this project the trials will be presented two by two, with links to the
original sources where they were collected from. Users can visit the sources,
then go back to the task page and cast their vote.

A PyBossa project is centered around **tasks**. A task is the user's atomic
operation of solving a given problem.


Components:

* `template.html` is the main task template file that will be used by the crowd
* `tutorial.html` is a "learning" template that is presented the first time a
  user enters the crowdsourcing project as a contributor, or on demand
* `project.json` contains the project identifier and metadata
* `results.html` is using PyBossa built in features to disseminate the results


## Usage

The easiest (and recommended) method to use the project source is through the
official command line PyBossa client, [pbs](https://github.com/PyBossa/pbs).

See the [installation](https://github.com/PyBossa/pbs#installation),
[configuration](https://github.com/PyBossa/pbs#configuring-pbs) and 
[usage](https://github.com/PyBossa/pbs#updating-project-templates) info on the 
project's page.

After installing and configuring `pbs`, if you update any project file you
should run `pbs update_project` for it to be updated with the latest files. See
`pbs --help` for more options.
