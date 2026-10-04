# Component Calculator ⚡

A modern, native Android application built with **Jetpack Compose** that helps electronics enthusiasts, students, and engineers quickly calculate the values of resistors and capacitors based on their visual codes.

## Features ✨

*   **Resistor Calculator (4-Band):**
    *   Interactive, visual representation of a resistor.
    *   Select band colors from dropdowns (1st Digit, 2nd Digit, Multiplier, Tolerance).
    *   Real-time calculation with automatic unit formatting (Ω, kΩ, MΩ, GΩ).
*   **Capacitor Calculator (Ceramic):**
    *   Interactive, visual representation of a ceramic disc capacitor.
    *   Input standard 2-digit or 3-digit EIA codes (e.g., `104`, `473`).
    *   Supports optional tolerance letters (e.g., `104J`).
    *   Real-time calculation with automatic unit formatting (pF, nF, µF).
*   **Modern UI/UX:**
    *   Built entirely with Jetpack Compose (Material Design 3).
    *   Clean, minimalist design with easy-to-use tabs for switching modes.

## Screenshots 📱
<div align="center">
<img width="500" height="1200" alt="image" src="https://github.com/user-attachments/assets/e307e503-d19f-41a7-ab71-7528818fec80" />
<img width="500" height="1200" alt="image" src="https://github.com/user-attachments/assets/acd87e01-b31e-4322-96d7-41d5a6ce4506" />
</div>

## Tech Stack 🛠️

*   **Language:** [Kotlin](https://kotlinlang.org/)
*   **UI Framework:** [Jetpack Compose](https://developer.android.com/jetpack/compose)
*   **Architecture:** Material 3, AndroidX Navigation
*   **Build System:** Gradle (Kotlin DSL)

## How to Run Locally 🚀

1.  Clone this repository:
    ```bash
    git clone https://github.com/Ritam0609/ComponentCalculator.git
    ```
2.  Open the project in **Android Studio** (Koala or newer recommended).
3.  Allow Gradle to sync the project dependencies.
4.  Connect an Android device via USB/Wi-Fi or start an Android Virtual Device (Emulator).
5.  Click the green **Run** ▶️ button in the top toolbar.

## Contributing 🤝

Contributions, issues, and feature requests are welcome!
Feel free to check [issues page](https://github.com/Ritam0609/ComponentCalculator/issues) if you want to contribute.

Some ideas for future features:
- Support for 5-band and 6-band resistors.
- Support for SMD (Surface Mount Device) resistor codes.
- Support for electrolytic capacitor voltage codes.

## License 📝

This project is open-source and available under the [MIT License](LICENSE).
