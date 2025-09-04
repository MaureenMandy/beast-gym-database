Beast Gym Management Database

Project Overview
A PostgreSQL relational database designed to manage gym operations, including memberships, trainers, classes, bookings, payments, and payroll.
It demonstrates database design, SQL queries, and analytics applied in a real-world fitness center.

Key Features:
Manage memberships and plans
Track trainers and class schedules
Handle payments and payroll
Generate analytics and insights
This project showcases database design, SQL skills, and business analytics in a practical scenario.

Project Structure
Beast-Gym-Database/
│
├─ data/           # Excel sheets of raw table data
├─ sql/            # SQL scripts: CREATE TABLE, INSERT, Queries
├─ erd/            # ERD images of database structure
├─ screenshots/    # pgAdmin screenshots
└─ README.md       # Project explanation

Database Tables

| Table Name           | Description |
|---------------------|-------------|
| Members             | Gym member details |
| Membership          | Membership types & durations |
| Plan                | Workout/subscription plans |
| Employees           | Staff details (trainers, receptionists, etc.) |
| Trainer Availability| Trainers’ schedules |
| Classes             | Group classes (Yoga, Zumba, Strength Training, etc.) |
| Booking             | Member bookings for classes or trainers |
| Payment             | Records of payments |

Future Scope
Integration with a frontend gym management system, advanced dashboards (Power BI/Tableau), and automated payment reminders and notifications.
