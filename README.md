# FlavourSome
. Go to Project Directory `cd `
3. Create a Virtual Environment `python3 -m venv env`
4. Activate Virtual Environment `source env/bin/activate`
5. Install Requirements Package `pip install -r requirements.txt`
6. Migrate Database `python manage.py migrate`
7. Create Super User `python manage.py createsuperuser`
8. Finally Run The Project `python manage.py runserver`
9. $ pip install pyqrcode



The Project is made to provide a User Interface to the user who wants to order food online. As now-a-days online food ordering is getting a boost because of the easy availability and low prices.

We used the django framework of pyhton to make this project's middleware and also HTML, CSS and JavaScript to design the webpages. We used django because, it provides a organized file structure and also it's easy to navigate the different files.

dbSQLite is used as the database of the Project to store the information of User and the Items of the Menu Bar. We also used local storage provided by the JavaScript to store the items in the cart of the user which is helpful to store the cart items even after closing the browser.

We also integrate this project for the payment and navigation aspects in future to give this project an aesthetic performance.

A django app which provide a UI to the user to order food online by adding the desired food in their cart. This project mainly made in HTML, CSS, JavaScript and dbSQlite.
