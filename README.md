# EASEPAPR

## Low-cost open-source powered air purifying respirator

## Easy, Accessible, open-Sourced, Efficient

```
Last Updated: May 28, 2020
```
**Team Members**
* Abebe Amare
* Achilles Dabrowski
* Alex Xu
* Franklin Boampong
* Samarth Lamba

![Overview](/figures/paproverview.png)

**Document License:**
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International

**Legal and Safety Disclaimer:**
Designs presented in this document have not been approved as a medical or protective device
by NIOSH, OSHA, the CDC, the FDA, or other regulatory agencies, nor have they received
Coronavirus Disease 2019 (COVID-19) Emergency Use Authorizations for Medical Devices.
Caution should be used when evaluating, constructing, and utilizing a device described by the
designs (or their derivatives) shown. Individuals are cautioned to construct this device and use
it at their own risk. We will keep our regulatory approval updated once it is approved by the
Emergency Use Authorizations for Medical Devices.

## Summary

In response to the worldwide COVID-19 pandemic, we present a low-cost, open-source Powered
Air Purifying Respirator (PAPR) device that may be used as personal protective equipment (PPE)
in the event that other forms of conventional PPE are unavailable. This PAPR alternative may be
constructed largely using off-the-shelf components and used to provide breathing protection to
a higher degree than improvised face masks. Our design focuses on the powered filtration unit
(blower) component of a full PAPR system. As the COVID-19 pandemic worsens and spreads to
less developed areas, we believe that there will be an even greater need for low-cost PPE
solutions for medical professionals and caretakers. Future work for this project includes
streamlining the design for prototyping, conducting laboratory filtration and CO​2​ testing, and
integrating the device with a PAPR hood system for full-system testing.

## Introduction

**Rationale**
Amid the 2019-2020 COVID-19 pandemic, there has been a severe shortage of personal
protective equipment (PPE) around the world for medical professionals. Particularly in the
United States, healthcare providers are running out of NIOSH-approved PPE to protect them in
the field when treating confirmed or presumed cases of COVID-19 or performing research
surrounding COVID-19 to prevent them from contracting the disease and spreading it to other
patients. Powered Air Purifying Respirators (PAPRs) are an alternative to the popular
industry-standard N95 masks and are regarded as one of the best PPE options for breathing
protection by the CDC (CDC, 2020). Unlike facemasks, PAPRs provide protection through the
provision of a continuous outward flow of filtered air to keep contaminating particles out.
Existing commercial PAPR solutions usually have a powered filtration unit that can be worn on a
belt or backpack.

One of the reasons why PAPRs are more effective than facemasks, as outlined by Grete
Porteous, M.D., is that ventilation mechanisms used in hospitals to care for patients can
produce virus-carrying aerosols that can be suspended in the air for a period of time, exposing
healthy individuals in treatment facilities to the virus (Porteous, Grete 2020). These aerosols
cannot be blocked by surgical masks. N95 masks are an alternative but they must be
uncomfortably fitted to the individual’s face and they are not easily duplicated through DIY
efforts due to difficulty in obtaining the N95 proper’s specialized fabric. Loose-fitting PAPR
hoods do not require fit testing and can be used with facial hair according to the CDC.

In addition, the cost associated with making them can significantly be decreased to suit the
temporary need for PAPRs while still protecting medical professionals. The cost of PAPRs used
by medical practitioners vary but “in one study, the cost for a PAPR was $768.20” and this is an


extraordinary amount especially in these tumultuous times where mass supply of PAPR is
required by medical practitioners (Church, Tyler J. 2019). Furthermore, filter media may be
difficult to find in the consumer marketplace.

**Proposal**
Our open-source PAPR design will fill the gap between the high demand for the PPE and the
available amount in the market. Our design uses inexpensive yet reliable materials that are
largely off-the-shelf or 3D-printed to construct a PAPR that is cheaper than N95 masks and
similar products but with the same functionality. Our design uses filters and fans that meet the
technical airflow and filtration requirements specified by CDC and NIOSH. In addition to being
cheaper, our device is similar to existing commercial solutions in size and portability. This
allows doctors to attach it to their waist while treating patients and to deliver the device in great
amounts worldwide.

As COVID-19 pandemic spreads around the world, there will be an even greater need for a
cheaper alternative to existing PPE solutions, especially in lesser developed areas where
protection is even more critical to public health due to less preventative care measures usually
taken in those locations in general.

