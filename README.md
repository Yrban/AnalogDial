# AnalogDial
This is an analog dial with a needle.

This view gives is a customizable analog dial with indicator needle. You can set:
- maxValue: Double
- numberOfMarkers: Int
- maxCurvePercent: Double
- gradient: [Color]

Pass in your value from 0 to the maximum value. This view will not properly handle a negative value and will simply display 0.
