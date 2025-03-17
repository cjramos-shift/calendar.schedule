# calendar.schedule
A web application for managing calendars, allowing users to create and schedule appointments and book meeting rooms.

![image](https://github.com/user-attachments/assets/50af758b-9b82-40fc-bcfa-fc802e78a8e3)

├── .gitignore<br>
├── Adapter.Inbound.Api<br>
    ├── Adapter.Inbound.Api.csproj<br>
    ├── Adapter.Inbound.Api.http<br>
    ├── Controllers<br>
    │   ├── UserController.cs<br>
    │   └── WeatherForecastController.cs<br>
    ├── Program.cs<br>
    ├── Properties<br>
    │   └── launchSettings.json<br>
    ├── WeatherForecast.cs<br>
    ├── appsettings.Development.json<br>
    └── appsettings.json<br>
├── Adapter.Outbound.Infra<br>
    └── Adapter.Outbound.Infra.csproj<br>
├── Aspire.Calendar<br>
    ├── Aspire.Calendar.ApiService<br>
    │   ├── Aspire.Calendar.ApiService.csproj<br>
    │   ├── Program.cs<br>
    │   ├── Properties<br>
    │   │   └── launchSettings.json<br>
    │   ├── appsettings.Development.json<br>
    │   └── appsettings.json<br>
    ├── Aspire.Calendar.AppHost<br>
    │   ├── Aspire.Calendar.AppHost.csproj<br>
    │   ├── Program.cs<br>
    │   ├── Properties<br>
    │   │   └── launchSettings.json<br>
    │   ├── appsettings.Development.json<br>
    │   └── appsettings.json<br>
    ├── Aspire.Calendar.ServiceDefaults<br>
    │   ├── Aspire.Calendar.ServiceDefaults.csproj<br>
    │   └── Extensions.cs<br>
    ├── Aspire.Calendar.Tests<br>
    │   ├── Aspire.Calendar.Tests.csproj<br>
    │   └── WebTests.cs<br>
    └── Aspire.Calendar.Web<br>
    │   ├── Aspire.Calendar.Web.csproj<br>
    │   ├── Components<br>
    │       ├── App.razor<br>
    │       ├── Layout<br>
    │       │   ├── MainLayout.razor<br>
    │       │   ├── MainLayout.razor.css<br>
    │       │   ├── NavMenu.razor<br>
    │       │   └── NavMenu.razor.css<br>
    │       ├── Pages<br>
    │       │   ├── Counter.razor<br>
    │       │   ├── Error.razor<br>
    │       │   ├── Home.razor<br>
    │       │   └── Weather.razor<br>
    │       ├── Routes.razor<br>
    │       └── _Imports.razor<br>
    │   ├── Program.cs<br>
    │   ├── Properties<br>
    │       └── launchSettings.json<br>
    │   ├── WeatherApiClient.cs<br>
    │   ├── appsettings.Development.json<br>
    │   ├── appsettings.json<br>
    │   └── wwwroot<br>
    │       ├── app.css<br>
    │       ├── favicon.png<br>
    │       └── lib<br>
    │           └── bootstrap<br>
    │               └── dist<br>
    │                   ├── css<br>
    │                       ├── bootstrap-grid.css<br>
    │                       ├── bootstrap-grid.css.map<br>
    │                       ├── bootstrap-grid.min.css<br>
    │                       ├── bootstrap-grid.min.css.map<br>
    │                       ├── bootstrap-grid.rtl.css<br>
    │                       ├── bootstrap-grid.rtl.css.map<br>
    │                       ├── bootstrap-grid.rtl.min.css<br>
    │                       ├── bootstrap-grid.rtl.min.css.map<br>
    │                       ├── bootstrap-reboot.css<br>
    │                       ├── bootstrap-reboot.css.map<br>
    │                       ├── bootstrap-reboot.min.css<br>
    │                       ├── bootstrap-reboot.min.css.map<br>
    │                       ├── bootstrap-reboot.rtl.css<br>
    │                       ├── bootstrap-reboot.rtl.css.map<br>
    │                       ├── bootstrap-reboot.rtl.min.css<br>
    │                       ├── bootstrap-reboot.rtl.min.css.map<br>
    │                       ├── bootstrap-utilities.css<br>
    │                       ├── bootstrap-utilities.css.map<br>
    │                       ├── bootstrap-utilities.min.css<br>
    │                       ├── bootstrap-utilities.min.css.map<br>
    │                       ├── bootstrap-utilities.rtl.css<br>
    │                       ├── bootstrap-utilities.rtl.css.map<br>
    │                       ├── bootstrap-utilities.rtl.min.css<br>
    │                       ├── bootstrap-utilities.rtl.min.css.map<br>
    │                       ├── bootstrap.css<br>
    │                       ├── bootstrap.css.map<br>
    │                       ├── bootstrap.min.css<br>
    │                       ├── bootstrap.min.css.map<br>
    │                       ├── bootstrap.rtl.css<br>
    │                       ├── bootstrap.rtl.css.map<br>
    │                       ├── bootstrap.rtl.min.css<br>
    │                       └── bootstrap.rtl.min.css.map<br>
    │                   └── js<br>
    │                       ├── bootstrap.bundle.js<br>
    │                       ├── bootstrap.bundle.js.map<br>
    │                       ├── bootstrap.bundle.min.js<br>
    │                       ├── bootstrap.bundle.min.js.map<br>
    │                       ├── bootstrap.esm.js<br>
    │                       ├── bootstrap.esm.js.map<br>
    │                       ├── bootstrap.esm.min.js<br>
    │                       ├── bootstrap.esm.min.js.map<br>
    │                       ├── bootstrap.js<br>
    │                       ├── bootstrap.js.map<br>
    │                       ├── bootstrap.min.js<br>
    │                       └── bootstrap.min.js.map<br>
├── Core.Application<br>
    ├── Core.Application.csproj<br>
    └── DTOs<br>
    │   ├── Request<br>
    │       └── UserRequestDTO.cs<br>
    │   └── Response<br>
    │       └── UserResponseDTO.cs<br>
├── Core.Domain<br>
    └── Core.Domain.csproj<br>
├── README.md<br>
├── Web.Calendar<br>
    ├── Components<br>
    │   ├── App.razor<br>
    │   ├── Layout<br>
    │   │   ├── MainLayout.razor<br>
    │   │   ├── MainLayout.razor.css<br>
    │   │   ├── NavMenu.razor<br>
    │   │   └── NavMenu.razor.css<br>
    │   ├── Pages<br>
    │   │   ├── Counter.razor<br>
    │   │   ├── Error.razor<br>
    │   │   ├── Home.razor<br>
    │   │   └── Weather.razor<br>
    │   ├── Routes.razor<br>
    │   └── _Imports.razor<br>
    ├── Program.cs<br>
    ├── Properties<br>
    │   └── launchSettings.json<br>
    ├── Web.Calendar.csproj<br>
    ├── appsettings.Development.json<br>
    ├── appsettings.json<br>
    └── wwwroot<br>
    │   ├── app.css<br>
    │   ├── favicon.png<br>
    │   └── lib<br>
    │       └── bootstrap<br>
    │           └── dist<br>
    │               ├── css<br>
    │                   ├── bootstrap-grid.css<br>
    │                   ├── bootstrap-grid.css.map<br>
    │                   ├── bootstrap-grid.min.css<br>
    │                   ├── bootstrap-grid.min.css.map<br>
    │                   ├── bootstrap-grid.rtl.css<br>
    │                   ├── bootstrap-grid.rtl.css.map<br>
    │                   ├── bootstrap-grid.rtl.min.css<br>
    │                   ├── bootstrap-grid.rtl.min.css.map<br>
    │                   ├── bootstrap-reboot.css<br>
    │                   ├── bootstrap-reboot.css.map<br>
    │                   ├── bootstrap-reboot.min.css<br>
    │                   ├── bootstrap-reboot.min.css.map<br>
    │                   ├── bootstrap-reboot.rtl.css<br>
    │                   ├── bootstrap-reboot.rtl.css.map<br>
    │                   ├── bootstrap-reboot.rtl.min.css<br>
    │                   ├── bootstrap-reboot.rtl.min.css.map<br>
    │                   ├── bootstrap-utilities.css<br>
    │                   ├── bootstrap-utilities.css.map<br>
    │                   ├── bootstrap-utilities.min.css<br>
    │                   ├── bootstrap-utilities.min.css.map<br>
    │                   ├── bootstrap-utilities.rtl.css<br>
    │                   ├── bootstrap-utilities.rtl.css.map<br>
    │                   ├── bootstrap-utilities.rtl.min.css<br>
    │                   ├── bootstrap-utilities.rtl.min.css.map<br>
    │                   ├── bootstrap.css<br>
    │                   ├── bootstrap.css.map<br>
    │                   ├── bootstrap.min.css<br>
    │                   ├── bootstrap.min.css.map<br>
    │                   ├── bootstrap.rtl.css<br>
    │                   ├── bootstrap.rtl.css.map<br>
    │                   ├── bootstrap.rtl.min.css<br>
    │                   └── bootstrap.rtl.min.css.map<br>
    │               └── js<br>
    │                   ├── bootstrap.bundle.js<br>
    │                   ├── bootstrap.bundle.js.map<br>
    │                   ├── bootstrap.bundle.min.js<br>
    │                   ├── bootstrap.bundle.min.js.map<br>
    │                   ├── bootstrap.esm.js<br>
    │                   ├── bootstrap.esm.js.map<br>
    │                   ├── bootstrap.esm.min.js<br>
    │                   ├── bootstrap.esm.min.js.map<br>
    │                   ├── bootstrap.js<br>
    │                   ├── bootstrap.js.map<br>
    │                   ├── bootstrap.min.js<br>
    │                   └── bootstrap.min.js.map<br>
└── calendar.schedule.sln<br>
