# Bamboo
This repository tracks the progress of potentially using eureka to train a task in simulation, port that task to a physical robot, then port that task to an individual connected to a BCI. This would allow the training of any skill in simulation to be moved to a human which would be mechanically turked into performing tasks they have never known how to do.

I want this technology to spread to everyone in the world. I want this technology to promote human growth and capability. Bamboo spreads wide, grows fast, and grows tall, hence the name.

## Step 1: Leveraging Eureka as in prior works:
Eureka was used to train a robotic dog to move during a simulation. The results are detailed in this following [article](https://interestingengineering.com/innovation/nvidia-robot-yoga-ball-balance). 

The first step would be to recreate this work - use Eureka to train a robot to do a task. 
Eureka is detailed in the following [github repository](https://eureka-research.github.io).

## Step 2: Port Eureka to a robotic form
The second step in this process is to move the trained model from Eureka to a robotic form. This proves that the code is useable in a robotic form. Imagine training in Eureka and porting to Spot (which has a [public sdk](https://dev.bostondynamics.com/docs/protos/readme)).
This process was detailed in the following [article](https://interestingengineering.com/innovation/nvidia-robot-yoga-ball-balance).

## Step 3: Porting the code to an animal connected to a BCI

In this step, an animal connected to a BCI would be mechanically turked to move based upon inputs. The BCI would need to be attached to locations of the brain that controls muscular movement. Fine-grained movement would need to be controlled and translated to some sort of API. From which the task that was trained in simulation would be used to train the human or animal. 

Rather than the BCI reading the positions of joints as in the following clip, the movement would be written to by sending a physical voltage to the area of the brain associated with stimulating the muscles that control that movement. See the following [video clip](https://youtu.be/m5TORNl_jgg?t=39):

This limiting factor for this work is step 3 - I believe it is possible to send a signal to the brain to move an animal's physical appendages, but it is unknown publicly if this is done or, if it is, to what degree this is acheived. Is there an API? Is there an interface that allows the control such as in the following [clip](https://www.google.com/search?q=black+widow+pig+scene+breathing&safe=active&client=safari&sca_esv=697ef796fdf142b1&rls=en&ei=80VFZsqENvuCwbkPrZW58AY&ved=0ahUKEwiKypK16JCGAxV7QTABHa1KDm4Q4dUDCA8&uact=5&oq=black+widow+pig+scene+breathing&gs_lp=Egxnd3Mtd2l6LXNlcnAiH2JsYWNrIHdpZG93IHBpZyBzY2VuZSBicmVhdGhpbmdImxdQyg1Y1RZwAngBkAEAmAFkoAGRBqoBAzguMbgBA8gBAPgBAZgCBqAC-QLCAgoQABiwAxjWBBhHwgIGEAAYFhgewgILEAAYgAQYhgMYigXCAgUQIRigAcICBRAhGJ8FmAMAiAYBkAYIkgcDNC4yoAfiEA&sclient=gws-wiz-serp#fpstate=ive&vld=cid:2c0cd745,vid:fWO9Lw4Z48E,st:0)? 

A crude example of this concept is [this presentation](https://vimeo.com/296925760) in which EMG is used to send a signal from one brain to control the arm movements of another individual.

Through the realization of this technology, people will be able to access skills, rather than knowledge, of which were never accessible before. I believe this will allow people to fundamentally change who they are in the world and make the world a better place for improving the quality of the people living in the world and the quality of their lives not unlike [Unity does in Rick & Morty](https://rickandmorty.fandom.com/wiki/Unity).

It is not hard to imagine a world where people are reformed by physically controlling their behaviors through software to enable them to live different lifestyles while understanding their intent without question. This method of reform eliminates any ambiguity in choice or intent, and results in an individual who's capabilities far surpass those that they had previously obtained or could have obtained in a lifetime through traditional means of education or reinforcement. These results are the results of this technology at its peak, and encourages the continuation of all human life because there is no penalty of doing such otherwise. It creates a world where reinforcement learning for the sake of behavioral reform is uncessessary and obsolete due to timliness, capability, and morality. 
