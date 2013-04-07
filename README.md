MarionetteJS Nuget Package
==========================

This is a [Nuget] (http://www.nuget.org) package for the popular [MarionetteJS] (http://www.marionettejs.com) project.  MarionetteJS is a composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications.

This package is published to the Nuget gallery [here] (https://nuget.org/packages/Backbone.Marionette/).

To package it, run this command from the root of this repository:

	NuGet Pack src\MarionetteJS.nuspec

To test the package locally, you can use the package manager console in Visual Studio:

	Install-Package Backbone.Marionette -Source C:\PathToThePackageDir\

For more information on creating packages with Nuget, visit http://docs.nuget.org/docs/creating-packages/creating-and-publishing-a-package.
