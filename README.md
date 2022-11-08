# KinoAOC

Advent of Code Helper integrations with [Kino](https://github.com/livebook-dev/kino) for [Livebook](https://github.com/livebook-dev/livebook).

## Installation

To bring KinoAOC to Livebook all you need to do is `Mix.install/2`:

```elixir
Mix.install([
  {:kino_aoc, git: "https://github.com/ljgago/kino_aoc"}
])
```

## Use

You only need add the smart cell `Advent of Code Helper` and select the `YEAR`,
`DAY`, `SESSION` and the output `ASSIGN TO`.

![Screenshot](priv/img/screen_1.png)

In `SESSION` you can configure a `secret` or set a string directly.
The session token is a cookie which is set when you login to AoC. You can find
it with your browser inspector.

> **Warning**
> The string mode save the content is directly in the notebook.
> Be careful to share the notebook.

A [tamplate](priv/livebook/aoc_template.livemd) that you can use.

## License

[MIT License](LICENSE)