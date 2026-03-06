💊 MedLife: E-Pharmacy Web Application
MedLife is a comprehensive full-stack E-Pharmacy platform designed to streamline medicine procurement and healthcare management. Beyond standard e-commerce features, it includes a doctor appointment system and utilizes professional software design patterns to ensure scalability and clean code.

🚀 Key Features
🛒 E-Commerce & Pharmacy
Medicine Catalog: Browse and search a vast inventory of medicines categorized by Generic Name, Manufacturer, and Strength.

Dynamic Cart System: Real-time quantity adjustments and automated price calculation.

Order History: Track previous purchases with timestamped records (UTC+6 synchronized).

👨‍⚕️ Healthcare Management
Doctor Appointment System: Search for specialists based on category (Speciality) or name and book consultations directly.

Smart Diagnosis Search: Advanced filtering to find doctors based on gender and availability.

💳 Secure Payments
SSLCommerz Integration: Professional payment gateway integration for real-world transactions.

Strategy-Based Payments: Support for multiple payment methods including Credit Cards and PayPal.

🔐 Administration
Admin Dashboard: Specialized access to manage user accounts and system data.

User Role Management: Ability to toggle user types (Admin/Regular User) and moderate the database.

🛠️ Technical Architecture
🏗️ Software Design Patterns (Advanced)
The application is built using professional design patterns to ensure the code is maintainable:

Factory Pattern: Implemented for user creation (RegularUserFactory & AdminUserFactory), decoupling the authentication logic from specific user classes.

Strategy Pattern: Used for the payment system (PaymentStrategy), allowing the app to switch between PayPal and Credit Card logic dynamically.

Singleton Pattern: Ensures a single, consistent instance of the PaymentGatewayConfig across the entire application.

Decorator Pattern: Custom @login_is_required decorators to secure routes and manage authorization.

💻 Tech Stack
Backend: Python (Flask)

Database: MySQL / SQLAlchemy ORM

Auth: Google OAuth 2.0 & Session-based authentication

Frontend: Jinja2 Templates, HTML5, CSS3, JavaScript



🔧 Installation & Setup:
1. Clone the repository: git clone https://github.com/Ga-lib/E-Pharmacy-Web-Application-.git
cd Medlife2
2. Set up Virtual Environment: python -m venv venv
source venv/bin/scripts/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies: pip install -r requirements.txt
4. Database Configuration: Import medlife2.sql into your MySQL server.
Update the SQLALCHEMY_DATABASE_URI in app.py with your credentials.
5. Run the App: python app.py

<img width="1917" height="928" alt="image_2023-10-22_02-07-52" src="https://github.com/user-attachments/assets/d3f3659f-f5fb-442a-93a0-9c256b37a9b8" />
<img width="421" height="708" alt="image" src="https://github.com/user-attachments/assets/bbdb05fe-9c82-48bf-a524-6970fd7c2523" />



ER DIAGRAM:

<img width="1113" height="1280" alt="image" src="https://github.com/user-attachments/assets/c5f9bbc9-9169-4ce8-88c2-34e5a8e94a63" />

SYSTEM USE CASE DIAGRAM:

<img width="1280" height="1024" alt="image" src="https://github.com/user-attachments/assets/26cb2021-c10b-4e2a-9aac-17beb80d25e2" />

EXPANDED USE CASE DIAGRAM:

<img width="1280" height="1208" alt="image" src="https://github.com/user-attachments/assets/7c1b7c1a-514f-4448-b22d-581eec209ba3" />

CLASS DIAGRAM:

<img width="1280" height="1071" alt="image" src="https://github.com/user-attachments/assets/476e8b81-66a7-4a3d-8238-46717dc3f161" />

SEQUENCE DIAGRAM:

<img width="4619" height="2625" alt="image" src="https://github.com/user-attachments/assets/b299e579-ad97-4423-b0a9-eaff6d098570" />








