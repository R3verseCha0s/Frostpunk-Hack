# Fallout 1 (Classic) Trainer

## About

![The trainer in action](https://github.com/danjaaron/Frostpunk-Hack/blob/master/frostpunk-trainer.PNG)

This repository contains the source code for a "God Mode" cheat for Frostpunk.

Whenever resources are expended in Frostpunk, whenever coal is burned by the generator or food is consumed by the citizens, there is a particular line of assembly which is executed by your CPU. 

This line of assembly is what causes your balance of coal, or food, or steam cores, or any other resource to change as a result of that event. 

This hack will temporarily "replace" that line of assembly with a new instruction, which instead makes that resource equal to 999.

So, rather than losing one food after it's consumed by your cook house, you will now have 999 food. 

This essentially solves every problem you may encounter in the game, hence "God Mode". 

## Setup

There are two options, depending on your system architecture.

### Option 1: Windows x86

If you're running Windows x86, simply run the standalone .EXE file after starting the game.


### Option 2: Cheat Engine

Open the attached Cheat Table (.CT) in Cheat Engine. Run the game and attach to the game process with Cheat Engine. 

Navigate to "Table" --> "Show Lua Script" and then click on "Execute Script". The trainer GUI shown above should open and the trainer will then activate. 

## Usage

Simply press the button to activate "God Mode" :)  
