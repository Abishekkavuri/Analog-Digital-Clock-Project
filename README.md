# Analog-Digital Clock Project

This project implements a dynamic clock using HTML, CSS, and JavaScript. The clock represents the hours, minutes, and seconds with stacked numbers, where:

- **Hours** are represented with 3 stacked numbers.
- **Minutes** are represented with 5 stacked numbers.
- **Seconds** are represented with 7 stacked numbers.

The clock runs smoothly and rotates continuously without reversing or resetting after 60 seconds.

---

## Features

- **Dynamic Clock**: Updates in real time to display the current hours, minutes, and seconds.
- **Stacked Numbers**: The numbers representing time are stacked vertically for each hand.
- **Continuous Rotation**: The second hand rotates clockwise without resetting after 60 seconds.
- **3D Design**: Stylish, 3D-like circular clock with attractive visuals.
- **Fully Responsive**: Fits any screen size.

---

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/Abishekkavuri/Analog-Digital-Clock-Project.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Analog-Digital-Clock-Project
   ```
3. Open `index.html` in your browser to view the clock.

---

## Preview

### Clock Overview

![Screenshot 2024-12-23 131946](https://github.com/user-attachments/assets/60aac37d-f296-44e1-b5e2-4da98b416af5)

*Figure 1: Clock displaying the current time.*

### Stacked Numbers

![Screenshot 2024-12-23 132003](https://github.com/user-attachments/assets/4b390d4e-19b4-40d9-8589-f295b9ce8d1e)

*Figure 2: Close-up of the stacked numbers.*

---

## How It Works

1. The clock fetches the current time using JavaScript's `Date` object.
2. Each pointer (hours, minutes, and seconds) rotates based on the calculated angle:
   - **Hour Hand**: Moves 30 degrees per hour.
   - **Minute Hand**: Moves 6 degrees per minute.
   - **Second Hand**: Moves 6 degrees per second.
3. Stacked numbers are dynamically updated based on the current time.
4. The second hand continues to rotate clockwise seamlessly without resetting.

---

## Technologies Used

- **HTML**: Structure of the clock.
- **CSS**: Styling and positioning.
- **JavaScript**: Logic for time updates and rotation.

---

## Contributing

Contributions are welcome! If you’d like to improve this project, please:

1. Fork the repository.
2. Make your changes.
3. Submit a pull request with a detailed explanation of your changes.

---


## Contact

For any questions or suggestions, feel free to reach out:

- **Email**: [mailtoabisheka@gmail.com](mailto:mailtoabisheka@gmail.com)
- **GitHub**: [Abisheka kavuri](https://github.com/Abishekkavuri?tab=repositories)

