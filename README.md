# todo - built with rust

Build: ```cargo build --release```

Usage:
```
> ./todo add "wake up" "make breakfast" "go shopping"
1. wake up
2. make breakfast
3. go shopping

> ./todo remove 3
1. wake up
2. make breakfast

> ./todo change 2 "make dinner"
1. wake up
2. make dinner

> ./todo ls
1. wake up
2. make dinner

> ./todo done 1
1. wake up V
2. make dinner
```