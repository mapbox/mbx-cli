# PAUSED DEVELOPMENT

Since [the SDK that it wraps](https://github.com/mapbox/mapbox-sdk-py/blob/master/CONTRIBUTING.md#attention-this-project-is-paused) has been deprecated, we have also archived this CLI. We encourage you to migrate to [the equivalent tiling and upload endpoints.](https://docs.mapbox.com/api/maps/mapbox-tiling-service/)

# Contributing

## Installation

We recommend using [`virtualenv`](https://virtualenv.readthedocs.org/en/latest/) to isolate dependencies for development.
This guide assumes that you have already created and activated a virtualenv for this project.

Ensure that you have the latest version of pip installed:
```
pip install -U pip
```

Clone the repository (alternatively, if you plan on making a pull request and are not in the Mapbox organization, use the [github page](https://github.com/mapbox/mapbox-cli-py) to create your own fork)
```
git clone git@github.com:mapbox/mapbox-cli-py.git
cd mapbox-cli-py
```

Install in "editable" mode with testing dependencies
```
pip install -U -r requirements-dev.txt
pip install -e .[test]
```

And finally create a separate branch to begin work
```
git checkout -b my-new-feature
```


## Submitting Pull Requests

Pull requests are welcomed! We'd like to review the design and implementation as early as 
possible so please submit the pull request even if it's not 100%. 
Let us know the purpose of the change and list the remaining items which need to be
addressed before merging. Finally, PR's should include unit tests and documentation 
where appropriate.


## Code of conduct

Everyone is invited to participate in Mapbox’s open source projects and public discussions: we want to create a welcoming and friendly environment. Harassment of participants or other unethical and unprofessional behavior will not be tolerated in our spaces. The [Contributor Covenant](http://contributor-covenant.org) applies to all projects under the Mapbox organization and we ask that you please read [the full text](http://contributor-covenant.org/version/1/2/0/).

You can learn more about our open source philosophy on [mapbox.com](https://www.mapbox.com/about/open/).

