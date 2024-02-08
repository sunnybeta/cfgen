# Compile Flags Generator

*A simple bash script to generate compile flags from a Makefile.*

This helps me in my C projects when the clangd LSP refuses to look for files outside the current directory.

## Setup

```bash
git clone https://github.com/sunnybeta/cfgen.git
cd cfgen
chmod +x cfgen
```

## Help

```
Usage: cfgen [FILE]

Generate compile_flags.txt file from a single Makefile

Example: cfgen root/Makefile

For bug report, raise an issue at https://github.com/sunnybeta/cfgen/issues or email Sunny Beta <sunnybeta@protonmail.com>.
```

:)
