# Django HTMX Tailwind Starter

Just my personal kickstarter for Django projects with a sprinkle of HTMX and a dash of Tailwind CSS. 

## Prerequisites

Before you begin, ensure you have the following installed on your system:
- Python 3.8 or newer
- pip (Python package installer)
- Node.js and npm (Node package manager)

## Getting Started

Follow these steps to get your Django project up and running with HTMX and Tailwind CSS:

### 1. Clone the Repository

Start by cloning this repository to your local machine:

```
git clone https://github.com/michaelaitken/django-htmx-tailwind-starter.git
cd django-htmx-tailwind-starter
```

### 2. Create a Virtual Environment

Create a new virtual environment in the project directory by running:

```
python -m venv .venv
```

Activate the virtual environment:

- On Windows:
```
.\.venv\Scripts\activate
```

### 3. Install Django

With the virtual environment activated, install Django using pip:

```
pip install django
```

### 4. Install Node Modules

Install the required Node.js modules specified in `package.json`:

```
npm install
```

### 5. Start the Project

With your virtual environment active, use the following command to start both the Django development server and the Tailwind CSS compiler:

```
npm run start
```

This command concurrently runs Django's development server and the Tailwind CSS compiler in watch mode, allowing you to see changes in real-time.

## Contributing

Contributions are welcome.
