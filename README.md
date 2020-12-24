# reading-list
A recommended reading list in FENGLIN group.

FORMAT: **TITLE**, venue, 1st author.

- [reading-list](#reading-list)
  - [Hardware](#hardware)
    - [Architecture Design](#architecture-design)
    - [Simulation Framework](#packetflow-scheduling)
    - [Packet/Flow Scheduling](#Simulation-Framework)
      - [Paper](#paper-1)
    - [TSN data plane](#tsn-data-plane)
      - [data plane abstraction paper](#data-plane-abstraction-paper)
  - [Software](#software)
    - [Scheduling](#scheduling)
      - [paper](#paper-2)
      - [slide](#slide-1)
      - [blog](#blog-1)
    - [Clock synchronization](#clock-synchronization)
      - [paper](#paper-3)
      - [slide](#slide-2)
      - [blog](#blog-2)
    - [End-system packet I/O](#end-system-packet-io)
      - [paper](#paper-4)
      - [slide](#slide-3)
      - [blog](#blog-3)

## Hardware

### Architecture Design

#### paper

1. **hXDP: Efficient Software Packet Processor on FPGA NICs**, OSDI 2020, Marco Brunella, etc. [pdf](https://www.usenix.org/system/files/osdi20-brunella.pdf)
3. **nanoPU: Redesigning the CPU-Network Interface to Minimize RPC Tail Latency**, Arxiv 2020, Stephen Ibanez (Stanford). [pdf](https://arxiv.org/pdf/2010.12114.pdf), [code](https://github.com/l-nic)
3. **PANIC: A High-Performance Programmable NIC for Multi-tenant Networks**, OSDI 2020, Jiaxin Lin (Wisconsin-Madison). [pdf](https://www.usenix.org/system/files/osdi20-lin.pdf), [sides](https://www.usenix.org/sites/default/files/conference/protected-files/osdi20_slides_lin.pdf), [code

#### blog

1. [What Does RISC and CISC Mean in 2020?](https://medium.com/swlh/what-does-risc-and-cisc-mean-in-2020-7b4d42c9a9de)

### Simulation Framework

#### paper

1. **FireSim: FPGA-Accelerated Cycle-Exact Scale-Out System Simulation in the Public Cloud**, ISCA 2018, Sagar Karandikar (UC Berkeley). [pdf](https://sagark.org/assets/pubs/firesim-isca2018.pdf), [website](https://fires.im/), [slide](http://iscaconf.org/isca2018/slides/1A3.pdf), [code]([github.com/firesim/firesim](https://github.com/firesim/firesim))
2. **FirePerf: FPGA-Accelerated Full-System Hardware/Software Performance Profiling and Co-Design**, ALPLOS 2020, Sagar Karandikar (UC Berkeley). [pdf](https://people.eecs.berkeley.edu/~alonamid/papers/asplos2020-fireperf.pdf)

### Packet/Flow Scheduling

#### Paper

1. **Programmable Calendar Queues for High-speed Packet Scheduling**, NSDI 2020, Sharma (NYU). [pdf](https://cs.nyu.edu/~anirudh/calendar_queues.pdf) 

### TSN data plane

#### data plane abstraction paper

1. **OpenFunction: An Extensible Data Plane Abstraction Protocol for Platform-Independent Software-Defined Middleboxes**, TON 2018, Chen Tian (Nanjing University). [pdf](https://cs.nju.edu.cn/tianchen/lunwen/2018/openfunction-tnet.pdf) 
2. **StreaMon: A Data-Plane Programming Abstraction for Software-Defined Stream Monitoring**, TDSC 2013, Giuseppe Bianchi (University of Rome Tor Vergata). [pdf](https://arxiv.org/pdf/1311.2442.pdf) 

## Software
### Scheduling
#### paper
#### slide
#### blog
### Clock synchronization
#### paper
#### slide
#### blog
### End-system packet I/O
#### paper
1. **Commodity Packet Capture Engines: Tutorial, Cookbook and Applicability**, IEEE Communications Surveys & Tutorials 2015, Victor Moreno. [**pdf**](https://ieeexplore.ieee.org/document/7101227)
#### slide
#### blog
1. [**Monitoring and Tuning the Linux Networking Stack: Sending Data**](https://blog.packagecloud.io/eng/2017/02/06/monitoring-tuning-linux-networking-stack-sending-data/)
2. [**Monitoring and Tuning the Linux Networking Stack: Receiving Data**](https://blog.packagecloud.io/eng/2016/06/22/monitoring-tuning-linux-networking-stack-receiving-data/)
3. [**Queueing in the Linux Network Stack**](https://www.coverfire.com/articles/queueing-in-the-linux-network-stack/)
