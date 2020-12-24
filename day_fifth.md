# Charging Problem
#### *Mobile phone not charge/mobile charge but not % increase(fake charging)*
## Solution
> 1. Check battery voltage(3.7~4.4v is OK)
> 1. Check battery pins for short/half short(leakage)
>     - Fix red probe at GND check battery "+" pin with black probe.
>     - If "+" pin shows:
>       - 250~750 reading means OK.
>       - less than 200 reading means half short(fake charging).
>       - beep means full short.
>       - no value means open(no any connections with board).
>       - *If battery connector reading is faulty replace it first.*
> 1. Check mobile phone charger( If reading is 5v in multimeter 20v DC means OK) or check in othe mobile.
> 1. Connect charger to mobile and and check 3.7~4.4v in +/- pin of battery connector:
>     - If less than 3.7v charging IC problem.
>     - If 3.7~4.4v battery problem.
>     - If 0v charger conector/ Components/IC problem.
