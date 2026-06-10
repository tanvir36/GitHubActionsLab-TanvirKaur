# GitHubActionsLab-TanvirKaur


## Workflow 1 - Dependent Jobs

This workflow demonstrates job dependencies using the `needs`
keyword. The jobs execute in sequence:

Build → Test → Deploy

## Workflow 2 - Multi Platform Testing

This workflow demonstrates running jobs on multiple operating
systems in parallel:

- Ubuntu
- Windows
- macOS

## Concepts Demonstrated

### needs
Creates job dependencies.

### runs-on
Specifies the operating system used by a job.

### actions/checkout@v4
Checks out repository code before running steps.

## Challenges Faced

Learning GitHub Actions syntax and understanding how job
dependencies and parallel execution work.
