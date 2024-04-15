# Run command
#web: gunicorn --bind :$PORT --workers 1 --threads 8 --timeout 0 main:app

#web: gunicorn -w 4 -k uvicorn.workers.UvicornWorker main:app

web: uvicorn main:app --reload
