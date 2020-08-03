An example of using Express with the Typescript complier tsc and with ts-node. Also shows debugging with vscode.

# Scripts

| `npm run ...`       | Description                                                                    |
| ------------------- | ------------------------------------------------------------------------------ |
| build               | Transpile index.ts using the Typescript complier tsc.                          |
| start-using-tsc     | Transpile index.ts using the Typescript complier tsc and run result with node. |
| start-using-ts-node | Transpile index.ts using ts-node.                                              |
| tslint:fix          |                                                                                |
| prettier:write      |                                                                                |

# Running With tsc

- Run script `start-using-tsc`.
- Open http://localhost:8080/

# Running With ts-node

- Run script `start-using-ts-node`.
- Open http://localhost:8080/

# Debugging With tsc

- Start debug configuration `Launch Program with tsc`.

# Debugging With ts-node

- Start debug configuration `Launch Program with ts-node`.

# Problems

Step Over debbuger command going into node internal files even setting skipFiles in launch.json
https://github.com/microsoft/vscode-js-debug/issues/603

vscode: 1.47.3. This will work if the new, upcoming JavaScript debugger is disabled by adding `"debug.javascript.usePreview": false` to your user settings.

# References
