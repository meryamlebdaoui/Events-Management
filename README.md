extract folder inside xampp/htdocs or wamp/htdocs
on config/database and adjust database connectivity
import database inside root dir (events.sql)

now open browser:

type :

	1. localhost/events/user/index.php    -GET-  - list all users
	2. localhost/events/user/create.php   -POST- {} payload
	3. localhost/events/user/view.php     -POST- {id:2} payload
	4. localhost/events/user/delete	   -POST- {id:12} payload