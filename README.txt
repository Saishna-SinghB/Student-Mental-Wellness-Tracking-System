WellnessHub

WellnessHub is a student mental wellness website. It helps students track their moods, keep a private journal, find support resources and book counselling sessions.

Main Features

Students: Mood tracking, journal, counselling bookings, anonymous peer support, achievements and notifications.

Counsellors: View students, manage appointments and review risk alerts.

Administrators: Manage users and counsellors, view reports and check system logs.

How to Run the Project

Install XAMPP and start Apache and MySQL.

Copy the Demo2 folder into C:\xampp\htdocs\.

Open http://localhost/phpmyadmin.

Create a database called wellnesshub and import wellnesshub.sql.

Check the database settings in demoDB.php. This copy uses MySQL port 3307; change it to 3306 if needed.

Open http://localhost/Demo2/ in your browser.

How to Use WellnessHub

Students: Click Create Account to register using your Richfield student details, or Login if you already have an account. Use the dashboard menu to track moods, write journal entries, book counselling or share anonymous posts.

Counsellors: Log in through the same login page. Use the counsellor dashboard to manage appointments, view students and review alerts.

Administrators: Log in through the same login page. Use the admin dashboard to manage accounts, reports and settings.

To reset a forgotten password, click Forgot Password? on the login page. Remember to Logout when finished.

Important Files and Folders

index.php – Welcome page.

login.php, register.php, forgot-password.php, change-password.php – Account pages.

dashboard.php, mood-tracking.php, journal.php – Student wellness pages.

counselling-booking.php, peer-support.php – Counselling and community support.

self-help-library.php, achievements.php, notifications.php – Other student features.

counsellor-*.php, risk-alerts.php – Counsellor pages.

admin-*.php, system-logs.php – Administrator pages.

css/style.css – Website design.

js/ – Website interactions and charts.

api/ – PHP code that handles requests and saves data.

demoDB.php – Database connection.

wellnesshub.sql – Database structure and sample data.

mail-config.php – Email setup for password recovery.

img/, lib/ – Images and included libraries.

Notes

Use XAMPP, not VS Code Live Server, to run the PHP website.

If you see 404 Not Found, check the Demo2 folder name and URL.

If the database fails, check MySQL and the port in demoDB.php.

weekly-summary.php shows an example email layout; automatic weekly emails are not included.

Change demo passwords and keep real student information private before publishing.

Built with: PHP, HTML, CSS, JavaScript and MySQL.
