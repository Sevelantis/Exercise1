# how to run:
run commands:
```
git clone https://github.com/Sevelantis/Exercise1
cd Exercise1/
```

# configure utility
```
source .env
```

# examples of usage
case simple run
```
timeitout ping 8.8.8.8
```

case parameter run
```
timeitout -t 2.3456 ping 8.8.8.8
```

case child parameter present ::  check 'err.log' file
```
timeitout -t 2.3456 ping 8.8.8.8
```

case child parameter not present :: check 'out.log' file
```
timeitout -t 2.3567 ping
```
