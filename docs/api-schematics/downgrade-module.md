# downgrade-module

Generates downgradeModule setup

## Usage

```bash
ng generate downgrade-module ...

```

### Options

| Name              | Alias | Description                                                                                       | Type    | Default value |
| ----------------- | ----- | ------------------------------------------------------------------------------------------------- | ------- | ------------- |
| `project`         |       | The name of the project                                                                           | string  | `undefined`   |
| `name`            |       | The name of the main AngularJS module.                                                            | string  | `undefined`   |
| `angularJsImport` |       | Import expression of the AngularJS application (e.g., --angularJsImport=some_node_module/my_app). | string  | `undefined`   |
| `skipFormat`      |       | Skip formatting files                                                                             | boolean | `false`       |
| `skipPackageJson` |       | Do not add @angular/upgrade to package.json (e.g., --skipPackageJson)                             | boolean | `false`       |
