# Antigravity Trading Project Requirements
Meka setup karanna oya pahatha ewa karanna (How to set this up):

## 1. Setup Python AI Model
1. Install Python 3.10+
2. Navigate to `python-ai` directory
3. `python -m venv venv` and activate it
4. Run `pip install -r requirements.txt`
5. Run the server: `uvicorn main:app --reload`
*Now the AI runs on http://127.0.0.1:8000*

## 2. Setup Laravel Backend
1. Install PHP 8.1+ & Composer
2. Initialize an actual Laravel app or copy the generated files into a new project
3. In a new fresh Laravel app, paste these folders in their respective places:
   - `app/Services/*`
   - `app/Http/Controllers/*`
   - `routes/*`
   - `resources/views/*`
4. Run `php artisan serve`

Once done, visit `http://127.0.0.1:8000` (or whatever Laravel port is) to open the TradingView Dashboard with the connected AI logic!
