# clia_flutter_quill

A mod of [flutter_quill](https://pub.dev/packages/flutter_quill) to be compatible with [flutter_quill_extensions](https://pub.dev/packages/flutter_quill_extensions).

`flutter_quill_extensions` depends on `math_keyboard`,
`math_keyboard` depends on `flutter_localizations` from SDK,
`flutter_localizations` depends on `intl` 0.17.0.

`flutter_quill` depends on `i18n_extension` 7.0.0, which depends on `intl` 0.18.0.

So I downgrade the version of `i18n_extension` to 6.0.0, to work with `flutter_quill_extensions`.
