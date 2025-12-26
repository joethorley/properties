**Solar Panels**

16 x 285 Watt Panels = 4.56 kW

Produces 4560 W / 56 VDC = 80 ADC

**Charger** PT-100

100 ADC

**Generator -** Honda EM3000c

Produces 2600 W / 57.6 VDC = 45 ADC

**Inverter -** Magnum MS4448PAE

60 ADC @ 56.0 VDC [determines percent max charge rate – 03E]

**Battery**

Relion 48V 300 AH Lithium = 15.3 kWh

Recommended Charge Current (> 0C) 100 ADC

Max Charge Current (-10 – 0C) 30 ADC

Max Charge Current (-20 -  -10C) 15 ADC

Keep battery in insulated box year round to ensure above 0C (BMS Disconnect -20C and 65C)

Manually recharge by starting generator when reaches 20% SOC or 50 V to preserve battery life.

**Setup**

[01A] Set Clock

[01D] Max Charge Amps: CC/CV (set from 03C)

[01E] Link PT Charge Settings: YES

[02A] Search Watts: OFF

[02B] LBCO (Low Battery Cut Out): 48 V (as fridge and washer only hard start loads)

[02F] Power up Always: ON

[03C] Battery Type: CC/CV (Constant Charge then Constant Voltage)

            **Set Max Charge Amps: 60 ADC* (maximum charge during CC phase)**

            Set CV Charge Volts: 56 VDC (maximum voltage during CV phase)

            Set CV Charge Done Amps: 15 ADC (0.05C)

            Set Max CC/CV Time: 12.0 Hrs

            Set Recharge Volts: 48.0

[03E] Max Charge Rate: 30-60% (percent of inverter max of 60 ADC = 30 ADC to not overload generator – pump and fridge off)

[06C] Max Charge Rate: 100% (percent of inverter max of 60 ADC)

[06D] Max Charge Time: 16.0 Hrs

*If can’t guarantee > 0C in battery bay set 03C Set Max Charge Amps to 30 ADC (otherwise 60 ADC)

**Questions**

03C Does max charge amps override 03E and 06C separately and combined?

03C Does amps drop to 15 ADC once reaches 56 VDC?

03C Set Max CC/CV Time < 12 Hrs??

If going away battery should be stored at 50% SOC.