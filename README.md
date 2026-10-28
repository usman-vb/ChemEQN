# ChemEQN ⚗️

ChemEQN is your intuitive chemical equation software! Enter reactions using common chemical names or molecular formulas, and let the software balance, analyze, and export them instantly. Featuring dual output modes (balanced text equations & industry-standard .RXN files), comprehensive stoichiometry calculations (limiting reactant, excess leftovers, theoretical yields), charge analysis for ionic equations, and an extensive offline chemical registry, it outshines others with seamless integration into professional tools like BIOVIA Draw and ACD ChemSketch. A fast, beautiful, and portable chemistry app designed for researchers, chemists, and students!

## 🆕 Current Version
- **Version:** 1.48 (First Official Stable Release)
- **Build Date:** October 26, 2026
- **Platform:** Windows 64-bit (Standalone Executable)

## ✨ Features

### ⚖️ Dual Output Modes (Text & .RXN File Generation)
- Generate standard balanced molecular formula text or export the reaction as an industry-standard MDL .RXN file.
- The generated .RXN files can be seamlessly opened, visualized, and edited in professional chemical drawing software like BIOVIA Draw and ACD ChemSketch.

### 🧮 Advanced Equation Balancing & Stoichiometry
- Powered by the ChemPy library for accurate balancing of complex chemical equations.
- Intelligently handles physical states (g, l, s, aq), predefined coefficients, and various reaction arrows (→, ⇌).

### ⭐ Molar Mass & Limiting Reactant Calculator
- Automatic molar mass breakdown table for all reactants and products (Compound | Molar Mass (g/mol) | Stoich. Coeff.) with total combined mass.
- Input reactant masses (in grams) to instantly identify the Limiting Reactant, calculate Excess Reactants Left Over, and compute Theoretical Yields of all products in both grams and moles.

### ⚡ Charge Analysis & Ionic Equation Support
- The built-in Charge Analysis tool automatically calculates and displays the net charge for each reactant and product species (e.g., [S₂O₃]²⁻: -2).
- Ensures strict charge conservation in complex ionic and redox equations.

### 📚 Smart Chemical Registry & Name-to-Formula Conversion
- Extensive, pre-cached offline chemical registry covering elements, diatomic molecules, inorganic salts, polyatomic ions, and organic compounds.
- Type common names (e.g., "benzene", "nitric acid", "water") or aliases for instant conversion into accurate molecular formulas and SMILES strings.

### 🎨 Interactive 2D Structure Visualization
- When exporting to .RXN mode, RDKit generates and renders 2D molecular structures directly on the result canvas.
- Visually verify the structural integrity of reactants and products before exporting.

### 🗂️ Reaction History Management & Auto-Save
- Robust History panel with live entry count: edit, remove, move up, and move down past equations.
- Auto-Save function periodically saves your current work as a `.ceqn` file, alongside JSON-based persistent history storage for quick retrieval.

### ⌨️ Comprehensive Menu System & Keyboard Shortcuts
- Fully integrated menu bar (File, Edit, Insert, Action, Help).
- Action menu shortcuts: Execute (F1), Toggle Output Mode (F2), Toggle Balance Equation (Ctrl+Shift+B), Toggle Auto-Subscript (F3), Toggle Superscript (F4), Toggle Auto-Save (Alt+S), Toggle History (Ctrl+Shift+H), and Search Google (F5).
- Insert menu offers 7 predefined reaction templates (Ctrl+Shift+1 to Ctrl+Shift+7): Nitration of Benzene, Haber–Bosch Process, Calcination Process, Neutralization Reaction, Redox Reaction, Cyanide Detoxification Reaction, and Arsenate-Iodide Redox Reaction.

### 🔤 Unicode Subscript & Superscript Auto-Formatting
- The Auto-Subscript and Superscript toggles dynamically convert standard numbers and charges into proper Unicode chemical notation (e.g., H₂O, [S₂O₃]²) as you type or upon final execution.

## 🖥 Screenshots
(Screenshots are stored in the `/Screenshots` folder.)

