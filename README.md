## Workflow Configuration

### Action Inputs

| Input Name        | Description                       | Type      | Default                                   | Required |
|-------------------|-----------------------------------|-----------|-------------------------------------------|----------|
| `target-repo-name`      | The base name of the cache.       | `string`  | `${{github.job}}`                         | No       |
| `copy-source`     | The base branch for the cache.    | `string`  | `master`                                  | No       |
| `target-branch`     | The path of the scons cache.      | `string`  | `${{github.workspace}}/.scons-cache/`     | No       |
| `commit-message`     | The path of the scons cache.      | `string`  | `${{github.workspace}}/.scons-cache/`     | No       |
| `current-directory`     | The path of the scons cache.      | `string`  | `${{github.workspace}}/.scons-cache/`     | No       |