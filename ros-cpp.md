---
layout: default
title: "C++ codeing Style in ROS projects"
---

# 1. Naming Conventions

The following shortcuts are used in this section to denote naming schemes:
- **CamelCased**: The name starts with a capital letter, and has a capital letter for each new word, with no underscores.
- **camelCased**: Like CamelCase, but with a lower-case first letter
- **under_scored**: The name uses only lower-case letters, with words separated by underscores. (yes, I realize that under_scored should be underscored, because it's just one word).
- **ALL_CAPITALS**: All capital letters, with words separated by underscores.

## 1.1 Packages
ROS packages are **under_scored**.

## 1.2 Topics / Services
ROS topics and service names are **under_scored**.

## 1.3 Files
All files are **under_scored**.

Source files have the extension **.cpp**.

Header files have the extension **.h**.

Be descriptive, e.g., instead of laser.cpp, use hokuyo_topurg_laser.cpp.

Normally a file implements a class, therefore name the file after the class. For example the class ActionServer would live in the file action_server.h.
