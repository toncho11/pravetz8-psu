# pravetz8-psu
Explains the different options for repairing or replacing a Pravetz 8 PSU.
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
Ypu can replace all electrolytic capacitors.

## 2) Buy MEAN WELL RT-65B 
It provides 5VDC/5A 12VDC/2.8A -12VDC/0.5A. This is a modern power supply. It is reported that it enters in the case of ST-41A. You need to also buy a 7905 voltage regulator to create -5V form the +5V. Note that now you might have 5A on the -5V instead of 0.5A which is not a problem to make it work, but might provide a high current in case of a problem with other components.

## 3) Buy 12V PSU + PicoPSU-80 + Adapter (PicoPSU към Aplle II)

## 4) Buy new PSU from Reactive Micro
Link: https://www.reactivemicro.com/product/universal-psu-63-watt-switching-power-supply
It is small and has a built in protection. Voltafes are: +12v @ 3A, +5v @6A, -12v @ .8A, -5v @ .8A which are OK. It can enter into the old case and there are also some tutorials on that. The seems not expensive, but when you add the shipping and probably an import tax from USA to Europe and it becomes a bit expensive.

