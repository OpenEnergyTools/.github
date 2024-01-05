# OpenEnergyTools

## Vision

Welcome to the OpenEnergyTools organization. This organization is aiming to host open-source software covering protection automation and control application in electrical energy systems.

> NOTE: Most of the projects are not yet started. We are working in the SCL editor as a basis for system configuration at the moment.

## Protection functions (not started)

### Protection (not started)

- Overcurrent protection (50/51)
- Directional overcurrent protection (67)
- Frequency protection (81)
- Undervoltage protection (27)
- Distance protection (21) incl. teleprotections schemes
- Differential protection
- etc.

## Test bench for protection functions acc. to 60255-1xx (not started)

### Control

- Circuit breaker control function (IEC 61850-8-1)
- Switch control functions
- Tapchanger control functions
- etc.

## Configuration tools (work in progress)

### IEC 61850 based tools (work in progress)

#### System Configuration ([SCLEditor](https://openenergytools.github.io/scl-editor)) acc. to IEC 61850-6

- Specification:
  - Creating logical node typical
  - Specify functions
  - Specify applications
- Tendering:
  - Create virtual IEDs
  - Various diffing functionality
- System specification:
  - Draw single line diagram
  - Work with bay templates
  - Link functions and application to the substation structure
- System configuration:
  - Configuration automation based on logic diagrams
  - Import/export of SCL files
  - Communication mappings
  - Update functionality based on solid diffing
- HMI configuration based on the IEC 61850-6-2
- IEC 61850-90-30 to configure the communication between functions/applications

#### IED configuration (not started)

- provide plugins to push configuration on protection automation and control function described in later sections.

### HMI configuration acc. to IEC 61850-6-2 (not started)

### vPac configuration acc. ???? (not started)
