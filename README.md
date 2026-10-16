# Machine Learning EVB Initial Binary Code

Welcome to the Machine Learning Evaluation Board (EVB) Initial Binary Code repository. 

This repository contains the pre-compiled binary files (`.bin` or `.hex`) for various Nuvoton Machine Learning Evaluation Boards. These initial binaries are provided to help users quickly restore their boards to the factory default state or test basic ML functionalities right out of the box.

## 📂 Directory Structure

The repository is organized into folders based on the specific Evaluation Board model. Inside each folder, you will find the corresponding binary codes.

*   📁 **`NuMaker-X-M55M1D/`**
    *   Contains the initial binary code for the NuMaker-X-M55M1D board.
*   📁 **`NuMaker-GestureAI-M55M1/`**
    *   Contains the initial binary code for the NuMaker-GestureAI-M55M1 board.
*   📁 **`NuMaker-VoiceAI-M55M1/`**
    *   Contains the initial binary code for the NuMaker-VoiceAI-M55M1 board.

##  How to Use (Flashing the Code)

You can upload these binary files to your development board using the Nuvoton ICP (In-Circuit Programming) Programming Tool.

### Prerequisites
1. Download and install the latest [Nuvoton ICP Programming Tool](https://www.nuvoton.com/tool-and-software/software-development-tool/programmer/).
2. Connect your NuMaker board to your PC via a USB cable (ensure it is connected to the Nu-Link interface).

### Flashing Steps
1. Open the **Nuvoton ICP Programming Tool**.
2. Select the target chip series (e.g., M55M1 series) and connect to the chip.
3. In the Load File section, load the desired binary file from the respective folder in this repository:
   * **APROM**: Select the provided binary file.
4. Check the programming options (ensure APROM is selected to be programmed).
5. Click **Start** to begin flashing the binary code onto your EVB.
6. Once the programming is complete, reset the board to run the initial ML application.

## 📝 Notes
* Please ensure you are flashing the correct binary for your specific board model to avoid unexpected behavior.
* For more detailed information on the machine learning models and source code, please refer to the official Nuvoton documentation or BSP (Board Support Package).