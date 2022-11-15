# minimalAPI
https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-7.0&amp;tabs=visual-studio-code



# Differences between minimal APIs and APIs with controllers
Minimal APIs have:

 Markup: 
 - Different support for filters. For more information, see Filters in Minimal API apps
 - No support for model binding, for example: IModelBinderProvider, IModelBinder. Support can be added with a custom binding shim.
    - No support for binding from forms, except for IFormFile. For more information, see File uploads using IFormFile and IFormFileCollection.
- No built-in support for validation, i.e. IModelValidator
- No support for application parts or the application model. There's no way to apply or build your own conventions.
- No built-in view rendering support. We recommend using Razor Pages for rendering views.
- No support for JsonPatch
- No support for OData

