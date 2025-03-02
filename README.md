# Hotel Booking System

A simple command-line hotel booking management system implemented in Python that allows users to create, manage, and track hotel bookings.

## Features

- Create new hotel bookings
- Generate booking confirmation files
- View all bookings in a formatted table
- Search for specific bookings
- Update booking information
- Cancel existing bookings

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook (if running the .ipynb file)

### Installation

1. Clone the repository or download the files
2. Ensure you have Python installed
3. Run the program using Jupyter Notebook or convert it to a .py file

## Usage

The system provides a menu-driven interface with the following options:

1. **Add New Hotel Booking**
   - Enter personal details (name, phone number)
   - Specify booking details (city, hotel, check-in/out dates)
   - Automatically generates a unique confirmation number

2. **Generate Booking Confirmation**
   - Creates a text file with booking details
   - File is named "confirmation_lastname.txt"

3. **Display All Bookings**
   - Shows all bookings in a formatted table
   - Includes confirmation numbers, guest details, and booking dates

4. **Display Specific Booking**
   - Search using confirmation number or phone number
   - Shows detailed information for the specific booking

5. **Update Booking Information**
   - Modify hotel name
   - Update check-in/check-out dates
   - Option to update both

6. **Exit**
   - Close the program

## Data Validation

The system includes validation for:
- Full name (must include first and last name)
- Phone numbers (must be 10 digits and start with "05")
- Dates (valid day/month/year format)
- Check-out date must be after check-in date

## File Structure

- Bookings are stored in `Bookings.txt`
- Individual booking confirmations are generated as separate text files

## Authors

- Joud Alsayid (50%)
- Sara Albajad (50%)

## Error Handling

The system includes error handling for:
- Invalid input data
- File operations
- Date validation
- Booking searches

## Notes

- All booking data is persistent and stored in text files
- Confirmation numbers are generated automatically using city and name initials plus random digits
- The system maintains data integrity through proper file handling 