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

![1719150544049](https://github.com/user-attachments/assets/bb20cffe-0b12-4dc4-bb82-3774492116df)
<br>
<BR>
<h2>V. Working Principle :</h2>

• CMOS circuit uses both P-type and N-type transistors to create logic functions, which are essential components in designing integrated circuits. The signal that turns ON one type of transistor can also turn OFF another type of transistor.
<br>
<br>
<br>
<h2>VI. Symbol Genarate :</h2>

![1719100416459](https://github.com/user-attachments/assets/60641c8a-65b9-4f6a-a454-7c638f4e35bc)
<br>
<br>
<br>
<h2>VII. Transient Analysis :</h2>

![1719122005348](https://github.com/user-attachments/assets/8fef94e6-8af4-476c-b2bb-25d1b1dde974)

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

![1719133644577](https://github.com/user-attachments/assets/4f74b137-234a-45f9-8779-567d1dc7f79c)

<br>
<br>
<br>
• To construct the VTC of the CMOS inverter, we need to graphically superimpose the I-V curves of the nMOS and pMOS onto a common    coordinate set.
<br>• Switching Threshold, VM is the point where Vin=Vout.
<br>• Graphically it calculated at intersection point of Vin curve with Vout curve.
<br>
<BR>
<h2>VIII. Propagation Delay :</h2>

It is time taken for be output to discharge from logic high 50% of fixed value or we can also defination as time taken by output charge from logic '0' value to be 50% of switch maximum value.

![Screenshot (139)](https://github.com/user-attachments/assets/9177b607-1c58-4941-b6b7-adad5016cfc0)

<br>
<br>
<br>
<h2>IX. The Propagation Delay can be Reduced by :</h2>
<br>• Increasing Power Supply
<br>• Increasing W
<br>• Reducing CL
<BR>
<BR>
<h2>X. Static CMOS properties : </h2>

Basic inverter belongs to class of static circuits
output always connected to either VDD or VSS.

• Rail to rail voltage swing.
<br>• Ratio less design.
<br>• Low output impedance.
<br>• Extremely high input impedance.
<br>• No static power dissipation.
<br>• Good noise properties/margins.
<BR>
<BR>
<h2>XI. CMOS Inverter Layout :</h2>


![1719184242276](https://github.com/user-attachments/assets/e89fad23-2f36-4cb9-9089-111d403ab9df)

<br>
<h2>XII. Conclusion :</h2>

Despite certain design and speed limitations, their low energy consumption, high efficiency, and excellent noise immunity make CMOS inverters the technology of choice for current and future high-density, high-performance electronic integrated circuit designs. With the continuous advancement and innovation of technology, it is expected that CMOS inverters will continue to play an increasingly important role in key fields such as microprocessors, storage devices, and communication systems, promoting the development of modern electronic equipment to a higher technical level.

