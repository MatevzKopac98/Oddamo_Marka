# HUSBAND_MODE v1.0 – Release notes

## Merge policy for `life_config.hpp`

When merging HUSBAND_MODE into an existing RELATIONSHIP_MODE install:

1. **HUSBAND_MODE wins every conflict by default.**
2. **Boys' Night Treaty:** the boys keep exactly **one** night per month.
   Not zero. Not four. One.
3. **Fridge Protection Act:** beer stock is **never downgraded** during a system upgrade.

## Known issues

- Not every commit on this branch went through code review.
  Some contributors were "just helping". Trust no one.

## After merging

```
g++ -std=c++17 upgrade.cpp -o upgrade
./upgrade
```
