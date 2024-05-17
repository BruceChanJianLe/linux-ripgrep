# ripgrep

This repository demonstrates usage of riggrep.

## Search and Replace

```bash
# Search for "global_planner" and replace with "globalPlanner"
rg -l "global_planner" | xargs sed -i "s/global_planner/globalPlanner/g"
```

## References
- https://jdhao.github.io/2020/02/16/ripgrep_cheat_sheet/
