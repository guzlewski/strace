# strace
This is my version of strace. It can be attached to the running process or start new. 
Attaching to the running process requires root/sudo privileges.

## Compilation
```bash
git clone https://github.com/guzlewski/strace
cd strace
make
```

## Usage
```
./strace.out EXECUTABLE [arg1] ... [argn]
```
```
./strace.out -p PID
```

## Example
```
./strace.out ls -l -a
```
