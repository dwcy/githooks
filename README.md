# githooks templates

> GET STARTED

1. In your git-repo you can find a hidden folder .git/hooks/
2. If you want to apply the hooks then remove .sample from the filename that you wish to use.
3. Or add any of the example files from this repo.


## Conventional Commits
Open commit-msg (The Commit Message hook using Conventional Commits)

Following the Conventional commit standard : https://www.conventionalcommits.org/en/v1.0.0/#summary
Test regex: https://regex101.com/r/dYaXqM/1

## Commits that work

```sh
> fix: successful commit message without scope
> fix(scope): successful fixed product bug using scope
> fix: A commit that is to long is not readable and when the maximum length will be reached and this line will not be valid 
> build: changes that affect the build of the project
> chore: Changes that does not affect the source code or test code
> ci: Changes to configuration of Continues Integrations
> docs: Only Documentation changes
> feat: MUST be used when a commit adds a new feature to your application or library.
> fix: MUST be used when a commit represents a bug fix for your application.
> refactor: Code refactoring
> revert: revert to previous commit
> perf: Perfomance improvements
> style: Code style changes
> test: Adding test code
´´´
