# homebrew-tap

Homebrew tap for the [catchbin](https://catchbin.io) CLI — a webhook inspector
with persistence (permanent webhook URLs, captured-event inspection, replay,
signature diagnostics).

## Install

```sh
brew install catchbin/tap/catchbin
```

This installs the `catchbin` command on macOS.

> **Linux / Windows:** Homebrew casks are macOS-only. Use the `curl | sh`
> installer or a direct download:
>
> ```sh
> curl -fsSL https://catchbin.io/install.sh | sh
> ```

## What's in here

`Casks/catchbin.rb` — the Homebrew cask for the `catchbin` CLI. It is generated
and pushed automatically by the CLI's release pipeline on every tagged release;
do not edit it by hand.

## License

The `catchbin` CLI is MIT-licensed.
