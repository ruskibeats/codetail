# CodeTail

A modern AI SDK interface built with Django and TailwindCSS.

## Features

- Modern, clean UI with TailwindCSS
- Sequential Processing Pipeline
- Real-time content processing
- Responsive design
- Dark mode support

## Setup

1. Clone the repository:
```bash
git clone https://github.com/ruskibeats/codetail.git
cd codetail
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Start development server:
```bash
python manage.py runserver
```

Visit http://localhost:8000/playground/ to see the interface.

## Project Structure

```
codetail/
├── agents/              # Agents app
│   ├── templates/       # Agent-specific templates
│   └── views.py        # Agent views and logic
├── templates/          # Global templates
│   └── base/           # Base templates
└── static/            # Static files
    ├── css/           # Compiled CSS
    └── js/            # JavaScript files
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)