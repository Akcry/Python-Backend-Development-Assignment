# To-Do List API

## Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd todo-api
   ```

2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Initialize the database:
   ```bash
   python -c "from app import db; db.create_all()"
   ```

5. Run the application:
   ```bash
   python app.py
   ```

## API Endpoints

- `GET /todos` - Retrieve a list of all to-do items.
- `POST /todos` - Add a new to-do item.
- `PUT /todos/<id>` - Update a to-do item.
- `DELETE /todos/<id>` - Delete a to-do item.
