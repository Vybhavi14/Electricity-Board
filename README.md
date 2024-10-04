# Electricity Connection Management System

## Description
This project uses React to create an Electricity connection management system. It enables users to handle requests for electrical connections, including making new ones, changing ones that already exist, and creating charts to show monthly connection statistics.

## Features
- A user-friendly interface for connection request management.
- Add/edit connection data using this form.
- The use of bar charts to visualise monthly requests.
- Date range and application status filtering options.
- Use of responsive design to improve accessibility across a range of devices.


## Technologies Used
- **React**: JavaScript library for building user interfaces.
- **CSS**: For styling the application.
- **Recharts**: For data visualization through charts.
- **React DatePicker**: For date selection.


## Installation
Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Steps to Install
1. Clone the repository:
   ```bash
   https://github.com/Vybhavi14/Electricity-Board.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Electricity-Board
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Usage
To run the application locally, use the following command:
```bash
npm start
```
This will start the development server, and you can access the application in your web browser at `http://localhost:3000`.

## Components
- **ConnectionForm**: A form for adding and editing connection requests.
- **Chart**: Displays monthly requests using a bar chart.
  

## Example JSON Data Structure
The application uses a JSON structure similar to the following for connection requests:

```json
[
  {
    "id": 1,
    "applicantId": "TS123",
    "name": "Ram",
    "loadApplied": 150,
    "status": "Approved",
    "dateOfApplication": "2023-08-15",
    "govtIdType": "Aadhar",
    "govtIdNumber": "1234-5678-9012"
  }
]
```

## Contributing
Contributions are welcome! 

```

