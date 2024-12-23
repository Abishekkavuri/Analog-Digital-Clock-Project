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
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project folder:
   ```bash
   cd your-repo-name
   ```
3. Open `index.html` in your browser to view the clock.

---

## Preview

### Clock Overview

![Clock Overview](./images/Screenshot%202024-12-23%20131946.png)
*Figure 1: Clock displaying the current time.*

### Stacked Numbers

![Stacked Numbers](./images/Screenshot%202024-12-23%20132003.png)
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

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For any questions or suggestions, feel free to reach out:

- **Email**: [your-email@example.com](mailto:your-email@example.com)
- **GitHub**: [your-username](https://github.com/your-username)

