# githooks templates

Custom githook templates.

## GET STARTED

1. In your git-repo you can find a hidden folder .git/hooks/
2. If you want to apply the hooks then remove .sample from the filename that you wish to use.
3. Or add any of the example files from this repo.

## Hook: Commit-msg

Hook that triggers on commit message

### Conventional Commits
Open commit-msg (The Commit Message hook using Conventional Commits)

Following the Conventional commit standard : https://www.conventionalcommits.org/en/v1.0.0/#summary
Test regex: https://regex101.com/r/dYaXqM/1

### Usage

<pre>
<b><a href="#types">&lt;type&gt;</a></b></font>(<b><a href="#scopes">&lt;optional scope&gt;</a></b>): <b><a href="#description">&lt;description&gt;</a></b>
<sub>empty separator line</sub>
<b><a href="#body">&lt;optional body&gt;</a></b>
<sub>empty separator line</sub>
<b><a href="#footer">&lt;optional footer&gt;</a></b>
</pre>

### Examples 

> fix: successful commit message without scope
> fix(scope): successful fixed product bug using scope
> fix: A commit that is to long is not readable and when the maximum length will be reached and this line will not be valid 

### Valid Convention types

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

### Scopes
The scope provides additional contextual information.

- Is an optional part of the format
- Allowed Scopes depends on the specific project
- Don't use issue identifiers as scopes
