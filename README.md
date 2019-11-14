# strace
This is my version of strace. It can be attached to running process or start new. 
Attaching to running process require root/sudo privileges.


## Compilation
```bash
git clone https://github.com/guzlewski/strace
cd strace
make
```

## Usage
```
./strace.out [executable] [arg1] ...
or
./strace.out -p [pid]
```

## License
Copyright (c) guzlewski. All rights reserved.
