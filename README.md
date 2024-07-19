# Pravetz 8 psu replacement options
Explains the different options for repairing or replacing a Pravetz 8 PSU. Pravetz 8 is an Apple II clone.

Как да поставим ново или да поправим старо захранване за Правец 8.

The power supply is usually ST-41A made from SENSTRON ELEC CO.
The voltages are:
| V | A |
| --- | --- |
| +5V | 5A |
| +12V | 2.5A |
| -5V | 0.5A |
| -12V | 0. 5A |

## 1) Replace capacitors
Ypu can replace all electrolytic capacitors. I did that myself because there were a few swollen capacitors. You can even test the power supply with something that you do not need such as a lamp or mechanical HDD. Problem is that without a load and even with one the voltages are different from specification. For example you can get 11V with the HDD attached instead of 12V or -4.6V with no load on the -5V rail. The voltages are supposed to stabilize once they all have a load while attached to the real motherboard. In a nutshell it is hard to tell if it is 100% OK (especially if you are not an expert) untill you plug it to the real motherboard, but then you risk damaging the motherboard.

## 2) Buy MEAN WELL RT-65B 
It provides 5VDC/5A 12VDC/2.8A -12VDC/0.5A. This is a modern power supply. It is reported that it enters in the case of ST-41A. You need to also buy a 7905 voltage regulator to create -5V form the +5V. Note that now you might have 5A on the -5V instead of 0.5A which is not a problem to make it work, but might provide a high current in case of a problem with other components.

## 3) Buy 12V PSU + PicoPSU-80 + Adapter (PicoPSU vs Aplle II)
* You need a 12V 12.5A brick PSU (similar to these used for laptops)
* The 12V PSU will power the PicoPSU-80 which will provide different output voltages on a 20 pin motherboard header
* Next you need this converter: https://www.tindie.com/products/dekunukem/picopsu-adaptor-for-apple-ii-ii-plus-iie pluged to the PicoPSU-80 that will provide the needed voltages for Pravetz 8. Note that your output plug which goes into the motherboard might be different from the one provided in the converter kit. The kit also has some protection fuses, but I am told that this protection will not be very usefull in most cases.

## 4) Buy new PSU from Reactive Micro
Link: https://www.reactivemicro.com/product/universal-psu-63-watt-switching-power-supply
It is small and has a built in protection. Voltafes are: +12v @ 3A, +5v @6A, -12v @ .8A, -5v @ .8A which are OK. It can enter into the old case and there are also some tutorials on that. It seems not expensive, but when you add the shipping and probably an import tax from USA to Europe and it becomes a bit expensive.

