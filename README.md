# BlazorToDo
A Microsoft Learn course on the basics of Blazor

I'm following the [Blazor ToDo List](https://learn.microsoft.com/en-us/training/modules/build-blazor-webassembly-visual-studio-code/?WT.mc_id=dotnet-35129-website) Microsoft Learn tutorial.

## .NET Core version used
In the tutorial they used .NET 6. 

## What version I'll use
I'll use .NET 8

## May need to use .NET 6
I've got .NET 6 and 8 installed on my desktop. But there's some differences. First, the tutorial, when I work with it at home, allows me to chose between erither VS Code or Visual Studio. And the other thing is from within Visual Studio, I cannot create a Blazor Server App cannot be created for .NET 8. At best I can only create it for .NET 7. And when I run the command `dotnet --list-sdks` doesn't list .NET 7, in Visual Studio. At best that I create a Blazor Server App with .NET 6.

### I've created the project using .NET 6

## The link I used
For some reason I don't understand, the Microsoft Learn course had two pages for unit 3 of this tutorial, which was **VERY** confusing!!! 
Since at this point I was more interested in learning Blazor Server apps than the pecularities of Visual Studio Code with Blazor, I decided to follow
this [unit 3](https://learn.microsoft.com/en-us/training/modules/build-blazor-webassembly-visual-studio-code/3-exercise-configure-enviromnent?pivots=vstudio) page instead.
I did *not* use the link at the beginning of this README!

### Additional learning
The [summer page](https://learn.microsoft.com/en-us/training/modules/build-blazor-webassembly-visual-studio-code/8-summary) has links to additional Microsoft Learn courses on Blazor.

## There's a change in the project template creationg for .NET 8!
I've just discovvered (12/25/2023) that Microsoft decided to remove the Blazor Server App template when creating a new Blazor project. They're consolidating project types. It is documented in the What's New in ASP.NET Core 8.0, the [New Blazor Web App template](https://learn.microsoft.com/en-us/aspnet/core/release-notes/aspnetcore-8.0?view=aspnetcore-8.0&wt.mc_id=msftsource_issue54WN3_email_gdc%3Focid%3Deml_pg420598_gdc_comm_mw&mkt_tok=MTU3LUdRRS0zODIAAAGQKEQEH0PIQ9UAGCfYCGAQpGGvRBF9R-9oKtD7zGVDQU-esQtnEcDT1r_FuAgsXwuOaoqKABc4QieBrujCqN1SYZNgZQZTWHIIfijfE6mnB0sB5xdhEbcZWzw#new-blazor-web-app-template) section. So, I could have started this using .NET 8 project template. Oh well.
