# Contiki-Cooja-Intro-01

Hands-on experience for Contiki-Cooja simulation.
Simulate broadcast in Cooja by using rime stack.

## Descriptions

It is my assignment for EIT digital coursera course - [Embedded Hardware and Operating Systems](https://www.coursera.org/learn/embedded-operating-system/home/info)
A random node broadcasts to all nodes when both an etimer event and a button sensor event are triggered. Tips: reuse and modify an example code in [example-broadcast.c](https://github.com/contiki-os/contiki/blob/master/examples/rime/example-broadcast.c) file. The file [example-trickle.c](https://github.com/contiki-os/contiki/blob/master/examples/rime/example-trickle.c) can be used as a reference for using buttons.

## Prerequisites

1. VirtualBox
2. [Instant Contiki](http://www.contiki-os.org/start.html)

## Run Simulation

### Clone this repo
1. create custom folder under "user@instant-contiki:~/contiki"
   $mkdir my-app
2. $cd my-app
3. $git clone https://github.com/supersubwoofer/contiki-cooja-intro-01
4. $cd contiki-cooja-intro-01

### Create Simulation in Cooja

