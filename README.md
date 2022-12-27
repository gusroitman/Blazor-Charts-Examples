### Hello! I´m Gustavo :wave:

### I made some different examples for making charts in Blazor using different free libraries like MudBlazor - Apex - ChartJs and Radzen. :chart:

#### You can find the libraries at the following links :

* [MudBlazor](https://mudblazor.com/)
* [Apexcharts Wrapper for Blazor](https://apexcharts.com/)
* [Chartjs wrapper for Blazor](https://www.iheartblazor.com/welcome)
* [Radzen](https://www.radzen.com/)


#### You need to install the following nuget libraries first :

```
<ItemGroup>
    <PackageReference Include="Blazor-ApexCharts" Version="0.9.16-beta" />
    <PackageReference Include="MudBlazor" Version="6.1.6" />
    <PackageReference Include="PSC.Blazor.Components.Chartjs" Version="6.0.35" />
    <PackageReference Include="Radzen.Blazor" Version="4.4.7" />
  </ItemGroup>
```
#### Then open Pages \_Layout.cshtml (Blazor Server .NET 6), Pages\_Host.cshtml (Blazor Server .NET 7) or wwwroot/index.html (Blazor WebAssembly) and include this snippets

```
    <script src="_content/MudBlazor/MudBlazor.min.js"></script>
    <script src="_content/Blazor-ApexCharts/js/apex-charts.min.js"></script>
    <script src="_content/Blazor-ApexCharts/js/blazor-apex-charts.js"></script>
    <script src="_content/PSC.Blazor.Components.Chartjs/lib/Chart.js/chart.js"></script>
    <script src="_content/PSC.Blazor.Components.Chartjs/Chart.js"></script>
    <script src="_content/Radzen.Blazor/Radzen.Blazor.js"></script>
```

#### You can also include globally in your _Imports.razor file of your Blazor application and import the namespaces and add the lines **@using Radzen** or **@using Mudblazor**. But since this is a demo which includes different libraries we include them on each page depending the library using.

#### Finally you could add the services to your program.cs like this :

```
builder.Services.AddMudServices();
```

#### Some screenshots of the different libraries used :

![This is an image](../../assets/images/chartsample1.png)
![This is an image](/assets/images/electrocat.png)
![This is an image](/assets/images/electrocat.png)
![This is an image](/assets/images/electrocat.png)
![This is an image](/assets/images/electrocat.png)


If you have any questions feel free to ask. :right_anger_bubble:
