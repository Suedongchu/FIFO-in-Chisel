FIFO-in-Chisel
=======================
a width and size scalable fifo in chisel

## How to use it

### clone Chisel Project Template
install Chisel Project Template with repo of [Chisel Project Template](https://github.com/ucb-bar/chisel-template.git) 

### copy files into src
* make a dir called utils under MyChiselProject/src/main/scala/ and MyChiselProject/src/test/scala/
* copy fifo.scala to MyChiselProject/src/main/scala/utils
* copy other source files to MyChiselProject/src/test/scala/utils

### get verilog and test fifo
```sh
cd MyChiselProject/
#get verilog
sbt "test:runMain utils.myFifoDriver"

#test fifo
sbt "test:runMain utils.myFifoTester"
```
