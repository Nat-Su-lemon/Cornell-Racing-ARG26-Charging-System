# Cornell-Racing-ARG26-Charging-System
<!-- Row 1: same visual height -->
<p align="center">
  <a href="https://github.com/Nat-Su-lemon/Cornell-Racing-ARG26-Charging-System/blob/main/assets/charger_full_cad.png">
    <img
      src="https://raw.githubusercontent.com/Nat-Su-lemon/Cornell-Racing-ARG26-Charging-System/main/assets/charger_full_cad.png"
      alt="Charger Full CAD"
      height="300"
    />
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://github.com/Nat-Su-lemon/Cornell-Racing-ARG26-Charging-System/blob/main/assets/lv_enclosure.png">
    <img
      src="https://raw.githubusercontent.com/Nat-Su-lemon/Cornell-Racing-ARG26-Charging-System/main/assets/lv_enclosure.png"
      alt="Low Voltage Enclosure"
      height="300"
    />
  </a>
</p>

<!-- Bottom image unchanged -->
<p align="center">
  <a href="https://github.com/Nat-Su-lemon/Cornell-Racing-ARG26-Charging-System/blob/main/assets/charger_ss_pcb.png">
    <img
      src="https://raw.githubusercontent.com/Nat-Su-lemon/Cornell-Racing-ARG26-Charging-System/main/assets/charger_ss_pcb.png"
      alt="Charger Subsystem PCB"
      width="600"
    />
  </a>
</p>

## Overview
  The charger, or charging system, is the electromechanical assembly responsible for charging the accumulator. It accepts AC power from an EV supply equipment using the J1772 interface and converts it to DC through the Elcon charger before delivering power to the accumulator. More broadly, the charging system functions as a simplified, external counterpart to the vehicle powertrain.
  The system incorporates many of the same subsystems found on the car’s powertrain, including high-voltage distribution, low-voltage control, shutdown circuitry, and safety interlocks, while excluding firmware-specific components. Because high voltage is present throughout the charging system, it contains several safety-critical elements. The shutdown circuit in particular must be present and fully functional to ensure safe operation.
  The primary goals for ARG26 include efficient mechanical packaging and harness routing, a reliable and robust electrical system, secure mounting to the charging cart during competition use, and comprehensive documentation detailing the design and operation of the charging system.

> ## 📄 Full Technical Report
> This GitHub repo only serves as the project documentation landing page. For more details regarding the technical and design aspects of this system, please refer to the [Google Docs technical report](https://docs.google.com/document/d/1nDSdyh8C3EoCIEV3Xa5Q3-b9oIaXxnFPz5djCGfBuzo/edit?tab=t.0).




