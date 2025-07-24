# Description of the components of the GitHub Actions yaml file

## GitHub actions yaml definition

```yaml
name: Run Shell commands
on:
  workflow_call:
  workflow_dispatch:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  run_shell_command:
    runs-on: ubuntu-latest
    steps:
      - name: Echo a string
        run: echo "DevSecOps in progress."
```

* name - Implies the name of the github actions yaml file.
* on - Implies when the action will take place.
* jobs - Implies what all actions will take place once the file is executed.
* run_shell_command - This is human-defined and is a logical identifier for the action(s) the job is meant to perform.
* runs-on - Specifies the machine on which the script runs.
* steps - The instructions that needs to be executed on the runner.
