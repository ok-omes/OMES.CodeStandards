<img src="./docs/OK_Logo_Horizontal_FullColour_Pos_RGB.svg" height="150px" alt="Oklahoma OMES" />

<br/>
<br/>


# OMES.CodeStandards
This is a common baseline for coding standards suitable for all Oklahoma projects and is intended to avoid policies where many projects will reasonably disagree based on different needs and environments.

## Philosophy

### Goals
* Reduce noise in commits, code-review, etc.
* Make it easier for unfamiliar developers to participate
* Provide immediate feedback to avoid extending the development cycle

### Anti-goals
* Creating second jobs: we will rely on automation rather than asking humans to behave like robots
* Picking sides in industry-wide debates without a strong consensus position

## General Practices
* We strongly recommend the use of version control hooks and continuous integration tests for any change which can be made or tested automatically. This makes it simple to setup a new copy of the repository by running pre-commit install after the first checkout to ensure that all subsequent commits will be reformatted and validated automatically, and CI tools can use pre-commit run to run all of the configured hooks during the build process as well.
  
* There are a number of similar tools which provide equivalent functionality. In accordance with the philosophy above, consistency is more important than any particular tool: the part which matters most is that it's run regularly by everyone on a team with identical results.

## Code Reusability
Any time you run into code that can be reused multiplaces places in a code base or across packages you should look into creating a package instead of a common file that get's moved from codebase to codebase. This goes back to our philosophy -- make it easier for unfamiliar developers to participate.
  * [NuGet](https://docs.microsoft.com/en-us/nuget/create-packages/creating-a-package)
  * [NPM](https://docs.npmjs.com/creating-and-publishing-unscoped-public-packages)
## Language-Specific Configuration
Each language has a subdirectory which contains a README file with instructions for the tools and conventions popular in that language. For example, .NET tooling will assume `.editorconfig`, but javascript will reasonably differ -- as always the most important thing is consistency.

## Suggestions
Please submit a pull request or start an issue to open something up for discussion.