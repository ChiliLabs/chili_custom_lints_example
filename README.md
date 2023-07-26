A sample app that uses Chili Custom Lints via [custom_lint](https://pub.dev/packages/custom_lint) package 

## Getting Started

Add this to your package's `pubspec.yaml` file:

```yaml
dev_dependencies:
  custom_lint: ^0.5.0 #check latest version
  chili_custom_lints:
    git:
      url: https://github.com/ChiliLabs/chili_custom_lints.git
```

Add this to your package's `analysis_options.yaml` file:

```yaml
analyzer:
  plugins:
    - custom_lint
```

Run `flutter pub get` to install and maybe restart your IDE.