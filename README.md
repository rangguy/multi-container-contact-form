# Contact Form System

A comprehensive contact form solution consisting of three interconnected modules: API Service, Client Application, and CMS.

## Modules

### 1. API Service (Golang)
**Repository**: [https://github.com/rangguy/api-contact-form](https://github.com/rangguy/api-contact-form)

Core backend service that handles:
- Form submission processing
- Data validation and sanitization
- Secure storage to database
- Email notification system
- RESTful API endpoints

**Tech Stack**:
- **Language**: Golang
- **Framework**: Gin
- **Database**: PostgreSQL
- **Environment**: Docker

### 2. Client Application (Next.js)
**Repository**: [https://github.com/rangguy/client-contact-form](https://github.com/rangguy/client-contact-form)

Modern frontend application featuring:
- Responsive contact form UI
- Form validation and error handling
- Submission state management

**Tech Stack**:
- **Framework**: Next.js 14
- **Language**: JavaScript
- **UI Library**: React Hook Form
- **Environment**: Docker
- **Styling**: Bootstrap CSS

### 3. CMS (Laravel)
**Repository**: [https://github.com/rangguy/cms-contact-form](https://github.com/rangguy/cms-contact-form)

Administration panel for:
- Submission management
- System configuration

**Tech Stack**:
- **Framework**: Laravel 12
- **Frontend**: Blade
- **UI**: Tailwind CSS
- **Environment**: Docker

## Development Setup

### Prerequisites
- Docker 27+
- Node.js 20+
- Go 1.23+ (for API)
- PHP 8.2+ (for CMS)
