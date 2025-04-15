# Project Management System

A comprehensive project and task management system built with Laravel and Vue.js, featuring modern UI components from Shadcn-vue.

## Features

### Project Management
- Create and manage projects with detailed information
- Set project timelines (start and end dates)
- Assign team members
- Categorize projects with custom tags
- Track project progress

### Task Management
- Create and assign tasks
- Set priorities and deadlines
- Create subtasks for complex work items
- Multiple assignees support
- Task status tracking (To-Do, In Progress, Done)

### Progress Tracking
- Kanban board view
- Real-time updates
- Task comments and discussions
- Progress reports
- Weekly automated reports for project managers

### User Management
- Role-based access control
- Project Manager and Team Member roles
- Team management within projects
- User authentication and authorization

## Tech Stack

### Frontend
- Vue.js 3
- Shadcn-vue components
- Tailwind CSS
- Vue Router
- Vuex/Pinia for state management

### Backend
- Laravel
- MySQL/PostgreSQL
- Laravel Sanctum for authentication
- Laravel Actions for business logic

## Getting Started

### Prerequisites
- PHP >= 8.1
- Composer
- Node.js >= 16
- npm or yarn
- MySQL/PostgreSQL

### Installation

1. Clone the repository
```bash
git clone [repository-url]
cd project-management-system
```

2. Install PHP dependencies
```bash
composer install
```

3. Install JavaScript dependencies
```bash
npm install
```

4. Create environment file
```bash
cp .env.example .env
```

5. Generate application key
```bash
php artisan key:generate
```

6. Configure database in .env file
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=project_management
DB_USERNAME=root
DB_PASSWORD=
```

7. Run migrations
```bash
php artisan migrate
```

8. Start the development server
```bash
php artisan serve
npm run dev
```

## Project Structure

```
project-management-system/
├── app/
│   ├── Actions/           # Business logic actions
│   ├── Http/
│   │   ├── Controllers/   # API controllers
│   │   └── Middleware/    # Custom middleware
│   ├── Models/            # Eloquent models
│   └── Services/          # Business services
├── resources/
│   ├── js/
│   │   ├── components/    # Vue components
│   │   ├── composables/   # Vue composables
│   │   └── views/         # Vue views
│   └── css/              # Stylesheets
├── routes/
│   ├── api.php           # API routes
│   └── web.php           # Web routes
└── tests/                # Test files
```

## API Documentation

The API documentation is available at `/api/documentation` when running the application.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Laravel](https://laravel.com)
- [Vue.js](https://vuejs.org)
- [Shadcn-vue](https://shadcn-vue.com)
- [Tailwind CSS](https://tailwindcss.com)
