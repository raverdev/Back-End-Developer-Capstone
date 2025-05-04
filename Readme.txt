You can run available unittests from VS terminal using command: python manage.py test tests/

Don't forget to activate the virtual env and cd into the littlelemon directory before running unit-tests command.

# To check that web application serves static HTML content with images and styles:
/restaurant

You can use the following API paths for testing using the Browser, Postman or Insomnia:

# JDOSER endpoint. E.g. Making a POST request and creating a new user
/auth/users/ 

# to login and auth get token
/api-token-auth/ 
# to login using JDOSER endpoint
/auth/token/login 

# menu items
/restaurant/menu/
/restaurant/menu/{menuItemId}

# table booking 
/restaurant/booking/tables/
/restaurant/booking/tables/{bookingId}
