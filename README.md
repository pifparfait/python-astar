python-astar
============

simple implementation of the a-star algorithm in python

using it is quite obvious, see example provided in module.

Here is an example of what is basically does :
```

+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+
|##|           |                    |        |              |
+ #+  +--+--+  +  +--+--+  +--+  +--+  +--+  +  +--+--+--+  +
| #|  |     |     |     |     |           |  |     |     |  |
+ #+  +  +  +--+--+  +  +--+  +--+--+--+--+  +--+  +  +  +  +
| #   |  |     |     |  |  |        |           |  |  |  |  |
+ #+--+  +  +--+  +--+  +  +  +--+--+  +--+--+  +  +--+  +  +
| #|     |  |     |  |  |     |     |        |  |  |     |  |
+ #+  +  +  +  +--+  +  +  +--+  +  +--+--+  +  +  +  +--+  +
| #|  |  |  |     |  |  |     |  |  |        |  |  |  |     |
+ #+--+  +--+--+  +  +  +--+--+  +  +  +--+--+  +  +  +  +  +
| ####|    ####|  |     |        |     |     |  |     |  |  |
+--+ #+--+ #+ #+  +  +--+  +--+--+--+--+  +  +--+--+  +  +  +
|  | ####| #| #|  |        |              |        |  |  |  |
+  +--+ #+ #+ #+  +--+--+  +  +--+--+--+--+--+  +--+  +  +--+
| ####| ####| #|     |     |        |  |        |     |     |
+ #+ #+--+--+ #+--+  +--+--+--+--+  +  +  +--+--+  +--+--+  +
| #| ####   | ### |              |  |  |        |     |     |
+ #+--+ #+--+--+# +--+--+--+  +  +  +  +--+--+  +--+  +  +--+
| ####| ######### |        |  |  |  |        |     |  |  |  |
+--+ #+--+--+--+--+--+--+  +  +--+  +--+--+  +--+  +  +  +  +
|  | ################## |  |                 |     |  |     |
+  +--+--+--+--+--+--+# +  +--+--+--+--+--+--+  +  +  +--+--+
|           | #######|#       |        |        |  |  |     |
+  +--+--+--+ #+--+ #+# +--+--+  +--+  +  +--+--+--+  +  +  +
|           | #|  | #|# |     |  |  |     |        |  |  |  |
+  +--+--+  + #+  + #+# +  +  +  +  +--+  +  +--+  +  +--+  +
|  |     |  | #|  | ### |  |     |        |  |     |  |     |
+  +--+  +  + #+  +--+--+  +--+--+--+--+--+  +  +--+  +  +--+
|     |  |  | #| ###### |                    |        |     |
+--+  +  +  + #+ #+--+# +--+--+--+--+--+--+--+--+--+--+  +  +
|  |  |  |  | #| #| ### |    ##########|    ####|        |  |
+  +  +  +  + #+ #+ #+--+  + #+--+--+ #+--+ #+ #+--+--+--+  +
|     |  |  | ####| ### |  | ###### | ####| #| #| ####|     |
+  +--+  +  +--+--+--+# +--+--+--+# +--+ #+ #+ #+ #+ #+  +--+
|  |     |        | ### | ######### |  | ####| ####| #|     |
+  +  +  +--+  +  + #+--+ #+--+--+--+  +--+--+--+--+ #+--+  +
|     |  |     |  | #######|        |              | ####|  |
+--+--+  +  +--+--+--+--+--+  +--+  +  +--+--+  +--+--+ #+  +
|        |                       |           |          ####|
+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+--+
```
enjoy -