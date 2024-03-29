# Naomi's TypeScript Config

This package holds my TypeScript configuration for easy installation and syncing changes across projects.

## Live Version

This package is currently published. [View the `npm` page](https://www.npmjs.com/package/@nhcarrigan/typescript-config).

## Installation

To install this package, run the following command:

```bash
npm i @nhcarrigan/typescript-config typescript
```

## Compatibility

This package is compatible with TypeScript 5.

## Usage

To use this package, add the following to your `tsconfig.json` file:

```json
{
  "extends": "@nhcarrigan/typescript-config"
}
```

By default, the root directory is `src` and the output directory is `prod`. To override these:

```json
{
  "extends": "@nhcarrigan/typescript-config",
  "compilerOptions": {
    "rootDir": "code",
    "outDir": "dist"
  }
}
```

## Feedback and Bugs

If you have feedback or a bug report, please feel free to open a GitHub issue!

## Contributing

If you would like to contribute to the project, you may create a Pull Request containing your proposed changes and we will review it as soon as we are able! Please review our [contributing guidelines](CONTRIBUTING.md) first.

## Code of Conduct

Before interacting with our community, please read our [Code of Conduct](CODE_OF_CONDUCT.md).

## License

This software is licensed under our [global software license](https://docs.nhcarrigan.com/#/license).

Copyright held by Naomi Carrigan.

## Contact

We may be contacted through our [Chat Server](http://chat.nhcarrigan.com) or via email at `contact@nhcarrigan.com`.