Furthermore, individuals caring for sick individuals at home are advised by the CDC to optimize
the PPE including using scarves and bandanas. Our system can be replicated in one’s own
home, requires no advanced manufacturing techniques, and, most importantly, provides far
better protection. In addition, our system will be cost effective and can be easily integrated into
existing manufacturing capabilities at scale without impacting the already burdened medical
device/equipment supply chain.

## Components

**PAPR Overview:**

The key components of a PAPR are:

1. **Blower/Fan: ​** Generates the flow of air through the entire system. It pulls air through the
    filter and delivers air to the user.
2. **Filter Media:​** Blocks the passage of droplets and particles, especially those that may
    carry viruses, bacteria, and other airborne pathogens.
3. **Battery:​** The power source of the PAPR, used to operate the Blower/Fan.
4. **Tubing: ​** Connects the blower fan to the hood, and provides for the passage of air. The
    tubing should be sealed off with gaskets and connectors to prevent contamination.


5. **Hood:​** Covers the user’s head completely, either in a tight-fitting or loose-fitting variant.
    Loose-fitting variants are more versatile (does not require fit testing, and are more
    comfortable), but have higher airflow requirements.

**Our Focus**
Our design focuses on the Powered Filtration Unit of a PAPR system. This includes the
integration design of a blower/fan, filter media, battery, and an interface for tubing that
connects to a hood. Because our goal was affordability and accessibility, readily available
off-the-shelf subcomponents were selected and remaining components could be created via
any consumer or commercial-grade 3D printer or alternative manufacturing technique such as
injection molding.

**Requirements**
The key metric in evaluating protection provided is the filter used. It has been demonstrated that
household HEPA filters (MERV 16) can effectively filter out viruses. Furthermore, airflow must
be maintained to guarantee positive pressure into the system. According to NIOSH standards
(6), air flow should be​ **6 CFM​** continuously into the hood, which is loose-fitting. This can be
replicated by commercially available, off-the-shelf components, including those parts we have
selected from hardware provider DigiKey and RS; please see the itemized list in the following
section.

The fan selected for the device was the ​NMB Technologies Corporation BG0903-B047-00S-00​,
for its airflow and static pressure characteristics. It is rated to operate at 12V, up to 13.8V.

The air filter selected for the device was the ​Kenmore 53295 HEPA Vacuum Media Filter​. Any 4”
x 6” x 1” HEPA or medical grade filter will work interchangeably.

The battery selected for the device was the 12 volt ​M12 REDLITHIUM CP1.5 Battery Pack​. Any
battery pack that utilizes the M12 shape/interface will work interchangeably, including the
extended battery pack variant from Milwaukee Tool (Techtronic Industries). This particular M
model consists of three 18650 battery cells.

Our tube interface is designed to fit ​ **standard CPAP tubing​** with ​ **22mm​** connectors.


## Design

**Assembly**

![Figure 1](/figures/figure1.png)

#### Figure 1. Exploded View of PAPR Assembly, Front.

Items Shown in **Figure 1** :

1. Filter Holder Cartridge Lid
2. HEPA Filter Media (4” x 6”)
3. Filter Holder Cartridge
4. On/Off Toggle Switch
5. Main Enclosure
6. Battery Holder/Slot
7. Main Enclosure Back Plate/Lid
**Blue Circles​** highlight M3 x 0.5 screws


![Figure 2](/figures/figure2.png)
#### Figure 2.​ Exploded View of PAPR Assembly, Rear.

Items shown in **Figure 2** :

8. Blower Fan
9. Belt/Strap Attachment Loops
**Orange Circles** highlight M4 x 0.7 Screws
**Green Circles** highlight M5 x 0.8 Screws
* Wires required to connect battery, switch, and blower fan components are not shown.
Please see **Itemized Cost & Link** section for more information.


![Figure 3](/figures/figure3.png)
#### Figure 3. Assembled PAPR, Front.

![Figure 4](/figures/figure4.png)
#### **Figure 4.** Assembled PAPR, Rear. Note the 22mm CPAP tube connector on the right side of the device.


![Figure 5](/figures/figure5.png)
#### Figure 5. Close-up of Battery Holder attachment and wire holes.

![Figure 6](/figures/figure6.png)
#### Figure 6. Wiring diagram for battery, switch, and fan components.

**Process and Attribution:**

The overall assembly, main enclosure, main enclosure backplate, filter cartridge, and filter
cartridge lid are original designs. Items were modeled using Autodesk Fusion 360.

The filter media model is of original design, mimicking a 4” x 6” HEPA filter that is commonly
available off-the-shelf.

