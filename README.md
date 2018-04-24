# Enhancing ASP.<span></span>Net with Vue.JS

> A simple project demonstrating Vue.js component integration with ASP.<span></span>Net Razor pages.

## Build ASP.<span></span>Net Application

If you don't have the .Net Core CLI installed, download it [here](https://www.microsoft.com/net/download/).

``` bash
# install npm dependencies
npm install

# install ASP.Net dependencies
dotnet restore

# build and run project on local server
dotnet run
```

The Vue.js components are located in the <code>src</code> directory at the root of the project.

The project is designed to build the ASP.<span></span>Net project as well as the Vue.js project simultaniously with the <code>dotnet run</code> command. 

The code for running the npm command can be found at the bottom of the <code>AspNet-Vue-Demo.csproj</code> file. 

The command below can be run to build the Vue.js components independantly and is safe to run while the ASP.<span></span>Net project is running.

## Build Vue.js Components and Bundle JS

``` bash
# build for production with minification
npm run build
```



