# figma

![figma](https://github.com/arnemolland/figma/workflows/Dart%20CI/badge.svg) ![pub](https://img.shields.io/pub/v/figma.svg) [![style: pedantic](https://img.shields.io/badge/style-pedantic-9cf)](https://github.com/dart-lang/pedantic) ![license](https://img.shields.io/github/license/arnemolland/figma.svg)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fiamsecy%2Ffigma.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fiamsecy%2Ffigma?ref=badge_shield)

A library for interacting with Figma APIs.

Created from templates made available by Stagehand under a BSD-style
[license](https://github.com/dart-lang/stagehand/blob/main/LICENSE).

## Usage

A simple usage example:

```dart
import 'package:figma/figma.dart';

main() {
  final client = FigmaClient('token');

  final file = await client.getFile('file_key');
}
```

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: https://github.com/arnemolland/figma/issues


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fiamsecy%2Ffigma.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fiamsecy%2Ffigma?ref=badge_large)