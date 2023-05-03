# E-commerce Web Application

This is an e-commerce web application built using [Django](https://www.djangoproject.com/) framework, designed to allow users to browse, search and purchase products online. This application supports user authentication, allowing registered users to view their order history, manage their profile, and save products to their cart.

## Features

* User authentication: Login, logout, and registration using Django's built-in authentication views.
* Product catalog: Browse, search, and view product details.
* Shopping cart: Add and remove products from the shopping cart and view cart summary.
* Checkout: Enter shipping and payment information and place orders.
* Order history: View past orders, order details, and shipping information.
* Search: Search for products by name, category, or price range.
* Contact us: Contact the store administrator for any inquiries or issues.

## Technologies Used

* Python 3
* Django
* HTML
* CSS
* JavaScript
* PostgreSQL

## Installation

1. Clone the repository to your local machine.
2. Create a virtual environment and activate it.
3. Install the required dependencies using pip:
   ```
   pip install -r requirements.txt
   ```
4. Setup PostgreSQL database and update the `DATABASES` configuration in `settings.py` file.
5. Apply migrations to create the database tables:
   ```
   python manage.py makemigrations
   python manage.py migrate
   ```
6. Create a superuser account:
   ```
   python manage.py createsuperuser
   ```
7. Run the development server:
   ```
   python manage.py runserver
   ```

## Usage

1. Open your web browser and go to `http://localhost:8000/` to access the home page of the application.
2. Browse, search, and select the products you want to purchase and add them to the shopping cart.
3. Once you're ready to checkout, click on the cart icon in the navigation bar to view the cart summary, then proceed to checkout.
4. Enter your shipping and payment information, review your order details, and place your order.
5. You can view your order history, saved products, and manage your profile by logging in with your credentials.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

