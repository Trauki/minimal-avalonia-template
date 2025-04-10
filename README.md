# Minimal Avalonia Template

Minimal template for creating [standalone executables](https://docs.avaloniaui.net/docs/deployment/native-aot) with [Avalonia](https://docs.avaloniaui.net/). 

Doesn't use:
- [Models](https://docs.avaloniaui.net/docs/guides/building-cross-platform-applications/architecture#common-architectural-patterns)
- [View Models](https://docs.avaloniaui.net/docs/concepts/the-mvvm-pattern/)
- [View Locater](https://docs.avaloniaui.net/docs/concepts/view-locator)

## Layout

- **Assets/** - Directory for storing static resources like images, icons, and other media.
- **Views/** - Directory containing the UI XAML files and C# code-behind files for different views (windows or pages).
- **App.axaml** - Defines the resources, theme, and window styles for the app.
- **App.axaml.cs** - The [code-behind](https://docs.avaloniaui.net/docs/guides/implementation-guides/code-behind) for **App.axaml** that handles app initialization and framework setup.
- **app.manifest** - Defines how the app interacts with Windows OS, including settings for permissions.
- **Template.csproj** - Project configuration file.
- **Program.cs** - Contains the entry point, where the Avalonia app is configured and launched using `AppBuilder`. This file ensures that the app starts correctly on the desktop platform and is set up to use the appropriate resources, like fonts and logging.




