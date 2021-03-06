# CloudEvents Schema VSC Extension

JSON Schema support for the [CloudEvents specification](https://github.com/cloudevents/spec/blob/master/spec.md)

## Features

### Code Hints

This extension provides Code Hints for JSON files in your project against the
CloudEvents specification JSON Schema.
This includes:

-   Prompting correct attribute names as you type.
-   Displaying of mismatched types or missing required properties
-   Allows use of Ctrl+Space to show available properties
-   Code completion even for enum types

### Code Snippets

This extension also provides Code Snippets for the CloudEvents markup:

-   cee: Create a new CloudEvents example

More features coming soon :)

## Building from source

If you do not want to get this extension from the Marketplace or would like to build and test
the latest changes/updates locally follow these steps:

1. Clone the extension git repository

```
git clone https://github.com/tsurdilo/cloudevents-schema-vscode.git
cd cloudevents-schema-vscode
```

2. Build and package the extension with vsce:

```
vsce package
```

To install vsce run:

```
npm install -g vsce
```

3. vsce will create a cloudevents-schema-vscode-$VERSION$.vsix file which you have to install to your ide, for this run:

```
code --install-extension cloudevents-schema-vscode-$VERSION$.vsix
```

to uninstall the extension run:

```
code --uninstall-extension cloudevents-schema-vscode-$VERSION$.vsix
```

## Contributing

This extension is open-source and free to use to anyone.
All/any contributions are very welcome and much needed in order to make this extension much better.
Best way to contribute is to create Pull Request(s) on the github project.
