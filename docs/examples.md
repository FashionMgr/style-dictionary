# Examples

To get you started, there are some example packages included that you can use. You can [take a look at the code on Github](https://github.com/amzn/style-dictionary/tree/master/example/) or you can use the CLI included to generate a new package using some of these examples. Here is how you can do that:

```bash
$ mkdir MyFolder
$ cd MyFolder
$ style-dictionary init [example]
```

Where `[example]` is one of: `basic`, `complete`.

## Basic
[View on Github](https://github.com/amzn/style-dictionary/tree/master/example/basic)

This example code is bare-bones to show you what this framework can do. Use this if you want to play around with what the Style Dictionary can do.


## Complete
[View on Github](https://github.com/amzn/style-dictionary/tree/master/example/complete)

This is a more complete package and should have everything you need to get started. This package can be consumed as a Cocoapod on iOS, as a node module for web, and as a local library for Android.

## Advanced
[View the folder](https://github.com/amzn/style-dictionary/tree/master/example/advanced)

If you want to look at more advanced examples of possible applications and customisations of Style Dictionary, the `examples/advanced` folder on GitHub contains these extra folders:

* [**assets-base64-embed**](https://github.com/amzn/style-dictionary/tree/master/example/advanced/assets-base64-embed) shows how it's possible to embed and distribute assets – like images, icons and fonts – directly as design tokens.
* [**auto-rebuild-watcher**](https://github.com/amzn/style-dictionary/tree/master/example/advanced/auto-rebuild-watcher) shows how to setup a "watcher" that auto-rebuilds the tokens every time there is a change in the properties.
* [**custom-templates**](https://github.com/amzn/style-dictionary/tree/master/example/advanced/custom-templates/custom-templates) shows how to use "custom" templates to generate design tokens files with custom formats, useful when you need to distribute your design tokens and integrate them with custom pipelines or scripts.
* [**custom-transforms**](https://github.com/amzn/style-dictionary/tree/master/example/advanced/custom-templates/custom-transforms) shows how to use custom tranforms (and transformGroups) to apply custom "tranformations" to the properties when converted to design tokens.
* [**multi-brand-multi-platform**](https://github.com/amzn/style-dictionary/tree/master/example/advanced/multi-brand-multi-platform) shows how to set up Style Dictionary to support a multi-brand (for brand theming) and multi-platform (web, iOS, Android) solution, with property values depending on brand and plaforms.
* [**npm-module**](https://github.com/amzn/style-dictionary/tree/master/example/advanced/npm-module) shows how to set up a style dictionary as an npm module, either to publish to a local npm service or to publish externally.
* [**s3**](https://github.com/amzn/style-dictionary/tree/master/example/advanced/s3) shows how to set up a style dictionary to build files for different platforms (web, iOS, Android) and upload those build artifacts, together with a group of assets, to an S3 bucket.
* [**referencing_aliasing**](https://github.com/amzn/style-dictionary/tree/master/example/advanced/referencing_aliasing) shows how to use referencing (or "aliasing") to reference a value -or an attribute– of a property and assign it to the value –or attribute– of another property.


---

#### Do you think an example is missing?<br/>Do you want to see another example added to the project?<br/>Do you have a working example that we can add to the list?

Fantastic! Let us know by [filing an issue](https://github.com/amzn/style-dictionary/issues) or sending us an email: style-dictionary@amazon.com.
