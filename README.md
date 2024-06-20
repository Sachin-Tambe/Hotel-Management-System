# Hotel Restaurant Management System

This Hotel Restaurant Management System is a Python-based application designed to streamline various operations in a restaurant. The system makes it easier for both customers and staff to manage orders, generate bills, and handle payments efficiently. Utilizing Tkinter for the graphical user interface, openpyxl for handling Excel files, ReportLab for generating PDFs, qrcode for creating QR codes, and PIL for image processing, this system offers a comprehensive solution for restaurant management.

## Features

### Menu Management
- **Multiple Menus**: Supports Breakfast, Brunch, Lunch, Afternoon Tea, and Dinner menus.
- **Dynamic Loading**: Menus are stored in separate text files and dynamically loaded into the application.

### Order Placement
- **User-Friendly Interface**: Customers can place orders by selecting items from the menu and specifying quantities.
- **Input Validation**: Ensures quantities are non-negative integers to prevent errors.

### Bill Calculation
- **Automatic Calculation**: Calculates the total bill based on the selected items and their quantities.
- **Running Total**: Updates the overall bill with each order and maintains detailed sales records.

### Sales Record Management
- **Excel Integration**: Saves sales records in an Excel file, capturing details like food items, quantities, and prices.
- **Data Analysis**: Facilitates easy tracking and analysis of sales data.

### Bill Generation
- **PDF Bills**: Generates detailed PDF bills listing all ordered items, their prices, and quantities.
- **Clear Display**: Clearly shows the total amount due on the bill.

### Online Payment Integration
- **QR Code Payment**: Generates a QR code containing UPI payment information for easy and secure online payments.

### Feedback Collection
- **Feedback Form**: Includes a form where customers can provide their feedback.
- **Feedback Storage**: Saves feedback in a text file for review and improvement of services.

### User Interface
- **Tkinter GUI**: Provides a user-friendly and visually appealing interface for all operations.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Sachin-Tambe/Hotel-Management-System.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Hotel-Management-System
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure the menu text files (`Breakfast.txt`, `Brunch.txt`, `Lunch.txt`, `Afternoon_Tea.txt`, `Dinner.txt`) are in the same directory as the script.
2. Run the application:
    ```bash
    python main.py
    ```
3. Use the GUI to:
    - Navigate through different menus.
    - Place orders.
    - View and print bills.
    - Make online payments using QR codes.
    - Provide feedback.

## Dependencies

- `tkinter`: For creating the graphical user interface.
- `openpyxl`: For creating and manipulating Excel files.
- `reportlab`: For generating PDF bills.
- `qrcode`: For creating QR codes for UPI payments.
- `pillow`: For image processing tasks.

Install dependencies using:
```bash
pip install tkinter openpyxl reportlab qrcode pillow
```

## File Structure

- `main.py`: The main script to run the application.
- `requirements.txt`: List of dependencies.
- `menu_files/`: Directory containing menu text files.
- `sales_records.xlsx`: Excel file to store sales records.
- `bill.pdf`: Generated PDF bill.
- `payment.jpg`: Generated QR code for UPI payment.
- `feedback.txt`: Collected feedback from customers.

## How to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

For major changes, please open an issue first to discuss what you would like to change.



## Contact

For any questions or suggestions, please contact [Sachin Tambe](sachin.tabaji.tambe@gmail.com).

---

Enjoy using the Hotel Restaurant Management System!

[GitHub Repository](https://github.com/Sachin-Tambe/Hotel-Management-System)
