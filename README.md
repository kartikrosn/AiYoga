# Yoga Instructor AI

# AIYogaInstructor

An AI-powered yoga instruction application that provides personalized yoga guidance and recommendations.

## Features

- Personalized yoga pose recommendations
- Interactive user interface
- User authentication system
- Real-time AI-powered guidance

## Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.7 or higher
- XAMPP or similar local server environment
- pip (Python package manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/varunjoshi84/aiyogainstructor.git
cd aiyogainstructor
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
- Copy `.env.example` to `.env`
- Update the `.env` file with your actual credentials:
  - Get your GROQ API key from [GROQ's website](https://groq.com)
  - Configure database settings if needed

## Running the Application

1. Start your local server environment (XAMPP)

2. Run the Flask application:
```bash
python app.py
```

3. Open your web browser and navigate to:
```
http://localhost:5000
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## Acknowledgments

- Thanks to GROQ for providing the AI capabilities
