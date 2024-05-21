# action-cmake

## Inputs

### `input_foo`

Some description. (default: bar).

### `input_bar`

Some description. (default: foo).

## Example usage

```yaml
- name: Build and publish
  uses: brinkqiang/action-cmake@<release>
  with:
    input_foo: ${{ secrets.FOO }}
    input_bar: "bar"
```