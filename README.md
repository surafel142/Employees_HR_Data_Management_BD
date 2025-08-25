# Employees Data Management System

![HR Management System](https://employeeshr.netlify.app/og-image.png)

This project is an HR Management System designed for different administrative levels in the Ethiopian public sector. It includes dashboards for:

1. Office HR
2. Woreda HR
3. Zone HR
4. System Admin

Each dashboard is tailored to the specific needs and responsibilities of the role.

## Live Demo

The application is hosted on Netlify:  
👉 [https://employeeshr.netlify.app/](https://employeeshr.netlify.app/)

## Features

### Office HR Dashboard
- Employee data management (add, view, edit, delete)
- Department-wise employee reports
- Gender and education level statistics
- Print and export functionality

### Woreda HR Dashboard
- Overview of multiple offices in the woreda
- Office management and filtering
- Communication with Office HR
- Woreda-level reporting

### Zone HR Dashboard
- Overview of multiple woredas in the zone
- Woreda management and comparison
- Communication with Woreda HR
- Zone-level analytics and reporting

### Admin Dashboard
- System overview and monitoring
- User management (add, remove, activate/deactivate)
- System configuration and settings
- Advanced analytics and data export

## Technologies Used

- HTML5
- CSS3 (Tailwind CSS framework)
- JavaScript (Chart.js for visualizations)
- Netlify for hosting

## How to Use

1. Visit the live site: [https://employeeshr.netlify.app/](https://employeeshr.netlify.app/)
2. Choose your role from the login page
3. Explore the features specific to your role:
   - Office HR: Manage employee data
   - Woreda HR: Monitor multiple offices
   - Zone HR: Analyze woreda performance
   - Admin: Configure system settings

## Project Structure

```
project-root/
├── index.html           # Main login page
├── office.html          # Office HR Dashboard
├── woreda.html          # Woreda HR Dashboard
├── zone.html            # Zone HR Dashboard
├── admin.html           # Admin Dashboard
├── README.md            # Project documentation
└── assets/              # Static assets
    ├── css/
    ├── js/
    └── images/
```

## Screenshots

| Office HR | Woreda HR |
|-----------|-----------|
| ![Office HR](screenshots/office-hr.png) | ![Woreda HR](screenshots/woreda-hr.png) |

| Zone HR | Admin |
|---------|-------|
| ![Zone HR](screenshots/zone-hr.png) | ![Admin](screenshots/admin.png) |

## Hosting

The project is hosted on Netlify at [https://employeeshr.netlify.app/](https://employeeshr.netlify.app/). Netlify provides:

- Continuous deployment from GitHub
- HTTPS encryption
- Global CDN
- Instant cache invalidation
- Automated builds

## Future Improvements

- Implement backend with user authentication
- Add database integration for persistent data
- Enhance reporting with more detailed analytics
- Add mobile responsiveness improvements
- Implement real-time communication features

## Contributing

Contributions are welcome. Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

---

For more details, visit the live site: [https://employeeshr.netlify.app/](https://employeeshr.netlify.app/ )
