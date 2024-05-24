**INTRODUCTION**

The proliferation of embedded systems has enabled the development of innovative and practical applications in various fields. One such application is the emulation of an Automated Teller Machine (ATM) using microcontroller technology. This project aimed to create a functional ATM prototype using a Raspberry Pi Pico microcontroller. The system includes an RC522 RFID module for card scanning, an OLED display for user interaction, a servo motor for dispensing and receiving money, and a keyboard for navigation. The prototype allows users to check their account balance, deposit money, and withdraw money, mimicking the fundamental operations of a standard ATM.

**COMPONENTS**

The project leveraged several key components to achieve its functionality. The Raspberry Pi Pico served as the central processing unit, storing user account information and managing the overall system. An RC522 RFID module was used to read users' RFID cards, providing a secure and convenient method for user authentication. An OLED display was incorporated to guide users through various processes, displaying prompts and transaction details. A servo motor was employed to control the physical movement of money, simulating the dispensing and receiving mechanisms of a real ATM. Finally, a standard keyboard was used for user input, allowing navigation through the different ATM functions.

**DISCUSSION**

The project began with the configuration and programming of the Raspberry Pi Pico. The microcontroller was programmed using MicroPython, which facilitated the integration of various peripherals. User account information, including account balances, was stored in the Pico's memory. The RC522 RFID module was connected to the Pico and programmed to read card data, ensuring secure access to the ATM system.
The OLED display played a crucial role in user interaction, providing clear instructions and feedback during transactions. The display showed welcome messages, prompted users to enter their PINs, and displayed account balances and transaction confirmations. This ensured a user-friendly interface that mimicked the experience of using a real ATM.
The servo motor was configured to simulate the physical handling of money. When a withdrawal was approved, the servo motor activated to dispense a predetermined amount of money. Conversely, during a deposit, the motor accepted the money. This mechanical aspect added a tangible element to the prototype, enhancing the realism of the ATM emulation.
The keyboard allowed users to navigate through the ATM's functions. Users could enter their PIN, select transaction types, and input amounts for deposits and withdrawals. The combination of these components resulted in a cohesive system that accurately emulated the core functionalities of an ATM.

**CONCLUSION**

The project successfully demonstrated the feasibility of using a Raspberry Pi Pico and various peripherals to emulate an ATM. The integration of an RC522 RFID module for secure card scanning, an OLED display for user interaction, a servo motor for money handling, and a keyboard for navigation created a functional prototype. Users could authenticate themselves, check their account balances, deposit money, and withdraw money, replicating the essential operations of a standard ATM. This project highlights the potential of microcontroller-based systems in creating practical and interactive applications.

**RECOMMENDATIONS**

For future improvements, several enhancements could be considered. Adding encryption for stored user data and communication between components would enhance the system's security, making it more suitable for real-world applications. Integrating a more sophisticated user interface, perhaps with a touchscreen display, could further improve user interaction. Expanding the system to handle multiple currencies and denominations would increase its versatility. Finally, implementing network connectivity to update account information in real-time would align the prototype more closely with modern ATMs. These recommendations aim to extend the functionality and applicability of the ATM emulator, providing a more robust and secure solution.






