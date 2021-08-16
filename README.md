# Dmenu Manager

Dmenu wrapper allowing the use of a toml file to configure dmenu.

See the [example config](./example.toml) for a full explanation of the config options.
Below is a minimal configuration.

`dmenu-manager ~/config.toml`
``` toml
# ~/config.toml
[menu]
#name = "command"
say-hi = "echo 'Hello, world!'"
first = { run = "echo first", group = 1 }
browser = "firefox"
music = "vlc ~/music"

[config]
dmenu.prompt = "example:"
```

## Unlicense
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

Read the full license in the [UNLICENSE](./UNLICENSE) file.
For more information, please refer to <http://unlicense.org/>
