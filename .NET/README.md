# .NET Style Guide

This is a common baseline `.editoconfig` to place into any this file can be placed in any .NET project. 

## Usage
Just copy it into your project's root directory and, if your editor doesn't have native support, [check for a plugin.](https://editorconfig.org/#download)

Where possible, configure tools to use `.editorconfig` rather than duplicating configuration in other files to avoid needing to synchronize customizations or exceptions.

## Conventions
For formatting options look at the `.editoconfig` and look up the rule on MSDN
* Defined naming conventions
  * [Async methods must end in Async](https://github.com/ok-omes/OMES.CodeStandards/blob/main/.NET/.editorconfig#L182)
  * [Public members must be Pascal Case](https://github.com/ok-omes/OMES.CodeStandards/blob/main/.NET/.editorconfig#L192)
  * [Const must be all upper case](https://github.com/ok-omes/OMES.CodeStandards/blob/main/.NET/.editorconfig#L200)
  * [Private must start with _ and be Camel Case](https://github.com/ok-omes/OMES.CodeStandards/blob/main/.NET/.editorconfig#L208)
  * [Insterfaces must start with an I](https://github.com/ok-omes/OMES.CodeStandards/blob/main/.NET/.editorconfig#L217)

## Design Guidelines
When it comes to .NET we need to adhear to the same stylistic decisions that is in the framework itself. You can read more about the [.NET Design Guidelines](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/). This doc expands on the following topics.
* [Naming Guidelines](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/naming-guidelines)
* [Type Design Guidelines](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/type)
* [Member Design Guidelines](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/member)
* [Designing for Extensibility](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/designing-for-extensibility)
* [Design Guidelines for Exceptions](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/exceptions)
* [Usage Guidelines](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/usage-guidelines)
* [Common Design Patterns](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/common-design-patterns)

## Extend
All .NET and C# `.editorconfig` options can be found [here](https://docs.microsoft.com/en-us/dotnet/fundamentals/code-analysis/style-rules/formatting-rules). If there is something that you would like to include or extend outside of what `.editconfig` can do out of the box the suggesterd option is [Resharper](https://www.jetbrains.com/help/resharper/EditorConfig_Index.html).