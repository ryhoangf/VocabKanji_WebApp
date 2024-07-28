Make sure that the Python you are using is the latest version.

Please install the following frameworks and packages before you test the program:
    pip install Flask
    pip install psycopg2-binary
    pip install flask_login

We're using PosgreSQL for this web app, you can download this at:
    https://www.postgresql.org/download/.
After installing PosgreSQL, please create a database and run the code in the file data_vocab_v2.db.
You need to edit the following line of code in the __init__.py file:
    app.config['SQLALCHEMY_DATABASE_URI'] = 'postgresql://postgres:ryhoangf@localhost/goikanji_db'
with the following syntax:
    app.config['SQLALCHEMY_DATABASE_URI'] = 'postgresql://postgres:your password@localhost/your database name'
