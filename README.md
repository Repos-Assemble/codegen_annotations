# codegen_annotations

Small annotation classes used to mark up your Dart classes for the `codegen` package to read and generate code from.

## What's inside

- Annotations for documenting generated fields, models, and state classes — see `lib/src/`

## Installation

```yaml
dependencies:
  codegen_annotations:
    git:
      url: https://github.com/Repos-Assemble/codegen_annotations.git
      ref: main
```

## Usage

```dart
import 'package:codegen_annotations/codegen_annotations.dart';
```

This package is meant to be used together with `codegen` and `build_runner`.

## Credits

This package began as an independent rewrite based on general Dart code-generation patterns. It is MIT licensed — see [LICENSE](./LICENSE).
