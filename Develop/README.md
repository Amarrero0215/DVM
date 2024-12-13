# Vehicle Management CLI

A TypeScript-powered Command Line Interface (CLI) application that allows users to create and manage different types of vehicles (`Car`, `Truck`, and `Motorbike`). The CLI also includes unique features such as `towing` for trucks and performing a `wheelie` for motorbikes.

---

## Features

- **Create Vehicles:** Add cars, trucks, and motorbikes with user-defined properties.
- **Perform Actions:**
  - General: Start, stop, accelerate, decelerate, turn, and reverse.
  - Truck-specific: Tow another vehicle.
  - Motorbike-specific: Perform a wheelie.
- **Dynamic Management:** Manage multiple vehicles dynamically through the CLI.

---

## Installation

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Run the Application:**
   ```bash
   npm start
   ```

---

## Usage

### **Create a New Vehicle**
1. Select `Create a new vehicle` from the menu.
2. Choose a vehicle type (`Car`, `Truck`, or `Motorbike`).
3. Provide the required properties (e.g., color, make, model).

### **Perform Actions on a Vehicle**
1. Select `Select an existing vehicle` from the menu.
2. Choose a vehicle.
3. Perform actions such as:
   - General: Print details, start, stop, accelerate, decelerate, etc.
   - Truck-only: Tow another vehicle.
   - Motorbike-only: Perform a wheelie.

---

## Example Workflow

1. **Create a Car:**
   - Enter `Color: Red`, `Make: Toyota`, `Model: Corolla`, `Year: 2020`, `Weight: 1500`, `Top Speed: 120`.
   - The car is added to the system.

2. **Create a Truck:**
   - Enter `Color: Blue`, `Make: Ford`, `Model: F-150`, `Year: 2022`, `Weight: 3000`, `Top Speed: 100`, `Towing Capacity: 5000`.
   - The truck is added to the system.

3. **Create a Motorbike:**
   - Enter `Color: Black`, `Make: Harley Davidson`, `Model: Sportster`, `Year: 2021`, `Weight: 500`, `Top Speed: 125`.
   - The motorbike is added to the system.

4. **Tow a Vehicle:**
   - Select the truck, then choose the `Tow` action, and select a car to tow.

5. **Perform a Wheelie:**
   - Select a motorbike and choose the `Wheelie` action.

---

## Walkthrough Video

[![Walkthrough Video](https://img.youtube.com/vi/your_video_id/0.jpg)](https://www.youtube.com/watch?v=your_video_id)

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Future Enhancements

- Add more vehicle types.
- Implement persistence to save and load vehicle data.
- Integrate unit testing for key methods.

