# ripgrep

This repository demonstrates usage of riggrep.

## Search and Replace

```bash
# Search for "global_planner" and replace with "globalPlanner"
rg -l "global_planner" | xargs sed -i "s/global_planner/globalPlanner/g"
```

## References
- https://jdhao.github.io/2020/02/16/ripgrep_cheat_sheet/

# [fd](https://github.com/sharkdp/fd)

Will move this to fd repo / notes when available.

## Copy a File recursively

```bash
fd -t d -d 1 | xargs -I {} cp -n param.yaml {}

# without fd
find . -mindepth 1 -maxdepth 1 -type d -exec cp -n param.yaml {}
```
