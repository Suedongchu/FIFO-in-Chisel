FIFO-in-Chisel
=======================
## How to use it

### clone Chisel Project Template
install Chisel Project Template with repo of [Chisel Project Template](https://github.com/ucb-bar/chisel-template.git) 

### copy files into src
1.make a dir called utils under MyChiselProject/src/main/scala/ and MyChiselProject/src/test/scala/
2.copy fifo.scala to MyChiselProject/src/main/scala/utils
3.copy other source files to MyChiselProject/src/test/scala/utils

### get verilog and test fifo
cd MyChiselProject/
#get verilog
sbt "test:runMain utils.myFifoDriver"

#test fifo
sbt "test:runMain utils.myFifoTester"
