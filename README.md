# reusable-workflows
> Reusable workflows for @palashmon repos

Reusable workflows allow you to embrace the DRY (Don't Repeat Yourself) principle and usher in standardization and consistently implement best practices. They smooth developer journeys, making processes more streamlined and efficient, without imposing undue restrictions.

A [reusable workflow](https://docs.github.com/en/actions/using-workflows/reusing-workflows) is a GitHub Actions file that can be executed by other workflows. A single workflow can call multiple reusable workflows, with each reference taking up just one line of YAML. This means that the "caller" workflow may contain just a few lines of YAML, but perform a large number of tasks, since it runs each "called" workflow entirely, as if its jobs and steps were part of its own.

### What are the benefits of reusable workflows?
Reusable workflows offer several benefits:

- Avoid redundancy
- Speed up workflow creation through reuse
- Reduce maintenance and enhance security by offering a library of reusable workflows that can be centrally maintained
- Promote the use of workflows that are well-designed, already tested, and proven effective