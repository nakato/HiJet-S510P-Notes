# Battery

The OEM battery is a Flooded Lead Acid battery.  It conforms to JIS M42.


## Maintenance

As a flooded lead acid battery, this is a maintenance item.  If unsure how to
maintain a flooded battery consult proper flooded lead acid battery maintenance
documentation or ask your local auto-parts store or mechanic.

If plates are exposed above water level, special care will need to be taken.

Shaking the vehicle may help find the water level if it is difficult to see.

OEM battery high and low levels should be visible without removing cover, but
confirming this by removing the cover the first time is a good idea.


## M42

The battery is an `M42`, this is a JIS format number used for Idle-Stop batteries.

It is similar to non-Idle-Stop battery xxB20L.  Manufactures appear to say
M42 can be used where a 60B20L would normally be used.  I do not know if
using a 60B20L in place of a M42 is advisiable.


### Technical Information

The following is sourced from the specs of various M42 batteries found for
sale. I do not know what the M42 spec specifies as a requirement, and the
specs from various manufactures may be exceeding the standard.

|   Sample |        CCA | Capacity |
| -------- | ---------- | -------- |
| A        | 400A       | 40Ah     |
| B        | ?          | 38Ah     |
| C [Note] | 500A (18c) | 40Ah     |
| D        | 400A       | 40Ah     |
| E        | 400A       | 40Ah     |

Note: Sample *C* with a 18c CCA rating is clearly a sub-standard product, because
that's not how CCA is measured, and I'm guessing this being used to hide an
inferior product.


### Lithium replacement

If the above numbers refer to complete capacity and not usable capacity, then
between 30-50% of the above is the usable capacity, which may mean there are
lithium car batteries that may be used in place of the flooded lead acid.

I do not know if switching to a LiFePO4 would work well with Idle-Stop as I
assume the ECU is monitoring battery voltage to determine if the battery is
prepared to run all the accessories and re-start the car before shutting the
engine off.


### Warranty

These batteries seem most commonly warrantied for 2 years.  Some manufactures
offer 3 years if the battery is used in a vehicle that does not have the
Idle-Stop feature.


## References

[Battery Decoding](https://www.daihatsu.co.jp/accessory/mokuteki/mordal_battery.htm)
