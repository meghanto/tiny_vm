# tiny_vm
A tiny virtual machine interpreter for Quack programs

## Work in progress

Instructions


For Almost-quack: (quack without typecase)

build 
```
cmake -S . -B ./build
cd build
make
cd ..
```

# Compile and Run:
```
./quack -i quacksample.qck  [-cn Main]
```
# Compile:

```
./quackc -i quacksample.qck [-cn Main]
```

Use the -o and -cn optional parameters to change the output file name and the program class name.

Options:

-i / --input : specify input quack program

-cn / --classname : specify program class name (defaults to Main)
