# Module README Template

This `README.md` should be placed inside each module folder (e.g., `Sensors/<Type>/<ModuleName>/`).
It documents the changelog, ordering specifications, and module details for that specific PCB.

---

# Module: `<Module Name>`

## 🏷️ Project Status

Choose **one** badge to indicate the current status of the module:

![Status](https://img.shields.io/badge/Status-Development-orange)
![Status](https://img.shields.io/badge/Status-Ordered-blue)
![Status](https://img.shields.io/badge/Status-Ready_for_Testing-yellow)
![Status](https://img.shields.io/badge/Status-Deployed-brightgreen)

*(Keep only the relevant badge active in the README. Remove the rest.)*

## 📜 Changelog

| Name  | Date       | Version | Updates                                                 |
| ----- | ---------- | ------- | ------------------------------------------------------- |
| Alice | 01/03/2025 | 1.0     | Initial schematic and layout setup                      |
| Bob   | 15/03/2025 | 1.1     | Updated footprint of sensor, adjusted routing           |
| Carol | 25/03/2025 | 1.1.1   | Fixed silkscreen text overlap, added missing test point |

*(Add rows for each update. Follow semantic versioning: Major.Minor.Patch)*

---

## ⚙️ Ordering Specifications

* **Board thickness**: \<e.g., 0.8 mm>
* **Impedance match**: \<Yes/No, Impedance ohm>
* **Impedance Calculated on** \<e.g., JLC04081H-3313>
* **Base material**: \<e.g., FR4>
* **Color**: \<e.g., Green>
* **Outer copper weight**: \<e.g., 1 oz>
* **Gold fingers**: \<Yes/No, Finish type>
* **Castellated holes**: <Yes/No>
* **Edge plating**: \<Yes/No>
* **Assembly side**: \<Top/Bottom/Both>

---

## 🧩 Module Details

* **Sensor description**: <Short functional description>
* **Used voltage**: \<e.g., 3.3V, Battery, 5V>
* **Used interface**: \<e.g., I2C, SPI, ADC>
* **Active power consumption**: \<Value + unit>
* **Max power consumption**: \<Value + unit>
* **Off mode power consumption**: \<Value + unit>

### Pin definitions

* `<Pin name>` → `<Function>`
* `<Pin name>` → `<Function>`


### Other information

* \<Addresses, special notes, mechanical details, etc.>

---

## 📂 Production References

* See related files in `production/Order_<date>`.

---

### Usage Notes

* Keep this file updated with every version change.
* Ensure production orders reference the correct version noted here.
* Use semantic versioning for updates (Major.Minor.Patch).


