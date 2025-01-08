# Coding Dojo - Refactoring Golf

This repository is largely based on https://github.com/daviddenton/refactoring-golf with some changes to ensure, that it
is possible to transform from the source to the target by only using actions provided by IntelliJ IDEA. For other IDEs
it might be necessary to perform some manual changes to achieve the desired transformation.

## Game

Transform the code from hole**N** until it matches the code in hole**N+1** except for the package name and whitespace.

## Rules

1. Only use actions provided by the IDE, such as the "Rename" or "Introduce Variable" action in IntelliJ. Context
   Actions in IntelliJ, that don't change the functionality (e.g. "Remove braces from 'else' statement" ) are also
   allowed.
2. Actions like "Reformat Code" and "Optimize Imports" are also allowed and don't have to be counted.
3. **DON'T** write any code manually. Input for actions be it inline or in a popup are allowed and don't increase the
   step count.

## Tips

- When using IntelliJ, select the package in the source module (e.g. `hole1/src/main/java/hole1`) and the target
  module (e.g. `hole2/src/main/java/hole2`) and use the "Compare Directories" action to see the differences from the
  source to the target.
- Create a branch per hole and commit each step separately to simplify counting of the refactoring steps. This also
  helps you backtrace if necessary.
- Ideally you create a new branch from the main branch for each hole to avoid. Otherwise, if you skip a hole, you might
  already have changes in the target module.
-

## Result

| Game           | your result |
|----------------|-------------|
| hole1 -> hole2 |             |
| hole2 -> hole3 |             |
| hole3 -> hole4 |             |
| hole4 -> hole5 |             |
| hole5 -> hole6 |             |
| hole6 -> hole7 |             |
