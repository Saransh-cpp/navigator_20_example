# navigator_example

Navigator 2.0 Pages API example and Router example.

## Pages API

Navigator's Pages API is a convenient way to declaratively set navigation stack in your Flutter app. Take a look at the `main.dart` entry point and please notice custom `PageManager` class that is handling list of pages provided to `Navigator`.

![](docs/pages.gif)

## Router widget

For more complex and robust needs you may use the Router widget. Simple implementation can be found in `main_router.dart` entry point. Take a look at the custom `TheAppPath` class storing typed path information and `RoutePageManager` handling list of pages provided to the `Navigator`.

![](docs/router.gif)

# More

Run on Flutter dev (1.23)

[Presentation at Flutter Cracow (Sept. 17th, 2020)](https://docs.google.com/presentation/d/1d8bdw5OKnY0HmY2GqAHo17LJvRjdmy3FAxFb9DDd90o/edit?usp=sharing)

[Presentation at DevFest Poland 2020]()