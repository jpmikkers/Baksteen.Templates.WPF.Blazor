# Baksteen.Templates.WPF.Blazor
Project template for hybrid WPF Blazor .NET 7 application. This is a nice entry point for a WPF based Blazor hybrid project, when you're not in the mood to deal with dotnet Maui's awkward packaging/deployment. A WPF based project will result in a good old executable you can copy and run anywhere as you please.

This template is based on the instructions of:

    https://learn.microsoft.com/en-us/aspnet/core/blazor/hybrid/?view=aspnetcore-7.0

    https://learn.microsoft.com/en-us/aspnet/core/blazor/hybrid/tutorials/wpf?view=aspnetcore-7.0

And then extended with the contents of the current mauiblazor project template

## How to use

Run the following command to install the template (this will download the nuget package from nuget.org):

    dotnet new install Baksteen.Templates.WPF.Blazor
    
Then use visual studio and create a new project, select 'WPF Blazor Template'

Alternatively you can create a new project from commandline as follows:

    dotnet new wpfblazor.app
  
To uninstall the template run this command:

    dotnet new uninstall Baksteen.Templates.WPF.Blazor
