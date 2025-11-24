# Hotel Management System (Tkinter)

This project is a basic **Hotel Management System GUI** built using Python's `tkinter` library and the `Pillow` (`PIL`) library for image handling. It provides a main dashboard window with navigation buttons for managing customers, room booking, and room details.

---

## Features

- Graphical interface built with `tkinter`.
- Header banner and logo images loaded and resized with `Pillow`.
- Sidebar menu with buttons:
  - **CUSTOMER** – opens customer management window.
  - **ROOM** – opens room booking window.
  - **DETAILS** – opens room details window.
  - **LOGOUT** – closes the application.
- Main area background and additional decorative images.
- Each section (Customer, Room Booking, Details) opens in a new `Toplevel` window.

---

## Project Structure


> Adjust filenames and paths as needed for your environment.

---

## Requirements

- Python 3.x
- `tkinter` (usually bundled with standard Python installation)
- `Pillow` (PIL fork) for image operations

Install Pillow:


---

## How to Run

1. Ensure `customer.py`, `room.py`, and `details.py` exist and define:
   - `cust_win`
   - `roombooking`
   - `detailsroom`
   classes respectively.
2. Place your image files in the specified folder and update the paths in `main.py` if they differ.
3. Run the main script:


- Edit button labels, fonts, and colors from the `Button` and `Label` configuration in the constructor.

---

## Notes

- Make sure all image paths are valid on your system.
- Keep a reference to image objects (as done with `self.photoimgX`) to prevent them from being garbage collected and disappearing from the GUI.
