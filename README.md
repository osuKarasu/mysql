# The MySQL Template for running a Ripple based osu! private server.

## How to install?

* Upload `ripple.mysql` to a MySQL database.
* Edit `setup_server_db.php`: change `DBUSER` and `DBPASS` to your MySQL username and password. If you are not on `localhost` change that as well.
* Run `setup_server_db.php` with the following command: `php setup_server_db.php` to setup the database.

This will create the FokaBot user.

If you can't/don't know how to do any of the above, you are not qualified.