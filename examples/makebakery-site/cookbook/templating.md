% Expand some variables in a file
% Michael F. Lamb
% Fri, 23 Apr 2021 15:17:30 -0700

Use a templating plugin like `_m4`, or do a one-off manual template using `executable`.

### Using `executable` for templating

```sh
#!/bin/sh
cat <<EOF
<html>
<p>This file was generated by $USER.</p>
</html>
EOF
```
