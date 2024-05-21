# action-cmake

## Inputs

### `build_type`

cmake build_type. (default: relwithdebinfo).

## Example usage

```yaml
- name: Build and publish
  uses: brinkqiang/action-cmake@v1
  with:
    build_type: 'relwithdebinfo'
```