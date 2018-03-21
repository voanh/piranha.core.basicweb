# Piranha.Core BasicWeb Template

## About

This is the standard template for creating a basic website with Piranha. It is
intended to be used with the cross platform .NET CLI tools. The NuGet package is 
**not** intended to install into an existing project.

## How to install & use the latest version

Install or update the template from NuGet:

    > dotnet new -i Piranha.BasicWeb.CSharp

Create a new project based on the template

    > dotnet new piranha

The template contains models, controllers and views for:

Startpage with a hero, variable amount of teasers and HTML content.
Blog archive with a hero and post listing.
Standard page with HTML content.
Standard blog post with a primary image and HTML content.

## How to contribute

Fork this repo to your GitHub account, clone it locally and try to follow
the following simple guidelines.

* **Never** write any code in your master branch
* When writing code, do it in a specific feature branch
* Send your pull request from that feature branch
* After your pull request has been accepted, sync the changes into master from the upstream remote
* Delete you feature branch
* Again, **NEVER** write any code in your master branch ;)