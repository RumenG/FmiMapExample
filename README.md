# FmiMapExample
This is an example project demonstrating how to use a map component in a WPF application. It is using [Bing Maps WPF Control](https://docs.microsoft.com/en-us/previous-versions/bing/wpf-control/hh750210(v%3Dmsdn.10)) and shows simple map with several pins (markers).
![Image](/Screenshot.png?raw=true)

## How to start
- Prerequisities:
  - .NET Framework 4.7
  - Visual Studio
- Download and install [Bing Maps WPF Control SDK](https://www.microsoft.com/en-us/download/details.aspx?displaylang=en&id=27165)
- Obtain [Bing Maps Key](https://docs.microsoft.com/en-us/bingmaps/getting-started/bing-maps-dev-center-help/getting-a-bing-maps-key?redirectedfrom=MSDN)
  - use any application name, select "Basic" key type and "Windows" application type
  - it's free and allows making up to 50000 transactions within any 24-hour period (more than enough for a school project)
- `git clone` this repo and open solution `FmiMapExample` in VisualStudio
- Copy your Bing Maps key and paste it as `CredentialsProvider` value in `MainWindow.xaml` file
- Run the application with F5
## Further reading
[Developing with the Bing Maps WPF Control](https://docs.microsoft.com/en-us/previous-versions/bing/wpf-control/hh830431(v=msdn.10))

[Bing Maps WPF Control API Reference](https://docs.microsoft.com/en-us/previous-versions/bing/wpf-control/mt712924(v=msdn.10))

[Developer Resources and Support](https://docs.microsoft.com/en-us/previous-versions/bing/wpf-control/hh709043(v=msdn.10))
