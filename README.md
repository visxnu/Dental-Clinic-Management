
# Dental Clinic Management

Dental Clinic Management is a comprehensive system designed to automate and streamline daily operations in a dental clinic. It allows users to efficiently manage patient records, schedule appointments, track treatment histories, and generate insightful reports, ensuring a smooth and organized workflow.

## Features

- **Patient Management:** Add, view, update, and delete patient information.
- **Appointment Scheduling:** Schedule and manage appointments efficiently.
- **Treatment Records:** Track dental treatments and maintain detailed histories.
- **Reporting:** Generate reports to gain insights into clinic operations.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/visxnu/Dental-Clinic-Management.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd Dental-Clinic-Management
   ```

3. **Install Dependencies:**

   Ensure you have Python installed. Then, install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations:**

   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server:**

   ```bash
   python manage.py runserver
   ```

6. **Access the Application:**

   Open your web browser and navigate to `http://127.0.0.1:8000/`.

## Usage

- **Admin Panel:** Access the admin interface at `http://127.0.0.1:8000/admin/` to manage the clinic's data.
- **Patient Management:** Use the 'Patients' section to add and manage patient records.
- **Appointment Scheduling:** Utilize the 'Appointments' section to schedule and oversee appointments.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries or support, please open an issue in this repository.

*Note: This project is intended for educational purposes and may require further customization for production use.*
