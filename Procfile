web:sh setup.sh && streamlit run main.py
web: gunicorn -b 0.0.0.0:8080 --workers=5 wsgi
