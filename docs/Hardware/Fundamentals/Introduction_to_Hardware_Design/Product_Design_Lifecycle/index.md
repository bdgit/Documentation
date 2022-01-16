---
layout: Hardware
title: Product Design Lifecycle
subtitle: Understanding the lifecycle of IoT and hardware products.
---

Designing an IoT/hardware device is an iterative and interelated process that typically consists of the following major phases:

* **Hardware Prototyping**
* **Industrial Design Prototyping**
* **Production Design & Optimization**

## Hardware Prototyping

IoT products are often designed from the inside-out, with the hardware-design ocurring first. Even industrial design-heavy products in which the industrial design drives many hardware layout decisions are first prototyped this way. Components used in this initial design phase are very large and there are usually lots of debug features built into the hardware design itself.  

This is phase is where many of the major hardware design decision are made and various hardware challenges are solved. It's not uncommon during this phase to approach hardware challenges from multiple angles and try different solutions. It can also be **very helpful at this stage to break the hardware design into constituent pieces and solve them individually** in their own breadboard and/or PCB prototypes before putting them together.

This phase often consists of the following tasks:  

 * **Breadboard Prototyping** - Breadboarding can be a fast and easy way to test parts of design problems and provide early feedback on what will work, and what will not. Often, pre-built modules are available that can greatly simplify this process.
 * **PCB Prototyping** - With the modern PCB supply chain, affordable PCBs can be fabricated within a week and received within two. With modern electronic designs, spinning a PCB might actually be easier or even required for particular design challenges.
 * **Hardware Design Validation** - Once a particular design challenge has a potential solution, it's important to test it and validate that it works. At this stage, it can often be helpful to try different approaches and evaluate their cost, complexity, and effectiveness.
 * **Design Integration** - While hardware design is typically approached by breaking it into pieces, it's important to test all the various solutions together to see if they fit in the overall design. This is an especially important step in regards to power management and budgeting, as only when all the pieces are together can you get an accurate understanding of how the overall solution behaves.

## Industrial Design Prototyping

Typically, once the basics of the hardware design are validated, a user design around the hardware is prototyped. Early industrial designs might be very far from the desired final design, especially in regards to size, as early hardware designs are typically much larger than volume production designs.

3D printing has revolutionized industrial design, providing a fast and cheap way to create and validate industrial designs, and there are a number of great Computer-Aided-Design (CAD) programs that simplify this process.

Internally, we use [AutoDesk Fusion 360](https://www.autodesk.com/products/fusion-360/overview) which has a free version for non-commercial use, but there are also some great free and open-source alternatives, such as [OpenJSCAD](https://github.com/jscad/OpenJSCAD.org).

## Production Design & Optimization

Once the major design challenges have been solved

[optimize components]
[production industrial design - injection molding, etc.]


* **Low-Volume Production** - [validation of early product. integration of industrial design. initial optimization for production]

* **High-Volume Production** - 



## [Next: Unit Production Scale](/Hardware/Fundamentals/Introduction_to_Hardware_Design/Production_Scale/)

