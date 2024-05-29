# Terminal

## Controle de processos

```bash
jobs
bg %1
fg %1
kill %1
kill -9 %1
wait %1
disown %1
nohup command &
ps
top, htop, btop
killall
pkill
pgrep
renice
nice
ionice
at
cron
```

## Redirecionamento

command > file
command >> file
command < file
command 2> file
command 2>> file

## Pipe

command1 | command2
command1 | command2 | command3

## Variáveis de ambiente

env
set
unset VAR
export VAR=value
PATH=$PATH:/new/path
echo $PATH

## Shell script

```bash
#!/bin/bash
# Comentário
echo "Hello, World!"
```

## Variáveis de shell

$VAR
${VAR}
$0, $1, $2, $3, $4, $5, $6, $7, $8, $9
$#, $*, $@
$?, $$

### Estruturas de controle

```bash
if [ condition ]; then
    command
elif [ condition ]; then
    command
else
    command
fi

for VAR in list; do
    command
done

while [ condition ]; do
    command
done

case $VAR in
    pattern1)
        command
        ;;
    pattern2)
        command
        ;;
    *)
        command
        ;;
esac
```

## Funções

```bash
function_name() {
    command
}
```

```bash
function_name() {
    command
    return value
}
```

## Comandos úteis

### find

find /path -name "file"

### grep

grep "pattern" file

### tr

tr 'a' 'A' < file

### sed

sed 's/pattern/replacement/' file

### awk

awk '{print $1}' file

### cut

cut -d' ' -f1 file

### sort

sort file

### uniq

uniq file

### wc

wc file

### head

head -n5 file

### tail

tail -n5 file



