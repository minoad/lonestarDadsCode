# Just enough shell to get you by

## Read, Filter, Slice, Manipulate loop

```shell
((cat/echo/tail/head) -> grep -> tr -> cut -> sort -> uniq ) loop
```

## Kill a process matching an expression

```shell
ps -ef | grep -i Gram | cut -d ' ' -f 2 | xargs -L 1 -I {} sh -c "kill -9 {}"
```
