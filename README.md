# Insurance Rate Kata
## Problem Description
Calculate the monthly insurance rate for a driver. A base rate is determined by the number of years the insured has been driving. Then all applicable discounts are summed, and then applied to the base rate. Finally the fee for the number of tickets the insured has been issued in the last 5 years is applied. 

### Base annual rate is determined by the number of years the insured has been driving.
*	Less than 3 years = $1700.00
*	3-5 years = $1500.00
*	6-10 years = $1200.00
*	11-15 years = $1000.00
*	More than 15 years = $750.00

### Discount rate is determined by the number of years the insured has been a member.
*	Silver is >3 years and gets a 3% discount. 
*	Gold is 4 to 8 years and gets a 6% discount.
*	Platinum is 9 to 15 years and gets a 9% discount.
*	Diamond is > 15 years and gets a 13% discount.

### One additional member discount is available if the insured belongs to any of the following groups. If the insured belongs to more than one group, only the largest discount will be applied.
*	Military veteran or active duty can receive 20%
*	College student can receive 8%
*	Software Engineers can receive 12%
*	Police, Fireman, and EMS can receive 5%
*	Teachers can receive 7%

### Ticket fees are calculated by multiplying the number of tickets issued in the last 5 years by $50.00
