# heroku-buildpack-run-rake-tasks

A buildpack to run arbitrary rake tasks during a deploy.

## Usage

The `.buildpack-run-rake-tasks` file in your apps root directory defines all rake tasks that should be run during this build step.
This file should include a single command per line. Ex:

```
assets:precompile
db:migrate
```
