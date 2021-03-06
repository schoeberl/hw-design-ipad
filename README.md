# Hardware Design on an iPad

This repository is an experiment to do hardware design with cloud based services and having only a tablet, an iPad, as frontend. Only at the very last stage we might need a laptop with an FPGA board attached.

Let's see where this journey leads us and what we can learn from it.

## Project Ideas

We could simply do a vending machine as a proof of the concept. But this is probably very booring ;)

At a greek island, some time ago, I sketched Lipsi, a tiny processor, or maybe better programmable state machine. A circuit itended for helper functions. Maybe this is a more interesting target. This project might also include some software tools, e.g., an assembler.


## How to Start?

The start is already done! This text is written in a web based editor on GitHub to edit README.md on the fly. Therefore, a repository at GitHub is the starting point.

## Where to Execute?

Editing some code can be done everywhere, even locally on an iPad. However, we need to execute stuff. And compilation and simulation of hardware description is (currently) not supported on the iPad. Therefore, we move to the cloud: https://c9.io/ provides an Ubuntu based development environment as cloud service. Simply cool!

Befor setting up a project in Cloud9, we need to decide on the tools. Within this experiment we wil use [Chisel](https://chisel.eecs.berkeley.edu), a modern hardware construction language. The setup is very minimal, as we just need the magic tool 'sbt' tool, which will download the Scala compiler and the Chisel library as needed.

So let's get started:

 * Register at Cloud9
 * Create a plain VM
 * Install sbt and have it in your path

As a first test we can clone the [Chisel tutorial](https://github.com/ucb-bar/chisel-tutorial) and check if the basic tests pass.
 
