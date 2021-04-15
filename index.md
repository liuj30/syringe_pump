# How to Build a Syringe Pump?

- **[Home](/syringe_pump/index)**
- [Mechanical](/syringe_pump/mechanical)
- [Electrical](/syringe_pump/Electrical)
- [Code](/syringe_pump/code)


See physical assembly page [here](/syringe_pump/physical_device)

# Watch the Syringe Pump in Action

[![Syringe Pump in Action](https://img.youtube.com/vi/9kMAXheGo4w/0.jpg)](https://www.youtube.com/watch?v=9kMAXheGo4w)

You should build and program your own syringe pump! This is a good way to combine your engineering trainnings and gain practical experience with building devices! It is a lot of fun and will help your future design projects (e.g. senior design project). So, get started and give it a try!

Specifications of the syringe pump: 

Since the syringe pump can hold up to 20 ml of solutions, this is the physical limitation that has to be considered when integrating this pump into a bioplotter. 

ml per step (resolution) = (linear distance / step) * cross section area of the syringe pump = (0.125 cm / 3200) * pi * (0.95 cm)^2 = 1.11E-4 ml/step

Max flow rate is limited by the revolutions per min of the stepper motor, which is 700 rmp. With this rate, the device can extend 875 mm per minute. In reality, the pump will never extend with such a high linear velocity. Therefore, the true limiting factor is the friction between the pump and solutions within it. 

