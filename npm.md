## Node Package Manager


Node Package Manager, or npm for short, is a tool for managing packages (or modules) in Node.js. Packages are files or directories stored in a package.json file, while modules are files or directories that can be loaded by a node from the node_modules.

| Command                                    | Description                                                                                    |
| ------------------------------------------ | ---------------------------------------------------------------------------------------------- |
| `npm install <packagename>`                | Install `package.json` dependencies                                                            |
| `npm i <packagename>`                      | Shorthand version of `npm install`                                                             |
| `npm uninstall <packagename>`              | Uninstall a package                                                                            |
| `npm un <packagename>`                     | Shorthand version of `npm uninstall`                                                           |
| `npm update <packagename>` or `npm update` | Update current package to latest version, if no package name specified the update all packages |
| `npm up <packagename"`                     | Shorthand version of updating packages                                                         |
| `npm list`                                 | Print all the packages and their versions installed as well as their dependencies              |
|                                            |                                                                                                |
|                                            |                                                                                                |
## Node Version Manager `nvm`

Switch between different Node.js versions.

| Command                            | Description                                                                    |
| ---------------------------------- | ------------------------------------------------------------------------------ |
| `nvm install <node_version>`       | Install specified node version                                                 |
| `nvm use <node_version>`           | Specifies which node version to use when multiple node versions are installed. |
| `nvm alias default <node_version>` | Make a node version default                                                    |
| `nvm install-latest-npm`           | Update node version installed with nvm                                         |

## Flags