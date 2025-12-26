---
aliases:
tags:
  - towhill
---
## Winterize

03C - *If can’t guarantee > 0C in battery bay set 03C Set Max Charge Amps to 30 ADC (otherwise 60 ADC which is the inverter max)

*03E -Set max charge percent rate to be 80% or 40% (depending on whether 03C is 30 or 60 ADC, respectively) so that max charge is 24 A to not overload generator. *
## **Setup Summer**

01A Set Clock
01D Max Charge Amps: CC/CV (set from 03C)
01E Link PT Charge Settings: YES

02A Search Watts: OFF
02B LBCO (Low Battery Cut Out): 48 V (as fridge and washer only hard start loads)
02F Power up Always: ON

03C Battery Type: CC/CV (Constant Charge then Constant Voltage)

Set Max Charge Amps: 60 ADC (maximum charge during CC phase)
Set CV Charge Volts: 56 VDC (maximum voltage during CV phase)
Set CV Charge Done Amps: 15 ADC (0.05C)
Set Max CC/CV Time: 12.0 Hrs
Set Recharge Volts: 48.0

03E Max Charge Rate: 40% so that 60 ADC * 0.4 = 24 ADC to not overload generator.

06C Max Charge Rate: 100% (percent of inverter max of 60 ADC)
06D Max Charge Time: 16.0 Hrs

**Questions**

03C Does max charge amps override 03E and 06C separately and combined?

03C Does amps drop to 15 ADC once reaches 56 VDC?

03C Set Max CC/CV Time < 12 Hrs??

If going away battery should be stored at 50% SOC.