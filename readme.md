## Mugi Cha-interpreter

Mugi Cha is Programing Language.<BR>
This repository forked from MugiCha.
Originally, Mugicha implemented both compiler and interpreter, but decided to divide this.

## Sample Code

This is mugicha language sample code.
```
func test(var x int) int {
  while x < 100 {
    print(x)
    x = x + 1
  }
  x
}

func main() int {
  var x int
  x = test(x = 0) + 1
  print(x)
  0
}
```

## Build

To build, run the following command.
```
make
```

## Execution exsample

run the following command.

### for interpreter
```
make run_interpreter
```

## contribution

Contributions welcome!

If there is contact, please write to the Issues. Or, please mail.
yoshidaforpublic@gmail.com

## License

 MIT
