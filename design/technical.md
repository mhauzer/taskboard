# TaskBoard Technical Design

# Architecture

```
+-----+ +-----+ +---------+
| Web | | iOS | | Android |
+--+--+ +--+--+ +----+----+
   |       |         |
   +-------+---------+
           |                   
+----------+----------+
| project-manager-api |
+----------+----------+
           |
      +----+----+
      | MariaDB |
      +---------+
```
