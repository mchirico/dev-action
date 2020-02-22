# Hello world javascript action

References:
[javascript-actions](https://github.com/actions/javascript-action)

https://help.github.com/en/actions/building-actions/creating-a-javascript-action



This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-javascript-action@v1
with:
  who-to-greet: 'Mona the Octocat'

# dev-action
