---
layout: post
title:  "The Pressure Instruments"
date:   2017-11-20 21:37:00
categories: nz-ppl
---

# The Flight Instruments

Instruments in the cockpit/flight deck fall into three groups: flight instruments,
engine instruments, and support services instruments.

Flight instruments fall into two categories:

 * Those which use **variations in air pressure**.
 * Those using the **properties of gyroscopic inertia**.

This section covers the former.

# Air pressure

The pressure instruments: **airspeed indicator (ASI), altimeter, vertical speed
indicator (VSI).** Each converts air pressure into a measurement, which can be
*dynamic pressure* or *static pressure*.

**Static Pressure**

 * At any point in the atmosphere, air exerts pressure in equally in all directions,
   called *static pressure*. This results from the **weight of air molecules above
   that point pressing down.**
 * Number of molecules above a point decreases with altitude (ie. as you go higher),
   therefore static pressure decreases with altitude.
 * Static pressure is sensed through a **static vent**.

**Dynamic Pressure**

 * Pressure on any solid body with resulting from its movement through the air is
   *dynamic pressure*.
 * Can either be caused by air flowing past a stationary body (eg. a tree being
   blown over), or the body moving through air (eg. hand out a car window).
 * Dynamic pressure depends on two factors:
    1. **Velocity of the body** relative to the air. eg. faster the car goes, stronger
       the dynamic pressure.
    2. **Density of the air**. In outer space, there would be no dynamic pressure
       regardless of how fast you travelled, because there are practically no
       molecules to impact you. At sea level, the opposite is true. At altitude you
       would feel *some* dynamic pressure, between the other two levels.

**Total Pressure**

Static pressure + dynamic pressure. **Also known as pitot pressure**.

# Pitot-Static System

 * Only instrument to use dynamic and static pressure.
 * Measures total pressure, and compares to the difference provided by static
   pressure from the static vent.
 * There are two common arrangements:
    1. A *combined* pitot-static head.
    2. A *pitot tube* and a separate *static vent*.
 * Must be placed where the **airflow is not greatly disturbed**, often forward of
   or beneath the outer section of one wing.
 * Some aircraft have two static vents, one on each side. This enables the static
   pressure reading to be evened out, especially when slipping or skidding. Static
   vents are usually placed where wind tunnel experiments have shown static pressure
   to be least affected by the airflow.
 * Provision is usually made for water collecting in the tubes (rain/condensation)
   to drain through *drain holes*.
 * Pitot heads often also fitted with an electric heating element to prevent or
   melt airframe icing.
 * Often an *alternate static source* in the cabin in case of the ports becoming
   blocked. **Cabin pressure is usually less (in an unpressurised aircraft) than
   outside, causing a slight instrument error.**

# Airspeed Indicator

 * Provides **indicated airspeed (IAS).** Measures dynamic pressure and gives a
   reading in knots. Dynamic pressure = total pressure - static pressure.
 * Consists of a diaphragm connected to the total pressure, surrounded by a
   chamber filled with static pressure. The difference is mechanically linked
   to be displayed on the ASI.
 * When no air flows, ambient pressure on both sides of the diaphragm is the same
   and the difference is zero, indicated on the ASI.
 * As airspeed increases, dynamic pressure increases but static pressure remains
   the same, the difference is greater than 0 and indicated on the ASI as knots.

**Colour Coding on the ASI**

 * **Green Arc** - normal-operating speed range. From V<sub>s1</sub> (flaps up,
   wings level) to V<sub>no</sub> (normal operating speed limit, or maximum
   structural cruising speed), which should not be exceeded except in smooth air.
 * **Yellow Arc** - caution range. From V<sub>no</sub> to V<sub>ne</sub> (never
   exceed speed). Should only operate in this range in smooth air.
 * **White arc** - flaps operating range. Stall speed at max gross weight in the
   landing configuration (V<sub>s0</sub> - full flaps, gear down, wings level,
   power off) up to V<sub>fe</sub>, maximum flaps-extended speed.
 * **Red radial line** - V<sub>ne</sub> - never exceed speed.

NB. All airspeeds refer to **IAS**, not TAS.

**IAS/TAS Relationship**

 * True Airspeed (TAS) is the *actual* speed of the aircraft through the air. This
   is rarely indicated on the ASI.
 * The ASI is designed to measure dynamic pressure **at one density**, the
   International Standard Atmosphere (ISA) Mean Sea Level (MSL) density.
 * As the aircraft climbs, air density decreases below the ISA MSL figure, and the
   speed indicated by the ASI will progressively be **reduced below its actual
   speed through the air.**

**If an aircraft climbs at a *constant IAS*, its *TAS* must increase to make up
for the less dense air being measured.

 * Fly the aeroplane by IAS - stall speeds, landing speeds, etc. are all IAS.
 * Use TAS for cross country planning, and manoeuvring at higher altitudes.
 * Also be aware that when **ambient air density varies significantly from ISA**
   (eg. very hot air), IAS and TAS may be significantly different, and have a
   big impact on takeoff and landing performance.

**Groundspeed (GS)**

 * Speed of the aircraft over the ground. Takes into account the speed of the air
   mass we're flying through, ie. the wind velocity (WV).
 * eg. If an aircraft is flying at 120kts at 5,000', let's assume it's flying at a
   TAS of 130kts. If there is no wind, then its GS is also 130kts.
    * However, if there's a WV, the GS of the aircraft will be *different* to its
      TAS, depending on the direction of the wind and the aircraft.
    * eg. a westerly at 30 knots, and the aircraft is headed directly into the
      wind. In this case its TAS is 100kts (TAS - WV). If turned 180 degrees, its
      GS will be 160kts (130TAS + 30WV). At intermediate headings, its speed will
      vary between 100kts and 160kts.

# Airspeeds Summary

 * IAS is the 'aerodynamic' airspeed of the aircraft, indicated on the ASI. At low
   altitudes, usually close to TAS.
 * TAS is the *actual speed* of the aircraft through the air. Calculated by applying
   correction for *air density* to IAS.
 * GS is actual speed over the ground. Calculated by applying wind velocity (WV) to
   the aircraft heading and TAS.

# Errors in the ASI

 * **Density Error** - inability of the ASI to account for variations in air
   density, ie. to give a TAS as discussed above. Some ASIs have a small rotatable
   scale which provides a compensation for density error, giving TAS as well as IAS.
 * **Position Error** - accuracy of how well the ASI 'reads' indicated airspeed
   depends on how accurately the pitot tube and static vent(s) are able to sense
   total and static pressure. 
    * If being flown at a nose-high attitude, or a slip/side, these vents could be
      at an unusual attitude to the oncoming airflow, and may register different
      pressures than actual.
    * **Any position error arising from a high nose attitude is allowed for in the
      calibration of V<sub>s0</sub> and V<sub>s1</sub>.**
    * **Position Error Corrections (PECs)** can be found in the POH, and sometimes
      in the cockpit, and can be used to calculate the **Calibrated Airspeed (CAS)**.
 * **Instrument Error** - some variations due to instrument wear and age, minor
   differences in manufacture, and application of the ASI to particular aircraft.
   Can usually be disregarded in practice.
