# `ccwc` Tasks

> ⚠️ Requires [mask][1] task runner to use.

## build

Builds the software.

Bourne Shell:

~~~sh
cargo build
~~~

PowerShell:

~~~powershell
[Diagnostics.Process]::Start("cargo", "build").WaitForExit()
~~~

## test

Runs unit tests, doc tests, and integration test.

Bourne Shell:

~~~sh
cargo test
~~~

PowerShell:

~~~powershell
[Diagnostics.Process]::Start("cargo", "test").WaitForExit()
~~~

## run

Runs the software; use `--` before supplying arguments.

Bourne Shell:

~~~sh
cargo run
~~~

PowerShell:

~~~powershell
[Diagnostics.Process]::Start("cargo", "run").WaitForExit()
~~~

[1]: https://github.com/jacobdeichert/mask
