# dotfiles-i3-config
Configuration files for [i3](https://i3wm.org/).

## TODO

### Split configuration

TL;DR: 

- split configuration in several files
- tried `include` directive with issues
- therefore tested building `config` file with a shell script (`build_i3_config_test`, `build_i3_config`)
- currently using `bindsym $mod+Shift+F5 exec --no-startup-id ~/.config/i3/build_i3_config_test, reload` for tests

- [ ] Split configuration into multiple files 
  - [ ] refactoring
    - [x] create `config` backup
    - [ ] add `KDE/Plasma` etc cases
  - [x] search for alternatives
    - [x] [i3 configurations split?](https://www.reddit.com/r/i3wm/comments/acybmc/i3_configurations_split/)
    - [x] [Source/import file from i3wm config](https://stackoverflow.com/questions/65044535/source-import-file-from-i3wm-config)
  - [ ] [Implement include config directive #4420](https://github.com/i3/i3/pull/4420)
    - [ ] [4.1. Include directive](https://i3wm.org/docs/userguide.html#include)
    - [ ] [Often requested include directive coming to i3 soon](https://www.reddit.com/r/i3wm/comments/ncetnh/often_requested_include_directive_coming_to_i3/)

### Fixes

- [x] Fix broken config
