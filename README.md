# Item Catalog - Restaurants and Menus
- This application views restaurants called from a database and their menu items.
- All CRUD operations are working effiecntly
- Authenticated users can add new restaurants and menu items.
- Only the creator of a restaurant can edit it.

## Third-party
- This application uses google sign in, and facebook sign in.

## oAuth
- oAuth is used to authenticate users.

## How to run?
- Clone this repo on your local machine.
- Place it in the same folder as vagrant file.
- In your `terminal` change directory to where you downloaded the repo.
- Run `vagrant up` then `vagrant ssh`
- Install the database required for this project `python database_setup.py` & `python lotsofmenus.py`
- Run the application `python project.py`
- Open your favourite browser and head to `http://localhost:5000` and enjoy the application.

### References
- This code is based on Udacity Course.
- Database files are from Udacity.