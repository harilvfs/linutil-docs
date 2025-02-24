---
title: "Commands"
description: ""
summary: ""
date: 2025-02-20T16:04:48+02:00
lastmod: 2023-02-20T16:04:48+02:00
draft: false
weight: 810
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

<img src="https://harilvfs.github.io/linutil-docs/images/script.png" width="50">


*Linutil supports various command-line arguments to customize its behavior. Here are some common arguments you can use:*

- `-c, --config <CONFIG>` : Path to the configuration file.
- `--override-validation` : Show all available options, disregarding compatibility checks (UNSAFE).
- `--size-bypass` : Bypass the terminal size limit.
- `-y, --skip-confirmation` : Skip confirmation prompt before executing commands.
- `-t, --theme <THEME>` : Set the theme to use in the application [default: `default`] [possible values: `default`, `compatible`].
- `-h, --help` : Print help.

For more detailed usage, run:

```bash
curl -fsSL https://christitus.com/linux | sh -s -- --help
```

```bash
linutil --help
```