### 1. Main Interface (Text Mode)
(https://github.com/usman-vb/ChemEQN/blob/main/Screenshots/ChemEQN_Text_Mode.png)
The clean interface with the Output Target Mode selector, equation input box, quick-insert symbol buttons (+, →, ⇌), and the balanced result with a detailed molar mass breakdown table.

### 2. Charge Analysis for Ionic Equations
(https://github.com/usman-vb/ChemEQN/blob/main/Screenshots/ChemEQN_Charge_Analysis.png)
Automatic charge conservation report for complex ionic equations such as [S₂O₃]²⁻ + [CN]⁻ → [SCN]⁻ + [SO₃]²⁻.

### 3. Molecular Structure (.RXN) Mode
(https://github.com/usman-vb/ChemEQN/blob/main/Screenshots/ChemEQN_RXN_Mode.png)
2D molecular structures of reactants and products rendered directly on the result canvas using RDKit.

### 4. External Software Integration
(https://github.com/usman-vb/ChemEQN/blob/main/Screenshots/ChemEQN_BIOVIA_Draw.png)
(https://github.com/usman-vb/ChemEQN/blob/main/Screenshots/ChemEQN_ChemSketch.png)
Exported .RXN files opened seamlessly in BIOVIA Draw 2025 and ACD ChemSketch (Freeware) for further editing and visualization.

### 5. Limiting Reactant & Theoretical Yield Analysis
(https://github.com/usman-vb/ChemEQN/blob/main/Screenshots/ChemEQN_Limiting_Reactant.png)
Stoichiometry analytics in action: limiting reactant identification, excess reactant leftovers, and theoretical product yields calculated from user-input reactant masses.

### 6. Menu System & Keyboard Shortcuts
(https://github.com/usman-vb/ChemEQN/blob/main/Screenshots/ChemEQN_Menu_Action.png)
(https://github.com/usman-vb/ChemEQN/blob/main/Screenshots/ChemEQN_Menu_Insert.png)
The Action and Insert menus displaying dedicated keyboard shortcuts and predefined reaction examples for rapid data entry.

### 7. About the Software & Author
(https://github.com/usman-vb/ChemEQN/blob/main/Screenshots/ChemEQN_About.png)
Version info, build details, external libraries used, and direct links to the developer's website and GitHub repository.

## ⚙️ System Requirements
- **Operating System:** Windows 10 or Windows 11 (64-bit)
- **Dependencies:** None. The software is fully self-contained. No Python installation or external libraries required!

## 📦 External Libraries Used (Bundled)
- rdKit
- Pillow
- ChemPy
- Numpy
- PySide6

## 🚀 How to Download and Run
ChemEQN is distributed as a portable, standalone Windows executable. No installation wizard is needed.
1. Navigate to the [Releases](https://github.com/usman-vb/ChemEQN/releases) section on the right-hand sidebar of this GitHub repository.
2. Download the latest ZIP archive (e.g., `ChemEQN-1.48.zip`).
3. Extract the contents of the ZIP file to any folder on your computer (e.g., `C:\ChemEQN-1.48` or your Desktop).
4. Double-click `ChemEQN.exe` to launch the application.
5. (Optional) Right-click the `.exe` file, select Send to > Desktop (create shortcut) for easy future access.

### ⚠️ Windows SmartScreen Notice:
Because this software is independently compiled and not signed with an expensive enterprise digital certificate, Windows Defender SmartScreen might flag it upon the first run. If this happens, simply click "More info" and then "Run anyway" to start the program safely.

## 👨‍ Developer
**Usman Afzal**
- 🌐 Website: [https://www.usmanafzal.pk](https://www.usmanafzal.pk)
- 🐙 GitHub: [https://github.com/usman-vb](https://github.com/usman-vb)

## 🔮 Planned Enhancements
- Net ionic equation derivation with automatic spectator ion removal.
- Batch equation balancing from text files with progress tracking.
- Export stoichiometry and molar mass analysis reports as professional PDF files.
- Online PubChem retrieval to extend the offline chemical registry.
- Dark mode UI theme.

## ⚠️ Disclaimer
This software is provided as freeware. It may contain bugs. Use it at your own risk, as its stability and functionality are not guaranteed for critical clinical or industrial applications without independent validation.

© 2026 ChemEQN. All Rights Reserved.