A battery housing was placed on the side of the fan housing and a hole was created on the
adjacent side of the fan housing to allow power and ground wires to run from the battery to the
fan **(Figure 5)**. This battery housing is adapted from AgentGene’s “Milwaukee M12 battery cap”
design under a Creative Commons BY-NC-ND 4.0 License.


The fan used in this design is the NMB Technologies Corporation BG0903-B047-00S-00. The
CAD model used is from the manufacturer and available for download here.

The toggle switch used in this design is the E-Switch 100SP1T1B4M2QE. The CAD model used
is from the manufacturer and available for download here.

**Differentiating Features:**

Our design focuses on two main aspects: cost and flexibility. By using off-the-shelf components
and 3D printable parts, the entire device’s cost totals approximately **$83.10;** see Itemized Cost
and Link for more information. Second, flexibility is achieved through the use of a modular
design. The filter cartridge holder can be swapped out for other designs to accommodate other
filter media types and shapes. For more information, see the Design Advice/Tips section. The
battery holder may also be swapped out to accommodate other battery shapes and connectors
as well, in a similar fashion. Finally, even though our air outlet design is modeled around a
22mm standard CPAP tube, adapters may be used to fit other sized tubing.

**Projected Airflow Performance**

![Figure 7](/figures/figure7.png)
#### Figure 7. Pressure-Airflow Characteristic curves for NMB BG0903 series blower fans. B047, theparticular model used in this PAPR design, is highlighted in red. Source: NMB.


## Assembly and Usage

An animation of the assembly process can be found here.

Please note that a PAPR hood and tubing are required as well before usage. In addition, this
device has **not** been air tested yet. It has not received any approval from a regulatory agency for
official PPE usage. Please construct and use **at your own risk**. Please see Legal and Safety
Disclaimer at the beginning of this document.

## Conclusion & Future Work

The design successfully incorporates all the main features needed for a PAPR design. The main
objectives for the design which include an easy to make, cost efficient and user-friendly device
were all met by the current design. These objectives were our priorities while designing the
device and future design iterations will also focus on them. Though this device is particularly
necessary during the COVID-19 pandemic, we envision the device making a breakthrough in the
medical field as it would significantly reduce the cost of Powered Air Purifying Respirators
(PAPRs), hence making PAPRs readily available for use in all hospitals. Looking past COVID-19,
this device would also be useful for medical researchers wanting to protect themselves from
any airborne diseases while performing research.

Future steps for this project include further prototyping and testing work as well as engaging the
open-source and medical communities for feedback to aid in iterative development. Any
individual or organization is free to use and build upon the work presented in this document
under a CC BY-NC-SA 4.0 License​.

## Design Advice / Tips

This section provides you with some tips on the modular aspects of this PAPR design, for you to
create your own designs and swappable components.

1. When deciding on the tubing to use with the 3D printed model, it is suggested you make
    use of tubing size adapters for larger or smaller tubing. Currently the device is designed
    to fit standard 22mm CPAP tubing. Please note that tube size has an effect on airflow
    pressure and volume.
2. Any PAPR hood should work with this design, given correct tubing adapters. However we
    recommend loose-fitting models over those that are tight-fitting. Makeshift hoods can
    also be used if they are flow-tested for CO​2​ concentrations internally.
3. The vertically positioned pegs used for attaching the battery holder are 4 mm in radius
    and 23.036 mm apart when measured from the center. They need to be at least long
    enough to be securely inserted into the main enclosure, which is about 10 mm in wall
    thickness.
4. The thread specifications between the main enclosure and the filter holder cartridge is
    2 5/16-16 UNS, under the ANSI standard.

## Itemized Cost & Links

The costs specified were obtained during time of device design and might change.

1. Blower Fan: NMB Technologies Corporation BG0903-B047-00S-00 - ($17.70)
2. Air filter: Kenmore 53295 HEPA Vacuum Media Filter - ($10.19)
3. Battery: M12 REDLITHIUM CP1.5 Battery Pack - ($49.00)
4. Switch: E-Switch 100SP1T1B4M2QE - ($1.99)
5. Screws and Fasteners:
    a. 2 x M5x0.8 (Fan Mount) - (~ $1.83)
    b. 4 x M4x0.7 (Back Lid) - (~ $1.65)
    c. 4 x M3x0.5 (Filter Holder Lid) - (~ $0.54)
6. Wiring: Recommended at least UL1007, AWG 26 spec Red (+) and Black (-) wire.
    (< $0.20)

Total cost (excluding 3D printing): **$83.**


## References

See EASEPAPR.pdf.
