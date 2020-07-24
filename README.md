# BlazorSPA
A template for a Blazor SPA, with multiple virtual pages.  
A Single Page Application.

Demostrates using multiple paths to the one page.  
MavMenu is just a menu with each item a different path to the same page.  
eg /Page/First  v /Page/Second etc.  
Conditional HTML depending upon the path used.

Demonstrates use of the **MyNavigationManager.LocationChanged** event.
Also uses OnInitializedAsync handler as well as the OnInitialized event handler.  
OnRendered event handler is also present as well as OnAfterRenderAsync.

Is a Blazor WASM app with ASP.NET backend, Has PWA enabled.  
The server has no special functionality at this stage.
