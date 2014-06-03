uploadtest
==========

```
for i in $(seq -f "%02g" 1 10); do dd if=/dev/zero of=file$i count=$((100*1024)); done
```
