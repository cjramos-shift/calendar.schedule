# calendar.schedule
A web application for managing calendars, allowing users to create and schedule appointments and book meeting rooms.

![image](https://github.com/user-attachments/assets/50af758b-9b82-40fc-bcfa-fc802e78a8e3)

├── .gitignore
├── Adapter.Inbound.Api
    ├── Adapter.Inbound.Api.csproj
    ├── Adapter.Inbound.Api.http
    ├── Controllers
    │   ├── UserController.cs
    │   └── WeatherForecastController.cs
    ├── Program.cs
    ├── Properties
    │   └── launchSettings.json
    ├── WeatherForecast.cs
    ├── appsettings.Development.json
    └── appsettings.json
├── Adapter.Outbound.Infra
    └── Adapter.Outbound.Infra.csproj
├── Aspire.Calendar
    ├── Aspire.Calendar.ApiService
    │   ├── Aspire.Calendar.ApiService.csproj
    │   ├── Program.cs
    │   ├── Properties
    │   │   └── launchSettings.json
    │   ├── appsettings.Development.json
    │   └── appsettings.json
    ├── Aspire.Calendar.AppHost
    │   ├── Aspire.Calendar.AppHost.csproj
    │   ├── Program.cs
    │   ├── Properties
    │   │   └── launchSettings.json
    │   ├── appsettings.Development.json
    │   └── appsettings.json
    ├── Aspire.Calendar.ServiceDefaults
    │   ├── Aspire.Calendar.ServiceDefaults.csproj
    │   └── Extensions.cs
    ├── Aspire.Calendar.Tests
    │   ├── Aspire.Calendar.Tests.csproj
    │   └── WebTests.cs
    └── Aspire.Calendar.Web
    │   ├── Aspire.Calendar.Web.csproj
    │   ├── Components
    │       ├── App.razor
    │       ├── Layout
    │       │   ├── MainLayout.razor
    │       │   ├── MainLayout.razor.css
    │       │   ├── NavMenu.razor
    │       │   └── NavMenu.razor.css
    │       ├── Pages
    │       │   ├── Counter.razor
    │       │   ├── Error.razor
    │       │   ├── Home.razor
    │       │   └── Weather.razor
    │       ├── Routes.razor
    │       └── _Imports.razor
    │   ├── Program.cs
    │   ├── Properties
    │       └── launchSettings.json
    │   ├── WeatherApiClient.cs
    │   ├── appsettings.Development.json
    │   ├── appsettings.json
    │   └── wwwroot
    │       ├── app.css
    │       ├── favicon.png
    │       └── lib
    │           └── bootstrap
    │               └── dist
    │                   ├── css
    │                       ├── bootstrap-grid.css
    │                       ├── bootstrap-grid.css.map
    │                       ├── bootstrap-grid.min.css
    │                       ├── bootstrap-grid.min.css.map
    │                       ├── bootstrap-grid.rtl.css
    │                       ├── bootstrap-grid.rtl.css.map
    │                       ├── bootstrap-grid.rtl.min.css
    │                       ├── bootstrap-grid.rtl.min.css.map
    │                       ├── bootstrap-reboot.css
    │                       ├── bootstrap-reboot.css.map
    │                       ├── bootstrap-reboot.min.css
    │                       ├── bootstrap-reboot.min.css.map
    │                       ├── bootstrap-reboot.rtl.css
    │                       ├── bootstrap-reboot.rtl.css.map
    │                       ├── bootstrap-reboot.rtl.min.css
    │                       ├── bootstrap-reboot.rtl.min.css.map
    │                       ├── bootstrap-utilities.css
    │                       ├── bootstrap-utilities.css.map
    │                       ├── bootstrap-utilities.min.css
    │                       ├── bootstrap-utilities.min.css.map
    │                       ├── bootstrap-utilities.rtl.css
    │                       ├── bootstrap-utilities.rtl.css.map
    │                       ├── bootstrap-utilities.rtl.min.css
    │                       ├── bootstrap-utilities.rtl.min.css.map
    │                       ├── bootstrap.css
    │                       ├── bootstrap.css.map
    │                       ├── bootstrap.min.css
    │                       ├── bootstrap.min.css.map
    │                       ├── bootstrap.rtl.css
    │                       ├── bootstrap.rtl.css.map
    │                       ├── bootstrap.rtl.min.css
    │                       └── bootstrap.rtl.min.css.map
    │                   └── js
    │                       ├── bootstrap.bundle.js
    │                       ├── bootstrap.bundle.js.map
    │                       ├── bootstrap.bundle.min.js
    │                       ├── bootstrap.bundle.min.js.map
    │                       ├── bootstrap.esm.js
    │                       ├── bootstrap.esm.js.map
    │                       ├── bootstrap.esm.min.js
    │                       ├── bootstrap.esm.min.js.map
    │                       ├── bootstrap.js
    │                       ├── bootstrap.js.map
    │                       ├── bootstrap.min.js
    │                       └── bootstrap.min.js.map
├── Core.Application
    ├── Core.Application.csproj
    └── DTOs
    │   ├── Request
    │       └── UserRequestDTO.cs
    │   └── Response
    │       └── UserResponseDTO.cs
├── Core.Domain
    └── Core.Domain.csproj
├── README.md
├── Web.Calendar
    ├── Components
    │   ├── App.razor
    │   ├── Layout
    │   │   ├── MainLayout.razor
    │   │   ├── MainLayout.razor.css
    │   │   ├── NavMenu.razor
    │   │   └── NavMenu.razor.css
    │   ├── Pages
    │   │   ├── Counter.razor
    │   │   ├── Error.razor
    │   │   ├── Home.razor
    │   │   └── Weather.razor
    │   ├── Routes.razor
    │   └── _Imports.razor
    ├── Program.cs
    ├── Properties
    │   └── launchSettings.json
    ├── Web.Calendar.csproj
    ├── appsettings.Development.json
    ├── appsettings.json
    └── wwwroot
    │   ├── app.css
    │   ├── favicon.png
    │   └── lib
    │       └── bootstrap
    │           └── dist
    │               ├── css
    │                   ├── bootstrap-grid.css
    │                   ├── bootstrap-grid.css.map
    │                   ├── bootstrap-grid.min.css
    │                   ├── bootstrap-grid.min.css.map
    │                   ├── bootstrap-grid.rtl.css
    │                   ├── bootstrap-grid.rtl.css.map
    │                   ├── bootstrap-grid.rtl.min.css
    │                   ├── bootstrap-grid.rtl.min.css.map
    │                   ├── bootstrap-reboot.css
    │                   ├── bootstrap-reboot.css.map
    │                   ├── bootstrap-reboot.min.css
    │                   ├── bootstrap-reboot.min.css.map
    │                   ├── bootstrap-reboot.rtl.css
    │                   ├── bootstrap-reboot.rtl.css.map
    │                   ├── bootstrap-reboot.rtl.min.css
    │                   ├── bootstrap-reboot.rtl.min.css.map
    │                   ├── bootstrap-utilities.css
    │                   ├── bootstrap-utilities.css.map
    │                   ├── bootstrap-utilities.min.css
    │                   ├── bootstrap-utilities.min.css.map
    │                   ├── bootstrap-utilities.rtl.css
    │                   ├── bootstrap-utilities.rtl.css.map
    │                   ├── bootstrap-utilities.rtl.min.css
    │                   ├── bootstrap-utilities.rtl.min.css.map
    │                   ├── bootstrap.css
    │                   ├── bootstrap.css.map
    │                   ├── bootstrap.min.css
    │                   ├── bootstrap.min.css.map
    │                   ├── bootstrap.rtl.css
    │                   ├── bootstrap.rtl.css.map
    │                   ├── bootstrap.rtl.min.css
    │                   └── bootstrap.rtl.min.css.map
    │               └── js
    │                   ├── bootstrap.bundle.js
    │                   ├── bootstrap.bundle.js.map
    │                   ├── bootstrap.bundle.min.js
    │                   ├── bootstrap.bundle.min.js.map
    │                   ├── bootstrap.esm.js
    │                   ├── bootstrap.esm.js.map
    │                   ├── bootstrap.esm.min.js
    │                   ├── bootstrap.esm.min.js.map
    │                   ├── bootstrap.js
    │                   ├── bootstrap.js.map
    │                   ├── bootstrap.min.js
    │                   └── bootstrap.min.js.map
└── calendar.schedule.sln
