# Full Custom Analog Inverter Design using Cadence EDA Tools
Full custom ASIC design defines all the photolithographic layers of the devices. Full-custom design is used for both ASIC design and for standard product design.

The Advantages of full-custom design include-<br>1. Reduced area, performance improvements.
<br>
2. Ability to integrate analog components and other pre-design and fully verified components, such as microprocessor cores, that form a system on a chip.

<h2>I. Prelude :</h2>

• Introduction to Full Custom IC Design Flow.

<h2>II. Objectives :</h2>

• Voltage Transfer Characteristics of CMOS Inverter.
<br>
• Performance metrics.
<br>
• Schematic Capture and Simulation using Virtuoso Schematic Editor.
<br>
• Creating Layout Using Virtuoso Layout Editor.

<h2>III. Tools Used :</h2>
• Schematic : Cadence Virtuoso - Schematic XL
<br>
• Simulation : Cadence Virtuoso - ADE L
<br>
• Layout : Cadence Virtuoso - Layout XL
<br>
• Technology : gpdk180

<h2>IV. CMOS Inverter Schematic :</h2>

![1719150544049](https://github.com/user-attachments/assets/a531c9ea-7641-4185-9e94-f2b781cf15a7)
<br>
<br>
<br>
<h2>V. Working Principle :</h2>

• CMOS circuit uses both P-type and N-type transistors to create logic functions, which are essential components in designing integrated circuits. The signal that turns ON one type of transistor can also turn OFF another type of transistor.
<br>
<br>
<br>
<h2>VI. Symbol Genarate :</h2>

![Screenshot-2](https://github.com/user-attachments/assets/34dcfbde-b20f-4ebe-a007-2aeafef31c3c)
<br>
<br>
<br>
<h2>VII. Transient Analysis :</h2>

![Screenshot-4](https://github.com/user-attachments/assets/16191248-7ba3-431d-8c24-dba78239f2bb)
<br>
<br>
<br>
• Towards the rails one of the transistor is cut-off and the other is in linear region.
<br>
• As we approach middle of the input voltage both the transistors are in saturation region.
<br>
• The slope of the VTC is known as the Gain of the gate.
<br>
<br>
<br>
![Screenshot-5](https://github.com/user-attachments/assets/c07ff67a-f214-4b22-b49d-b60ea5b09655)
<br>
<br>
<br>
• To construct the VTC of the CMOS inverter, we need to graphically superimpose the I-V curves of the nMOS and pMOS onto a common    coordinate set.
<br>• Switching Threshold, VM is the point where Vin=Vout.
<br>• Graphically it calculated at intersection point of Vin curve with Vout curve.
<br>

<h2>VIII. Propagation Delay :</h2>

It is time taken for be output to discharge from logic high 50% of fixed value or we can also defination as time taken by output charge from logic '0' value to be 50% of switch maximum value.

![WhatsApp Image 2024-07-16 at 16 20 51_6aadb7d9](https://github.com/user-attachments/assets/8423ccfd-ef12-4def-a6c5-d193bf09dba5)
<br>
<br>
<br>
<h2>IX. The Propagation Delay can be Reduced by :</h2>
<br>• Increasing Power Supply
<br>• Increasing W
<br>• Reducing CL

<h2>X. Static CMOS properties : </h2>

Basic inverter belongs to class of static circuits
output always connected to either VDD or VSS.

• Rail to rail voltage swing.
<br>• Ratio less design.
<br>• Low output impedance.
<br>• Extremely high input impedance.
<br>• No static power dissipation.
<br>• Good noise properties/margins.

<h2>XI. CMOS Inverter Layout :</h2>


![Screenshot-6](https://github.com/user-attachments/assets/d74a5e55-a4b2-4f78-83d6-4b0bc66c3cce)
<br>
<br>
<br>
<h2>XII. Conclusion :</h2>

Despite certain design and speed limitations, their low energy consumption, high efficiency, and excellent noise immunity make CMOS inverters the technology of choice for current and future high-density, high-performance electronic integrated circuit designs. With the continuous advancement and innovation of technology, it is expected that CMOS inverters will continue to play an increasingly important role in key fields such as microprocessors, storage devices, and communication systems, promoting the development of modern electronic equipment to a higher technical level.

